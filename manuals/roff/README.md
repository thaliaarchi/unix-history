# UNIX roff documentation

Documentation on the formatting request lines supported by UNIX roff, unifying
the manuals for BCPL runoff from 1969 and 1971 and UNIX roff from V3–V7. See the
BCPL memos for more details besides the table.

Sources:
- [BCPL runoff](https://manpages.bsd.lv/history.html#x1969):
  - ["Runoff"](https://manpages.bsd.lv/history/runoff69.low.pdf) \
    Douglas McIlroy, AT&T Bell Labs Technical Memorandum, 17 September 1969 \
    [[high quality scan](https://manpages.bsd.lv/history/runoff69.high.pdf.gz)]
  - ["Roff"](https://manpages.bsd.lv/history/roff71.low.pdf) \
    Douglas McIlroy, AT&T Bell Labs Technical Memorandum, 12 January 1971 \
    [[high quality scan](https://manpages.bsd.lv/history/roff71.high.pdf.gz)]
- [UNIX roff](https://manpages.bsd.lv/history.html#x1971):
  - "V2" roff binary from June 1972 in [s2-bits](https://www.tuhs.org/Archive/Distributions/Research/1972_stuff/s2-bits.tar.gz)
    tape (lookup table)
  - UNIX [V3](http://squoze.net/UNIX/v3man/man1/roff),
    [V4](http://squoze.net/UNIX/v4man/man1/roff),
    [V5](http://squoze.net/UNIX/v5man/man1/roff),
    [V6](http://squoze.net/UNIX/v6man/man1/roff),
    and V7 manuals

| Request           | Break    | Initial   | Meaning                                                                                                                                 | Versions    |
| ----------------- | -------- | --------- | --------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| `.ad`             | yes      | yes       | Adjust (justify) right margin of filled lines.                                                                                          | BCPL69, V2+ |
| `.ar`             | no       | arabic    | Arabic page numbers.                                                                                                                    |             |
| `.bl n`           | yes      | -         | Insert contiguous block of *n* blank lines, on a new page if necessary.                                                                 | V2+         |
| `.bm +n`          | no       | n=4       | Bottom margin is *n* lines below foot.                                                                                                  | BCPL        |
| `.bp +n` [^bp]    | yes      | n=1       | Begin new page and number it *n*; if *n* is not given, normal sequencing occurs.                                                        |             |
| `.br`             | yes      | -         | Line break. Begin a new line without filling the current line (synonym for `.sp 0`).                                                    |             |
| `.cc c`           | no       | c='.'     | Control character is *c*.                                                                                                               |             |
| `.ce n`           | yes      | -         | Center the next *n* input lines without filling and break on each.                                                                      |             |
| `.cn`             | no       | yes       | Case normal on input.                                                                                                                   | BCPL        |
| `.cr`             | no       | no        | Case reversed. Exchange upper and lower case letters only on input.                                                                     | BCPL        |
| `.de xx`          | no       | -         | Define parameterless macro to be invoked by request `.xx` (definition ends on line beginning with `..`).                                | V2+         |
| `.ds`             | yes      | no        | Double space (synonym for `.ls 2`).                                                                                                     |             |
| `.ef t`           | no       | t=""      | Even page foot title is *t*.                                                                                                            |             |
| `.eh t`           | no       | t=""      | Even page head title is *t*.                                                                                                            |             |
| `.en`             | yes      |           | End of footnote.                                                                                                                        | BCPL71      |
| `.eo +n`          | yes      | n=0       | Even page offset is *n* (see `.po`).                                                                                                    | BCPL69      |
| `.fi`             | yes      | yes       | Fill output lines.                                                                                                                      |             |
| `.fn`             | no       |           | Beginning of footnote.                                                                                                                  | BCPL71      |
| `.fo t`           | no       | t=""      | All foot titles are *t*.                                                                                                                |             |
| `.fs t`           | no       | t=""      | Footnote separator is *t*.                                                                                                              | BCPL71      |
| `.hc c`           | no       | none      | Hyphenation character is *c*.                                                                                                           | BCPL71, V2+ |
| `.he t`           | no       | t=""      | All head titles are *t*.                                                                                                                |             |
| `.hx`             | no       | -         | Title lines are suppressed.                                                                                                             | V2+         |
| `.hy n`           | no       | n=1[^hy]  | Hyphenation is done, if *n*=1; and is not done, if *n*=0.[^hy]                                                                          | BCPL71, V2+ |
| `.ig`             | no       | -         | Ignore input lines through a line beginning with `..`.                                                                                  | V2+         |
| `.in +n`          | yes[^in] | -[^in]    | Indent *n* spaces from left margin.                                                                                                     |             |
| `.ix +n`          | no       | -         | Same as `.in` but without break.                                                                                                        | V2+         |
| `.jo`             |          |           | *Undocumented*                                                                                                                          | V2          |
| `.ju`             | yes      | yes       | Justify right margin.                                                                                                                   | BCPL71      |
| `.li n`           | no       | -         | Literal. Treat next *n* lines as text.                                                                                                  |             |
| `.ll +n`          | no       | n=65[^ll] | Line length including indent is *n* characters.                                                                                         |             |
| `.ls +n` [^ls]    | yes      | n=1       | Line spacing set to *n* lines per output line.                                                                                          | BCPL71, V2+ |
| `.m1 n`           | no       | n=2       | Put *n* blank lines between the top of a new page and the head title.                                                                   | V2+         |
| `.m2 n`           | no       | n=2       | Put *n* blank lines between the head title and beginning of text on page.                                                               | V2+         |
| `.m3 n`           | no       | n=1       | Put *n* blank lines between the end of text and the foot title.                                                                         | V2+         |
| `.m4 n`           | no       | n=3       | Put *n* blank lines between the foot title and the bottom of page.                                                                      | V2+         |
| `.mg n`           | no       | empty     | Next line sets merge pattern *n*, 1≤*n*≤4.                                                                                              | BCPL71      |
| `.mk`             |          |           | *Undocumented*                                                                                                                          | V2          |
| `.n1`             | no       | no        | Number lines in margin, starting from 1 on each page. Head and foot titles are not numbered. Add 5 to page offset.[^n1n2]               | V2+         |
| `.n2 n`           | no       | no        | Number lines in margin, starting from *n*; stop numbering if *n*=0. Head and foot titles are not numbered. Add 5 to page offset.[^n1n2] | V2+         |
| `.na`             | yes      | no        | Stop adjusting the right margin.                                                                                                        | BCPL69, V2+ |
| `.ne n`           | no       | -         | Need room for lines. Begin new page, if *n* output lines (*2n* if double-spaced) cannot fit on present page.                            |             |
| `.nf`             | yes      | no        | Nofill. Stop filling output lines, i.e., break on each input text line.                                                                 |             |
| `.ni +n`          | no       | n=0       | Line numbers are indented *n*.                                                                                                          | V2+         |
| `.nj`             | yes      | no        | No justification of right margin.                                                                                                       | BCPL71      |
| `.nn +n`          | no       | -         | The next *n* output lines are not numbered.                                                                                             | V2+         |
| `.nx file`        |          | -         | Switch input to `file`.                                                                                                                 | V2+         |
| `.of t`           | no       | t=""      | Odd page foot title is *t*.                                                                                                             |             |
| `.oh t`           | no       | t=""      | Odd page head title is *t*.                                                                                                             |             |
| `.oo +n`          | yes      | n=0       | Odd page offset is *n* (see `.po`).                                                                                                     | BCPL69      |
| `.op`             | yes      |           | Begin an odd page.                                                                                                                      | BCPL        |
| `.pa +n`          | yes      | n=1       | Synonym for `.bp`.                                                                                                                      |             |
| `.pl +n`          | no       | n=66      | Paper length is *n* lines including margins.[^pl]                                                                                       |             |
| `.po +n` [^po]    | no[^po]  | n=0       | Page offset, i.e., move all output *n* spaces right.                                                                                    |             |
| `.ro`             | no       | arabic    | Roman page numbers.                                                                                                                     |             |
| `.sc c`           | no       | c='#'     | Shift character is *c*.                                                                                                                 | BCPL        |
| `.sk n` [^sk-1]   | no       | -         | Skip *n* pages. Produce *n* blank pages with head and foot titles.[^sk-2]                                                               |             |
| `.sp n`           | yes      | -         | Space. Insert block of *n* blank lines, except at top of page.[^sp-1] [^sp-2]                                                           |             |
| `.ss`             | yes      | yes       | Single space output lines (synonym for `.ls 1`).                                                                                        |             |
| `.ta n n..` [^ta] | no       | 9 17 25 … | Set pseudotab columns.                                                                                                                  |             |
| `.tc c`           | no       | c=' '     | Tab replacement character is *c*.                                                                                                       | V2+         |
| `.ti +n`          | yes      | -         | Temporarily indent next output line *n* spaces.                                                                                         |             |
| `.tm +n`          | no       | n=4       | Top margin is *n* lines above head.                                                                                                     | BCPL        |
| `.tr cdef..`      | no       | -         | Translate character *c* into *d*, *e* into *f*, etc.                                                                                    |             |
| `.ul n`           | no       | -         | Underline the letters and numbers in the next *n* input lines.                                                                          |             |
| `.un n`           | yes      |           | Unindent (synonym for `.ti -n`).                                                                                                        | BCPL, V2    |

[^bp]: BCPL `.bp` takes no argument.
[^hy]: BCPL71 `.hy` is "hyphenation mode is n, 0≤n≤3" with initial n=3.
[^in]: BCPL `.in` is break=no and initial n=0.
[^ll]: BCPL `.ll` is initial n=60.
[^ls]: BCPL71 `.ls` is `.ls n`.
[^n1n2]: V3 `.n1` writes "Head and foot titles are not numbered", but V4+ do
  not. V6-V7 `.n1` and `n2` write "Add 5 to page offset", but V3-V5 do not.
[^pl]: BCPL `.pl` writes "paper length is n including margins" and V3+ writes
  "Total paper length taken to be n lines", which should be the same
[^po]: BCPL69 `po` is `.po n` and break=yes.
[^sk-1]: BCPL `.sk` is `.sk +n` and writes "skip at next new page to page n", so
  it seems to skip to page *n*, instead of skipping *n* pages.
[^sk-2]: BCPL `.sk` writes "skip at next new page to page n", V3 writes "n pages
  with head and foot titles but otherwise blank will be output beginning with
  the next page containing text" and V4-V7 write "Produce n blank pages starting
  next page".
[^sp-1]: BCPL69 `.sp` skips n+1 lines if double-spaced; others are unspecified.
[^sp-2]: V3 `.sp` writes "Insert block of n blank lines. If the bottom of a page
  is reached, remaining lines are not put on next page" and V6-V7 write "Insert
  block of n blank lines, except at top of page".
[^ta]: BCPL `.ta` takes tab settings from the following line instead of on its
  line.

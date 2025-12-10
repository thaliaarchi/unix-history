# UNIX Manuals

- "DRAFT: The UNIX Time-Sharing System" \
  D. M. Ritchie \
  circa Spring 1971

  A draft manual for PDP-11 UNIX in the style of a technical report preceding
  the First Edition manual. It was found by Doug McIlroy among the papers of Bob
  Morris.[^mcilroy1] [^mcilroy2] This draft is ancestral to the published
  manuals and the SIGOPS/CACM paper[^mcilroy1] [^mcilroy3] and contains the
  famous claim "UNIX contains a number of features very seldom offered even by
  larger systems".[^mcilroy2]

  It writes that UNIX-11 was "a few months old" and that UNIX-7 had "been in
  existence about a year". Based on that, Doug dates it to mid-1971 and notes
  that UNIX had only 21 system calls at the time of the manual, a number that
  had increased to 34 by 3 November 1971 when the First Edition manual was
  produced.[^mcilroy1] Warner Losh dates it to spring 1971 by placing UNIX-7 at
  late 1969 and UNIX-11 at February 1971.[^losh]

  It was apparently printed with a Teletype Model 37, as it uses half line feeds
  for subscripts and periods raised as multiplication dots, a relatively rare
  feature. The manual mentions Teletype Models 33, 35, and 37 and implies that
  most users would be familiar with the Model 37.[^archibald]

  A number of versions are available:
  - [UnixEditionZero.pdf](https://www.tuhs.org/Archive/Distributions/Research/McIlroy_v0/UnixEditionZero.pdf):
    the original scan from Doug McIlroy [^readme] [^toomey1]
  - [UnixEditionZero-OCR.pdf](https://www.tuhs.org/Archive/Distributions/Research/McIlroy_v0/UnixEditionZero-OCR.pdf):
    a smaller version with OCR by Nelson Beebe [^beebe] [^readme]
  - [UnixEditionZero-Threshold_OCR.pdf](https://www.tuhs.org/Archive/Distributions/Research/McIlroy_v0/UnixEditionZero-Threshold_OCR.pdf)
    an even smaller version by Paul McJones [^readme]
  - [UnixEditionZero.txt](https://www.tuhs.org/Archive/Distributions/Research/McIlroy_v0/UnixEditionZero.txt)
    a text version by Warren Toomey [^toomey2]
  - [v0.txt](v0.txt):
    a text version by Thalia Archibald, matching the original formatting using
    Teletype Model 37 escape sequences which can be rendered with Yufeng Gao's
    [Teletype 37 PDF](https://github.com/TheBrokenPipe/Teletype-37-PDF) tool
    [^archibald]
  - [UnixEditionZero-reset_troff.pdf](https://doc.cat-v.org/unix/v0/UnixEditionZero-reset_troff.pdf):
    a `troff` re-setting by David Lind [^cat-v]
  - [https://github.com/Random832/McIlroy_v0](https://archive.softwareheritage.org/browse/origin/directory/?origin_url=https://github.com/Random832/McIlroy_v0):
    an unfinished text version by Random832 [^random]

  Remarks from TUHS discussion in [November](https://www.tuhs.org/pipermail/tuhs/2015-November/thread.html#7674)
  and [December](https://www.tuhs.org/pipermail/tuhs/2015-December/thread.html#7720)
  2015:
  - roff had no macros back then, so a recreation using raw groff would likely
    be close to the original. Doug McIlroy also detailed a history of
    roff.[^mcilroy4] [^anthony]
  - `create(2)`and `sys creat` were spelled differently. [pages 8, A1-4]
    [^neukirchen]
  - In the `creat` documentation, "NO!" is handwritten next to “Mode is a number
    encoding the protection bits as specified under the "chmod" command
    below”. [page 8] [^cowan]
  - "i-number" is documented as standing for "identification number", not "index
    number" as later claimed. [page 11] [^readme]
  - The shell prompt was `@`. [page 14] [^cowan]
  - Standard error did not exist. [page 14] [^archibald]
  - `fork` is documented as `fork(label)`, though the `sys fork` assembly
    reference admits that the label argument is a white lie. The signature is
    `sys fork; (old process return); (new process return)`. [pages 18, A1-2]
    [^horsfall]
  - `execute(2)` and `sys exec` were spelled differently. [pages 19, A1-5]
    [^archibald]
  - The paper tape driver was in a blocked format with checksums. [page 23]
    [^cowan]
  - ^\ caused an arbitrary non-shell process to core dump if several are running
    and interrupt with DEL or ^C did not exist yet. [page 26] [^cowan]
  - CLI switches did not exist yet and files passed to the B interpreter must be
    preceded with a hyphen. [page 28] [^cowan]
  - Files had only one execute bit. [page 29] [^cowan]
  - Page A7 is missing in the hard copy and scan.[^horsfall] [^toomey2]
    [^mcilroy5]

  [^readme]: https://www.tuhs.org/Archive/Distributions/Research/McIlroy_v0/Readme
  [^mcilroy1]: Doug McIlroy https://www.tuhs.org/Archive/Distributions/Research/McIlroy_v0/Readme
  [^mcilroy2]: Doug McIlroy at 24 Nov 2015 01:55:36 UTC https://www.tuhs.org/pipermail/tuhs/2015-November/007674.html
  [^mcilroy3]: Doug McIlroy at 25 Nov 2015 05:08:17 UTC https://www.tuhs.org/pipermail/tuhs/2015-November/007685.html
  [^toomey1]: Warren Toomey at 28 Nov 2015 23:24:13 UTC https://www.tuhs.org/pipermail/tuhs/2015-November/007700.html
  [^beebe]: Nelson H. F. Beebe at 29 Nov 2015 17:51:19 UTC https://www.tuhs.org/pipermail/tuhs/2015-November/007705.html
  [^neukirchen]: Leah Neukirchen at 29 Nov 2015 20:21:05 UTC https://www.tuhs.org/pipermail/tuhs/2015-November/007707.html
  [^cowan]: John Cowan at 30 Nov 2015 04:02:44 UTC https://www.tuhs.org/pipermail/tuhs/2015-November/007714.html
  [^horsfall]: Dave Horsfall at 30 Nov 2015 04:26:35 UTC https://www.tuhs.org/pipermail/tuhs/2015-November/007715.html
  [^random]: Random832 at 2 Dec 2015 00:44:02 UTC https://www.tuhs.org/pipermail/tuhs/2015-December/007722.html
  [^mcilroy4]: Doug McIlroy at 8 Dec 2015 18:20:12 UTC https://www.tuhs.org/pipermail/tuhs/2015-December/007777.html
  [^anthony]: Charles Anthony at 8 Dec 18:47:57 UTC https://www.tuhs.org/pipermail/tuhs/2015-December/007778.html
  [^toomey2]: Warren Toomey at 26 Dec 2015 14:09:03 UTC https://www.tuhs.org/pipermail/tuhs/2015-December/007981.html
  [^cat-v]: cat-v.org. ["UNIX Edition Zero"](https://doc.cat-v.org/unix/v0/)
  [^losh]: Warner Losh. ["Hidden Early History of Unix"](https://papers.freebsd.org/2020/fosdem/losh-hidden_early_history_of_unix/).
    FOSDEM '20
  [^archibald]: Thalia Archibald from this project
  [^mcilroy5]: Doug McIlroy at 10 Dec 2025 20:34:49 UTC, private correspondence,
    "I found my hard copy. Alas, page A7 is truly missing."

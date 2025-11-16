# General sources for early UNIX licensees

- [*A Statistical Examination of The Evolution of the UNIX System*](http://jsg.id.au/misc/Shamim_Sharfuddin_Pirzada-1988-PhD-Thesis.pdf) \
  Shamim Sharifuddin Pirzada \
  Imperial College of Science, Technology and Medicine, University of London \
  Doctor of Philosophy thesis, September 1988

  TODO: Pages 64–182.

  - Summer 1971: the patent office was successfully preparing their patent
    applications on UNIX [page 31]
  - V2 in June 1972: 10 installations [page 33, V2 manual]
  - c.1972/1973: SCCS-C forked from V2/V3 [page 32, my interpretation]
  - V3 in February 1973: 16 installations [page 33, V3 manual]
  - Ken had a list of the first 25 licensees (later licensing was handled by
    AT&T and they have records) [page 64]
  - c.1973: PWB forked from V2/V3 [page 32, my interpretation]
  - October 1973: license to Columbia University (first educational license)
    [page 47]
  - October 1973: license to The Children's Museum in Boston (first
    non-educational recipient) [page 47]
  - c.1974: USG/1.0 forked from V3 [page 32, my interpretation]
  - February 1974: license to The Hebrew University of Jerusalem (first
    organization outside the US) [page 47]
  - May 1974: Queen Mary College in London [page 47]
  - July 1974: the Rand Corporation (first commercial license) [page 47]

  > *Sources*
  >
  > The lack of proper record keeping by all the UNIX groups has resulted in a
  > large amount of valuable "hard" information being lost, so this study (and,
  > to a greater extent, others before it) has had to rely on informal records
  > and recollections of pertinent staff.
  >
  > This section has been pieced together from almost complete collections of
  > the *UNIX Newsletter* (first published by the USG, see below), *;login:*
  > (the newsletter of USENIX, see below), licensing records, System Release
  > Descriptions, Manuals and even (for organization charts) old Bell Labs
  > telephone books! [page 29]

  > By the summer of 1971, the text processing had been implemented and patent
  > office was successfully preparing their patent applications on UNIX, hence
  > fulfilling their charter. [page 31]

  Graphic (my interpretation): SCCS-C forked from v2/v3 (c.1972/1973), PWB
  forked from v2/v3 (c.1973), USG/1.0 forked from v3 (c.1974) [page 32]

  > Ken Thompson and Dennis Ritchie published the first UNIX Programmers Manual
  > in November 1971 describing the system as it was at the end of the Origins
  > section described above. With the C compiler working, more people were
  > attracted to the UNIX programming environment. The system improved steadily
  > until, by June 1972, there were enough changes to warrant a republication of
  > the manual. The assembler and the loader had undergone some reorganisation
  > but the most important change in v2 was the introduction of the interprocess
  > communication mechanism: pipe. Pipes were to become one the distinguishing
  > features of UNIX. By this time the number of UNIX installations had grown to
  > ten.
  >
  > In the early days people who wanted UNIX systems just went along to the
  > Research Center and took a magnetic snapshot of what was on Thompson's
  > system at the time, there wasn't an official release or a distribution tape
  > as such. The version of UNIX on the Research Center was known after the
  > edition number of the current manual. So, for example, between the
  > publication of the first edition of the manual and before the second, the
  > system was known as version 1 or v1.
  >
  > The third edition of the manual was published in February 1973, to bring it
  > in line with the software changes to accommodate the upgrade to the
  > PDP-11/45. A number of applications programs were re-written in C as the
  > UNIX programmer population grew slightly. As the popularity of UNIX
  > increased (the number of installations increasing to 16), more attention was
  > paid to help the inexperienced users. [page 33]

  > The licensing agreements with educational institutions and other non-profit
  > organisations were very different to the commercial ones. Initially, the
  > Research Center was so keen to get it out of the door, that they were
  > against charging even a service fee but as the volume grew, they gave in.
  > The first educational licence was granted, in October 1973, to Columbia
  > University and Ken Thompson personally installed the system. Educational
  > licences for the latest Research versions are still offered for nominal
  > charges but Thompson no longer goes out to install them!
  >
  > The Children's Museum in Boston was the first non educational recipient of
  > UNIX in October 1973 and The Hebrew University of Jerusalem was the first
  > organization outside the US to obtain a licence, in February 1974. Queen
  > Mary College in London was granted a licence in May 1974 and the Rand
  > Corporation became the first commercial licensee, in July 1974. [page 47]

  > The system was initially distributed by dumping the contents of the CSRC
  > machine onto tape and sending the tape out with a covering letter and
  > minimal documentation (installation guide and manual) but a list of
  > installation was kept. New editions of the manual were prepared when it was
  > apparent to staff at CSRC that the manual no longer reflected the state of
  > the CSRC system, this was usually done informally and no official release
  > documents as such, were prepared. This strategy still exists today but the
  > distribution was handed over to the Computing Library at Bell Labs, which
  > set up slightly more formal arrangements based on distribution tapes
  > supplied by the CSRC, for the releases v6 - v8. [page 60]

  > *Research*
  >
  > UNIX gurus are commonly portrayed, for example in USENIX or EUUG
  > conferences, as unruly, casual and disorganised. This is somewhat borne out
  > by their record keeping record. The researchers were so concerned with
  > pushing at the frontiers of operating system technology (in writing UNIX)
  > that they did not bother to keep the 'old stuff'.
  >
  > Hence in the CSRC archives,<sup>2</sup> Getting hold of UNIX systems
  > representing each of the five versions before v6 has turned out to be a
  > major challenge since no dumps from that era survived in the CSRC archives.
  > The author was able to locate only one UNIX system corresponding to the v5
  > era, 3 and none before that. Since Research UNIX did get outside the CSRC,
  > from v3 onwards, there was a chance that someone might have preserved it but
  > there was no positive response to several requests in electronic newsgroups,
  > conferences etc. However, some old paper tapes and DECtapes of unknown
  > content were discovered underneath the floor-boards in the UNIX room.
  >
  > With a track record of poor record keeping, it came as a surprise when the
  > first six editions of the manual were found neatly bound in the UNIX room.
  > The seventh edition is generally available and the author has obtained
  > copies of eighth and ninth editions as well, making a complete set.
  >
  > Getting hold of other information on Research UNIX has been less fruitful.
  > Private records of changes made to the system were kept (e.g. `ken` kept
  > records of changes made to the kernel when UNIX was identifiably 'his baby',
  > in the early days) but got truncated every time the file got too big
  > (supposedly fairly often) and deleted at machine changes. So, changes
  > information is irrecoverably lost. Similarly system logs containing records
  > of system crashes etc. have also been lost over the years. However, a list
  > of the first 25 licensees was obtained from Thompson (who was handling the
  > distribution himself at that stage). Subsequently licensing was handled by a
  > Western Electric division and then AT&T Technologies (AT&T-T). AT&T-T have
  > detailed records but were not able to send them to the investigator in time
  > for inclusion in this study.
  >
  > 2\. In reality, their 'archive' is simply a room adjoining the UNIX room
  > where the dump tapes and other precious material are kept. There is
  > virtually no security, indeed, there isn't even a list of what is stored in
  > the room! [pages 63–64]

  Are these DECtapes under the floorboards the Dennis_Tapes?

- ["TUHS Distribution Release Dates"](https://www.tuhs.org/Archive/Distributions/RELEASE_DATES),
  modified 3 March 1998

  TODO: Review sources

  | Version           | Date               | Cite  |
  | ----------------- | ------------------ | ----- |
  | **Research UNIX** |                    |       |
  | 1st Edition       | November 3, 1971   | [QCU] |
  | 2nd Edition       | June 12, 1972      | [QCU] |
  | 3rd Edition       | February, 1973     | [QCU] |
  | 4th Edition       | November, 1973     | [QCU] |
  | 5th Edition       | June, 1974         | [QCU] |
  | 6th Edition       | May, 1975          | [QCU] |
  | 7th Edition       | January, 1979      | [QCU] |
  | 8th Edition       | February, 1985     | [QCU] |
  | 9th Edition       | September, 1986    | [QCU] |
  | 10th Edition      | October, 1989      | [QCU] |
  | **USDL UNIX**     |                    |       |
  | PWB/UNIX          | June 1977 (in use) | [QCU] |
  | Mini-UNIX         | around may 1977    | [QCU] |
  | 32V               | early 1979         | [LWU] |
  | **BSD Releases**  |                    |       |
  |      1BSD         | March 9, 1978      | [QCU] |
  |      2BSD         | mid 1978           | [QCU] |
  |      3BSD         | late 1979          | [QCU] |
  |    2.8BSD         | July, 1981         | [KSJ] |
  |  2.8.1BSD         | January, 1982      | [QCU] |
  |    2.9BSD         | July, 1983         | [KSJ] |
  |  2.9.1BSD         | November, 1983     |       |
  |    2.9BSD-Seismo  | August, 1985       | [SMS] |
  |   2.10BSD         | April, 1987        | [KKK] |
  | 2.10.1BSD         | January, 1989      | [SMS] |
  |   2.11BSD         | February, 1992     | [SMS] |
  |   2.11BSD #366    | February, 1997     | [SMS] |

  Sources:
  - QCU= A Quarter Century of UNIX \
    Peter Salus \
    Addison-Wesley \
    ISBN 0-201-54777-5
  - LWU= Life With UNIX \
    Don Libes, Sandy Ressler \
    Prentice-Hall \
    ISBN 0-13-536657-7
  - SMS= Steven Schultz \
    sms@moe.2bsd.com
  - KKK=
  - KSJ=

- ["Licenses on Unix"](https://venam.net/blog/unix/2017/06/04/licenses.html) \
  Patrick Louis, 4 June 2017

  The first source license was sold in 1975, to UIUC for UNIX V5. Berkeley
  obtained UNIX V5 in 1974.

  TODO: Find primary sources

  > Unix wise, before 1975, all the Research Unix that Bell Labs produced were
  > for internal use only. It was only in 1975 that the first source license for
  > UNIX V5 was sold to the University of Illinois Department of Computer
  > Science, UIUC. This was a great move for the university of Illinois because
  > they started working on implementing ARPANET on those Unix machines,
  > creating the RFC 681, for NETWORK UNIX, with FTP and telnet clients. The
  > first Unix later to included them was BSD.
  >
  > At the time, Bell Labs wanted to sell licenses but for non-university users
  > it wanted to sell them at $20K which was very expensive. The V6 version of
  > UNIX did turn that around and was the first commercially successful UNIX. It
  > remained the most widely used version into the 80s. V7 superseded it later
  > in 1978, but V6 still remained the most used. As we’ve said, at those time
  > the source code was available to anyone who got the software, and so it was
  > a great tool to teach in universities. The license they provided with the
  > software didn’t explicitly say anything special about sharing the source,
  > licenses for softwares didn’t mean much yet.
  >
  > One of the university who got hold of UNIX V5 in 1974 was the university of
  > Berkely. Now you might wonder, “that’s before 1975”, yes it is, because no
  > license was sold to Berkeley, at least not yet. It all happened because a
  > teacher named Bob Fabry was teaching a course about OS principles and took
  > UNIX as an example. It was more like an informal notice written by the
  > developers themselves.

- ["Hidden Early History of Unix"](https://papers.freebsd.org/2020/fosdem/losh-hidden_early_history_of_unix/) \
  Warner Losh \
  FOSDEM '20

  > **PDP-7 Unix**
  > - […]
  > - Ported to PDP-7, PDP-9 and PDP-15
  >   - Total install base was 4 (1 pdp-7, 2 pdp-9 and 1 pdp-15)

  > **4th Edition (November 1973)**
  >
  > - […]
  > - Key revision for Bell System adoption and specialization
  > - First version released to Universities (4 or 5 universities)
  > - USENIX forms

  > **When was the first fork Unix version?**
  >
  > - BSD forking 7th Edition (well, 32V, 7th edition for VAX)? (1980)
  > - PWB 1.0 fork of 6th Edition? (Started 1973, first release 1977)
  > - USG fork of UNIX/TS 1.0 from 6th Edition? (Started 1973, first release
  >   1975)
  > - MERT forking UNIX/RT from 4th Edition? (1973)
  > - New Jersey Bell forking SCCS from 1st/2nd Edition? (1971/1972)
  >
  > - Close to a 4 way tie for the honors of FIRST

  References: [The Bell System Technical Journal](https://archive.org/details/bstj-archives?query=unix),
  1978–1983

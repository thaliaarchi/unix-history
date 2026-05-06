# General sources for early UNIX licensees

- "oldest surviving Unix machine?"
  [[Google Groups](https://groups.google.com/g/net.unix-wizards/c/XX9wwC2PMFk/m/ngH-OcxV1SoJ),
  [Usenet Archives](https://www.usenetarchives.com/view.php?id=net.unix-wizards&mid=PDUyOTlAdXR6b28uVVVDUD4)] \
  Henry Spencer \
  net.unix-wizards, 19 March 1985

  Early UNIX installations still running as of 1985:
  - Installed late 1972 or early 1973: Bell System 8th-Street site in LA
    (PDP-11/20? running Cosnix, a hacked derivative of V3)
  - After that: Bell Labs Whippany (PDP-11/45 #570 running Cosnix)
  - Columbia received Unix license number one
  - Late 1973: V4 licenses for University of Alberta (PDP-11/45 #315), Johns
    Hopkins University (PDP-11/45 #493, given to the Chemistry Department), and
    the Cooper Union (PDP-11/45, now running V6)
  - Late 1974: University of Toronto's original PDP-11/45
  - Late winter or spring 1975: University of Vermont, Vermont Lung Center
    (PDP-11/40 running an early V6)

  Henry Spencer at 19 March 1985 13:09:05 UTC:

  ```
  Out of curiosity, I'm interested in locating the oldest Unix machine
  that is still running Unix. U of T's original 11/45 is idle right now
  but will be running Unix again shortly; this sets a "latest bound" on
  the oldest machine, since our 45 appears to have been running Unix late
  in 1974. This was one of the first 20 or so licensed Unixes outside Bell.
  An older machine would have to be either inside Bell, or one of those
  early few.

  If the oldest machine turns out to be within Bell, I'm also interested
  in the oldest non-Bell Unix machine.

  Whatever machine is the oldest, it's not at the Murray Hill research
  lab. I've already asked Dennis about this; nothing in his vicinity
  is particularly old.

  Since PDP-7 Unix can safely be assumed to be dead, the oldest Unix
  machine will have to be an 11. Specifically, it will have to be a
  45, a 40, or just possibly a 20, since our 45 pre-dates the official
  announcement of the 70.

  Please reply to me by mail; I will post the results.
  --
  Henry Spencer @ U of Toronto Zoology
  {allegra,ihnp4,linus,decvax}!utzoo!henry
  ```

  Ed Gould at 25 March 1985 18:54:17 UTC:

  ```
  > Since PDP-7 Unix can safely be assumed to be dead, the oldest Unix
  > machine will have to be an 11.
  > --
  > Henry Spencer @ U of Toronto Zoology

  Well, maybe not! DEC dragged a PDP-7 to its booth at UniForum in
  Dallas, and although they didn't get it running Unix for that
  show they were hot on the trail of a Unix tape for it. Maybe
  in Portland or Anaheim? (Are you interested in a machine that was
  running Unix in ancient times or an ancient machine running Unix?
  Clearly this is the latter.)

  --
  Ed Gould mt Xinu, 739 Allston Way, Berkeley, CA 94710 USA
  {ucbvax,decvax}!mtxinu!ed +1 415 644 0146
  ```

  Henry Spencer at 30 March 1985 19:41:30 UTC:

  ```
  There are indeed people within Dec who are making a serious effort to
  get Unix V1 running on a PDP-7. But my specific interest is in things
  that have been running Unix all along, not Unix newly brought up on a
  machine that happens to be an antique. (Anyone for a 7094 Unix port?)

  To give people a quick progress report on what I've found, the oldest
  Unix machine is unquestionably within Bell. There are still some old
  11s running derivatives of the assembler version of Unix, i.e. V3 or
  earlier. Obviously they are running canned applications, not serving
  as development environments. The oldest non-Bell Unix is less clear,
  and I'm still getting information on this. Our old 11/45 has quite
  definitely lost, by the way, since there were a handful of Unixes in
  the field rather earlier (probably before official licensing started,
  unless I've got the dates wrong).


  --
  Henry Spencer @ U of Toronto Zoology
  {allegra,ihnp4,linus,decvax}!utzoo!henry
  ```

  Al Baldwin at 3 April 1985 16:19:42 UTC:

  ```
  While I was in research at the University of Vermont, a group involved
  with the Vermont Lung Center program project grant bought an 11/40.
  After much frustration attempting to use RSX-11M Ver. 2.0 (for those
  who know, multi-user on "M" in those days was a dream), the person
  responsible for the system was convienced to try the "new" OS from
  Bell Labs. As I recall, this was around late winter or spring of 1975.
  The UN*X was version 6 (but real early). The system consisted of:

  PDP-11/40 CPU with EIA and FIS (useless for UN*X!!).
  32K core memory (DEC)
  16K core memory (Plessey)
  Dual RK03 2.4 meg. disk drives
  6 DL11-E single line interfaces
  Children's Museum's RK05 and DL11-E drivers

  That's right, a 48K machine. This machine ran like this until
  1979 when it was upgraded to an 11/45 (64K) + RK06's. I inherited
  the system in 1978 (and promptly worked an upgrade). The 11/45 ran
  until the project folded in 1984. Throughout the entire time, the
  original V6 code was used (no upgrade to V7 due to the applications).

  What I found impressive was the fact that not one line of kernel
  code was modified during that time (only I/O driver code, RK06s,
  tty driver, etc.). Most all of the system failures were due to
  power fails (V6 didn't cope with that condition well), or hardware
  problems. In fact, it was not uncommon towards the end for the 11/45
  system to run 3 or 4 months between reboots (and then only for PM).


  Al Baldwin
  AT&T-Bell Labs
  ...!ihnp4!hou2d!afb3


  [These opinions are my own....Who else would want them!!!]
  ```

  "oldest Unix machine(s)"
  [[Google Groups](https://groups.google.com/g/net.unix-wizards/c/4zZR9FyzM8k/m/0Xu77eACHEAJ),
  [Usenet Archives](https://www.usenetarchives.com/view.php?id=net.unix-wizards&mid=PDU1ODRAdXR6b28uVVVDUD4)] \
  Henry Spencer \
  net.unix-wizards, 10 May 1985

  Henry Spencer at 10 May 1985 13:38:56 UTC:

  ```
  Well, the mail about still-operational ancient Unix machines has petered
  out, so here's the summary of results that I promised. For the purposes
  of terminology in this article, I will pretend that Bell-System divestiture
  didn't happen, since virtually all the events in question happened before
  the breakup.

  The oldest still-running Unix machine is unquestionably within the Bell
  System. The Murray Hill research lab long since put its old machines
  out to pasture, but there are some very old applications machines still
  operational.

  In particular, there are machines still running Cosnix, which was a hacked
  derivative of the assembly-language Unix (V3). Obviously these are not
  now used much as development machines, but as turnkey applications systems.
  Incidentally, some, possibly all, of the applications are written in the
  old "fc" semi-interpretive Fortran! 11/45 number 570 (numbers started at
  100, Research's 45 was 110) is still running Cosnix at Bell Labs Whippany.
  There is a still-older Cosnix machine in the Bell System 8th-Street site
  in LA; it was installed in late 72 or early 73. Considering the timing,
  this might be an 11/20 rather than a 45. This would appear to be the
  Grand Prize winner for oldest Unix still operating.

  Outside the Bell System, the picture is less clear. Unix license number
  one went to Columbia, but this may not be too significant; I don't have
  dates for the licenses, and in any case license dates don't necessarily
  correlate with operational dates. Of the people I actually got responses
  from, it would appear to be a three-way tie, all for V4 in late 1973,
  between U of Alberta (11/45 #315, still running), Johns Hopkins U (11/45
  #493, given to Chemistry Dept. but believed still running), and the Cooper
  Union for the Advancement of Science and Art (a small NYC engineering
  school) (11/45, #???, still running, possibly still V4!).

  Corrections and addenda would be appreciated.

  Thanks to all the people who replied with information, notably Dennis
  Ritchie and John Mashey for the info on the Cosnix systems.
  --
  Henry Spencer @ U of Toronto Zoology
  {allegra,ihnp4,linus,decvax}!utzoo!henry
  ```

  Roy Smith at 12 May 1985 10:24:38 UTC:

  ```
  > and the Cooper Union for the Advancement of Science and Art (a small NYC
  > engineering school) (11/45, #???, still running, possibly still V4!).

  Yes, Cooper still has their '45 going strong, but with V6. I
  learned on that machine during my undergrad years there (1977-81). They
  added a 160 Mb fuji since I left, but still boot off the 2 RK-05's they had
  when I got there (yup, 5 Mb total disk space).

  Isn't it amazing how 32 people can do real work on a machine with
  256K of core (I think they finally upgraded to MOS ram) and a kernal that
  only takes up about 20K?
  --
  allegra!phri!roy (Roy Smith)
  System Administrator, Public Health Research Institute
  ```

- *The Times Index*

  TODO: Finish searching "unix" in ["Times (London, England : 1931) -- Indexes -- Periodicals"](https://archive.org/search?query=subject%3A%22Times+%28London%2C+England+%3A+1931%29+--+Indexes+--+Periodicals%22)

  - [*The Times Index*](https://archive.org/details/timesindex0000unse_l1f1?q=unix) \
    January–December 1983

    - "'Unix aims for UK micro market'" in *The Times*, 5 November 1983, pages 8
      and 20f [page 237 "Computers, Software, Articles"]

  - [*The Times Index*](https://archive.org/details/timesindex0000unse_m9o8?q=unix) \
    January–December 1986

    - Unix discussed in *The Sunday Times*, 24 August 1986, Special Report
      article, page 53a [pages 21 "American Telephone and Telegraph" and 208
      "Operating Systems"]
    - "former ICL chief claims new set of conversion tools will take systems
      written under IBM's mainframe operating environment and convert them for
      Unix in a tenth of time take with ordinary manual methods" in *The Times*,
      20 May 1986, page 32d [page 208 "Operating Systems"]

  - [*The Times Index*](https://archive.org/details/timesindex0000unse_p3k4?q=unix) \
    January–December 1999

    - "IBM set to sell Linux operating system developed by Finnish student with
      its corporate computer networks in threat to Microsoft Windows product" in
      *The Times*, 20 February 1999, page 23a [page 299 "Operating systems"]
    - "Microsoft criticised over plans to incorporate Windows Game Manager into
      operating system software to restrict children's access to unsuitable
      games" in *The Sunday Times*, 4 July 1999, pages 2 and 18a [page 299
      "Operating systems"]
    - "Govt Information Service which manages Queen's Website switches from
      using Unix operating system to Linux" in *The Times*, 18 October 1999,
      page 3c [page 299 "Operating systems", 434 "Internet and World Wide Web",
      and 707 "Internet and World Wide Web, Access"]

- [*A Statistical Examination of The Evolution of the UNIX System*](https://www.tuhs.org/Archive/Documentation/Theses/Shamim_Sharfuddin_Pirzada-1988-PhD-Thesis.pdf) \
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

- [*Life with UNIX: A Guide for Everyone*](https://www.tuhs.org/Archive/Documentation/Books/Life_with_Unix.pdf) \
  Don Libes and Sandy Ressler, 1989

  A good early history: MULTICS, PDP-10 request, Space Travel, PDP-7, patent
  office, pipes, NB kernel rewrite attempt, C structs and globals, kernel and
  shell rewritten in C, UNIX Systems Group for internal support, V4 distributed
  to several universities, CACM '74 paper, V5 for educational, V6 widely used,
  commercial licenses bug reports to `research` over uucp, PWB, V6, Mike Lesk's
  Portable C Library (later rewritten by Dennis as stdio), first UNIX users
  meeting in NYC with 40 attendees, UNIX News, Lions' Commentary, various ports
  (Interdata 8/32, Interdata 7/32, VM/370), 1BSD, V7 with K&R C and Bourne
  shell, 32V, Whitesmiths C. [pages 3–12].

  > In 1973, C was enhanced to support structures and global variables. At this
  > point, Ken and Dennis successfully rewrote the UNIX kernel in C. The shell
  > was also rewritten (from assembler) into C. This improved the robustness of
  > the system and made programming and debugging much easier.
  >
  > At this point, there were approximately 25 UNIX systems. A UNIX Systems
  > Group was created at the Labs for internal support. Several universities
  > contacted Bell Labs and received copies of the Fourth Edition. Agreements
  > were signed not to disclose the source code, but no licenses were in use at
  > this point. Ken made the tapes himself and didn’t charge anything. The first
  > tapes went to Columbia University in New York.
  >
  > In 1974, Ken and Dennis published a paper in Communications of the ACM,
  > describing the UNIX system. At that time, Communications was the premier
  > journal for computer science research, and the article raised interest in
  > UNIX considerably throughout academia. The Fifth Edition was officially made
  > "The number of UNIX installations has grown to 10, with more expected." –
  > The UNIX Programmer’s Manual, Second Edition, available to universities "for
  > educational purposes." The price was nominal – enough to cover the cost of
  > reproducing a set of tapes and manuals. The Fifth Edition was used as a
  > teaching aid at many universities. [page 7]
  >
  > In 1975, the Sixth Edition UNIX system was released. This was the first UNIX
  > that became widely used outside the Labs. AT&T (through Western Electric
  > Co.) began offering licenses to commercial and government users. [page 8]

  > By the end of 1978, there were over 600 UNIX installations. Most were
  > universities and government facilities. [page 12]

  > According to Tannenbaum:†
  >
  > > BTL didn’t really have a distribution policy in the early days, you got a
  > > disk with a note:
  > >
  > > > Here’s your rk05, Love, Dennis.
  > >
  > > If UNIX crapped on your rk05, you’d write to Dennis for another.
  >
  > Eventually, Bell succumbed to the pressure for distributing UNIX. It
  > developed a simple licensing policy: No support, no trial period, no
  > warranties, no advertising, no bug fixes, and payment in advance.
  >
  > † Andy Tannenbaum, "Politics of UNIX," Washington, DC USENIX
  > Conference, 1984. [page 13]

  TODO: Read Tannenbaum source.

  > However, a tremendous number of people were using UNIX at Bell internally.
  > In order to support all these projects, a UNIX support group called USG
  > (UNIX Support Group) was created. Unfortunately, USG was allowed only to
  > provide support, not to do any development. The result was that, both inside
  > and outside Bell, users did their own development. This was further
  > encouraged by the complete access to the source code that came with UNIX.
  > USG created several releases of UNIX, most of them only available inside the
  > Labs. [page 13]

  Which internal releases?

  TODO: Continue reading from page 15

- [*A Quarter Century of UNIX*](https://archive.org/details/aquartercenturyofunixpeterh.salus_201910) \
  Peter H. Salus, 1994

  TODO: Read this.

- ["Unix at 25"](https://web.archive.org/web/19961220135639/http://www.byte.com/art/9410/sec8/art3.htm) \
  Peter H. Salus \
  BYTE, October 1996

  TODO: Cite relevant sections.

- ["History of Computing at Bell Labs"](https://research.swtch.com/bell-labs) \
  Doug McIlroy \
  Bell Labs retirement talk, 1997

  > 28:40 During the 60s, we undertook an enormous development project in the
  > guise of research, which was MULTICS, and it was the notion of MULTICS was
  > computing was the public utility of the future. Machines were very
  > expensive, and ?indeed? like you don’t own your own electric generator, you
  > rely on the power company to do generation for you, and it was seen that
  > this was a good way to do computing -- time sharing -- and it was also
  > recognized that shared data was a very good thing. MIT pioneered this and
  > Bell Labs joined in on the MULTICS project, and this occupied five years of
  > system programming effort, until Bell Labs pulled out, because it turned out
  > that MULTICS was too ambitious for the hardware at the time, and also with
  > 80 people on it was not exactly a research project. But, that led to various
  > people who were on the project, in particular Ken Thompson -- right there --
  > to think about how to -- Dennis Ritchie and Rudd Canaday were in on this too
  > -- to think about how you might make a pleasant operating system with a
  > little less resources.
  >
  > 30:30 And Ken found -- this is a story that’s often been told, so I won’t go
  > into very much of unix -- Ken found an old machine cast off in the corner,
  > the PDP-7, and put up this little operating system on it, and we had immense
  > GE635 available at the comp center at the time, and I remember as the
  > department head, muscling in to use this little computer to be, to get to be
  > Unix’s first user, customer, because it was so much pleasanter to use this
  > tiny machine than it was to use the big and capable machine in the comp
  > center. And of course the rest of the story is known to everybody and has
  > affected all college campuses in the country.

  Talks about a team which troubleshooted a race condition in an anti-missile
  defense system for a year.

  TODO: Read referenced *A History of Engineering & Science in the Bell System:
  Communications Sciences, 1925-1980* by S. Millman (1984)

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

- Ohio LinuxFest 2009, "40 years of UNIX" \
  Columbus, Ohio, 25 and 26 September 2009 \
  [[audio](https://archive.org/details/OhioLinuxfest2009)]
  [[registration](https://www.developerfusion.com/event/50984/ohio-linuxfest-2009-sept-25-27/)]

  TODO: All three talks have noisy audio, which captured the background noise of
  the ballroom. Clean up the audio and upload to the Internet Archive.

  TODO: Listen to these talks.

  - "Shared Destiny: 40 Years of UNIX, 40 Years of VM, and How They Came Together" \
    David Boyes and Scott Courtney, 26 September 2009
    [[video](https://www.youtube.com/watch?v=_Fgsam53mM8)]
    [[noisy audio](https://archive.org/details/OhioLinuxfest2009/32-David_Boyes_and_Scott_Courtney-Shared_Destiny_40_Years_of_UNIX_and_VM.flac)]

    Abstract:
    > As UNIX was being born at Bell Labs, the VM operating system was being
    > born at IBM. Though mainframe Linux is a comparatively recent phenomenon,
    > VM and UNIX share common roots that are subtle but deep, with a rich
    > heritage of open source code, community involvement, and developer
    > passion. We explore the history of VM that led it to be such a fine
    > platform for Linux, and how UNIX and UNIX tools evolved in the mainframe
    > hardware environment in the decades before Linux.

  - "The Importance of 1969" \
    Peter Salus, 26 September 2009
    [[noisy audio](https://archive.org/details/OhioLinuxfest2009/42-Peter_Salus-The_Importance_of_1969.flac)]

    Abstract:
    > In January 1969 the planning that resulted in the Internet and the Web was
    > begun. At the end of that year, on December 28, Linus Torvalds was born.
    > Join Peter as he tracks that year and the influences that have brought us
    > to Columbus.

  - "A Surfeit of Sophistication" \
    M. Douglas McIlroy, 26 September 2009
    [[noisy audio](https://archive.org/details/OhioLinuxfest2009/92-M_Douglas_McIlroy-A_Surfeit_of_Sophistication.flac)]

    Abstract:
    > Hidden complexity in the service of simplicity is no vice. But one's heart
    > sags in the face of complexity that bubbles to the surface in hundred-page
    > "man pages" and thousand-line makefiles. Sophistication, unfortunately, is
    > the easy way to get noticed, while simplification is often subliminal. As
    > an unabashed cheerleader for the underdog, I will try to redress the
    > imbalance by looking at some incidents large and small of the tug-of-war
    > between these two poles.

    Doug was [interviewed](https://vimeo.com/7203377#t=1691.453) by Aaron
    Newcomb of the_source about his talk.

- [[TUHS] ed.c on Unix v5](https://www.tuhs.org/pipermail/tuhs/2015-December/007908.html) \
  Marc Rochkind, TUHS, 19 December 2015

  > Right. Obviously Doug can supply the details, but I recall that around 1972
  > or so Dick Haight used to go over from Piscataway to Murray Hill to get a
  > new system, and there would be some sort of indication about whether it was
  > a good day or a bad day to make a tape.

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

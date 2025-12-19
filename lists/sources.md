# Sources for lists of early UNIX users

- ["The UNIX Time-Sharing System"](https://dl.acm.org/doi/10.1145/800009.808045) \
  Dennis M. Ritchie and Ken Thompson \
  Bell Laboratories \
  Fourth ACM Symposium on Operating Systems Principles,
  IBM Thomas J. Watson Research Center, Yorktown Heights, New York,
  15–17 October 1973.

  TODO: Locate copy. Only the abstract is available.

- ["The UNIX Time-Sharing System"](https://dl.acm.org/doi/10.1145/361011.361061) \
  Dennis M. Ritchie and Ken Thompson \
  Bell Laboratories \
  Communications of the ACM, Volume 17, Number 7, July 1974 \
  [[digitized](https://dsf.berkeley.edu/cs262/unix.pdf)]

  > UNIX is a general-purpose, multi-user, interactive operating system for the
  > Digital Equipment Corporation PDP-11/40 and 11/45 computers.

  > This is a revised version of a paper presented at the Fourth ACM Symposium
  > on Operating Systems Principles, IBM Thomas J. Watson Research Center,
  > Yorktown Heights, New York, October 15-17, 1973.

  > There have been three versions of UNIX. The earliest version (circa 1969-70)
  > ran on the Digital Equipment Corporation PDP-7 and -9 computers. The second
  > version ran on the unprotected PDP-11/20 computer. This paper describes only
  > the PDP-11/40 and /45 [1] system since it is more modern and many of the
  > differences between it and older UNIX systems result from redesign of
  > features found to be deficient or lacking.
  >
  > Since PDP-11 UNIX became operational in February 1971, about 40
  > installations have been put into service; they are generally smaller than
  > the system described here. Most of them are engaged in applications such as
  > the preparation and formatting of patent applications and other textual
  > material, the collection and processing of trouble data from various
  > switching machines within the Bell System, and recording and checking
  > telephone service orders. Our own installation is used mainly for research
  > in operating systems, languages, computer networks, and other topics in
  > computer science, and also for document preparation.

  > 72 user population \
  > 14 maximum simultaneous users \
  > 300 directories \
  > 4400 files \
  > 34000 512-byte secondary storage blocks used

- ["The UNIX Time-Sharing System"](https://archive.org/details/bstj57-6-1905) \
  Dennis M. Ritchie and Ken Thompson \
  Bell Laboratories \
  The Bell System Technical Journal, Volume 57, Number 6, pages 1905–1929,
  July–August 1978 \
  [[HTML by Dennis Ritchie](https://www.nokia.com/bell-labs/about/dennis-m-ritchie/cacm.html)]
  [[digitized PDF](https://www.scs.stanford.edu/nyu/04fa/sched/readings/unix.pdf)]

  > (Manuscript received April 3, 1978)

  > UNIX* is a general-purpose, multi-user, interactive operating system for the
  > larger Digital Equipment Corporation PDP-11 and the Interdata 8/32
  > computers.

  > † Copyright 1974, Association for Computing Machinery, Inc., reprinted by
  > permission. This is a revised version of an article that appeared in
  > Communications of the ACM, 17, No. 7 (July 1974), pp. 365-375. That article
  > was a revised version of a paper presented at the Fourth ACM Symposium on
  > Operating Systems Principles, IBM Thomas J. Watson Research Center, Yorktown
  > Heights, New York, October 15-17, 1973.

  > There have been four versions of the UNIX time-sharing system. The earliest
  > (circa 1969-70) ran on the Digital Equipment Corporation PDP-7 and -9
  > computers. The second version ran on the unprotected PDP- 11/20 computer.
  > The third incorporated multiprogramming and ran on the PDP-11/34, /40, /45,
  > /60, and /70 computers; it is the one described in the previously published
  > version of this paper, and is also the most widely used today. This paper
  > describes only the fourth, current system that runs on the PDP-11/70 and the
  > Interdata 8/32 computers. In fact, the differences among the various systems
  > is rather small; most of the revisions made to the originally published
  > version of this paper, aside from those concerned with style, had to do with
  > details of the implementation of the file system.
  >
  > Since PDP-11 UNIX became operational in February, 1971, over 600
  > installations have been put into service. Most of them are engaged in
  > applications such as computer science education, the preparation and
  > formatting of documents and other textual material, the collection and
  > processing of trouble data from various switching machines within the Bell
  > System, and recording and checking telephone service orders. Our own
  > installation is used mainly for research in operating systems, languages,
  > computer networks, and other topics in computer science, and also for
  > document preparation.

  > Overall, we have today:
  >
  > 125 user population \
  > 33 maximum simultaneous users \
  > 1,630 directories \
  > 28,300 files \
  > 301,700 512-byte secondary storage blocks used

- ["Unix Programmer's Manual: Second Edition"](http://squoze.net/UNIX/v2man/man0) \
  Ken Thompson and Dennis Ritchie, June 12, 1972

  > Finally, the number of UNIX installations has grown to 10, with more
  > expected.

- ["Unix Programmer's Manual: Third Edition"](http://squoze.net/UNIX/v3man/man0) \
  Ken Thompson and Dennis Ritchie, February 1973

  > Finally, the number of UNIX installations has grown to 16, with more
  > expected.

- ["Unix Programmer's Manual: Fourth Edition"](http://squoze.net/UNIX/v4man/man0.pdf) \
  Ken Thompson and Dennis Ritchie, November 1973

  > The number of UNIX installations is now above 20, and many more are
  > expected.

- ["Unix Programmer's Manual: Fifth Edition"](http://squoze.net/UNIX/v5man/man0.pdf) \
  Ken Thompson and Dennis Ritchie, June 1974

  > The number of UNIX installations is now above 50, and many more are
  > expected.

- List of UNIX licensees, Ken Thompson, 27 June 1975 \
  [Dennis_Tapes](https://www.tuhs.org/Archive/Applications/Dennis_Tapes/)
  `dmr_tapes.tgz/ken/distr/{form.m,nmrc}`,
  The Unix Heritage Society: \
  51 UNIX licensees listed and 55 installations listed

  In a DECtape donated by Dennis Ritchie is a `fed(6)`/`form(6)` form letter
  document from Ken listing UNIX licensees that closely resembles the first UNIX
  News list. It is generated with the `nmrc` shell script in V6. See Jonathan
  Gray's [2023-07-12 TUHS message](https://www.tuhs.org/pipermail/tuhs/2023-July/028601.html)
  discovering this.

  The metadata from `dir`:

  ```
  Mode       UID GID  Size Date                Name
  ---------- --- --- ----- ------------------- ---------------
  -rw-rw-rw-   6   1 20992 1975-06-27 20:30:20 ./distr/form.m
  -rw-rw-rw-   6   1   114 1975-06-27 20:31:44 ./distr/nmrc
  ...
  ```

- List of UNIX users in BTL, Ken Thompson, 3 July 1975 \
  [Dennis_Tapes](https://www.tuhs.org/Archive/Applications/Dennis_Tapes/)
  `dmr_tapes.tgz/ken/let/unix.r`,
  The Unix Heritage Society:
  11 people listed

  The metadata from `dir`:

  ```
  Mode       UID GID  Size Date                Name
  ---------- --- --- ----- ------------------- ---------------
  -rw-rw-rw-   0   1   813 1975-07-03 16:58:38 ./let/unix.r
  ```

- UNIX News [July 16, 1975](https://www.tuhs.org/pipermail/tuhs/2023-October/029087.html):
  at least 49 UNIX licensees counted

  The number of worldwide UNIX licenses [[Hendrik-Jan Thomassen](https://www.youtube.com/watch?v=boahlBmc-NY&t=2434s)
  at 41:06]:
  > Circulation 49 [page 1]

  This letter was one year after KU Nijmegen received their copy [at 41:18].

- UNIX News [July 30, 1975](https://archive.org/details/unix_news_july-30-1975),
  pages 9–11: 37 members listed and at least 51 UNIX licenses counted

  The number of UNIX News members:
  > Circulation 37 [page 1]

  > There were no objections to publishing the mailing list and so we are
  > including it in this issue.  The integer part of the sequence number on the
  > first line corresponds to a list of licensees that Ken Thompson keeps.  The
  > fractional part designates multiple installations under a single license.
  > Since we now have several such, we will mail a copy of the newsletter to
  > each, provided we receive a returned copy of the coupon on the invitation to
  > subscribe.
  >
  > The original letter went to approximately 76 people, all but 6 of whom
  > replied.  Subsequent letters recently went to 20 new installations and, to
  > date the mailing list contains 37 names.  Our only communications problems
  > are with locations where the only name is a contracts officer and with
  > multiple installations.  I would ask each of you to scan the list of names
  > and let me know of any installations you know of which are not on the list.
  > [page 1]

  Any installations which did not respond to the letter were removed from the
  list, creating the gaps in the Ken's sequence numbers. The highest number in
  the sequence is 51, which matches Ken's list from a month prior, so it is
  unlikely there were any new licensees since then.

  > UNIX at the Children's Museum has been fully operational since August, 1974.
  > Development work jointly with Harvard University began the previous winter,
  > making us one of the first non-Bell users. [page 8]

- UNIX News [February 10, 1976](https://archive.org/details/unix_news_feb-10-1976),
  page 7b: about 20 West Coast UNIX Users attendees

  > A meeting of the West Coast UNIX Users was held at the Naval Postgraduate
  > School, Monterey, California on October 31.  About 20 people attended the
  > meeting.  The University of California accounted for about half the
  > participants, including representatives from the Berkeley, UCLA, and San
  > Diego campuses.  There were also people from the Stanford Medical School,
  > Data Disk, Inc. (Sunnyvale, Ca.), the Naval Postgraduate School, and Rand.

- UNIX News [March 19, 1976](https://archive.org/details/unix_news_march-19-1976),
  pages 11–14a: 80 members listed

  > **MAILING LIST**
  >
  > The attached mailing list is a major revision of the old list.  It is based
  > upon a list of licensees dated February 1976 and is ordered on state and by
  > zip code within the state.  It is likely that errors have crept in during
  > the editing.  Please check your listing and send in corrections.  An area of
  > difficulty is multiple installations under a single license.  If you know of
  > facilities other than those listed, please let us know. [page 3]

- UNIX News [July 1976](http://www.toad.com/early-usenix-newsletters/197607-unix-news-n7.pdf):
  over 125 members counted

  > **UNIX NEWS**
  >
  > The mailing list for UNIX NEWS is now over 125. [page 1]

- UNIX News [September 1976](https://archive.org/details/unix_news_september-1976),
  pages 2–6: 138 members listed

  > **MEMBERSHIP LIST**
  >
  > As previously announced, this issue of UNIX NEWS contains the Unix Users'
  > Group Membership list as of October 4, 1976.
  >
  > The list is ordered as follows:
  >
  > 1. United States sorted on two character state abbreviation and by zip-code
  >    within state.
  > 2. Canada sorted by postal code.
  > 3. Other Countries sorted on name of country.
  >
  > The list, in machine readable form, is on its way to Chicago Circle for
  > inclusion in the next software disribution. [page 1]

- "UNIX Time-Sharing System: A Retrospective" \
  Dennis Ritchie \
  Tenth Hawaii International Conference on the System Sciences, Honolulu,
  January 1977

  TODO: Locate copy

- ;login: [July 1977](https://archive.org/details/login_july-1977),
  pages 8–12: 168 members listed

  > **MAILING LIST**
  >
  > The mailing list for this issue is reproduced, with telephone numbers, in
  > this issue.  It also appears in the file "3/mlist.jul77" on the distribution
  > tape.  On the tape it is formatted in the same way as it was in
  > distribution 2.  The details are in directory "bklyn" of distribution 2.
  > [page 1]

- ;login: [October 1977](https://archive.org/details/login_october-1977):
  over 250 members counted

  > **USERS GROUP**
  >
  > The membership in the Users' Group now exceeds 250. [page 1]

- Australian UNIX Users Group Newsletter [October 1978](https://archive.org/details/auugnv01.1):
  38 AUUGN members [listed](../auugn/1978-10/4.txt)

- ["UNIX Time-Sharing System: A Retrospective"](https://archive.org/details/bstj57-6-1947) \
  Dennis Ritchie \
  The Bell System Technical Journal, Volume 57, No. 6, pages 1947–1969, \
  July–August 1978

  > Manuscript received January 6, 1978 [page 1]

  > A version of this paper was presented at the Tenth Hawaii International
  > Conference on the System Sciences, Honolulu, January, 1977. [page 1947]

  > Since its development in 1971, it has become quite widely used, although
  > publicity efforts on its behalf have been minimal, and the license under
  > which it is made available outside the Bell System explicitly excludes
  > maintenance. Currently, there are more than 300 Bell System installations,
  > and an even larger number in universities, secondary schools, and commercial
  > and government institutions. [page 1948]

- ;login: [February 1980](https://archive.org/details/login_february-1980),
  pages 19a–22b: 447 Boulder Usenix conference registrants listed

  > **THE BOULDER SOFTWARE TOOLS AND USENIX MEETINGS IN SUMMARY**
  >
  > **SOFTWARE TOOLS and USENIX Meetings** \
  > Boulder, Colorado \
  > January 28 -- February 2, 1980
  >
  > […]
  >
  > In general, there is rapid growth in the size of both these users groups;
  > there were 450 attendees at the USENIX meeting, which is the largest
  > attendance yet. [page 3a]

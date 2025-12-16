# Jay Lepreau sources

TODO: Jay Lepreau's [Flux profile](https://www.flux.utah.edu/profile/lepreau),
[CS site](https://web.archive.org/web/19970605053419/http://www.cs.utah.edu/~lepreau/),
[OSDI '94](https://web.archive.org/web/19970614003821/http://www.cs.utah.edu/~lepreau/osdi94/index.html).

- ["A Portable C Compiler for the DEC-20"](https://archive.org/details/pcc_for_dec-20_1981-04-24) \
  Jay Lepreau \
  Computer Science Department, University of Utah \
  24 April 1981

  A port of Steve Johnson's Portable C Compiler to the DECSYSTEM-20.

  Mentions computers used by the Computer Science Department at the University
  of Utah, including PDP-11s running UNIX, one of which is the primary machine
  used by the CAGD/graphics group, a DECSYSTEM-2060, used by the LISP group and
  the Applicative Multiprocessing (AMPS) group, and a VAX-11/750 to arrive in
  June 1981.

  > The primary research facility of the Computer Science Department is the
  > Decsystem-2060, but many smaller machines are also heavily used, including
  > several PDP-11's running Unix.  One of the 11's is the primary machine used
  > by the Department's well-known CAGD/graphics group.  A VAX-11/750 is
  > expected in June of this year, and promises to be of great importance to the
  > various experimental research programs.  Its large address space makes it
  > particularly attractive to several groups who have exhausted their
  > single-section address space on the 20, such as the LISP group and the
  > Applicative Multiprocessing (AMPS) group.

  Transcription in 1981-04-24_pcc_for_dec-20.txt.

- ["A 'Virtual Unix' for TOPS-20"](https://archive.org/details/vunix_talk_1982-01) \
  Jay Lepreau \
  Computer Science Department, University of Utah \
  USENIX, January 1982

  Abstract from [;login: January 1982](https://archive.org/details/login_january-1982/page/15/mode/1up):

  > They are building a virtual UNIX to run under TOPS-20 so they can access the
  > system languages and extended addressing of the DEC-20.  Their goals are to
  > provide the same file format for both TOPS-20 and "VUNIX", to be able to
  > access both environments from C, to keep kernel changes invisible to user
  > programs, and to not hack TOPS-20.  The order of projects has been to make
  > PCC work, then provide a V7 environment, then transport user programs. Major
  > problems encountered include the 20’s 36 bit word (standard byte size is 7
  > bits!), line terminators (CR/LF-LF), long file names, and no links.
  >
  > They have found that the "portable" C compiler is not particularly portable
  > to word-addressable machines.  They also found problems with the C language
  > specifications when the target machine is dissimilar to the canonical PDP-11
  > architecture.

  From the presentation notes:

  > Bootstrapping Hosts
  >
  > 1. 11/34 V6
  >    - PCC + YACC V7 split I/D
  > 2. 11/45 V6
  > 3. 11/45 V7
  >
  > [page 5]

- ["2007 and 2008 Report"](https://www-old.cs.utah.edu/docs/misc/0708-report.pdf) \
  School of Computing, University of Utah

  > Jay’s career at the University of Utah spanned more than a quarter century.
  > In 1980, he joined the Department of Computer Science as an undergraduate
  > student and programmer, under the direction of Randy Frank. After earning
  > his degree in 1983, Jay became the manager of the systems programming group.
  > He helped introduce Utah to UNIX, and by 1987, Jay was the acting head of
  > the department’s computing facility which included 100 or so HP, Apollo, and
  > Sun workstations as well as a few “legacy” VAX computers.
  >
  > In the late 1980s, Jay received funding from Hewlett-Packard to port BSD
  > UNIX to HP workstations, leading to the first release of “HP BSD 4.3”
  > in 1988. Jay became the Assistant Director of the department’s Center for
  > Software Science (CSS) in 1990, where he and his staff continued to receive
  > funding to work on systems software such as the GNU compiler tools and the
  > Mach operating system. The work quickly shifted from engineering to
  > research, and in 1994, Jay received his first major ARPA contract to
  > investigate “Fast and Flexible Mach-based Systems.” Also in 1994, Jay served
  > as the program chair for the first-ever OSDI symposium, which he conceived
  > and founded---and which has become one of the premier venues for systems
  > research. In 1995, Jay renamed his group as the Flux Operating Systems
  > Project. The Flux Group was born!

- [RFC 990: "Assigned Numbers"](https://archive.org/details/rfc990?q=utah) \
  J. Reynolds and J. Postel \
  Network Working Group, November 1986

  ```
  Class B Networks

     * Internet Address  Name          Network                References
     - ----------------  ----          -------                ----------
     […]
     R 128.110.rrr.rrr   UTAH-NET      UTAH-CAMPUS-NET            [JL15]

  Class C Networks

     * Internet Address  Name          Network                References
     - ----------------  ----          -------                ----------
     […]
     R 192.005.012.rrr   UTAH-NET-C    UTAH-COMPUTER-SCIENCE-NET  [GW22]
     […]
     R 192.012.056.rrr   UTAH-AP-NET   Utah-Appolo-Ring-Net       [JL15]
     […]

                                   PEOPLE
     […]
     [GW22]    Grant Weiler        UTAH      Weiler@UTAH-20.ARPA
     […]
     [JL15]    Jay Lepreau         UTAH      Lepreau@UTAH-CS.ARPA
  ```

## Faculty file

Collection Acc0526: [University of Utah Historical Faculty Files, 1920-2012](https://archiveswest.orbiscascade.org/ark:80444/xv51861) \
University of Utah Historical Faculty Files, 2008 \
Wade K. Jensen to Mark C. Pendleton, 2008 \
Container: Box 157 \
Box 20091 H-838 \
Folder 36: Jay Lepreau

- Appointment as Research Professor in the School of Computing \
  University of Utah, School of Computing, 2004

  A. Lorris Betz, Interim President, University of Utah, 14 June 2004:

  > I am pleased to advise you that the University's Board of Trustees has
  > approved your appointment to the auxiliary faculty of the University of Utah
  > as Research Professor in the School of Computing, effective July 1, 2004 and
  > ending June 30, 2005.  This supersedes your appointment as Research
  > Associate Professor in the School of Computing.

  - "Curriculum Vitae" \
    Jay Lepreau, 16 March 2004

    > **Advisor to Masters Students**
    >
    > Siddarth Aggarwal, M.S. "Research in Progress," commenced January 2004.
    >
    > Mac Newbold, M.S. "Reliability and State Machines in an Advanced Network
    > Testbed," commenced August 2001, graduation expected May 2004 (now
    > successful founder of local software company).
    >
    > Shashi Guruprasad, M.S. "Issues in Hybrid Network Experimentation using
    > Simulation and Emulation," commenced May 2001, graduation expected May
    > 2004.
    >
    > Abhijeet Joglekar, M.S. "High Capacity Network Link Emulation using
    > Network Processors," commenced May 2001, defended December 2003,
    > graduation to be May 2004 (now at Intel).
    >
    > Parveen Patel, M.S. "Hybrid Resource Control for Fast-path Active
    > Extensions," commenced May 2001, thesis defended August 2003; graduated
    > (now at Microsoft).
    >
    > Kevin Van Maren, M.S. "The Fluke Device Driver Framework, thesis defended
    > May 1999; graduated.
    >
    > Patrick Tullmann, M.S. "The Alta Operating System," thesis defended March
    > 1999; graduated (now at VMWare).
    >
    > **Unofficial Advisor to Students**
    >
    > Sidney G. Bytheway, "TrISH-Transparent Integrated Storage Hierarchy," M.S.
    > thesis defended August 1995; graduated.
    >
    > Paul Roberts, "Implementation and Evaluation of Data Breakpoints Schemes
    > in an Interactive Debugger," M.S. thesis defended April 1995; graduated.
    >
    > **Advisor to Undergraduate Students**
    >
    > Cory Steffen, Engineering Scholar, commenced January 2004.
    >
    > Jonathon Duerig, commenced October 2003.
    >
    > David S. Anderson, commenced August 2003.
    >
    > Russell Christensen, Computer Engineering senior thesis advisor, commenced
    > January 2002.
    >
    > Jason Morgan, Honor's thesis advisor, January-September 2001 (changed
    > interest and topic).
    >
    > Chad Barb, commenced September 2000; also senior thesis advisor; B.S.
    > received May 2003 (now at Sensory Sys).
    >
    > Robert Ricci, commenced November 2000; also Honor's thesis advisor; B.S.
    > received August 2001 (now Flux research staff and author of several
    > papers).
    >
    > Mac Newbold, commenced January 2000; B.S. received May 2001.
    >
    > Timothy Stack, June 1998 - August 1998, B.S. received August 1998 (now
    > Flux research staff and paper author).
    >
    > Eric Pabst, February 1997 - March 1998.
    >
    > Christopher Alfeld, commenced August 1996, B.S. Computer Science received
    > May 2000, B.S. Mathematics received May 2001 (now Wisconsin Math Ph.D.
    > student).
    >
    > Bartholomew Robinson, August 1995 - August 1998, B.S. received August 1998
    > (now at Inktomi/lahoo).
    >
    > David G. Andersen, December 1997 - June 1998, B.S. received June 1998.
    > (now MIT CS Ph.D. student and top 2004 systems faculty candidate).
    >
    > Bryan A. Ford, September 1992 - November 1997, B.S. received June 1998
    > (now MIT CS Ph.D. student).
    >
    > James Simister, August 1997 - June 1998, B.S. received June 1998 (now at
    > em Ware).
    >
    > Kevin Frei, February 1996 - June 1997, B.S. received June 1997 (now at
    > Microsoft).
    >
    > Nathan Dykman, January 1995 - June 1996, B.S. received June 1996 (now Utah
    > Ph.D. student).
    >
    > **Unofficial Co-advisor to Students**
    >
    > Linus Kamb, "Extending Fluke IPC for Transparent Remote Communication,"
    > M.S. received December 1998 (advised with J. Carter).
    >
    > Ajay Chitturi, "Implementing Mandatory Network Security in a
    > Policy-flexible System," M.S. received June 1998 (advised with G.
    > Lindstrom) (now at Microsoft).
    >
    > Peter J. Hoogenboom, "System Performance Advisor: an Expert System for
    > UNIX System Performance
    >
    > Management," M.S. received January 1992 (advised with R. Kessler).
    >
    > Douglas B. Orr, 1992 - 1995 (advised with J. Carter) (now VP Engineering
    > at Arbor Networks).
    >
    > Stephen Clawson, undergraduate, B.S. received July 1995 (advised with J.
    > Carter) (now at Alcatel).
    >
    > **Member of Graduate Committee**
    >
    > Roland Kempter, Ph.D. ECE Department, "High-capacity Wireless Access
    > Protocols." Jason Baker, M.S., "Maya: Multiple Syntax Extension in Java,"
    > proposal defended October 1999. thesis defended June 2002, graduated.
    >
    > Yury Izrailevsky, M.S., "Supporting Persistent Java Objects in a
    > Distributed Storage System," proposal defended October 1999.
    >
    > Godmar Back, Ph.D. "Isolation and Sharing in a Multi-Process Java Virtual
    > Machine," dissertation defended June 2001; graduated.
    >
    > Anand Ranganathan, M.S., "Design and Implementation of KOLA," proposal
    > defended November 1998.
    >
    > Sai R. Susarla, Ph.D., "Flexible Wide Area Consistency Management,"
    > proposal defended September 2001.
    >
    > Dilip R. Khandekar, "Quarks: Distributed Shared Memory as a Basic Building
    > Block for Complex Parallel and Distributed Systems," M.S. thesis defended
    > January 1996; graduated.
    >
    > **Post-doctoral Fellows**
    >
    > John Regehr, April 2001 - June 2003.

- Appointment as Research Associate Professor of Computer Science \
  University of Utah, Department of Computer Science, 2000

  J. Bernard Machen, President, University of Utah, 13 June 2000:

  > I am pleased to advise you that the University's Board of Trustees has
  > approved your appointment to the auxiliary faculty of the University of Utah
  > as Research Associate Professor of Computer Science, effective July 1, 2000
  > and ending June 30, 2001.

- Appointment as Research Assistant Professor of Computer Science \
  University of Utah, Department of Computer Science, 1997

  Jerilyn S. McIntyre, Interim President, University of Utah, 10 November 1997:

  > I am pleased to advise you that the University's Board of Trustees has
  > approved your appointment to the auxiliary faculty of the University of Utah
  > as Research Assistant Professor of Computer Science, effective October 1,
  > 1977 and ending June 30, 1998.

## 1980 fan-fold papers

See [1980_lepreau/](1980_lepreau/) for documents of Jay Lepreau's from a box of
line printer and dot matrix printouts from 1980.

## Students I know

- Anton Burtsev (Ph.D.)
- Jonathon Duerig (B.S.)
- Rob Ricci (B.S.)

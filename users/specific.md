# Sources for specific early UNIX licensees

Covers early UNIX licensees with only one source: University of Waterloo;
University of Illinois Urbana-Champaign; Naval Postgraduate School; and
University of California, Berkeley.

Licensees with more than one source are in separate files:
[University of Alberta](alberta.md) and [University of Utah](utah/README.md).

License agreements are in licenses/.

- University of Waterloo Archives \
  [Fonds SCA160 - J. Wesley Graham fonds](https://archives.uwaterloo.ca/j-wesley-graham-fonds)
  - Accession GA133 - J. Wesley Graham fonds, 1946-1999
    - File 1529 UNIX - 1974-1977 \
      Contents: correspondence, memoranda, background information.

- ["The Network UNIX System"](https://archive.org/details/networkunixsyste155holm) \
  Steve Holmgren \
  Center for Advanced Computation, University of Illinois Urbana-Champaign \
  18 March 1975

  Network UNIX had been running full time since around 18 February 1975:

  > Reliability
  >
  > As of this writing network UNIX has been running on a full time basis for
  > about four weeks.  During that period, there were between three and four
  > crashes a day. This is not a valid indicator because many of the failures
  > were due to hardware problems.  More recently the hardware has been
  > re-configured to improve reliability and the crash rate has been reduced to
  > one a day with a down time of 2-3 minutes. This is expected to continue, but
  > the sampling period hasnt been long enough for any dependable analysis.
  >
  > Availability
  >
  > Bell Laboratories must be contacted for a license to the base system itself.
  > Bell's policy in the past has been to license the system to universities for
  > a nominal fee, $150.00, and unfortunately for a cost of $20,000.00 to
  > "non-university" institutions. [page 5]

- [*MUNIX, A Multiprocessing Version of UNIX*](https://calhoun.nps.edu/entities/publication/a21d30db-8224-434c-bd58-04ae96d68965) \
  John Alfred Hawley, III and Walter de Brito Meyer \
  Naval Postgraduate School \
  Master's thesis, June 1975

  UNIX acquired in fall 1974:

  > For the purpose of student and faculty research at the Naval Postgraduate
  > School in the Computer Science and Signal Processing disciplines, computer
  > hardware and software was purchased in the fall of 1974. The purchase
  > consisted of two PDP 11/50 processors manufactured by Digital Equipment
  > Corporation, a CSP 30 processor made by Computer Signal Processors
  > Incorporated, discs, terminals, graphics display devices, various types of
  > primary memory, and other peripherals (See Fig 1).
  >
  > The ultimate goal of this relatively large system was to integrate all the
  > components specifically to support signal processing research. When the
  > entire system is not devoted to the real time realm of signal processing, it
  > will be used as a tool by students and faculty involved in computer science
  > related activities such as software engineering research. An agreement with
  > Bell Laboratories provided the software to operate this hardware, in the
  > form of UNIX, a monoprocessing/multiprogramming/time-shared operating
  > system. [page 7]

  TODO: Read from page 8

- [*Open Sources: Voices from the Open Source Revolution*](https://www.oreilly.com/openbook/opensources/book/kirkmck.html) \ \
  Twenty Years of Berkeley Unix: From AT&T-Owned to Freely Redistributable \
  Marshall Kirk McKusick, January 1999

  - January 1974: Computer Science, Mathematics, and Statistics Departments
    jointly acquired V4 after Fabry attended SOSP'73.
  - Spring 1974: Profs. Eugene Wong and Michael Stonebraker purchased a
    PDP-11/40 running V5.
  - Fall 1975: Ken Thompson, Jeff Schriebman, and Bob Kridle brought up V6 on a
    newly arrived PDP-11/70.
  - Early 1978: Prof. Richard Fateman acquired a VAX-11/780 and UNIX/32V.

  > Ken Thompson and Dennis Ritchie presented the first Unix paper at the
  > Symposium on Operating Systems Principles at Purdue University in
  > November 1973. Professor Bob Fabry, of the University of California at
  > Berkeley, was in attendance and immediately became interested in obtaining a
  > copy of the system to experiment with at Berkeley.
  >
  > At the time, Berkeley had only large mainframe computer systems doing batch
  > processing, so the first order of business was to get a PDP-11/45 suitable
  > for running with the then-current Version 4 of Unix. The Computer Science
  > Department at Berkeley, together with the Mathematics Department and the
  > Statistics Department, were able to jointly purchase a PDP-11/45. In January
  > 1974, a Version 4 tape was delivered and Unix was installed by graduate
  > student Keith Standiford.
  >
  > Although Ken Thompson at Purdue was not involved in the installation at
  > Berkeley as he had been for most systems up to that time, his expertise was
  > soon needed to determine the cause of several strange system crashes. […]
  >
  > Though Unix was soon reliably up and running, the coalition of Computer
  > Science, Mathematics, and Statistics began to run into problems; Math and
  > Statistics wanted to run DEC's RSTS system. After much debate, a compromise
  > was reached in which each department would get an eight-hour shift; Unix
  > would run for eight hours followed by sixteen hours of RSTS. To promote
  > fairness, the time slices were rotated each day. Thus, Unix ran 8 a.m. to 4
  > p.m. one day, 4 p.m. to midnight the next day, and midnight to 8 a.m. the
  > third day. Despite the bizarre schedule, students taking the Operating
  > Systems course preferred to do their projects on Unix rather than on the
  > batch machine.
  >
  > Professors Eugene Wong and Michael Stonebraker were both stymied by the
  > confinements of the batch environment, so their INGRES database project was
  > among the first groups to move from the batch machines to the interactive
  > environment provided by Unix. They quickly found the shortage of machine
  > time and the odd hours on the 11/45 intolerable, so in the spring of 1974,
  > they purchased an 11/40 running the newly available Version 5. With their
  > first distribution of INGRES in the fall of 1974, the INGRES project became
  > the first group in the Computer Science department to distribute their
  > software. Several hundred INGRES tapes were shipped over the next six years,
  > helping to establish Berkeley's reputation for designing and building real
  > systems.
  >
  > Even with the departure of the INGRES project from the 11/45, there was
  > still insufficient time available for the remaining students. To alleviate
  > the shortage, Professors Michael Stonebraker and Bob Fabry set out in June
  > 1974, to get two instructional 11/45's for the Computer Science department's
  > own use. Early in 1975, the money was obtained. At nearly the same time, DEC
  > announced the 11/70, a machine that appeared to be much superior to the
  > 11/45. Money for the two 11/45s was pooled to buy a single 11/70 that
  > arrived in the fall of 1975. Coincident with the arrival of the 11/70, Ken
  > Thompson decided to take a one-year sabbatical as a visiting professor at
  > the University of California at Berkeley, his alma mater. Thompson, together
  > with Jeff Schriebman and Bob Kridle, brought up the latest Unix, Version 6,
  > on the newly installed 11/70.
  >
  > […]
  >
  > Early in 1978, Professor Richard Fateman began looking for a machine with a
  > larger address space on which he could continue his work on Macsyma
  > (originally started on a PDP-10). The newly announced VAX-11/780 fulfilled
  > the requirements and was available within budget. Fateman and thirteen other
  > faculty members put together an NSF proposal that they combined with some
  > departmental funds to purchase a VAX.
  >
  > Initially the VAX ran DEC's operating system VMS, but the department had
  > gotten used to the Unix environment and wanted to continue using it. So,
  > shortly after the arrival of the VAX, Fateman obtained a copy of the 32/V
  > port of Unix to the VAX by John Reiser and Tom London of Bell Labs.

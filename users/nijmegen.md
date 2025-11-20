# Sources for the Katholieke Universiteit Nijmegen and UNIX

TODO: Search for details on [AT Computing](https://www.atcomputing.nl/), the
company Hendrik-Jan co-founded with Ger Austen (some details at
https://nl.wikisage.org/wiki/AT_Computing).

- ["COMLNK — a File Transport and Job Entry Utility for a Communication Link"](https://sci-hub.st/10.1002/spe.4380070205) \
  Jan van den Bos and Hendrik-Jan Thomassen \
  Software: Practice and Experience, Volume 7, March/April 1977

  COMLNK implements communication between IBM 360/370 and PDP-11 running DEC DOS
  and translates between EBCDIC and ASCII as appropriate.

  > COMLNK is a software system designed to provide the user of a communication
  > link between two processors with facilities for file transport and job
  > submission from one computer to another. It has been implemented for a high
  > speed communication link between an IBM 360/370 running under OS/MFT, MVT
  > VS1 or VS2 and a PDP 11 running under DOS. The various record formats which
  > are supported by the operating systems for their file organizations can be
  > handled in a straightforward manner, while conversion options from one
  > format to another are possible. Files may be shipped, listed on the IBM
  > printer, punched on the IBM punch or submitted to the jobqueue.

  The future plans section mentions UNIX:

  > Since its implementation COMLNK has provided data communications functions
  > to a still growing number of users. With the help of a short instruction
  > manual the difficulties of using the package have been proved surmountable.
  > A spooled version of COMLNK to be supported by the UNIX operating system is
  > in an advanced state of completion.

  TODO: This is Hendrik-Jan's only paper on dblp, but [Jan](https://dblp.org/pid/95/2736.html)
  has several others.

- ["GPGS: A Device-independent General Purpose Graphic System for Stand-alone
  and Satellite Graphics"](https://dl.acm.org/doi/10.1145/563858.563878) \
  L.C. Caruthers, Jan van den Bos (University of Nijmegen), and
  A. van Dam (Brown University) \
  SIGGRAPH '77, 20 July 1977, pages 107–111

  > Full assembly language implementations exist for PDP 11 (under DOS, RSX,
  > RT-11, and Unix operating systems) and for IBM 360/370 - PDP 11 (RT-11 and
  > Unix) satellite systems. The GPGS-F ANSI FORTRAN subset implementation
  > supports Tektronix 4010-4015 and Kingmatic plotters [9]. Currently the
  > following graphics devices are supported by the assembly language versions:
  >
  > stand-alone:
  > - IBM: Tektronix 4C10/4012/4014/4015 (batch and TSO), Calcomp plotter
  > - PDP: Vector General, Tektronix 4010/4012/4014/4015, Tektronix plotter, DEC
  >   line printer, Versatec plotter printer
  >
  > satellite system:
  > - Vector General on PDP 11 [page 118]

- "UNIX: het standaard operating system" \
  G.J.M. Austen and H.J. Thomassen, 1983

  The first book about UNIX in Dutch.

  TODO: Scan physical copy, as there are apparently no digital copies.

- ["from UNIX to Linux: a time lapse of 45 years"](https://www.youtube.com/watch?v=boahlBmc-NY) \
  Hendrik-Jan Thomassen \
  T-Dose 2016

  - The famous photo taken in 1972 of Ken and Dennis shows the following:
    - A brand PDP-11/45, just introduced a few months before [1:49], from a
      pre-production batch of 10 [5:54]. On the Dutch market, he estimates it
      would have cost 300–400,000 guilders, which could buy a freestanding house
      [14:58].
    - CPU console with switches and lights. [15:20]
    - A PDP-11/20 to control the display. [15:26]
    - Drum disk with a track for each frame of the rendering. [16:20]
    - Magnetic tapes. [17:25]
    - Paper tape. Paper tape holds 400 bytes per meter. 64GB on paper tape would
      almost circle the globe. [15:45]
    - Main disk was a cassette drive. [19:28]
    - Console, 110 baud. Commands are short from difficult typing typing.
      [20:25]
  - Nijmegen's copy of UNIX cost nothing. [8:20]
  - Nijmegen initially used DEC DOS. [8:33]
  - Nijmegen had 64K memory and asked for another 8K every year. [11:15]
  - The console at Bell Labs had a lamp that turned on when swapping. They told
    the secretary to order more memory when she saw it on. [22:39]
  - Ken prepared a disk cartridge and sent it to Nijmegen in fall 1974. [24:21]
  - Hendrik-Jan came there by accident when they introduced him to the system at
    Murray Hill and had never heard of UNIX before. [24:38]
  - When Hendrik-Jan visited Murray Hill, he asked who was using UNIX and they
    checked with the librarian who managed the licenses. The only in Europe was
    Prof. George Coulouris from Queen Mary College in London. The second closest
    to Nijmegen was Tel Aviv. While there, they wrote his name on the list as
    second in Europe. [24:38]
  - By the time they got their cartridge, a professor from Louvain in Belgium
    had bypassed them and got their UNIX up before. [25:26]
  - The computer they had at Nijmegen, a PDP-11/45, was 11 cabinets in its
    heydey. When it was going to be junked, they donated it to him and he has it
    in a lecture room of his company. [25:50]
  - `dd` is listed as "convert and copy a file" in the V5 manual, but since `cc`
    was taken, they incremented both letters. [30:39]
  - Patent US4135240 describes `setuid` in terms of hardware. [39:00]
  - UNIX News July 16, 1975 [40:34]
  - K&R C was the definition of C after the cleanup of the kernel from 16- to
    32-bit. [48:35]
  - Microsoft XENIX was the first commercial UNIX, the first to get a reseller
    contract. [49:40]
  - His book with Ger was the first about UNIX in Dutch. [55:54]

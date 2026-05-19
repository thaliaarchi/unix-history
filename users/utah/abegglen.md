# Paul Abegglen sources

Paul Abegglen inquired about UNIX in November 1973, making him the first person
from the University of Utah connected to UNIX [Ritchie 1973].

Paul attended Idaho State University [obituary 1995], completed an M.S. in
Electrical Engineering at the University of Utah in 1969 or 1970 [Abegglen,
Faris 1970], evidently completed a doctorate in Computer Science at the
University of Utah around 1972 or 1973 [Ritchie 1973, Futrell 1975, obituary
1995], taught at the University of Utah [obituary 1995], then worked for US West
in Salt Lake City as a programmer from 1978 or 1979 until his death in 1995
[obituary 1995].

According to his M.S. thesis, he completed it in 1970. However, a paper based on
it was submitted to IEEE on 8 August 1969 as [Abegglen, Faris, and Hankley
1970], which states that the thesis had been submitted to the Department of
Electrical Engineering. I need to get a scan of his thesis to refine this.

Paul evidently received a doctorate, but I have not found his dissertation. In
[Ritchie 1973] and [Futrell 1975], Paul is addressed with the title Dr., so he
completed a doctorate at the latest by November 1973. His obituary states he
received an advanced degrees in Electrical Engineering and Computer Science from
the University of Utah, indicating his doctorate would have been in Computer
Science.

Paul wrote the software for the Mass Spectral Data Gathering System during at
least October 1972 to December 1973, though possibly until June 1974 [Futrell
1975]. This system runs on a PDP-11/20 under, apparently, DEC DOS. Data is
gathered for the AEI MS-30 mass spectrometer and the MAT CH-7 mass spectrometer
and stored on an RK-11 disc.

Then how did his doctorate line up with the mass spectrometry project? The
Futrell report was submitted March 1975, covered January 1973 to June 1974, and
Paul's code comments range from 25 October 1972 to 27 December 1973. Since he
was already a doctor in November 1973, it's unlikely this project was for his
doctorate. Lots of fundamental code by him is dated to December 1973, after this
point, and such comments are often not updated as work progresses, so he was
likely involved longer. It would also be quite an interdisciplinary
dissertation, though probably more common for the field back then. Instead, it's
probable he completed his doctorate before the project, around summer 1972. This
is a feasible duration.

He inquired to Dennis Ritchie about UNIX on 21 November 1973, among the first
batch of external people interested in the system. He described a PDP-11/45 and
PDP-11/20 and was interested in the available software and making DEC subsystems
run under UNIX. At the time, he was writing software for the the data gathering
and analysis system of the mass spectroscopy project. The software was in
DEC-style assembly and ran with DEC DOS on the PDP-11/20. Due to a lack of other
record of Paul associated with UNIX, it is unlikely he acquired a distribution,
probably because it would not work with his software.

Was he connected to Martin Newell? Probably not. The mass spectrometry
computer(s) were in the Department of Chemistry's Mass Spectrometry Center. This
wasn't a general facility like the University of Utah Computer Center, so
crossover seems unlikely. Martin was setting up a new graphics facility based on
a PDP-11/45 from 1973 to 1975 [Newell vita 1975]. The PDP-11/45 Paul mentioned
to Dennis is not identified as part of the mass spectroscopy project, but it
seems unlikely he was describing this new machine.

## Sources

- ["Fundamentals and design of a real-time data acquisition and analysis system"](https://utah-primoprod.hosted.exlibrisgroup.com/permalink/f/dtufc4/UUU_ALMA21280289060002001) \
  Paul C. Abegglen and William Rusell Faris \
  Department of Electrical Engineering, University of Utah \
  M.S. Thesis, 1970 \
  TK7.5 1970 .A2, Special Collections, Marriott Library

  TODO: Request digitization.

- ["Design of a Real-Time Central Data Acquisition and Analysis System"](https://sci-hub.st/10.1109/PROC.1970.7539) \
  Paul C. Abegglen, William R. Faris (Guidance and Control Branch, Service
  Engineering Division, Ogden Air Materiel Area, Hill Air Force Base), and
  William J. Hankley (Department of Electrical Engineering, University of Utah) \
  Proceedings of the IEEE, Volume 58, Number 1, January 1970 \
  Manuscript received 8 August 1969

  Paul probably did OS design? This appears to be the commonality here too

  Central Data Acquisition and Analysis System

  > This paper is based on a thesis by P. C. Abegglen and W. R. Faris submitted
  > to the Department of Electrical Engineering, University of Utah, Salt Lake
  > City, Utah. [page 38]

  > The computer selected to solve the CDAAS problem was the SEL 840-MP. This
  > machine is a general-purpose computer having 32K words of 24 bits each.

- [Letter from Dennis Ritchie to Paul C. Abegglen, Department of Chemistry,
  University of Utah](../../letters/dmr/lett8) \
  modified 4 December 1973, in reply to 21 November 1973 letter \
  [Dennis_Tapes](https://www.tuhs.org/Archive/Applications/Dennis_Tapes/)
  `dmr2/let/lett8`,
  The Unix Heritage Society

  Paul Abegglen asked about UNIX software, apparently about text formatting
  programs, compiler-compilers, and Snobol, and about making DEC subsystems run
  under UNIX. He described a PDP-11/45 and PDP-11/20. License agreements were
  available at this point and the manual was only distributed with a license.

  > Dr. Paul C. Abegglen \
  > Department of Chemistry \
  > University of Utah \
  > Salt Lake City, Utah 84112

  > Thank you for your kind letter of November 21 regarding the UNIX
  > time-sharing system. UNIX is a proprietary system which is available, on a
  > cost-free basis, to educational institutions under license from the Western
  > Electric Company. To obtain a copy of the license agreement you may write to
  > Mr R. G. Shahpazian […]. You should also send a copy of your letter to Mr.
  > S. P. Morgan

  > Making DEC subsystems run under UNIX is likely to involve a fair amount of
  > work. As you must have gathered from the paper, the system interface is
  > completely different.

  > The PDP 11/45 you describe is sufficient to run UNIX. I'm afraid I can't
  > offer you any encouragement as far as the 11/20 is concerned.  The version
  > of the system for machines without segmentation is so different internally,
  > and requires so much handcrafting to adapt it to its hardware configuration,
  > that we are unable to support it.

  The metadata from `dir`:

  ```
  Mode       UID GID  Size Date                Name
  ---------- --- --- ----- ------------------- -------------
  -rw-rw-rw-   7   1  2826 1973-12-04 06:14:09 ./let/lett8
  ```

- ["Studies in Chemical Ionization Mass Spectrometry"](https://apps.dtic.mil/sti/trecms/pdf/ADA018355.pdf) \
  Jean H. Futrell (Departments of Chemistry and Materials Science, University of
  Utah) with contributions from Thomas Elwood, Paul Abegglen, and Fred Hileman \
  Department of Chemistry, University of Utah \
  Report date: March 1975 \
  Period covered: January 1973–June 1974

  This report details research in chemical ionization mass spectroscopy and the
  computer instrumentation to support it, the MS-30/CH-7 Mass Spectral Data
  Gathering System. It runs on a PDP-11/20 under, apparently, DEC DOS. Data is
  gathered for the AEI MS-30 mass spectrometer and the MAT CH-7 mass
  spectrometer and stored on an RK-11 disc.

  Paul Abegglen wrote the software for the system with comments indicating
  development between 25 October 1972 and 27 December 1973. His is the only name
  in the code, so he may be the sole software author.

  Its software listings look to be complete and could be reconstructed. The
  octal dump would make exact transcription quite certain. The software is
  written in DEC-style PDP-11 assembly.

  This project was sponsored by the Air Force, but the work was done at the
  University of Utah.

  TODO: Review publications by other contributors.

  TODO: Find photos of a similar mass spectroscopy system. The photos in this
  report are very poor quality.

  > This report was prepared by Professor Jean H. Futrell of the Departments of
  > Chemistry and Materials Science, University of Utah. Professor Futrell
  > wishes to acknowledge the contributions of Dr. Thomas Elwood, Dr. Paul
  > Abegglen, and Mr. Fred Hileman to the research reported herein.
  >
  > This report covers work conducted from January 1973 through June 1974. The
  > report was submitted by the author in December 1974. [page iii]

  > These research efforts have involved studies in chemical ionization mass
  > spectrometry which have led to improved instrumentation, techniques and
  > methodology for trace analysis. Much of the work has emphasized instrumental
  > developments. These have included the development of high pressure ion
  > sources for chemical ionization studies with a high resolution mass
  > spectrometer, the development of super pressure (20 torr) ion sources for
  > exploring maximum sensitivity of chemical ionization mass spectrometry, and,
  > most recently, the development of combined gas chromatography-electron
  > impact-chemical ionization mass spectrometry using a dual-source, dual-beam
  > mass spectrometer. This report describes some applications of the latter
  > instrument plus the computer software developed for accumulation of data and
  > data reduction. [pages i–ii]

  TODO: Review these reports:

  > This document reports a continuation of research efforts described in
  > previous technical reports by the author, AFML-TR-70-65, "High Resolution
  > Chemical Ionization Mass Spectroscopy" (May, 1970), AFML-TR-71-98, Studies
  > in Chemical Ionization Mass Spectroscopy" (June, 1971), and AFML-TR-73-63,
  > "An Improved Chemical Ionization Mass Spectroscopy System" (March, 1973).
  > [page 1]

  > This report constitutes a progress report on our continuing effort to
  > develop an analytical system involving computerized GC-CI-EI mass
  > spectrometry. Although Air Force sponsorship has been terminated the ongoing
  > effort will be reported in the scientific literature. [page 4]

  > The MS-30/CH-7 Mass Spectral Data Gathering System is a comprehensive system
  > of modular computer programs which provide a real-time data acquisition,
  > storage and retrieval capability for the AEI MS-30 mass spectrometer and the
  > MAT CH-7 mass spectrometer. Magnetic field strength and ion intensity data
  > are gathered automatically via hardware interfaces and stored in a
  > systematic way on a removable medium RK-11 disc which is part of the
  > DEC-PDP-11-20 computer system. [page 48]

  > The above sequence of commands would cause the A/D converters to be
  > calibrated, pertinent information concerning the data to be stored on disc,
  > data to be taken from the spectrometer and stored on disc, a total ion
  > current versus scan number plot to be displayed on the graphics display, the
  > raw data to be retrieved from the disc and written on DEC TAPE and an exit
  > to the monitor to be performed. [page 55]

  Instructions to load the resident monitor and execute the Data Gathering
  System are on pages 48–50. The text it types once loaded into memory is:

  ```
  DOS  V008A
  DA   01-JAN-72
  TI   00:00:00
  $
  ```

  Then the commands to login and set the date and time are:

  ```
  $ LOG  XXX,YYY
  $ DATE   03-Nov-73
  $ TIME   13:51:32
  ```

  > UNIVERSITY OF UTAH \
  > DEPARTMENT OF CHEMISTRY \
  > MASS SPECTROMETRY CENTER \
  > [page 77]

  > MASS SPECTROMETRY CENTER \
  > UNIVERSITY OF UTAH \
  > DEPARTMENT OF CHEMISTRY \
  > [page 256]

  Routines attributed to Paul Abegglen:
  - DISC TO LINEPRINTER I/O ROUTINE, P.C. ABEGGLEN, 12 DEC 73
  - MASS SPECTRUM PLOT ROUTINE, P.C. ABEGGLEN, 13-DEC-73
  - MASS CHROMATOGAM ROUTINE, P.C. ABEGGLEN, DEC. 10. 1973
  - TELETYPE INPUT/OUTPUT ROUTINE and LINEPRINTER OUTPUT ROUTINE, BY: P. C.
    ABEGGLEN, OCT. 25, 1972
  - TTY CONTROL CHARACTER INPUT DECODING ROUTINE, P C. ABEGGLEN, 27-DEC-73
  - REGISTER SAVE/RESTORE ROUTINE, BY: P. C. ABEGGLEN, OCT. 30, 1972
  - DOUBLE PRECISION INTEGER TO ASCII CONVERSION ROUTINE, BY: P. C. ABEGGLEN, 31
    AUG. 1973

- ["DEATH: PAUL C ABEGGLEN"](https://www.deseret.com/1995/11/19/19205716/death-paul-c-abegglen/) \
  19 Nov 1995 \
  Deseret News

  > Paul C Abegglen, passed away November 17, 1995 at his home in Salt Lake
  > City, Utah.
  >
  > Paul was born August 31, 1943 at Rexburg, Idaho to Ivan and Paulleen
  > Abegglen. He attended Idaho State University and received advanced degrees
  > in Electrical Engineering and Computer Science from the University of Utah.
  > Paul worked for US West as a computer programmer for the past 17 years.
  > Prior to that he taught at the University of Utah. Paul frequently said, "I
  > was fortunate enough that my advocation was my vocation."
  >
  > Survived by wife, Suzanna Abegglen; two step-sons, Casey and Michael Kome;
  > parents, Ivan and Paulleen Abegglen, St. Anthony, Idaho; brother, Donn
  > Abegglen, Tempe, Arizona; two sisters, Julie Ann Hill, Idaho Falls, Idaho;
  > and Diane Abegglen, Salt Lake City.

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

For his M.S. thesis through Hill Air Force Base, he designed the Central Data
Acquisition and Analysis System for the SEL 840-MP computer installed at Newark
Air Force Station, Ohio.

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
probably because it would not work with his software. But, due to his expertise
in writing systems software, he would have had an interest in emerging operating
systems.

Was he connected to Martin Newell? Probably not. The mass spectrometry
computer(s) were in the Department of Chemistry's Mass Spectrometry Center
[Futrell 1975], which was evidently in the main chemistry building [Futrell
2012]. This wasn't a general facility like the University of Utah Computer
Center, so crossover seems unlikely. Martin was setting up a new graphics
facility based on a PDP-11/45 from 1973 to 1975 [Newell vita 1975]. The
PDP-11/45 Paul mentioned to Dennis is not identified as part of the mass
spectroscopy project, but it seems unlikely he was describing this new machine.

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

  For his M.S. thesis through Hill Air Force Base, he designed the Central Data
  Acquisition and Analysis System for the SEL 840-MP computer installed at
  Newark Air Force Station, Ohio.

  > This paper discusses the design and operation of a Central Data Acquisition
  > and Analysis System (CDAAS) which has been installed at Newark Air Force
  > Station, Ohio. The primary emphasis of this paper is on the data
  > acquisition, storage, and retrieval, as opposed to data analysis. […] The
  > computer used is the SEL 840-MP, manufactured by Systems Engineering
  > Laboratories of Fort Lauderdale, Fla. The entire acquisition and analysis
  > scheme selected revolves about the priority interrupt and multiprogramming
  > capabilities of the 840-MP, which is discussed in some detail.

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
  Gathering System. It runs on a PDP-11/20 under, apparently, DEC DOS V8. Data
  is gathered for the AEI MS-30 mass spectrometer and the MAT CH-7 mass
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

  This is apparently DOS V8. It resembles a [DOS V9 transcript](https://github.com/pdp11/mit-gt40-spacewar/blob/master/build/transcript.txt).

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

- [Oral history interview with Jean H. Futrell](https://digital.sciencehistory.org/works/vm40xs61n) \
  28 and 29 October 2012 \
  Interviewed by Michael A. Grayson

  While at the University of Utah, Futrell led research in mass spectroscopy,
  among many other things. He started out on the main campus. His work with the
  CH7 and MS30 mass spectrometers that Abegglen was involved with seems to have
  been during this period. He then moved his labs to to Research Park, being the
  only chemistry labs at Research Park, and did various research for chemistry,
  medicine, and engineering. Then he moved back to the main chemistry building
  in the wing with physical chemists, doing more fundamental experiments.

  The university was rapidly hiring and expanding Research Park, in order to
  improve its research reputation. He does not mention computer graphics or
  Evans & Sutherland.

  Relationship with Bendix:

  > By the way, the time-of-flight mass spectrometer that I bought [at ARL] had
  > an ion source designed by Joe Franklin for them to do a chemical ionization,
  > and I had bought it, and the extra pumps and so on, and it didn’t work,
  > either. So, I had to learn more than I wanted to know about time-of-flight
  > mass spectrometers, and I learned how to make it work, and this got me into
  > a very close relationship with Bendix Corporation for time-of-flight mass
  > spectrometers. [This becomes significant after I move to Utah. My first
  > consulting job as an academic was with Bendix.]

  On University of Utah hiring culture:

  > And so anyhow, I was leaving a lot of things behind, [and there were] a lot
  > of unknowns, uncertainties. But intuitively I knew it was what I wanted to
  > do. I wanted to move back to the West. It was not California, but it was
  > getting back in the West, that had some appeal to me. And having met Henry
  > Eyring and some of his people, being keenly interested in that theoretical
  > framework, and doing experiments that relate directly to those theoretical
  > predictions, all seemed to suggest that it made sense to do that.
  >
  > And so I decided to make the jump, and become an experimentalist working on
  > some of the central themes [that] Eyring, Wahrhaftig, and other folks, [J.]
  > Calvin Giddings, gas chromatography, some really good people [cared about].
  > I was the start of the new expansion of the University of Utah, where they
  > had resolved, for whatever reason, to stop hiring Mormons [to fill their
  > vacancies].
  >
  > So, their new president, [James C. Fletcher], had been the head of the Jet
  > Propulsion Laboratory—a physicist—and so he was the new president of the
  > University. He had completely new ideas, okay? [Fletcher] wanted
  > [well-meaning faculty search committees to stop using the appeal of residing
  > near the Mother Church as a recruiting tool]. He wanted to hire the very
  > best people you could find, and he [knew how CalTech and its associated Jet
  > Propulsion Laboratory operated in Pasadena]. And he wanted Utah to [proceed]
  > in that philosophical framework. And so he said, “You hire the best people.
  > I don’t care what they cost. Hire the best people, and I want them to be
  > doing something that’s of current scientific interest, and I can do the
  > math, and I can explain it to the legislature, and everyone else, that
  > someone who comes in and is funded to do research will bring in the
  > students, that he will build the reputation of the University, and every
  > dollar brought in from federal sources will be spent [in our state] at least
  > five times over and they will be providing revenues to the state of Utah,
  > and I can persuade them to put funds into the state university.” Well, that
  > was the hang-up. That’s the hard part, is convincing them to do the final
  > step of investing in the state university. That was his mantra, and so I was
  > kind of swept in in that timeframe. And as I said, I had three funded
  > research grants by the time I showed up [in between]. I went from
  > Wright-Patterson to Berkeley [for the summer] to have a crash course in
  > learning to be a [professor and my initial grant writing effort proved
  > superbly successful].

  About the CH-7 and MS30 mass spectrometers, presumably the same ones used in
  the project Abegglen was involved in:

  > We had acquired by this time a [MAT] CH-7 mass spectrometer, okay? So,
  > Marvin and I decided to make CH7+. Why not? It would be really neat. […] And
  > I used the CH-7 to publish the […] first paper and one of the very few
  > papers that I published on sequencing of peptides, and I was the first
  > person to do it by chemical ionization mass spectrometry18.

  > So, we did the MS30, which was a parallel beam oddity mass spectrometer, and
  > so we built a chemical ionization source for one beam, and the electron
  > impact source for the other, and so we had our calibration spectrum on one
  > side, and the chemical ionization spectrum, whatever it was, on the other
  > side. We could leak samples into both sources and get those results.
  > Simultaneously. That was kind of interesting. It was obvious that putting a
  > computer on the mass spectrometer was an interesting and important thing to
  > do. I made a mistake of deploying too many resources to do something that
  > was [so] obvious, that other people would work [very hard on the problem].
  > But we were among the first, maybe the first, to actually—I think the
  > first—to actually put a computer on a quadrupole mass filter mass
  > spectrometer. I got involved with Bob [Robert E.] Finnigan, when he was at
  > SRI [Stanford Research Institute], before he branched off to form his own
  > company.19 And I actually had acquired two quadrupoles, one at
  > Wright-Patterson and one at Utah, from Finnigan, when they were still made
  > at Stanford Research Institute. And I did a number of experiments with this.
  > […] IBM [introduced] a laboratory computer, and I’ve forgotten what they
  > called it.

  Moved to Research Park:

  > Anyhow, there were several other things that we did. I got sort of
  > involved/intrigued by some let’s say practical side experiments, and got
  > involved in the NSF-funded center at Utah called the Flammability Research
  > Center. With this drop-off in funding, drop-off in support for students,
  > [and since] I had a dual appointment in engineering as well as chemistry, I
  > moved to [University of Utah] Research Park to be head of the analytical
  > part of this NSF-funded center to do fire toxicology.

  Chemistry, medicine, and engineering appointments at Utah:

  > And I got involved in artificial heart projects, and other things…[Utah’s]
  > artificial eye [project]. So, all kinds of experiments where a little bit of
  > knowledge of physics, and chemistry, and mass spectrometry can significantly
  > affect biomedical […] experiments. And so, you know, [with] a dual
  > appointment, license to wear a gown and walk through some of those rooms.
  > […] I had then chemistry, medicine, and engineering appointments.

  Move back to the main campus:

  > And my lab was no longer on campus. And I decided to sort of go back to my
  > roots and go back to doing more fundamental experiments, collision-induced
  > dissociation, this time to understand from a very fundamental viewpoint how
  > it works, and to do it for larger molecules. […] [And] reestablish my
  > research on the main campus back in the Department of Chemistry.

  He was the only example in chemistry at Research Park:

  > And when I went there, they were hiring so many people, they were planning
  > to expand into Research Park, where my research labs were located, but they
  > never did, at least in terms of chemistry, and so I was an isolated example
  > there. And so, I insisted in coming back into the main chemistry building
  > and back into the wing physical chemists were located, and so on. I was sort
  > of getting back into that and getting research grants to build a new mass
  > spectrometer, having a double focusing first-stage instrument to then
  > collide in a molecular beam sense with larger molecules, and anything that
  > we chose, actually, to look at the collision-induced dynamics, what are the
  > scattering angles, what are the products, what are their translational
  > energies, and so on. So, a very fundamental study of collision-induced
  > dynamics of the MSMS tandem mass spectrometry experiment. We were going to
  > use everything we had learned.

  Move to Delaware:

  > And so, moved across the country [to the University of Delaware]. […] And
  > one of the moving trucks turned over on the Pennsylvania Turnpike and
  > destroyed the tandem mass spectrometer that we had built.

# Sources for Bell Labs, Holmdel and UNIX

- ["A Graphical Display System Utilizing Plasma Panels"](https://sci-hub.st/10.1016/0097-8493(75)90004-7) \
  John F. Jarvis \
  Bell Laboratories, Holmdel, NJ \
  SIGGRAPH '74, July 1974, pages 175–180

  Presumably they were not using UNIX yet, as they seem to describe using a
  custom-made monitor, instead of a ready-made kernel. This system may be the
  first implementation described in SIGGRAPH '75.

  > Abstract—A graphics display system utilizing recently available 512 line
  > plasma panels interfaced to a DEC PDP-I1 computer will be described. As
  > the panel electronics allow one cell to be turned on or off each 20/μsec
  > the required display processor functions are implemented in software with
  > no loss of performance. This results in a display system with a rich
  > instruction set as the entire PDP-I1 instruction set becomes part of the
  > graphics instruction set. Since the plasma panels combine both memory and
  > selective erase, a unique capability has thus been achieved.
  >
  > […]
  >
  > The plasma panel display system (PPDS) thus consists of a small general
  > purpose computer (DEC PDP-11/20), a simple hardware interface to multiple
  > plasma panels and a data link to the controlling computer system. This
  > hardware runs under the control of a simple monitor program in the
  > PDP-11/20 which includes interpretive software to generate display
  > primitives. The PPDS when viewed from the controlling computer appears as
  > graphical display processor controlling multiple panels and incorporating
  > a powerful display instruction set. [page 175]

- ["An Area Organized Data Structure for Interactive Graphics"](https://dl.acm.org/doi/10.1145/563732.1138366) \
  John F. Jarvis \
  Bell Laboratories, Holmdel, NJ \
  SIGGRAPH '75, June 1975, pages 184–190

  > The Area Data Base and algorithms described in the previous sections have
  > been tested in two different implementations. The first, made in the
  > confines of a large general purpose time sharing system, served to verify
  > the essential ideas of the technique and allowed algorithm development to
  > proceed. Windowing (Figure 2) and the tracing of electronically continuous
  > paths (Figure 3) algorithms were created. This implementation also yielded
  > information on the data base structureing parameters. […]
  >
  > The second implementation was made on a DEC PDP-11/45 system operating
  > under control of the UNIX<sup>4</sup> time sharing system. This version
  > consists of the data base manipulation routines, an input language
  > processor and output modules to generate displays on a plasma
  > display<sup>5</sup> attached to the 11/45 or on a microfilm recorder.
  > [page 188]
  >
  > 4\. D. M. Ritchie and K. Thompson, "The UNIX Time Sharing System," CACM,
  > Vol. 17, pp. 1365-1375, July 1974.
  >
  > 5\. J. F. Jarvis, "A Graphical Display System Utilizing Plasma Panels,"
  > presented at First Annual Conference on Computer Graphics, Boulder,
  > Colorado, July 15, 1974.

- ["The Line Drawing Editor, an Experiment in Computer Vision"](https://dl.acm.org/doi/10.1145/563274.563328) \
  John F. Jarvis \
  Bell Laboratories, Holmdel, NJ \
  SIGGRAPH '76, July 1976, pages 288–292

  > The host computer system for this project is a large DEC PDP-11/45 which
  > includes a cache memory, demountable disks, industry compatible 9-track
  > magnetic tape and a floating point processor. The system operates under
  > control of the BTL developed UNIX timesharing system[3]. The most important
  > restriction imposed on the LDE [Line Drawing Editor] by this system is the
  > limitation of core resident program and data to 64K (1K=1024) bytes. A
  > PDP-11/20 is attached as a peripheral to the 11/45 and serves as a
  > controller for graphical displays and a camera. A description of the display
  > system which incorporates Owens-Illinois 512-60 plasma panels is given in
  > [4]. The camera is a EMR 659D Optical Data Digitizer[5]. The LDE requires
  > hardcopy produced from drawings described in a data base in the 11/45 file
  > system. These are produced on a FR80 microfilm recorder which is driven from
  > a magnetic tape.

- ["A Software Test-Bed for the Development of 3-D Raster Graphics Systems"](https://dl.acm.org/doi/10.1145/965161.806815) \
  Turner Whitted and David M. Weimer \
  Bell Laboratories, Holmdel, NJ \
  SIGGRAPH '81, August 1981, pages 271–277

  > The entire test-bed is coded in the C language and has been tested on two
  > machines (a PDP-11/45 and a VAX-11/780) running the UNIX operating system.
  > Because C allows the programmer to declare variables as either 16 or 32
  > bit integers independently of machine word length, identical code will run
  > on either machine. We do find, however, that the larger addressing space
  > of the 32 bit machine is necessary for conducting any really useful work.
  >
  > This system incorporates features that were suggested to us in
  > conversations with a number of helpful people including Frank Crow of Ohio
  > State University, Jim Blinn of JPL, Ed Catmull and Loren Carpenter of
  > LucasFilm Ltd., Jeff Lane of Boeing, and Lance Williams of NYIT. We also
  > wish to thank Steve Rubin for acting as our first user and main guinea
  > pig. [page 275]

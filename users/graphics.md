# Graphics uses of UNIX

See [University of Utah](utah/graphics.md) and [Bell Labs, Holmdel](holmdel.md)
separately for graphics.

- [*Proceedings of SIGGRAPH '74*](https://dblp.org/db/conf/siggraph/siggraph1974.html) \
  15–17 July 1974

  [Bell Labs, Holmdel](holmdel.md) was presumably not yet using UNIX for
  graphics.

  No papers mention UNIX, but several mention PDP-11s.

  Note that the papers from this conference were published in Computers &
  Graphics, available via ScienceDirect, and are not linked from the
  proceedings, so need to be individually searched.

- [*Proceedings of SIGGRAPH '75*](https://dl.acm.org/doi/proceedings/10.1145/563732) \
  25–27 June 1975

  [Bell Labs, Holmdel](holmdel.md) was using UNIX for graphics.

- [*Proceedings of SIGGRAPH '76*](https://dl.acm.org/doi/book/10.1145/563274),
  14–16 July 1976

  - ["The HRD-1 Laser Display System"](https://dl.acm.org/doi/10.1145/563274.563289) \
    P. A. Woodsford \
    Laser-Scan Laboratories Ltd., Cambridge, England \
    SIGGRAPH '76, pages 68–73.

    Shows a woman operating the RD1-console with a comically large screen. It is
    controlled by a PDP-11/45.

  - See [Bell Labs, Holmdel](holmdel.md)

- [*Proceedings of SIGGRAPH '81*](https://archive.org/details/siggraph81confer15sigg),
  3–7 August 1981

  UNIX was used for graphics work at Bell Labs at Murray Hill, University of
  Minnesota, Brown University, University of Toronto, and Bell Labs at Holmdel.

  - ["Contour Filling in Raster Graphics"](https://dl.acm.org/doi/10.1145/800224.806786) \
    Theo Pavlidis \
    Bell Laboratories, Murray Hill, NJ \
    SIGGRAPH '81, pages 29–36

    > The algorithm described in Tables I and II was implemented in the C
    > Language under the UNIX operating system. It was run on a PDP11/45
    > computer with a Ramtek 9300 display. [page 34]

  - ["Parallel Processing Image Synthesis and Anti-Aliasing"](https://dl.acm.org/doi/10.1145/800224.806789) \
    Richard Weinberg \
    Computer Science Department, University of Minnesota \
    SIGGRAPH '81, pages 55–62

    > To demonstrate the feasibility of the processing scheme, simulation
    > programs were written by the author using the language "C" under the UNIX
    > operating system on a DEC PDP-11/45 at the Image Processing Center,
    > University of Minnesota. Film output was recorded on a Discomed film
    > recorder. [page 61]

  - ["An Integrated System for Creating and Presenting Complex Computer-Based
    Documents"](https://dl.acm.org/doi/10.1145/965161.806805) \
    Steven Feiner, Sandor Nagy, and Andries van Dam \
    Computer Graphics Group, Department of Computer Science, Brown University
    SIGGRAPH '81, pages 181–189

    > Our document system is implemented under UNIX on a timeshared VAX 11/780.
    > The graphics display is a Ramtek 9400 graphics system with a 1280 x 1024 x
    > 8 frame buffer, affording high image resolution. The belief, however, that
    > more powerful, less expensive hardware can eventually be packaged to be
    > about the size of a book has been a fundamental motivating force behind
    > the project. [page 182]

  - ["Towards a Laboratory Instrument for Motion Analysis"](https://dl.acm.org/doi/abs/10.1145/800224.806806) \
    Ronald Baecker, David Miller, and William Reeves \
    Department of Computer Science and Computer Systems Research Group,
    University of Toronto \
    SIGGRPAH '81, pages 191–197

    > The central processor is a PDP-11/45 with full complement of memory and
    > several large disk storage modules. Almost all of the motion analysis
    > software is resident on this machine. The MC6800 processor is used as
    > slave to the 11/45. It functions as an intelligent controller to the video
    > disk, which stores in analogue form the raw video images of the entity
    > under study. Computer synthesized images from the 11/45 are produced by
    > the SPIWRIT graphics processor, described in more detail in section V. The
    > images from the video disk and SPIWRIT are fed into a simple video mixing
    > unit which superimposes the SPIWRIT images on the raw video images. The
    > images are then displayed for the user to see on a standard colour
    > television display screen. The digitizing tablet is used by the
    > interactive user to give commands to the system and to make sketches.
    >
    > Basic system software has been written for all of the hardware components
    > under the UNIX operating system (Bell 1978). The SPIWRIT display is
    > supported by a general-purpose device-independent graphics package called
    > GPAC (Reeves 1978). GPAC also supports a generalized event-driven input
    > mechanism and sketching software for the digitizing tablet. The MC6800
    > video disk controller sub-system allows the 11/45 to instruct the
    > controller to play back asynchronously a sequence of frames at a given
    > rate. The controller returns a message to the 11/45 when it has finished.
    > The trickiest part of the system software is ensuring that the motion
    > analysis system can run in real-time without severely impacting other
    > timesharing users of UNIX. [page 193]

  - See [Bell Labs, Holmdel](holmdel.md)

  > **Bulkhead Part With Intersection Cut**
  > by Richard F. Riesenfeld, et al
  >
  > This was modelled and rendered using the Alpha-1 system at the University of
  > Utah, which is discussed in "Using the Oslo Algorithm as a Basis for CAD/CAM
  > Geometric Modelling." *Proceedings of the Second National Computer Graphics
  > Association Conference*, Baltimore, 14-18 June 1981.
  >
  > Identification of back cover photographs [page 346]

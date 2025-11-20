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

  TODO: Search this conference and earlier for Evans & Sutherland.

  - ["The HRD-1 Laser Display System"](https://dl.acm.org/doi/10.1145/563274.563289) \
    P. A. Woodsford \
    Laser-Scan Laboratories Ltd., Cambridge, England \
    SIGGRAPH '76, pages 68–73.

    Shows a woman operating the RD1-console with a comically large screen. It is
    controlled by a PDP-11/45.

  - See [Bell Labs, Holmdel](holmdel.md)

- [*Proceedings of SIGGRAPH '77*](https://dl.acm.org/doi/proceedings/10.1145/563858),
  20–22 July 1977

  - ["Glide: A Language for Design Information Systems"](https://dl.acm.org/doi/10.1145/563858.563863) \
    Charles Eastman and Max Henrion \
    Institute of Physical Planning,
    School of Urban and Public Affairs and Department of Architecture,
    Carnegie-Mellon University \
    SIGGRAPH '77, pages 24–33

    > The complete specification of GLIDE is available in [6]. It has been
    > implemented on a PDP-10, under the TOPS-18 operating system. using the
    > Bliss implementation language. Implementation is also planned for a
    > PDP-11/34, under the UNIX operating system. Versions are anticipated for
    > both storage tube and refresh display graphics.

  - ["Anima II: A 3-D Color Animation System"](https://dl.acm.org/doi/10.1145/563858.563870) \
    Ronald J. Hackathorn \
    Computer Graphics Research Group, Ohio State University \
    SIGGRAPH '77, pages 54–64

    Discusses implementations at other universities, including Utah and Case
    Western. Case Western has an Evans & Sutherland Shaded Graphic System which
    runs with a PDP-11, but they use Algol, so it sounds to not be UNIX.

    > During the past several years, films from the University of Utah (16),
    > General Electric Corp. (17) and by N. Max (18), illustrate that the
    > ability to produce 3-D shaded object animation has been a significant
    > addition to the field of computer animation. Max's comment about his film,
    > "Sphere Eversion," describes the basic feeling towards this type of
    > animation: "The film produces a visualization which could not have been
    > achieved in any other medium, and could never have been animated by hand."
    > (26) [page 54]
    >
    > […]
    >
    > Based on the literature to date, there have been many computer graphics
    > facilities which have implemented either a technique for generating 3-D
    > objects, an animation language, or a visible surface algorithm. Two
    > examples would be the University of Utah which produced the Watkins
    > Algorithm (31,33), and Archuleta's work at Lawrence Livermore Laboratory
    > (2) where he implemented a fast version of the Watkins Algorithm on a CDC
    > 7600. However, only a few facilities have attempted to integrate these
    > fundamental capabilities into one complete system for the expressed
    > purpose of animation.
    >
    > […]
    >
    > Case Western Reserve University has a computer system which can generate
    > shaded perspective pictures in real time. This "Shaded Graphic System" was
    > developed for Case by Evans and Sutherland Corporation at a cost $400,000.
    > It consists of a graphics processor driving a pipeline of special purpose
    > hardware for matrix multiplication and shading. Sharing memory with the
    > graphics processor is a PDP-11 with a 10 megabyte disk and an assortment
    > of I/O devices. 3-D data is processed on a scan line by scan line basis by
    > a hardware implementation of Watkin's hidden surface algorithm and sent to
    > a shader which uses the Gouraud shading technique (21). The resulting
    > image is displayed on a raster scan CRT for real-time display. A camera
    > unit with color filters under computer control is used to produce computer
    > animated films.
    >
    > Jones (22) describes a high level programming language he implemented for
    > the Case system. It consists of a complete implementation, for the PDP 11,
    > of Algol-60 with the addition of string variables, I/O facilities, and
    > extensions for handling graphic shaded images. The primary purpose of this
    > work was to facilitate the use of a custom-built system which can produce
    > shaded images in real time. According to Jones one important advantage of
    > Algol was its block structure which Jones decided would lend itself quite
    > nicely to the description of graphical structures. The consequence of this
    > approach is that just as Algol itself is a way of talking about
    > algorithms, the graphic-extended Algol is a way of talking about graphical
    > data structures. [page 56]

  - ["A Simple Approach to Computer Aided Milling with Interactive Graphics"]() \
    Steven G. Satterfield, Francisco Rodriguez, and David F. Rogers \
    Computer Aided Design and Interactive Graphics Group,
    U. S. Naval Academy \
    SIGGRAPH '77, pages 107–111

    Uses Evans & Sutherland Picture System.

    > The major hardware components of CAMILL are an interactive refresh
    > graphics system and a numerically controlled three axis milling machine.
    > The graphics system is an Evans & Sutherland Computer Corporation PICTURE
    > SYSTEM, driven by a Digital Equipment Corporation PDP-11/45. User
    > interaction with the graphics system is primarily through the use of
    > function switches, control dials and a tablet. The actual milling of the
    > ship hulls is performed with a Pratt and Whitney TRIMAC XV computerized
    > numerically controlled three axis milling machine. To supplement the
    > milling machines control panel and act as a front end processor, a
    > Tektronix 4051 Graphic System has been interfaced to the TRIMAC
    > mini-computer controller. For obtaining high resolution hard copy plots at
    > various stages of the design process, there is a large (4'x8') XYNETICS
    > flat bed plotter which is controlled off line by magnetic tape.

  - See [University of Nijmegen](nijmegen.md)

  - See [University of California, Berkeley](berkeley.md)

- *Proceedings of SIGGRAPH '78*: TODO

- *Proceedings of SIGGRAPH '79*: TODO

- *Proceedings of SIGGRAPH '80*: TODO

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

  - See [Brown University](brown.md)

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

# Evans & Sutherland

- ["Picture System 2 Hardware Diagnostic Manual"](http://bitsavers.informatik.uni-stuttgart.de/pdf/evansAndSutherland/picture_system_2/901180-001_Picture_System_2_Hardware_Diagnostic_Manual_2ed_197811.pdf) \
  Evans & Sutherland, Second Edition, November 1978

  Picture System diagnostics are not distributed for UNIX; however, that does
  not imply that PS-2 did not support UNIX at this time.

  > **0.2 OPERATING SYSTEMS**
  >
  > Picture System diagnostics are distributed for execution on the PDP-11 under
  > the following operating systems: (1) E&S Diagnostic Monitor (ESD). This
  > package includes diagnostics for PICTURE SYSTEM 1 as well as PICTURE
  > SYSTEM 2. Executable programs and all other files in this package are RT-11
  > compatible. (2) Unmapped RSX-11M, which does not utilize PDP-11 memory
  > management (3) Mapped RSX-11M, which does utilize PDP-11 memory management.
  > At the present time, only PS-2 diagnostics which do not utilize DMA's or
  > interrupts are available in this package.

- ["Computer Graphics at Evans & Sutherland and Pixar"](https://ieeexplore.ieee.org/document/10736176)
  [[Bitsavers](https://bitsavers.org/pdf/evansAndSutherland/History/Mantle_-_Computer_Graphics_at_Evans_and_Sutherland_and_Pixar_202410.pdf)] \
  Mickey W. Mantle \
  IEEE Computer Graphics and Applications, 25 October 2024

  - Evans & Sutherland
    - E&S, around 1973, was split into two divisions: the Interactive Systems
      Division (Picture Systems) and the Simulation Systems Division (Flight
      Simulators). The Picture Systems were end-user, vector devices until the
      early 1980s, primarily used for creating and editing (e.g., CAD). The
      simulators turned to raster displays in the mid-1970s for more realistic
      displays of runways, buildings, etc. [p.128]
    - Photos of PS1, PS2, Multi Picture System, PS300, and PS340. [p.129]
    - Picture System 1 [p.128]
      - Mickey Mantle and Steve McAllister developed the graphics software package
        (GSP), device drivers for RT-11, and Picture System User's Manual.
    - Picture System 2 (1976–1983) [p.128–130]
      - Mickey Mantle and Steve McAllister developed the GSP, device drivers for
        RT-11, RSX-11M, and VAX/VMS, and PS2 GSP User's Manual.
      - PS2 was source code compatible with PS1 and still required a PDP-11 host.
      - Tom Ferrin created the UNIX PS2 GSP.
    - Multi Picture System (1977–1979) [p.130]
      - Added a second display to the PS2 and set of input devices for two-user
        use. It used a PDP-11 or VAX-11 host, often PDP-11/70 or VAX-11/780.
    - Picture System 300 (1980–1984) [p.131]
    - PS320 (1983) [p.131]
      - A two-user PS300.
    - PS340 (1984) [p.131–132]
      - Has both a vector and a raster display.
    - PS330, PS350, PS390 (1985–1988) [p.132]
    - PS360 (PS300 Unix port) (1983) [p.133]
      - A port of Berkeley Unix to the PS300. It was shut down after completion,
        since E&S was not interested in making general-purpose computers. The
        PS300 was essentially a self-contained Motorola 68010 computer system.
    - REALimage 3D chips and add-in boards (1987–1988) [p.132]
    - Picture System Lorgnette Stereo Viewer (1974) [p.132]
      - A stereoscopic viewer for the PS1 that produces two offset images and
        alternately masks each eye with a rotating disc at 30fps.
    - Video Frame Buffer (1973–1977) [p.132]
      - The first commercial video (raster) frame buffer. Enabled by
        dynamic RAM chips. 512x512 resolution, 8-bit grayscale or color-map color.
      - NYIT created the first full-color 24-bit RGB framebuffer by using three of them
        and a 1024x1024 8-bit framebuffer by using four of them.
    - Mickey Mantle taught a PS2 course at NYIT in 1976 after they bought
      a PS2 and video frame buffers. [p.135]
  - Pixar and Disney [p.135–]
    - The Pixar Image Computer (PIC) used Unix. [p.136]

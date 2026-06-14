# Jim Blinn sources

TODO: https://www.jimblinn.com/

TODO: Sources after September 1988 not reviewed. https://utah-primoprod.hosted.exlibrisgroup.com/primo-explore/search?query=creator,contains,Blinn,%20James,AND&tab=everything&search_scope=EVERYTHING&sortby=date2&vid=UTAH&mode=advanced&offset=50

- ["Texture and Reflection in Computer Generated Images"](https://dl.acm.org/doi/10.1145/563274.563322) \
  James F. Blinn, Martin E. Newell (University of Utah) \
  Proceedings of SIGGRAPH '76, 14-16 July 1976, p.266

  Paper announcement or abstract.

- ["Texture and Reflection in Computer Generated Images"](https://dl.acm.org/doi/10.1145/360349.360353) \
  James F. Blinn, Martin E. Newell \
  Communications of the ACM, 1 October 1976 \
  Volume 19, Issue 10, p.542-547

  Has renderings of the Utah Teapot. It spread mostly from here [[email](2025-12-18_archibald_newell_blinn.txt)].

  > **Resource Requirements**
  >
  >    The images shown in this paper were all generated
  > on a PDP-11/45 computer having a 256K-byte random
  > access frame buffer which was used as the depth buffer.
  > The main routines were written in Fortran and the
  > critical parts were written in assembly language. The
  > computation time of the extended subdivision algo-
  > rithm is roughly proportional to the area covered by
  > visible objects. Images of nontextured objects of
  > the type used in this paper take about 25 minutes. The
  > addition of texture or reflection increases this time by
  > about 10 percent. All images have a resolution of
  > 512×512 picture elements.

- ["Models of Light Reflection for Computer Synthesized Pictures"](https://dl.acm.org/doi/10.1145/563858.563893) \
  James F. Blinn (University of Utah) \
  Proceedings of SIGGRAPH '77, 20 July 1977, p.192-198

  Shows some sphere-like models.

- ["A Homogeneous Formulation for Lines in 3 Space"](https://dl.acm.org/doi/10.1145/563858.563900) \
  James F. Blinn (University of Utah) \
  Proceedings of SIGGRAPH '77, 20 July 1977, p.237-241

  Matrices.

- "The Progression of Realism in Computer Generated Images" with Newell,
  16-19 October 1977

- ["A Scan Line Algorithm for Displaying Parametrically Defined Surfaces"](https://dl.acm.org/doi/10.1145/988437.988439) \
  James F. Blinn (Caltech/JPL) \
  Proceedings of SIGGRAPH '78, 2 August 1978, p.1-7

- ["A Scan Line Algorithm for Displaying Parametrically Defined Surfaces"](https://dl.acm.org/doi/10.1145/800248.807364) \
  James F. Blinn (Caltech/JPL) \
  Proceedings of SIGGRAPH '78, 23 August 1978, p.27

  Abstract.

- ["Clipping Using Homogeneous Coordinates"](https://dl.acm.org/doi/10.1145/800248.807398) \
  James F. Blinn (Caltech/JPL), Martin E. Newell (XEROX/PARC) \
  Proceedings of SIGGRAPH '78, 23 August 1978, p.245-251

- ["Simulation of Wrinkled Surfaces"](https://dl.acm.org/doi/10.1145/800248.507101) \
  James F. Blinn (Caltech/JPL) \
  Proceedings of SIGGRAPH '78, 23 August 1978, p.286-292

- ["Computer Display of Curved Surfaces"](https://collections.lib.utah.edu/ark:/87278/s6pp4whm) \
  James Frederick Blinn \
  Doctor of Philosophy dissertation \
  Department of Computer Science, University of Utah, December 1978

  Advisor: Martin Newell (p.8)

  Renderings:
  - orange peel and its texture (p.v)
  - stationary points: saddle point, parabolic cylinder, local maximum, and
    local minimum (p.23–24)
  - Gourard and Phong shading (p.108)
  - intersection errors due to linear Z interpolation (p.109) and linear
    parametric interpolation (p.111)
  - comparison of Phong and Torrance-Sparrow reflection distributions for
    incident light at 30° (p.125) and 70° from normal (p.126)
  - metallic (p.128) and non-metallic (p.129) surfaces for various light source
    directions (p.128)
  - sphere with specular texture and grid pattern (p.132)
  - Melitta jug with specular texture and random pattern (p.132)
  - objects made with normal vector perturbation: strawberry, Celtic knots on
    spheres, log, moon, ring, Melitta teapot, raised letters on spheres
    (p.137–138)
  - objects with environment reflections: windows reflecting off of Melitta
    teapot, earth and sun reflections on satellite (p.147)
  - ideal low pass filter weighting function (p.151)
  - Fourier window function (p.153)
  - Bartlett window function (p.154)
  - texture filtering with/without filtering and with/without interpolation
    (p.158–159)
  - normal vector perturbation filtering

  No hardware specifics.

- ["Scan Line Methods for Displaying Parametrically Defined Surfaces"](https://dl.acm.org/doi/10.1145/358808.358815) \
  Jeffrey M. Lane (Boeing Commercial Airplane Company),
  Loren C. Carpenter (Boeing Computer Services),
  Turner Whitted (Bell Laboratories),
  James F. Blinn (Caltech/JPL), \
  Communications of the ACM, 1 January 1980, p.23-34

- ["Computer Magic for 'COSMOS'"](https://www.proquest.com/docview/196338149) \
  Dr. James F. Blinn, Pat Cole, Charles E. Kolhase \
  American Cinematographer, October 1980

  Details on the production of animations for PBS "COSMOS".

  > The main computer used to produce the calculations is a DEC PDP 11/55. This
  > computer interfaces with the two graphics display systems. For vector
  > graphics, we used an Evans and Sutherland (E&S) Picture System which has
  > special-purpose hardware for rapid three-dimensional transformations, such
  > as translation, scaling, rotation, and viewing in perspective. Even with
  > this sophisticated equipment, in many instances, the hardware did not have
  > sufficient numeric precision to represent the large range of numbers
  > encountered in astronomical phenomena, therefore, extra software was
  > necessary to allow more accurate simulations. The raster output device we
  > used was another E&S product called a digital frame buffer which consists of
  > a large computer memory. One unit of memory (a "byte") is associated with
  > each pixel to be displayed on a screen. As the main computer calculates
  > values and stores them into the frame buffer, a subsidiary microprocessor
  > continuously reads the memory and synthesizes a conventional video signal
  > which is displayed on a CONRAC monitor. Our frame buffer stores 512 lines of
  > 512 pixels each, equivalent to 256,000 pixels. Only 480 lines are displayed.

  A camera records frames displayed on a screen.

- ["Teapot by Computer"](https://www.studiopotter.org/digital-issue/173) \
  James Blinn \
  Studio Potter, Volume 10, June 1982, p.30-32

  > The teapot was originally designed by my thesis advisor, Martin Newell, who
  > is a computer scientist from England. When Martin Newell wanted some objects
  > with which to show off his computer programs, he picked a tea service: a
  > teapot, a teacup, and a teaspoon. (I think he had an actual tea set at home
  > that he used for inspiration and for the general shape, but the images were
  > not reproductions.) The original teapot shape which was made was taller than
  > the one in this picture. This is because one day some people came by who
  > were interested in funding our research, so to demonstrate how the changes
  > could be made in the image by stretching it and scaling it, we shrunk the
  > set by a factor of about three quarters, and decided it looked better that
  > way.

- ["Light Reflection Functions for Simulation of Clouds and Dusty Surfaces"](https://dl.acm.org/doi/10.1145/800064.801255) \
  James F. Blinn (JPL) \
  Proceedings of SIGGRAPH '82, 1 July 1982, p.21-29

- ["A Generalization of Algebraic Surface Drawing"](https://dl.acm.org/doi/10.1145/800064.801290) \
  James F. Blinn (JPL) \
  Proceedings of SIGGRAPH '82, 1 July 1982, p.273

- ["A Generalization of Algebraic Surface Drawing"](https://dl.acm.org/doi/10.1145/357306.357310) \
  James F. Blinn (JPL) \
  ACM Transactions on Graphics, 1 July 1982, p.236-256

- ["Panel: The Simulation of Natural Phenomena"](https://dl.acm.org/doi/10.1145/964967.801142) \
  Charles A. Csuri, James Blinn (JPL), Julian Gomez, Nelson Max, William Reeves \
  SIGGRAPH '83, July 1983, p.137-139

- ["How Many Ways Can You Draw a Circle?"](https://ieeexplore.ieee.org/document/4057251) \
  James F. Blinn \
  IEEE Computer Graphics and Applications, August 1987, p.39-44

  > Let's begin with something I've been thinking about
  > for some time. When I was young I collected stamps;
  > now I collect algorithms for drawing circles. (I also col-
  > lect empty margarine tubs, but that's another story.) It's
  > traditional at this time to drag in the ancient Greeks
  > and mention how they considered the circle the most
  > perfect shape and all that. But it is interesting to see
  > how many essentially different algorithms one can find
  > for drawing them.

- ["The World’s Largest Easter Egg"](https://ieeexplore.ieee.org/document/499) \
  James F. Blinn \
  IEEE Computer Graphics and Applications, March 1988, p.16-23

  > Since it’s almost Easter, I thought I would take this
  > opportunity to write about the world’s largest Easter
  > egg. The egg was designed, fabricated, and erected by
  > Ron Resch with the assistance of his student Robert
  > McDermott at the University of Utah. I became
  > involved for a time near the end of the project and
  > learned several interesting lessons in geometric model-
  > ing and numerical analysis, which I will pass on here. I
  > will also point out some as yet unsolved problems con-
  > cerning the geometry of some of Resch’s dome struc-
  > tures. More details can be found in McDermott’s thesis,
  > Geometric Modelling in Computer Aided Design, Uni-
  > versity of Utah, Computer Science Dept., March 1980
  > (available from University Microfilms, 300 N.Zeeb Rd.,
  > Ann Arbor, MI 48106).
  >
  > **The problem** \
  > Why an Easter egg, you might ask? Well, it seems
  > there’s a town in Alberta, Canada, just east of Edmon-
  > ton, named Vegreville, which has a large Ukrainian
  > population. The town fathers wanted to build a monu-
  > ment in the local park, which would symbolize their
  > culture and bring recognition to the town. The Ukrain-
  > ians are well known for their very elaborate decoration
  > of Easter eggs. So what better way to commemorate
  > their cultural heritage than to build a permanent,
  > three-story high, monumental sculpture of a n Easter
  > egg. Now, egg builders are not easy to find, yet after
  > months of looking the town council ultimately became
  > connected with Ron Resch (then a professor at the Uni-
  > versity of Utah and now with Evans & Sutherland as a
  > consultant) who had been working on novel dome
  > structures.

- ["Computer Graphics Techniques and Computer-Generated Movies"](https://www.sciencedirect.com/science/article/abs/pii/0010465588902305) \
  Robert E. Holzman, James F. Blinn \
  Computer Physics Communications, April 1988, p.229-233

- ["The 3D Kaleidoscope"](https://ieeexplore.ieee.org/document/7756) \
  James E Blinn (Caltech) \
  IEEE Computer Graphics and Applications, September 1988

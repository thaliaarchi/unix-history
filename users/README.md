# Lists of early UNIX users

Numbers of UNIX licensees, installations, UNIX News / ;login: mailing list
members, and USENIX conference registrants.

| Date             | Count                                       | Source                   |
| ---------------- | ------------------------------------------- | ------------------------ |
|                  | 4 UNIX-7 installs                           | Losh FOSDEM '20          |
| June 12, 1972    | 10 installs                                 | Second Edition manual    |
| February 1973    | 16 installs                                 | Third Edition manual     |
| November 1973    | >20 installs                                | Fourth Edition manual    |
| June 1974        | >50 installs                                | Fifth Edition manual     |
| June 27, 1975    | [51 licensees, 55 installs](1975-06-27.txt) | Ken's Dennis_Tapes list  |
| July 16, 1975    | ≥49 licensees                               | UNIX News July 16, 1975  |
| July 30, 1975    | [37 USENIX, ≥51 licensees](1975-07-30.txt)  | UNIX News July 30, 1975  |
| March 19, 1976   | [80 USENIX](1976-03-19.txt)                 | UNIX News March 19, 1976 |
| July 1976        | >125 USENIX                                 | UNIX News July 1976      |
| September 1976   | [138 USENIX](1976-09.txt)                   | UNIX News September 1976 |
| July 1977        | 168 USENIX [TODO]                           | ;login: July 1977        |
| October 1977     | >250 USENIX                                 | ;login: October 1977     |
| January 6, 1978  | 300 Bell installs, ≫300 non-Bell installs   | BSTJ 57.6 page 1947      |
| October 1978     | [38 AUUGN](../auugn/1978-10/4.txt)          | AUUGN October 1978       |
| January 28, 1980 | 447 Boulder USENIX [TODO]                   | ;login: February 1980    |

[^nijmegen]: "SOFTWARE AGREEMENT between WESTERN ELECTRIC COMPANY, INCORPORATED
  and KATHOLIEKE UNIVERSITEIT Effective as of December 1, 1974"
[^holmgren]: "The Network UNIX System" \
  Steve Holmgren \
  Center for Advanced Computation, University of Illinois Urbana-Champaign \
  18 March 1975
[^munix]: *MUNIX, A Multiprocessing Version of UNIX* \
  John Alfred Hawley, III and Walter de Brito Meyer \
  Naval Postgraduate School \
  Master's thesis, June 1975
[^news7507]: UNIX News July 30, 1975
[^pirzada]: *A Statistical Examination of The Evolution of the UNIX System* \
  Shamim Sharifuddin Pirzada \
  Imperial College of Science, Technology and Medicine, University of London \
  Doctor of Philosophy thesis, September 1988
[^smillie]: *The Department of Computing Science: The First Twenty-Five Years* \
  Keith Smillie \
  Department of Computing Science Technical Report TR-91-01, February 1991 \
  University of Alberta
[^releases]: "TUHS Distribution Release Dates",
  modified 3 March 1998
[^mckusick]: *Open Sources: Voices from the Open Source Revolution* \
  Twenty Years of Berkeley Unix: From AT&T-Owned to Freely Redistributable \
  Marshall Kirk McKusick, January 1999
[^venam]: "Licenses on Unix" \
  Patrick Louis, 4 June 2017

UNIX licensees by institution and version. Ken's license number is only listed
for an institution's first version acquired. I assume that Ken's license number
was ordered by date and that any dates conflicting with that order are
imprecise.

TODO: What versions are Network UNIX and MUNIX derived from?

| #   | Date                        | Version           | Institution                             | Notes                                                                  | Sources                |
| --- | --------------------------- | ----------------- | --------------------------------------- | ---------------------------------------------------------------------- | ---------------------- |
|     | Summer 1971                 | ?                 | Patent office                           | Successfully preparing patent applications on UNIX                     | [^pirzada]             |
| \-  | November 3, 1971            | **V1**            | -                                       | -                                                                      | [^releases]            |
| \-  | June 12, 1972               | **V2**            | -                                       | -                                                                      | [^releases]            |
| \-  | February 1973               | **V3**            | -                                       | -                                                                      | [^releases]            |
| 1   | October 1973                | ?                 | Columbia University                     | License granted, first educational license                             | [^pirzada]             |
| 2   | October 1973                | V4                | University of Alberta                   | V4 shipped                                                             | [^smillie]             |
| 3   | October 1973                | ?                 | The Children's Museum                   | First non-educational licensee                                         | [^pirzada]             |
| \-  | November 1973               | **V4**            | -                                       | -                                                                      | [^releases]            |
| 9   | at latest Winter 1973/1974  | ?                 | Harvard University                      | Start of joint work with the Children's Museum                         | [^news7507]            |
| 14  | February 1974               | ?                 | Hebrew University of Jerusalem          | License granted, first licensee outside the US                         | [^pirzada]             |
| 23  | January 1974                | V4                | University of California, Berkeley      | V4 delivered (attended SOSP'73)                                        | [^mckusick]            |
| 24  | May 1974                    | ?                 | Queen Mary University of London         | License granted                                                        | [^pirzada]             |
| \-  | June 1974                   | **V5**            | -                                       | -                                                                      | [^releases]            |
|     | Spring 1974[1]              | V5[1] [2]         | University of California, Berkeley      | Purchased a PDP-11/40 running V5[1], no license sold[2]                | 1[^mckusick] 2[^venam] |
| 26  | July 1974                   | ?                 | The Rand Corporation                    | License granted, first commercial licensee                             | [^pirzada]             |
| 27  | before Feb 1975[1], 1975[2] | V5[2]             | University of Illinois Urbana-Champaign | Network UNIX running full time[1], first source license for V5 sold[2] | 1[^holmgren] 2[^venam] |
| 34  | Fall 1974                   | ?                 | Naval Postgraduate School               | Purchased (to be used for MUNIX)                                       | [^munix]               |
| 49  | December 1, 1974            | ?                 | Katholieke Universiteit Nijmegen        | License effective date                                                 | [^nijmegen]            |
| \-  | May 1975                    | **V6**            | -                                       | -                                                                      | [^releases]            |
|     | Fall 1975                   | V6                | University of California, Berkeley      | Thompson brought up V6 over one-year sabbatical                        | [^mckusick]            |
| \-  | around May 1977             | **Mini-UNIX**     | -                                       | -                                                                      | [^releases]            |
| \-  | June 1977 (in use)          | **PWB/UNIX**      | -                                       | -                                                                      | [^releases]            |
| \-  | March 9, 1978               | **1BSD**          | -                                       | -                                                                      | [^releases]            |
| \-  | mid 1978                    | **2BSD**          | -                                       | -                                                                      | [^releases]            |
| \-  | January 1979                | **V7**            | -                                       | -                                                                      | [^releases]            |
| \-  | early 1979                  | **32V**           | -                                       | -                                                                      | [^releases]            |
|     | after early 1978            | 32V               | University of California, Berkeley      | Obtained a copy of 32V after arrival of VAX-11/780                     | [^mckusick]            |
| \-  | late 1979                   | **3BSD**          | -                                       | -                                                                      | [^releases]            |
| \-  | July 1981                   | **2.8BSD**        | -                                       | -                                                                      | [^releases]            |
| \-  | January 1982                | **2.8.1BSD**      | -                                       | -                                                                      | [^releases]            |
| \-  | July 1983                   | **2.9BSD**        | -                                       | -                                                                      | [^releases]            |
| \-  | November 1983               | **2.9.1BSD**      | -                                       | -                                                                      | [^releases]            |
| \-  | February 1985               | **V8**            | -                                       | -                                                                      | [^releases]            |
| \-  | August 1985                 | **2.9BSD-Seismo** | -                                       | -                                                                      | [^releases]            |
| \-  | September 1986              | **V9**            | -                                       | -                                                                      | [^releases]            |
| \-  | April 1987                  | **2.10BSD**       | -                                       | -                                                                      | [^releases]            |
| \-  | January 1989                | **2.10.1BSD**     | -                                       | -                                                                      | [^releases]            |
| \-  | October 1989                | **V10**           | -                                       | -                                                                      | [^releases]            |
| \-  | February 1992               | **2.11BSD**       | -                                       | -                                                                      | [^releases]            |
| \-  | February 1997               | **2.11BSD #366**  | -                                       | -                                                                      | [^releases]            |

UNIX licensees ordered by Ken's license number or by first appearance.

List sources:
1. Ken's list from Dennis_Tapes, June 27, 1975
2. UNIX News July 30, 1975
3. UNIX News March 19, 1976
4. UNIX News September 1976
5. AUUGN October 1978, trimmed to only new institutions

| Ken #     | First installation        | Institution                                           | City                         | Department                       | Contact                        | Lists   |
| --------- | ------------------------- | ----------------------------------------------------- | ---------------------------- | -------------------------------- | ------------------------------ | ------- |
| 0.1       |                           | Bell Telephone Laboratories                           | Murray Hill, NJ              |                                  | Mr. Ken Thompson               |   2   4 |
|           |                           | Bell Telephone Laboratories                           | Murray Hill, NJ              |                                  | Mr. Dennis M. Ritchie          |     3 4 |
|           |                           | Bell Telephone Laboratories                           | Murray Hill, NJ              |                                  | Mr. Joseph F. Maranzano        |     3 4 |
|           |                           | Bell Telephone Laboratories                           | Murray Hill, NJ              |                                  | Irma B. Biren                  |       4 |
| 0.2       |                           | Bell Telephone Laboratories                           | Holmdel, NJ                  |                                  | Mr. Clyde P. Imagna            |   2 3 4 |
|           |                           | Bell Telephone Laboratories                           | Holmdel, NJ                  |                                  | Mr. J.J. Molinelli             |       4 |
|           |                           | Bell Telephone Laboratories                           | Piscataway, NJ               |                                  | R.C. Haight                    |       4 |
|           |                           | Bell Telephone Laboratories                           | Piscataway, NJ               |                                  | John R. Mashey                 |       4 |
|           |                           | Western Electric                                      | New York, NY                 | Patent License Manager           | Richard G. Shahpazian, Esq.    |     3   |
|           |                           | Western Electric                                      | Greensboro, NC               | Patent License Manager           | Richard G. Shahpazian, Esq.    |       4 |
| 1         | Oct 1973 [^pirzada]       | Columbia University                                   | New York, NY                 | Biological Sciences              | Prof. Cyrus Levinthal          | 1       |
| 1a, 1     |                           | Columbia University                                   | New York, NY                 | Biological Sciences              | Mr. Reidar Bornholdt           | 1 2 3 4 |
| 2         | Oct 1973 (V4) [^smillie]  | University of Alberta                                 | Edmonton, AB, Canada         | Computing Science                | Prof. T. A. Marsland           | 1 2 3 4 |
| 3         | Oct 1973 [^pirzada]       | The Children's Museum                                 | Boston, MA                   |                                  | Mr. Bill Mayhew                | 1 2 3 4 |
| 4         |                           | Princeton University                                  | Princeton, NJ                | Electrical Engineering           | Prof. Bruce W. Arden           | 1 2 3 4 |
|           |                           | Princeton University                                  | Princeton, NJ                | Statistics                       | Prof. Peter Bloomfield         |     3 4 |
| 5         |                           | University of Wisconsin                               | Madison, WI                  | Computer Science                 | Prof. E. J. Desautels          | 1 2 3 4 |
| 6         |                           | California Institute of Technology                    | Pasadena, CA                 |                                  | Mr. A. J. Lindstrom            | 1       |
| 7         |                           | Case Western Reserve University                       | Cleveland, OH                | Biometry                         | Mr. Gary M. Goins              | 1 2 3 4 |
| 8         |                           | Johns Hopkins University                              | Baltimore, MD                | Electrical Engineering           | Prof. W. H. Huggins            | 1 2 3 4 |
| 9         | ≤Winter 1973/1974 [^news7507] | Harvard University                                | Cambridge, MA                | Computation                      | Mr. Brent Byer                 | 1       |
| 9         |                           | Harvard University                                    | Cambridge, MA                | Science Center                   | Mr. Lewis A. Law               |   2 3 4 |
|           |                           | Harvard University                                    | Boston, MA                   | Public Health                    | Shao-Sun Chien                 |       4 |
| 10        |                           | Georgia Institute of Technology                       | Atlanta, GA                  | Information and Computer Science | Dr. Vladimir Slamecka          | 1       |
|           |                           | Georgia Institute of Technology                       | Atlanta, GA                  | Information and Computer Science | Carl Bedingfield               |     3   |
|           |                           | Georgia Institute of Technology                       | Atlanta, GA                  | Information and Computer Science | Henry N. Camp                  |       4 |
| 11        |                           | Brooklyn College of CUNY                              | New York, NY                 | Computer Systems                 | Dr. Kenneth King               | 1       |
| 11a, 11.1 |                           | Brooklyn College of CUNY                              | Brooklyn, NY                 | Physics                          | Prof. Melvin Ferentz           | 1 2 3 4 |
| 11.2      |                           | Brooklyn College of CUNY                              | Brooklyn, NY                 | Computing Center                 | Mr. Ira Fuchs                  |   2 3 4 |
|           |                           | CUNY Graduate Center                                  | New York, NY                 |                                  | Mr. Sol Congola                |     3   |
|           |                           | CUNY Graduate Center                                  | New York, NY                 | Computer Center                  | Dr. Leon Landovitz             |       4 |
| 12        |                           | Columbia University                                   | New York, NY                 | Physicians and Surgeons          | James P. Lewis                 | 1       |
| 12        |                           | Columbia University                                   | New York, NY                 | Physicians and Surgeons          | Dr. Lou Katz                   |   2 3 4 |
| 13        |                           | Oregon Museum of Science and Industry                 | Portland, OR                 | Computing                        | Mr. Rusty Whitney              | 1       |
| 13        |                           | Oregon Museum of Science and Industry                 | Portland, OR                 | Computer Center                  | Mr. Barry Smith                |   2 3 4 |
| 14        | Feb 1974 [^pirzada]       | Hebrew University of Jerusalem                        | Jerusalem, Israel            | Computer Science                 | Mr. Gideon Yuval               | 1 2     |
|           |                           | Hebrew University of Jerusalem                        | Jerusalem, Israel            | Computer Science                 | Prof. Amnon Barak              |     3 4 |
| 15        |                           | University of California, San Francisco               | San Francisco, CA            | Contracts and Grants             | Mr. Stanley C. Bateman         | 1       |
|           |                           | University of California, San Francisco               | San Francisco, CA            | Pharmacy                         | Thomas E. Ferrin               |       4 |
|           |                           | University of California, San Francisco               | San Francisco, CA            | Radiology                        | Vernon Smith                   |       4 |
| 16        |                           | California State University                           | Fullerton, CA                | Quantitative Methods             | Prof. D. A. Michalopoulos      | 1       |
| 17        |                           | Polytechnic Institute of New York, Long Island Center | Farmingdale, NY              |                                  | Prof. N. Marcuvitz             | 1       |
|           |                           | Polytechnic Institute of New York, Long Island Center | Farmingdale, NY              |                                  | Mr. George Kull                |   2 3 4 |
| 18, 18.1  |                           | University of Waterloo                                | Waterloo, ON, Canada         | Computer Science                 | Prof. R. W. Peebles            | 1 2 3 4 |
| 18.2      |                           | University of Waterloo                                | Waterloo, ON, Canada         | Computer Science                 | Dr. Ernest Chang               |   2 3 4 |
| 19        |                           | University of Utah                                    | Salt Lake City, UT           | Computer Science                 | Mr. Martin E. Newell           | 1 2 3 4 |
| 20        |                           | Queen's University at Kingston                        | Kingston, ON, Canada         | Computing Science                | Prof. D. A. Jardine            | 1       |
|           |                           | Queen's University at Kingston                        | Kingston, ON, Canada         | Comp. and Info. Sci.             | Prof. Jeffrey Kulick           |     3 4 |
|           |                           | Queen's University at Kingston                        | Kingston, ON, Canada         | Comp. and Info. Sci.             | Prof. D. A. Jardine            |       4 |
| 21        |                           | Saint Olaf College                                    | Northfield, MN               | Science Building                 | Prof. Ralph H. Bjork           | 1 2 3   |
|           |                           | Saint Olaf College                                    | Northfield, MN               | Academic Computer Center         | Timothy W. Hoel                |       4 |
| 22        |                           | Duke University                                       | Durham, NC                   | Medical Center                   | Prof. C. Frank Starmer         | 1 2 3   |
|           |                           | Duke University                                       | Durham, NC                   | Computer Science                 | Prof. Susan Gerhart            |       4 |
| 23        | Jan 1974 (V4) [^mckusick] | University of California, Berkeley                    | Berkeley, CA                 | Computer Science                 | Prof. Bob Fabry                | 1 2 3 4 |
|           |                           | University of California, Berkeley                    | Berkeley, CA                 | Computer Science                 | Prof. Mike O'Malley            |     3   |
|           |                           | University of California, Berkeley                    | Berkeley, CA                 | EECS                             | Prof. Michael Stonebraker      |     3   |
| 24        | May 1974 [^pirzada]       | Queen Mary University of London                       | London, England              | Computer Science                 | Dr. M. S. Cole                 | 1   3   |
|           |                           | Queen Mary University of London                       | London, England              | Computer Science                 | Jon Rowson                     |       4 |
| 25        |                           | Yale University                                       | New Haven, CT                |                                  | Mr. John E. Ecklund            | 1       |
|           |                           | Yale University                                       | New Haven, CT                | Computer Science                 | Robert W. Tuttle               |     3 4 |
|           |                           | Yale University                                       | New Haven, CT                | Psychology                       | Dr. Michael Kubovy             |     3 4 |
|           |                           | Yale University                                       | New Haven, CT                | Chemistry                        | Prof. Kenneth Wiberg           |       4 |
|           |                           | Yale University                                       | New Haven, CT                | Computer Center                  | Greydon C. Freeman             |       4 |
|           |                           | Yale University                                       | New Haven, CT                | Lung Research Center             | Roger Deshaies                 |       4 |
|           |                           | Yale University                                       | New Haven, CT                | PDP-11 Computer Room             | Registrar's Office             |       4 |
| 26        | Jul 1974 [^pirzada]       | The Rand Corporation                                  | Santa Monica, CA             | Information Sciences             | Dr. P. Weiner                  | 1       |
| 26        |                           | The Rand Corporation                                  | Santa Monica, CA             | Information Sciences             | Mr. John Lowry                 |   2 3   |
| 26a       |                           | The Rand Corporation                                  | Santa Monica, CA             | Information Sciences             | Ms. Lois H. Heiser             | 1       |
|           |                           | The Rand Corporation                                  | Santa Monica, CA             |                                  | Lauren Weinstein               |       4 |
| 27        | <Feb 1975 [^holmgren]     | University of Illinois Urbana-Champaign               | Urbana, IL                   | Computer Science                 | Prof. D. B. Gillies            | 1       |
| 27a       |                           | University of Illinois Urbana-Champaign               | Urbana, IL                   | Computer Science                 | Greg Chesson                   | 1       |
|           |                           | University of Illinois Urbana-Champaign               | Urbana, IL                   |                                  | Steve Holmgren                 |     3 4 |
| 28        |                           | University of Texas at Dallas                         | Richardson, Texas            | Physical Sciences                | Mr John Vanderford             | 1       |
| 28        |                           | University of Texas at Dallas                         | Richardson, Texas            | Advanced Studies                 | D. W. Canham, Jr.              |   2 3 4 |
| 29        |                           | Université catholique de Louvain                      | Louvain-La-Neuve, Belgium    | Informatique                     | Prof. E. Milgrom               | 1 2 3 4 |
| 30        |                           | Stanford University School of Medicine                | Stanford, CA                 | Radiology                        | Prof. C. J. Karzmark           | 1 2 3 4 |
| 31        |                           | University of Alabama in Birmingham                   | Birmingham, AL               |                                  | Mr. Travis Wood                | 1   3 4 |
| 32        |                           | Knox College                                          | Galesburg, IL                | Computer Center                  | Mr. William C. Ripperger       | 1 2 3 4 |
| 33        |                           | University of Edinburgh Medical School                | Edinburgh, Scotland          | Medical Computing                | Mr. Jeffrey Tansley            | 1 2     |
|           |                           | University of Edinburgh                               | Edinburgh, Scotland          | Computer Science                 | Mr. Jeffrey Tansley            |     3 4 |
| 34        | Fall 1974 [^munix]        | Naval Postgraduate School                             | Monterey, CA                 | Computer Science                 | Prof. Belton E. Allen          | 1 2 3   |
|           |                           | Naval Postgraduate School                             | Monterey, CA                 | Computer Science                 | Prof. Gerald L. Barksdale, Jr. |       4 |
| 35        |                           | University of North Carolina at Chapel Hill           | Chapel Hill, NC              | Computer Science                 | Prof. James D. Foley           | 1 2 3 4 |
| 36        |                           | The Spence School                                     | New York, NY                 |                                  | Mr. Dustin H. Heuston          | 1 2 3 4 |
| 37        |                           | University of Toronto                                 | Toronto, ON, Canada          | Computer Research                | Mr. T. C. Stevens              | 1       |
| 37        |                           | University of Toronto                                 | Toronto, ON, Canada          | Computer Research                | Mr. Dennis Smith               |   2     |
|           |                           | University of Toronto                                 | Toronto, ON, Canada          | Computer Systems Research        | Mr. Tom Horsley                |     3   |
|           |                           | University of Toronto                                 | Toronto, ON, Canada          | Computer Research                | Mr. K. C. Patnaik              |       4 |
| 38        |                           | University of Saskatchewan                            | Saskatoon, SK, Canada        | Computational Science            | R. M. Kavanaugh                | 1       |
| 38        |                           | University of Saskatchewan                            | Saskatoon, SK, Canada        | Computational Science            | Peter Hardie                   |   2 3 4 |
| 39        |                           | Princeton University                                  | Princeton, NJ                | Statistical Computing            | D. R. McNeil                   | 1       |
| 40        |                           | Denison University                                    | Granville, OH                | Purchasing                       | H. L. Conts, Jr.               | 1   3   |
|           |                           | Denison University                                    | Granville, OH                | Computer Center                  | Director                       |       4 |
| 41        |                           | Minuteman Regional Vocational High School             | Lexington, MA                |                                  | H. Bellmar                     | 1   3 4 |
| 42        |                           | International Institute for Applied Systems Analysis  | Laxenburg, Austria           | Computing Services               | Jim Curry                      | 1   3 4 |
| 43        |                           | Carleton College                                      | Northfield, MN               | Computer Center                  | Carl Henry                     | 1 2 3 4 |
| 44        |                           | Foundation Mathematisch Centrum                       | Amsterdam, Netherlands       | Computer Science                 | D. W. de Bakker                | 1   3 4 |
| 45        |                           | East Brunswick High School                            | East Brunswick, NJ           |                                  | Mr. Seymour Grodstein          | 1 2 3 4 |
| 46        |                           | The Cooper Union                                      | New York, NY                 | Engineering                      | C. W. Tan                      | 1       |
|           |                           | The Cooper Union                                      | New York, NY                 | Computer Center                  | Robert P. Hopkins              |     3 4 |
| 47        |                           | University of South Carolina                          | Columbia, SC                 |                                  | H. S. Eisenstein               | 1   3   |
|           |                           | University of South Carolina                          | Columbia, SC                 |                                  | H. K. Eisenstein               |       4 |
| 48        |                           | University of New South Wales                         | Kensington, NSW, Australia   |                                  | R. Whitfeld                    | 1       |
|           |                           | University of New South Wales                         | Kensington, NSW, Australia   | Computer Science                 | Dr. John Lions                 |     3 4 |
|           |                           | University of New South Wales                         | Kensington, NSW, Australia   | Computing Services               | Manager                        |       4 |
| 49        | Dec 1 1974 [^nijmegen]    | Katholieke Universiteit Nijmegen                      | Nijmegen, Netherlands        |                                  | J. van den Bas                 | 1       |
|           |                           | Katholieke Universiteit Nijmegen                      | Nijmegen, Netherlands        | Science                          | Hendrik-Jan Thomassen          |     3 4 |
| 50        |                           | Heriot-Watt University                                | Edinburgh, Scotland          | Electrical Engineering           | P. L. De Souza                 | 1       |
| 50        |                           | Heriot-Watt University                                | Edinburgh, Scotland          | Electrical Engineering           | Prof. F. G. Heath              |   2 3 4 |
| 51        |                           | University of Manitoba                                | Winnipeg, MB, Canada         | Computer Science                 | Dr. R. J. Collens              | 1 2 3 4 |
|           |                           | University of Manitoba                                | Winnipeg, MB, Canada         | Computer Science                 | Dr. J.M. Wells                 |       4 |
|           |                           | University of California, San Diego                   | La Jolla, CA                 | Chemistry                        | John Cornelius                 |     3 4 |
|           |                           | University of California, San Diego                   | La Jolla, CA                 | Physics                          | Lawrence McDaniel              |       4 |
|           |                           | California Polytechnic State University               | San Luis Obispo, CA          | Comp. Sci. and Stat.             | Dr. James L. Beug              |     3   |
|           |                           | California Polytechnic State University               | San Luis Obispo, CA          | Computer Center                  | Marc Lewis                     |       4 |
|           |                           | California Polytechnic State University               | San Luis Obispo, CA          | Computer Center                  | Mr. John Bass                  |       4 |
|           |                           | Data Disc Inc.                                        | Sunnyvale, CA                |                                  | Eric Sultan                    |     3   |
|           |                           | National Bureau of Standards                          | Washington, DC               |                                  | Brian Lucas                    |     3 4 |
|           |                           | The Pentagon                                          | Washington, DC               |                                  | Major Allan R. Wylie           |     3 4 |
|           |                           | The Pentagon                                          | Washington, DC               | Defense Comm. Agency             | Charles F. Anderson            |       4 |
|           |                           | University of Delaware                                | Newark, DE                   | Computing Center                 | John J. Falcone                |     3   |
|           |                           | University of Delaware                                | Newark, DE                   | Computer Science Laboratory      | Michael B. Raffel              |       4 |
|           |                           | Rush Medical Center                                   | Chicago, IL                  | Medicine                         | Laurens V. Ackerman, M.D.      |     3 4 |
|           |                           | University of Illinois Chicago                        | Chicago, IL                  | Information Engineering          | Mr. Michael T. O'Brien         |     3 4 |
|           |                           | Purdue University                                     | West Lafayette, IN           | Electrical Engineering           | James J. Besemer               |     3 4 |
|           |                           | Purdue University                                     | West Lafayette, IN           | Agricultural Engineering         | Stephen J. Mahler              |     3 4 |
|           |                           | National Security Agency                              | Fort G. G. Meade, MD         |                                  | Dennis L. Mumaugh              |     3 4 |
|           |                           | Commercial Union Leasing                              | New York, NY                 |                                  | Mr. Dick Shore                 |     3 4 |
|           |                           | Bronx Community College                               | Bronx, NY                    | Computing Center                 | Mr. Meyer Shopko               |     3   |
|           |                           | New York Institute of Technology                      | Old Westbury, NY             | Computer Graphics                | Prof. Ed Catmull               |     3 4 |
|           |                           | Cornell University                                    | Ithaca, NY                   | Computer Graphics                | David H. Bessel                |     3 4 |
|           |                           | Moravian College                                      | Bethlehem, PA                | Computer Center                  | Mr. Rance De Long              |     3 4 |
|           |                           | RLG Associates, Inc.                                  | Reston, VA                   |                                  | Harold A. Solow                |     3 4 |
|           |                           | Computing Devices Company                             | Ottawa, ON, Canada           |                                  | W. D. Richardson               |     3 4 |
|           |                           | Bell Canada                                           | Dorval, QC, Canada           |                                  | Michael R. Collins             |     3   |
|           |                           | University of Kent at Canterbury                      | Canterbury, Kent, England    | Computing Laboratory             | Stephen Binns                  |     3   |
|           |                           | University of Kent at Canterbury                      | Canterbury, Kent, England    | Computing Laboratory             | Dr. R.P.A. Collinson           |       4 |
|           |                           | Digital Laboratory                                    | Beer-sheva, Israel           |                                  | Ralph Pesso                    |     3 4 |
|           |                           | Universidad Simon Bolivar                             | Caracas, Venezuela           | Informacion Y Computacion        | Hernán Suárez-Flamerich        |     3 4 |
|           |                           | University of California, Los Angeles                 | Los Angeles, CA              | Computer Science                 | Prof. Gerald J. Popek          |       4 |
|           |                           | Naval Electronics Laboratory Center                   | San Diego, CA                |                                  | Glen M. Brechlin               |       4 |
|           |                           | Naval Personnel R & D Center                          | San Diego, CA                |                                  | L.H. Brock                     |       4 |
|           |                           | University of California, Santa Barbara               | Santa Barbara, CA            | Computer Center                  | Steve Smith                    |       4 |
|           |                           | Amcomp                                                | Sunnyvale, CA                |                                  | Bob Marsh                      |       4 |
|           |                           | Stanford University                                   | Stanford, CA                 | Geophysics                       | Jon. F. Claerbout              |       4 |
|           |                           | Naval Research Lab.                                   | Washington, DC               |                                  | James Lucas                    |       4 |
|           |                           | Southern Illinois University                          | Carbondale, IL               | Computer Science                 | Dr. A.M. Mark                  |       4 |
|           |                           | Mitre Corp.                                           | Bedford, MA                  |                                  | Ken Biba                       |       4 |
|           |                           | Mitre Corp.                                           | Bedford, MA                  |                                  | Dr. John C. C. White           |       4 |
|           |                           | L.G. Hanscom AFB                                      | L.G. Hanscom AFB, MA         | ESD/MCIT                         | Capt Paul Karger               |       4 |
|           |                           | MIT Lincoln Laboratory                                | Cambridge, MA                | Applied Seismology               | Peter Neilson                  |       4 |
|           |                           | MIT Lincoln Laboratory                                | Lexington, MA                |                                  | Alan G. Nemeth                 |       4 |
|           |                           | Department of Defense                                 | Ft. Meade, MD                |                                  | J. Gary Donnelly               |       4 |
|           |                           | University of Minnesota                               | Minneapolis, MN              | Interactive Computation Lab.     | Prof. W.R. Franta              |       4 |
|           |                           | University of Minnesota                               | Minneapolis, MN              | Computer Science                 | Prof. G. Michael Schneider     |       4 |
|           |                           | Washington University                                 | St. Louis, MI                | Biomedical Computer Laboratory   | Kenneth L. Ripley              |       4 |
|           |                           | Stevens Institute of Technology                       | Hoboken, NJ                  | Electrical Engineering           | Prof. Emil C. Neu              |       4 |
|           |                           | Sandia Laboratories                                   | Albuquerque, NM              |                                  | C. J. Fisk                     |       4 |
|           |                           | Los Alamos Scientific Laboratory                      | Los Alamos, NM               |                                  | R.P. Kruger                    |       4 |
|           |                           | Yourdon, Inc.                                         | New York, NY                 |                                  | P.J. Plauger                   |       4 |
|           |                           | Brookhaven National Laboratory                        | Upton, NY                    | Physical Review                  | Stuart Kern                    |       4 |
|           |                           | University of Toledo                                  | Toledo, OH                   |                                  | Computer Services              |       4 |
|           |                           | Xavier University                                     | Cincinnati, OH               | Physics                          | Prof. Frederick G. Werner      |       4 |
|           |                           | University of Pennsylvania                            | Philadelphia, PA             | Bio Phys and Phys Biochem        | Mr. Scott M. Eleff             |       4 |
|           |                           | Texas Medical Center                                  | Houston, TX                  | Baylor College of Medicine       |                                |       4 |
|           |                           | University of Texas at Austin                         | Austin, TX                   | Computation Center               | David M. Phillips              |       4 |
|           |                           | University of Texas at El Paso                        | El Paso, TX                  | E. E.                            | Glenn Gibson                   |       4 |
|           |                           | Science Applications, Inc.                            | Arlington, VA                |                                  |                                |       4 |
|           |                           | ARPA                                                  | Arlington, VA                |                                  | Steve Walker                   |       4 |
|           |                           | University of Vermont                                 | Burlington, VT               | Lung Center                      | Mr. Richard Becker             |       4 |
|           |                           |                                                       | Toronto, ON, Canada          |                                  | Mr. Rick Macfarlane            |       4 |
|           |                           | University of Calgary                                 | Calgary, AB, Canada          | Environmental Design             | Prof. Lawrence O. Sinkey       |       4 |
|           |                           | University of British Columbia                        | Vancouver, BC, Canada        | Animal Resource Ecology          | Stephen W. Borden              |       4 |
|           |                           | University of Sydney                                  | Sydney, NSW, Australia       | Computer Science                 | Ian Jackson                    |       4 |
|           |                           | University of Newcastle                               | Newcastle, NSW, Australia    | Computing Centre                 | J.A. Lambert                   |       4 |
|           |                           | Technische Universität Berlin                         | Berlin, Germany              |                                  |                                |       4 |
|           |                           | University of Sussex                                  | Brighton, England            | Cognitive Studies                | Dr. Steven Hardy               |       4 |
|           |                           | University of Essex                                   | Colchester, England          |                                  |                                |       4 |
|           |                           | University of Glasgow                                 | Glasgow, Scotland            | Computing Science                | William Findlay                |       4 |
|           |                           | Loughborough University of Technology                 | Loughborough, England        | Computer Studies                 | D.W. Taylor                    |       4 |
|           |                           | University of Newcastle upon Tyne                     | Newcastle upon Tyne, England |                                  |                                |       4 |
|           |                           | University of London, Westfield College               | London, England              |                                  | Colin Taylor                   |       4 |
|           |                           | Technion - Israel Institute of Technology             | Haifa, Israel                |                                  |                                |       4 |
|           |                           | Vrije Universiteit                                    | Amsterdam, Netherlands       | Mathematics                      | Dr. Andrew Tanenbaum           |       4 |
|           |                           | Royal Military College                                | Campbell, ACT, Australia     |                                  |                                |       5 |
|           |                           | University of Melbourne                               | Melbourne, VIC, Australia    |                                  |                                |       5 |
|           |                           | University of Queensland                              | Brisbane, QLD, Australia     |                                  |                                |       5 |
|           |                           | Macquarie University                                  | Sydney, NSW, Australia       |                                  |                                |       5 |
|           |                           | Australian Atomic Energy Commission                   | Sydney, NSW, Australia       |                                  |                                |       5 |
|           |                           | CSIRO                                                 | Canberra, ACT, Australia     |                                  |                                |       5 |
|           |                           | University of Wollongong                              | Wollongong, NSW, Australia   |                                  |                                |       5 |
|           |                           | NSW Institute of Technology                           | Sydney, NSW, Australia       |                                  |                                |       5 |
|           |                           | University of Adelaide                                | Adelaide, SA, Australia      |                                  |                                |       5 |

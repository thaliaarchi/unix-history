# Sources for the University of Utah and UNIX

## People

- [David Evans](evans.md)
- [Ivan Sutherland](sutherland.md)
- [Martin Newell](newell.md)
- [Jim Blinn](blinn.md)
- Ed Catmull
- [Paul Abegglen](abegglen.md)
- Gary Lindstrom
- [Mike Hibler](hibler.md)
- [Jay Lepreau](lepreau.md)

First listed in June 1975:

```
801-581-8224
Mr. Martin E. Newell
Computer Science Dept.
Univ. of Utah
Salt Lake City, Utah 84112
```

First listed in July 1977:

```
801-531-7711
Walter B. Dilts
Berkeley Scientific Laboratories
Clinical Laboratory Division
330 West 5th South
Salt Lake City, Utah 84101
```

First listed in February 1980:

- Randy Frank, University of Utah
- Spencer W. Thomas, University of Utah

## Areas

- [Graphics](graphics.md)
- [ARPANET](arpanet.md)

## Research questions

I'm a PhD student in computer science. We recently discovered a tape here in the
MEB from early 1974, that contains the only surviving copy of UNIX V4, the
earliest version of the UNIX operating system to be publicly released. I am
researching our early involvement with UNIX circa 1973–1977 to write an article
which will be released in December once we've digitized it.

My priority is to learn why we first obtained UNIX (e.g., our connection to
SOSP'73 where it was first announced) and what we did with it (e.g., was it used
for graphics? was it an ARPANET node?). I have a good idea of when we acquired
it from tracking down other universities' license agreements with Western
Electric, but I want to find ours. I know Martin Newell obtained it, but he
doesn't remember it; this may indicate not much was thought of this first
version, so locating these materials could prove difficult.

## Timeline

A more concrete UNIX-in-graphics timeline is forming:

- We get V4 in 1974 and it's unsuitable and quickly forgotten.
- In 1977, UNIX and C were as new as Carbon is now. That's enough time for early
  adopters to build off of it.
- The first uses of UNIX in the Computer Graphics conference were in 1976 in
  Bell Labs and 1977 outside. It was becoming popular in graphics.
- A UNIX driver was created for the Evans & Sutherland Picture System 2 between
  May 1977[^ps2_brief] [^losalamos] and October 1978[^ps2_unix]. \
  (The August 1978 paper is likely out of date by several months, due to
  publishing lag and it referring to the decisions made at the start of the
  project. The October 1978 manual refers to an earlier version of the UNIX
  support.)
- Ed Catmull started the graphics group at NYIT in November 1974, so their
  parallel use of UNIX may have developed from the Zeitgeist, not Utah.

[^ps2_brief]: "Picture System 2 Product Brief" \
    Evans & Sutherland, May 1977 \
    Collection MS 0625 David C. Evans papers, Box 61, Folders 1–2 \
    University of Utah Libraries,
    Special Collections, J. Willard Marriott Library

    The supported operating systems mentioned were DOS/BATCH, RT-11, and
    RSX-11M.

[^losalamos]: "A High Performance Graphics System for the CRAY-1" \
    Robert H. Ewald and Lynn D. Maas \
    Los Alamos Scientific Laboratory \
    SIGGRAPH '78, August 1978, pages 76–81

    > support software for the Picture System 2 would have to be written since
    > Evans and Sutherland does not currently support UNIX. […] A Picture System
    > 2 UNIX I/O driver, written in the "C" language, was obtained from the
    > University of California, San Francisco, [Ferrin, 1977].

    The cited PS-2 User's Manual is dated May 1977, same as the Product Brief.

[^ps2_unix]: "UNIX Picture System II User Guide" \
    Jim Clark \
    Evans & Sutherland, October 1978 \
    Collection MS 0625 David C. Evans papers, Box 61, Folders 1–2 \
    University of Utah Libraries,
    Special Collections, J. Willard Marriott Library

    > A new Picture System II device driver is complete […]. The new system has
    > several advantages over the previous routines. […] The system is about
    > five times faster than the previous system. Some of this gain […] results
    > from fewer UNIX system calls.

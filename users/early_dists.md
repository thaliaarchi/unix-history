# "Good day to cut a tape"

I've been making the claim that early UNIX tapes were copied on-demand from
Ken's research machine and that they'd sometimes wait until the system was
stable. But, hearing this repeated back to me today has motivated to check my
sources again.

For example, I wrote this in December about V4 and said similar on Saturday at
VCF PNW:

> UNIX wasn’t versioned as we know it today. In the early days, when you wanted
> to cut a tape, you’d ask Ken if it was a good day—whether the system was
> relatively bug-free—and copy off the research machine. The manuals were
> versioned and you got whatever the last one was.
>
> The V5 manual is dated June 1974 (anyone know a better date?), same as our
> tape. I suspect the next manual was finished days or weeks after this was
> sent, so this may perhaps be the most extreme drift in an extant copy of UNIX
> between the manual features and the shipped features.
    https://www.tuhs.org/pipermail/tuhs/2025-December/032861.html

Why do the distribution tapes not have development artifacts?
Why do they have large swaths of files with the same modification time?

*A Statistical Examination of The Evolution of the UNIX System*
Shamim Sharifuddin Pirzada
Imperial College London, PhD thesis, September 1988
https://www.tuhs.org/Archive/Documentation/Theses/Shamim_Sharfuddin_Pirzada-1988-PhD-Thesis.pdf

> In the early days people who wanted UNIX systems just went along to the
> Research Center and took a magnetic snapshot of what was on Thompson's system
> at the time, there wasn't an official release or a distribution tape as such.
> The version of UNIX on the Research Center was known after the edition number
> of the current manual. So, for example, between the publication of the first
> edition of the manual and before the second, the system was known as version 1
> or v1. [page 33]

> The system was initially distributed by dumping the contents of the CSRC
> machine onto tape and sending the tape out with a covering letter and minimal
> documentation (installation guide and manual) but a list of installation was
> kept. New editions of the manual were prepared when it was apparent to staff
> at CSRC that the manual no longer reflected the state of the CSRC system, this
> was usually done informally and no official release documents as such, were
> prepared. This strategy still exists today but the distribution was handed
> over to the Computing Library at Bell Labs, which set up slightly more formal
> arrangements based on distribution tapes supplied by the CSRC, for the
> releases v6 - v8. [page 60]

[*A Quarter Century of UNIX*](https://archive.org/details/aquartercenturyofunixpeterh.salus_201910) \
Peter H. Salus \
1994

> But after the first paper was delivered in October 1973, you could have the
> bits put on your RK05 disks. In the early spring of 1974, Lou Katz (then at
> Columbia University) organized a meeting of Unix users. Columbia had been the
> recipient of the first distribution—first on disk, then on 9-track tape—in the
> autumn (“Cy got RK05s for the department,” Katz told me, “but we didn't have a
> drive, so I drove down to Murray Hill and Ken cut me a 9-track tape.”)
> [page 65]

> The tape was personally produced by Ken, who gave it to me [Mike Tilson] at
> Bell Labs. (Then, as now, AT&T was slow to ship. But unlike now, you could
> bypass the paperwork and get the tape yourself.) [page 123]

["Unix at 25"](https://web.archive.org/web/19961220135639/http://www.byte.com/art/9410/sec8/art3.htm) \
Peter H. Salus \
BYTE, October 1996

> Then in October 1973, Thompson and Ritchie gave a paper at the SOSP (Symposium
> on Operating System Principles), and the cat was out of the bag. Immediately
> after SOSP, other sites began requesting this new system. The first user to
> get a tape of the system was Lou Katz at Columbia University in Manhattan. “Cy
> [Cyrus Levinthal, chair of the department of biological sciences] got RKO5s
> [disk packs] for the department, but we didn't have a drive,” Katz says. “So I
> drove down to Murray Hill, and Ken [Thompson] cut me a 9-track tape.”
>
> That was in July 1974; Unix was not quite five years old. Then the publication
> of the SOSP paper in the July issue of the Communications of the ACM caused an
> explosion in demand for the fledgling operating system.

[*Life with UNIX: A Guide for Everyone*](https://www.tuhs.org/Archive/Documentation/Books/Life_with_Unix.pdf) \
Don Libes and Sandy Ressler, 1989

> In 1973, […] there were approximately 25 UNIX systems. A UNIX Systems Group
> was created at the Labs for internal support. Several universities contacted
> Bell Labs and received copies of the Fourth Edition. Agreements were signed
> not to disclose the source code, but no licenses were in use at this point.
> Ken made the tapes himself and didn’t charge anything. The first tapes went to
> Columbia University in New York. [page 7]

[[TUHS] ed.c on Unix v5](https://www.tuhs.org/pipermail/tuhs/2015-December/007908.html) \
Marc Rochkind, TUHS, 19 December 2015

> Right. Obviously Doug can supply the details, but I recall that around 1972 or
> so Dick Haight used to go over from Piscataway to Murray Hill to get a new
> system, and there would be some sort of indication about whether it was a good
> day or a bad day to make a tape.

["[TUHS] unix v4 tape found"](https://www.tuhs.org/pipermail/tuhs/2025-December/032861.html) \
Thalia Archibald \
19 December 2025

> UNIX wasn’t versioned as we know it today. In the early days, when you wanted
> to cut a tape, you’d ask Ken if it was a good day—whether the system was
> relatively bug-free—and copy off the research machine. The manuals were
> versioned and you got whatever the last one was.
>
> The V5 manual is dated June 1974 (anyone know a better date?), same as our
> tape. I suspect the next manual was finished days or weeks after this was
> sent, so this may perhaps be the most extreme drift in an extant copy of UNIX
> between the manual features and the shipped features.

"UNIX V4: History and recovery" \
Thalia Archibald \
VCF PNW, 2 May 2026

> So I did all this digging. And then Aleks, who found the tape, found this
> letter from Ken, apologizing that they were delayed shipping the system
> because they needed to print more docs. So now this is quite an interesting
> tidbit because the tape is from June 1974 and UNIX V5 was released in June
> 1974, but the documentation we received was for V4. So what happened is we
> probably got the very last printing of the documentation. And because in those
> days when you got a distribution, you'd ask Ken, "is today a good day to cut a
> tape?", and if it was, he'd copy it for you. But if not, he'd say, "oh, I've
> got some bugs to fix; come back later." So it was very bleeding edge. And so
> ours is not really V4. But it is V4 because UNIX was versioned by the manual,
> so I still call it V4. But it's pretty much the cleanest V5 you could get. The
> other V5 we have is nine months later.

Zoot, Mainframe Enthusiasts, 5 May 2026

> the release mechanism was that when someone wanted a tape you would go ask Ken
> "if this is a good day or not" and then they just stored the development
> environment to tape)

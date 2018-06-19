Dr. Driver’s Syllabi
====================

This repository holds the code and policy I use to make my course
syllabi in LaTeX.

History
-------

For several years now I have produced my syllabi in LaTeX (or [XeTeX][],
to be exact). Since mid-2013 I have version controlled them in [Git][].
Then, in late 2014, I decided to make them available in this [public
repository][repo] on GitHub.

I use LaTeX for consistency, durability, and [beauty][]. I use Git to
aid my pursuit of continuous improvement, particularly in the
foundational courses that I teach year in and year out. I use GitHub in
the interest of accountability. To my mind a syllabus is a public
document. I want mine to be good enough that I don’t mind having them on
the open web.

The whole system allows me, and my students, and anyone else who might
be interested, to see how my courses have developed over time. I find it
particularly useful for my introduction to the Hebrew Bible/Old
Testament, which I have taught regularly since the Fall of 2008. It has
been through several major iterations since then, and many of those
developments are now recorded here.

```tex
% Taught as RLGS 1013 in:
%   - Fall 2008
%   - Winter 2009
%   - Fall 2009
%   - Winter 2010
%   - Fall 2010
%   - Winter 2011
%   - Winter 2012
%   - Fall 2012
%   - Winter 2013
% Taught as BSTH 1013 in:
%   - Fall 2013 (first to be included in this repo)
%   - Winter 2014
%   - Fall 2014
%   - Winter 2015
%   - Fall 2015
%   - Winter 2016
% Taught as BF 1001 in:
%   - Fall 2016
%   - Fall 2017
%   - Fall 2017(Int - online section run parallel to campus course)
%   - Fall 2018
%   - ...

```

Anyone else who finds this text machinery useful is welcome to fork it
and adapt it for their own use ([CC BY-SA 4.0][license]). If you do,
please remove the school- and course-specific branding, policy, and
content.


Fonts
-----

My use of `fontspec` calls for a good pair of well-designed fonts.
Currently I use [Minion][] and [Myriad][], by Robert Slimbach and, in
the latter case, Carol Twombly. The combination may be plain vanilla,
but it’s efficient, and for technical documents I think it makes sense
to use a “[crystal goblet][goblet].” In the past I have used Martin
Majoor’s [FF Scala][FFS], one of the original superfamilies from
[FontShop][FSS]. For Greek and Hebrew text I usually call on the freely
available [SBL BibLit][SBL], by John Hudson.

The `fontspec` package will issue warnings if certain OpenType features
are not available, but the build process will halt if the specified
fonts are not available to it. Any who fork this repo will need to have
the correct fonts installed, or else to edit the `fontspec` definitions
in `includes/preamble.tex`.

[XeTeX]: https://en.wikipedia.org/wiki/XeTeX
[Git]: https://git-scm.com
[repo]: https://github.com/danieldriver/Syllabi
[beauty]: http://www.nitens.org/taraborelli/latex
[license]: https://creativecommons.org/licenses/by-sa/4.0/
[Minion]: https://en.wikipedia.org/wiki/Minion_(typeface)
[Myriad]: https://en.wikipedia.org/wiki/Myriad_(typeface)
[goblet]: http://www.typographia.org/1999/graphion/crystal-goblet.html
[FFS]: http://scalafont.com
[FSS]: https://www.fontshop.com/superfamilies/ff-scala
[SBL]: http://www.sbl-site.org/educational/biblicalfonts.aspx

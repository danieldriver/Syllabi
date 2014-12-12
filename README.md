DRD's Syllabi
=============

Code and policy for making my course syllabi in LaTeX

Fonts
-----

My use of `fontspec` calls for a good pair of full-featured fonts (serif
and sans serif with small caps, old style numbers, etc). Currently I use
Martin Majoor's [FF Scala][FFS], one of the original superfamilies from
[FontShop][FSS]. Additionally, for Hebrew text I call on the freely
available [SBL BibLit][SBL], by John Hudson.

The `fontspec` package will issue warnings if OpenType features are not
available, but the build process will halt if the specified fonts are
not available to it. Any who fork this repo will need either to have the
correct fonts installed, or to edit the `fontspec` definitions in
`includes/preamble.tex`.

[FFS]: http://scalafont.com
[FSS]: https://www.fontshop.com/superfamilies/ff-scala
[SBL]: http://www.sbl-site.org/educational/biblicalfonts.aspx
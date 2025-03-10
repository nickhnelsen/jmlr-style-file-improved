# JMLR style file

Improved LaTeX style file for the Journal of Machine Learning Research.

Notable changes to `jmlr2e.sty` include:
- Require amsthm package
- Add period after first level section number (both in main body and appendix)
- Add period after last level section number (both in main body and appendix)
- Remove copyright and license if preprint option is enabled
- Fix proof environment to allow custom proof names
- Add counter to "example" theorem environment
- Add "assumption" and "notation" theorem environments with counters, and "problem" and "Main Theorem" theorem environments with no counters

Notable changes to `sample.tex` include:
- Default to "nohyperref" option
- Load hyperref with custom link colors and pagebackref
- Add sample theorem and proof environments with custom names

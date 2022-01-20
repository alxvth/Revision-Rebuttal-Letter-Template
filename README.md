# Revision and Rebuttal letter template

Roughly based on this [Paper Submission Revision Template](https://docs.google.com/document/d/1Vef5VaW1j_vtg5z9lWJo4aKgzM0hUe3UnfBdY6-_1DM/edit) presented in a VIS Failiure session at IEEE Vis 2020 session.

## Sections

Comment in/out whatever section you need.
The (optional)-marked section are probably not necessary but may be useful to write anyway since that will force you to extract main issues raised by all reviewers.

1. (optional) Summaries of all reviews
2. (optional) Main issues raised in the reviews and author's responses
3. Full reviews and point-by-point responses
4. Difference version of previous and current submisison


## latexdiff (bad) practice

1. Download the submitted version from Overleaf and rename all figures and section folder to *-old
2. Use latexdiff on linux to create a diff between the current master HEAD and the submitted version (with --flatten)
	```latexdiff --flatten main.tex ../OLD_VERSION/main.tex > ../Diff/diff.tex```
4. compile under windows
	- when the new version deleted some user-definition like
	```\newcommand{\spatialNeighborhoodChannel}[2][c]{\ensuremath{\mathcal{N}^{S, \numSpNeigh}_{#2#1}}}```
	you'll need to add them again, otherwise the crossed out mentions of that from the old version cannot correctly be resolved

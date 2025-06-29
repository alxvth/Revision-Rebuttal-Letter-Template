# Revision and Rebuttal Letter Template

This template is based on the ideas in the [Paper Submission Revision Template](https://docs.google.com/document/d/1Vef5VaW1j_vtg5z9lWJo4aKgzM0hUe3UnfBdY6-_1DM/edit) by Leilani Battle presented at the IEEE Vis 2020 [Fail Fest Workshop](https://virtual.ieeevis.org/year/2020/session_w-failfest.html) ([failfest.github.io](https://failfest.github.io/)).
<!-- Archive link for the Paper Submission Revision Template: https://web.archive.org/web/20210216160619/https://docs.google.com/document/d/1Vef5VaW1j_vtg5z9lWJo4aKgzM0hUe3UnfBdY6-_1DM/edit -->

Have a look at the [example PDF](example/Revision_Rebuttal_Letter_Template.pdf) or view this project [in Overleaf](https://www.overleaf.com/read/wxwnzwjycrpd#c1c24c).

## Usage
Interleave reviewer comments with
``` latex
\begin{response}
    point-by-point responses
\end{response}
```
that describe how you will tackle the raised concerns.
Ideally, phrase your responses in a past tense.
This way, you might be able to more easily re-use your responses when writing a final response letter.

Additionally, it can be helpful to first summarize each review in your own words and then outline main and recurring concerns, critiques and suggestions.

## Sections

The template starts out with four sections, but of course you may use any subset in your response letter: 

1. Summaries of Reviewer Concerns and Our Revisions
2. Summaries of Individual Reviews
3. Full Reviews and Point-by-Point Responses
4. A comparison view of the original submission and current revision, created with [latexdiff](https://github.com/ftilmann/latexdiff/) (check the [ctan package](https://ctan.org/pkg/latexdiff) or [Overleaf's docs](https://www.overleaf.com/learn/latex/Articles/Using_Latexdiff_For_Marking_Changes_To_Tex_Documents) for more info)
   - The `\highlightDeletion` with `\highlightAddition` commands as exemplified above indicate additions and deletions like the latexdiff package

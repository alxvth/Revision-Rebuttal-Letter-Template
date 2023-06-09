# Revision and Rebuttal letter template

Roughly based on this [Paper Submission Revision Template](https://docs.google.com/document/d/1Vef5VaW1j_vtg5z9lWJo4aKgzM0hUe3UnfBdY6-_1DM/edit) presented at the IEEE Vis 2020 [Fail Fest Workshop](https://virtual.ieeevis.org/year/2020/session_w-failfest.html) ([failfest.github.io](https://failfest.github.io/)) by Leilani Battle.

## Usage recomendations
Interleave reviewer comments with
``` latex
\begin{response}
point-by-point respones,
\end{response}
```
that describe how you will tackle the raised concerns.
Ideally, phrase your responses in a past tense.
This way, you might be able to more easily re-use your responses when writing a final response letter.

Additionally, it can also be helpful to first summarize each reviews in your own words and then outline the main and recurring reviewer's concerns.

Have a look at the [example PDF](example/Revision_Rebuttal_Letter_Template).

## Sections

Use sections you need or see fit.

1. Summaries of Reviewer Concerns and Our Revisions
2. Summaries of Individual Reviews
3. Full Reviews and Point-by-Point Responses
4. Difference Version of Previous and Current Submisison
5. (Optional) A differerence view between the previous and new paper created with [latexdiff](https://github.com/ftilmann/latexdiff/) ([ctan package](https://ctan.org/pkg/latexdiff), and more [info](https://www.overleaf.com/learn/latex/Articles/Using_Latexdiff_For_Marking_Changes_To_Tex_Documents))
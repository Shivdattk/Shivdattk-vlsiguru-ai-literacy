# Week 01 AI Assistant Comparison
## Common question
"Who introduced the Transformer architecture, in what year, and what was the paper's title?"

## Tool 1
Name: Claude
Answer summary: "Attention Is All You Need" by Vaswani et al., 2017, from Google; replaces recurrence with attention.
Strengths: concise and correct on title, lead author, year.
Weaknesses: gave no clickable source unless asked; venue/affiliation details needed separate checking.

## Tool 2
Name: Gemini
Answer summary: 2017, by researchers at Google, listed all eight authors, title "Attention Is All You Need".
Strengths: complete, correct author list and order; more detail than Claude's "Vaswani et al."
Weaknesses: "at Google" is a simplification: one author lists Univ. of Toronto, one lists no affiliation; no source link given.

## Verification source
https://arxiv.org/abs/1706.03762

## Final comparison
- Accuracy: Both correct on title, year, authors. Gemini's affiliation claim was mostly correct but simplified.
- Traceability: Neither answer included a source link.
- Explanation quality: Both concise; Gemini gave fuller detail.
- Ease of verification: High; arXiv page confirms core facts in seconds.
- Which claims required correction or qualification? Gemini's "researchers at Google" (Gomez and Polosukhin: see verification log).

## Lesson
The lesson is that the riskiest part of an otherwise correct answer is usually the extra detail nobody asked for.

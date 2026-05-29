# Shreeshail Padadali — Resume

LaTeX source for my professional resume, alongside the latest compiled PDF.

## Files

| File | What it is |
| ---- | ---------- |
| [`Shreeshail_Resume.tex`](Shreeshail_Resume.tex) | The LaTeX source. Edit this. |
| [`Shreeshail.pdf`](Shreeshail.pdf) | Latest compiled PDF. |

## How to compile on Overleaf (easiest)

1. Go to <https://www.overleaf.com/> and sign in (free account works).
2. **New Project → Blank Project**, name it `Shreeshail-Resume`.
3. In the editor, replace the contents of `main.tex` with the contents of [`Shreeshail_Resume.tex`](Shreeshail_Resume.tex).
4. Click **Recompile**. The PDF preview appears on the right.
5. Click the download arrow above the preview to save `Shreeshail_Resume.pdf`.

## How to compile locally (TeX Live or MacTeX)

```bash
pdflatex Shreeshail_Resume.tex
# Run twice if hyperlinks don't render the first time:
pdflatex Shreeshail_Resume.tex
```

## Updating the resume

1. Edit `Shreeshail_Resume.tex` (every section is clearly labelled with comments).
2. Compile (Overleaf or `pdflatex`).
3. Replace the old `Shreeshail.pdf` with the new one.
4. Commit + push.

## Customisation pointers

| Section | Where to edit |
| ------- | ------------- |
| Name + contact info | The `% HEADER` block |
| Career Objective | The `% CAREER OBJECTIVE` block |
| Education | The `% EDUCATION` block |
| Skills | The `% TECHNICAL SKILLS` block |
| Work experience | The `% EXPERIENCE` block — copy a `\resumeSubheading` block to add a new role |
| Projects | The `% PROJECTS` block — copy a `\resumeProjectHeading` block to add a new project |
| Co-curricular | The `% CO-CURRICULAR & LEADERSHIP` block |

## Live links in this resume

- Portfolio: <https://shreeshail-sp.github.io/Portfolio/>
- Airbnb Sentiment Analysis (live demo): <https://shreeshail-sp.github.io/Air_BNB_Sentiment-_Ananlysis/>
- AI-powered Scalable MLOps Platform (repo): <https://github.com/Shreeshail-sp/AI-powered-Scalable-MLOps-Platform>
- Airbnb Sentiment Analysis (repo): <https://github.com/Shreeshail-sp/Air_BNB_Sentiment-_Ananlysis>

---

Built using [Jake Gutierrez's open-source resume template](https://github.com/jakegut/resume) (MIT licensed).

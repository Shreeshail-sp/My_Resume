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
4. Click **Recompile**. The single-page A4 PDF preview appears on the right.
5. Click the download arrow above the preview to save `Shreeshail_Resume.pdf`.

## How to compile locally (TeX Live or MacTeX)

```bash
pdflatex Shreeshail_Resume.tex
# Run twice if hyperlinks don't render the first time:
pdflatex Shreeshail_Resume.tex
```

## Resume design at a glance

- **Format:** A4, single page, 11pt body text.
- **Style:** Jake Gutierrez's open-source LaTeX template (MIT) with a blue accent palette.
- **Sections:**
  - Header (name + 6 clickable links: Phone, Gmail, Portfolio, LinkedIn, GitHub, Kaggle)
  - Career Objective
  - Education (CMR Institute of Technology, Ambika PU College)
  - Technical Skills (2-column tabularx layout, ~17 categories)
  - Experience (Avijo — DevOps Intern)
  - Projects (Airbnb Sentiment Analysis with live demo, FinBot News Research Tool)
  - Co-Curricular & Extra-Curricular (Certifications, Industrial Visits, Sports)
- **ATS-friendly:** uses `\pdfgentounicode=1` so the PDF text is machine-readable.

## Live links in this resume

- Portfolio: <https://shreeshail-sp.github.io/Portfolio/>
- LinkedIn: <https://www.linkedin.com/in/shreeshailsp/>
- GitHub profile: <https://github.com/Shreeshail-sp>
- Kaggle: <https://www.kaggle.com/shreeshail2004>
- **Airbnb Sentiment Analysis (live demo):** <https://shreeshail-sp.github.io/Air_BNB_Sentiment-_Ananlysis/>
- **Airbnb Sentiment Analysis (repo):** <https://github.com/Shreeshail-sp/Air_BNB_Sentiment-_Ananlysis>
- **FinBot (repo):** <https://github.com/Shreeshail-sp/FinBot>

## Updating the resume

1. Edit `Shreeshail_Resume.tex` (every section is clearly labelled with comments).
2. Compile (Overleaf or `pdflatex`).
3. Replace the old `Shreeshail.pdf` with the new one.
4. Commit + push.

## Customisation pointers

| Section | Where to edit |
| ------- | ------------- |
| Name + contact info | The `% HEADING` block |
| Career Objective | The `% CAREER OBJECTIVE` block |
| Education | The `% EDUCATION` block — copy a `\resumeSubheading` block to add a new entry |
| Skills | The `% TECHNICAL SKILLS` `tabularx` block |
| Work experience | The `% EXPERIENCE` block |
| Projects | The `% PROJECTS` block — copy a `\resumeProjectHeading` block to add a new project |
| Co-Curricular | The `% CO-CURRICULAR` block — three sub-categories (Certifications, Industrial Visits, Sports) |
| Accent colour | `\definecolor{accentblue}{RGB}{26, 82, 160}` near the top |

---

Built using [Jake Gutierrez's open-source resume template](https://github.com/jakegut/resume) (MIT licensed).

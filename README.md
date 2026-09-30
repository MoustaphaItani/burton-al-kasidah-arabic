# Burton's Kasidah: preliminary Arabic translation

This is a complete, editable LaTeX project for Overleaf, based on the attached
`Burton_Al_Kasidah_Arabic_Preliminary(1).docx`.

## Compile on Overleaf

1. Choose **New Project -> Upload Project** and upload the ZIP file.
2. Set the project's **Compiler** to **XeLaTeX**.
3. Set **Main document** to `main.tex` if it is not selected automatically.
4. Click **Recompile**.

The included `latexmkrc` also selects XeLaTeX. The bundled Amiri fonts remove
any need to install fonts or upload additional files. The table of contents
and PDF bookmarks are generated automatically.

Official multilingual typesetting guidance:
https://www.overleaf.com/learn/latex/Multilingual_typesetting_on_Overleaf_using_polyglossia_and_fontspec

## Editing

- `main.tex`: title page and the order of the sections.
- `preamble.tex`: typography, page layout, and the recorded model and duration.
- `content/credit.tex`: explicit AI contribution statement.
- `content/introduction.tex`: scope and Burton's pseudotranslation.
- `poem/01.tex` to `poem/09.tex`: all 268 numbered couplets and Burton's glosses.
- Other files in `content/`: the preface, two notes, conclusion, translator's
  explanations, and source references.
- `fonts/OFL.txt`: license for the two unchanged Amiri font files.

For a poem edit, keep each `\Couplet{number}{first line}{second line}{gloss}`
command intact. The fourth argument is `{}` when there is no gloss. Latin
words inside Arabic paragraphs are enclosed in `\textenglish{...}`.

## Attribution and timing

The preliminary Arabic translation, added contextual notes, and original
document preparation were produced by ChatGPT / OpenAI at Moustapha Itani's
request and under his direction. The model label **GPT-6.1 Sol Max** and elapsed
time **1h 10m 13s** are the project initiator's record of that first drafting
session. They are stated explicitly in the Arabic contribution page. The later
LaTeX conversion is acknowledged separately.

The poem, Burton's preface, both original notes, and his conclusion are retained.
The front matter now explains pseudotranslation, including the allure of a
fictional foreign source and its other literary functions, with a scholarly
reference. No claim of being the first Arabic translation is made.

## Local compilation

From this directory, run `latexmk main.tex` with a TeX Live installation that
includes XeLaTeX, fontspec, polyglossia, bidi, geometry, setspace, needspace,
parskip, and hyperref. The project uses UTF-8 throughout.

# Compiling Lecture Notes to a Chapter (Checklist + Standards)

This document is the end-to-end workflow for turning lecture material (PDFs or page images) into a self-contained chapter inside `Lecture Notes/`. It exists so `AGENTS.md` can stay short; follow this file whenever the task is “compile a lecture” or “revise a compiled lecture chapter.”

## Scope and location rules

Work only inside `Lecture Notes/` (including `Lecture Notes/images/`) while a lecture-derived writeup is still being checked. Do not edit `Book/` chapters or other vault sections during compilation.

## Chapter targets (what “compiled” means)

A compiled lecture chapter reads like a textbook section, not like a transcript:

- No references to “the lecture notes,” “these notes,” or similar.
- Clear sectioning (e.g., `## 1.6x.1 ...`) with consistent notation and conventions.
- Important, reusable equations are in equation callouts and are interpreted in prose immediately after the callout.
- Figures have diagnostic captions that match the actual embedded image.
- Exercises are self-contained prompts; solutions follow immediately in prose; “Lessons Learned” follows each exercise.
- Indices in `Lecture Notes/` are updated (Glossary, Symbol Index, Equation Index).
- No bracketed editing comments remain.

## Required callouts (minimum standard)

### Equations

Use:

`> [!equation] Specific, distinguishing title`

Immediately after every equation callout, add an interpretation paragraph **outside** the callout. When it fits, start with “This equation says that …” and briefly explain:

- what the equation means in words,
- what the key grouped factors/terms represent,
- any useful limiting/special cases for interpretation or dimensional checking.

Avoid duplicating an interpretation if a good one already appears immediately nearby.

### Definitions

Use:

`> [!definition] Term`

Also mark the first appearance in prose as `==Term==`.

### Figures

Use:

`> [!figure] Figure <section>.<N>: Short descriptive title`

Embed the image inside the callout, and keep the entire caption inside the callout (prefix every line with `>`). Captions must be grounded in the **actual** image:

- Open/view the referenced image before writing the caption.
- Describe only what is visibly present (panels, axes, labels, annotations, dashed guides, circuit elements, etc.).
- Use the figure’s notation; if it differs from the chapter’s, map it explicitly (“labeled $C_d$ in the figure”).
- Make the caption diagnostic: what is input vs. output, what is plotted against what, what feature the reader should read off (intercept/slope, time constant, plateau, sign convention, etc.).

### Draw-it

Use:

`> [!draw-it] Draw-it: Specific skill title`

Draw-it callouts test whether the reader can reproduce the conceptual imagery of a figure (plots, diagrams, labeled features) from a self-contained prompt.

- Place the draw-it callout **immediately before** the figure callout it references.
- Number prompts when there is more than one.
- Prompts must be self-contained: include enough givens (step size, scan rate, time window, controlled vs. measured quantity, sign conventions) so the reader can draw the correct qualitative shape without consulting the figure.
- Specify exactly what must appear (axes labels, key markers like $t=0^+$ or $t=\\tau$, intercept/slope, plateau level, etc.).
- Do not embed solutions (including the target final equation) unless the intended exam skill is explicitly “draw the plot given this explicit formula.”

### Questions (review questions)

Use:

`> [!Questions] Questions: Specific topic`

Questions callouts are short exam-style prompts that test recall and light application of the **most important** ideas in the immediately surrounding section.

- Make prompts self-contained and **do not include solutions**.
- If there are multiple prompts, number them (`> 1.`, `> 2.`, …).
- Do not “give away” answers by embedding the target equation or by restating a previous question’s answer as the premise for a later question.
- Prefer prompts about assumptions, limiting cases, distinctions (model vs. device, faradaic vs. non-faradaic), sign/reference conventions, and “how to proceed” rules.
- When a section introduces explicit definitions, include “Define …” prompts for those terms (using the chapter’s exact terminology).

### Exercises and solutions

Use:

`> [!exercise] Exercise N: Skill title`

The exercise callout contains **only** the problem statement and is fully self-contained. Every line (including blank lines) inside the callout must be prefixed with `>`.

The solution follows immediately after the callout (not in a callout). After the solution, add:

`> [!Lessons] Lessons Learned: ...`

Lessons are reusable principles/workflows, not a recap of a numerical answer.

### Lessons Learned (after exercises)

Use:

`> [!Lessons] Lessons Learned: Short title`

Lessons Learned panels are the “what to remember next time” outputs after a worked exercise.

- Make lessons general and reusable (a workflow, a diagnostic check, a sign-convention rule, or an order-of-operations rule), not a restatement of the final numerical result.
- Number each lesson (`> **Lesson 1:** ...`, `> **Lesson 2:** ...`) and include a blank callout line (`> `) between lessons when there are multiple.
- Avoid duplicating lessons that already appeared earlier in the same chapter unless repetition is genuinely helpful.

## Indices to update (Lecture Notes quarantine)

All indices live in `Lecture Notes/`:

- `Lecture Notes/Glossary.md`: add new `==...==` terms; keep alphabetized.
- `Lecture Notes/Symbol Index.md`: add missing symbols used in important equations; keep table alphabetized; constants must include values + units; disambiguate overloaded symbols.
- `Lecture Notes/Equation Index.md`: copy each equation callout verbatim, add a short explanation paragraph immediately below it, and keep entries alphabetized by callout title (case-insensitive).

## Compilation checklist

### 1) Pre-flight

- [ ] Identify the source lecture date(s) and topic(s).
- [ ] Locate the source PDF/page images and confirm the pages you must cover.
- [ ] Decide the chapter filename using the house convention: `<section> Lecture Notes (YYYY-MM-DD) <Topic>.md`.

### 2) Assets (figures)

- [ ] Extract/collect figures as PNGs under `Lecture Notes/images/` with stable, descriptive names that include the lecture date.
- [ ] Embed each major figure in a `> [!figure]` callout.
- [ ] Open/view each image and write a caption that matches what is actually shown.
- [ ] Add `> [!draw-it]` callouts only when a figure’s conceptual shape/diagram is something a professor could plausibly ask a student to reproduce.

### 3) Chapter writeup

- [ ] Write textbook-style prose with consistent section headings and notation.
- [ ] Remove any “the notes” language.
- [ ] Replace bracketed revision comments `[ ... ]` by revising the surrounding text, then delete the brackets.

### 4) Equations and symbols

- [ ] Wrap important/reusable equations in `> [!equation]` callouts with distinguishing titles.
- [ ] Add an interpretation paragraph immediately after each equation callout.
- [ ] Scan every equation callout for symbols and update `Lecture Notes/Symbol Index.md` accordingly.

### 5) Definitions

- [ ] Wrap explicit definitions in `> [!definition]`.
- [ ] Mark first appearances in prose as `==Term==`.
- [ ] Add new terms to `Lecture Notes/Glossary.md` (alphabetized).

### 6) Exercises, questions, and lessons

- [ ] Ensure each `> [!exercise]` contains only a self-contained prompt (no intermediate results).
- [ ] Ensure the solution follows immediately in prose, and add a `> [!Lessons]` panel after each exercise.
- [ ] For `> [!Questions]` callouts: number prompts when there are multiple; make prompts self-contained; do not embed answers (especially the target equation); ensure definition prompts appear when the section defines terms.
- [ ] For `> [!Lessons]` panels: lessons are generalizable workflows/rules, not the specific computed answer.

### 7) Final quality pass

- [ ] No bracketed editing comments remain.
- [ ] No references to “the lecture notes.”
- [ ] Every exercise callout is prompt-only and fully `>`-prefixed.
- [ ] Every important equation used repeatedly is in an equation callout and appears in `Lecture Notes/Equation Index.md`.
- [ ] Glossary, Symbol Index, and Equation Index remain alphabetized and consistent with the chapter.

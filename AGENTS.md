# Agent Instructions (Repository-Wide)

This file applies to the entire `me412` vault unless a more-specific `AGENTS.md` exists in a subdirectory.

Before responding in this repository, read `style.md` and follow it exactly for writing style and mode behavior (Outline Mode, Derivation Mode, Transcription Mode, Bridge Mode).

If any instruction in `style.md` conflicts with default assistant conventions, prefer `style.md`. If `style.md` conflicts with a direct user request in the current chat, follow the user request.

# Compiling a Lecture Note to a Chapter

For the full workflow, checklist, and callout/indices standards, follow `Compiling Lecture Notes.md`.

Key invariant while compiling: work only inside `Lecture Notes/` (including `Lecture Notes/images/`) until lecture-derived writeups have been checked for correctness and consistency with the book.

## Callouts (quick rules)

- **Figures:** Open/view the embedded image before writing or revising a caption; captions must be diagnostic (axes, variables, conventions, and what feature to read off).
- **Draw-it:** Place `> [!draw-it]` immediately before its referenced figure; make prompts self-contained; do not embed answers; avoid filler phrases like “without looking at the figure”; prefix every callout line with `>`.


# Rules for Editing Chapters


## Editing Comments

Editing comments are surrounded by square brackets, e.g., `[editing comment]`. Treat these as actionable revision notes about the immediately surrounding passage (often the sentence or paragraph directly above).

When you revise a passage in response to an editing comment, use the surrounding chapter context to keep terminology, scope, and conventions consistent. After revising, remove the bracketed comment (or incorporate the concern into the prose) so the chapter reads cleanly.

When editing a passage that includes an equation callout (a block beginning with `> [!equation]`), ensure the callout has a specific, context-appropriate title. Be specific enough to distinguish different forms that may recur across the chapter (e.g., “activity form” vs “concentration form”), so you do not end up with many different equations sharing the same generic title.

## Equations

When editing or adding equations, prioritize symbolic clarity and consistency over terseness.

Whenever you encounter an equation callout (a block beginning with `> [!equation]`), check whether the chapter text already contains a clear interpretation paragraph immediately after it. If not, add one (outside the callout): “This equation says that …” plus a brief explanation of key terms/chunks and useful special cases, without giving away answers to nearby review questions.

If a symbol is used for more than one quantity within a chapter (for example, $R$ as the gas constant and $R$ as an electrical resistance), treat this as an overloaded symbol that must be disambiguated in the chapter’s `Symbol Index.md`. Do not “merge” meanings into a single row or pack multiple unit systems into a single Units cell.

For constants, record the numerical value in the `Value` column of the chapter symbol index. If multiple unit conventions are commonly useful in the context of the notebook, add an additional row immediately below the constant with the alternative value and units. In that alternative-units row, leave the `Meaning` and `Description` cells blank so the row reads as a unit conversion rather than a second definition.

When you revise an equation callout, scan the equation for symbols and update the symbol index (and, when applicable, the chapter glossary) so the chapter remains self-contained.

Whenever you see an equation callout (a block beginning with `> [!equation]`), try to give it a specific, context-appropriate name in the callout header (e.g., `> [!equation] Nernst equation (concentration form)`), rather than leaving it untitled. Choose names that are specific enough to distinguish closely related forms that may recur across the chapter (e.g., “activity form” vs “concentration form,” “standard-state form,” “linearized/approximate form,” “integrated form,” “cell form” vs “half-cell form”), so you do not end up with many different equations sharing the same generic title.

Each chapter should maintain an `Equation Index.md` file in the chapter folder. When you add or revise an equation callout, copy that equation (keeping the same callout type and title) into the equation index and add a short explanation immediately below the callout. The explanation should, where it makes sense, state the verbal meaning of the equation (“this equation says that …”) and identify the meaning of important chunks (common grouped factors or terms) that help with interpretation or dimensional checking. Keep the equation index in alphabetical order by the callout titles (case-insensitive).


## Conventions

Some chapters use convention callouts (blocks beginning with `> [!convention]`) to capture local rules that readers must apply consistently (sign conventions, reference directions, electrode/cell-schematic conventions, “left vs right” definitions, what is held constant, naming/labeling conventions, etc.).

When you see a convention callout, replace any placeholder text with a short, self-contained description of the convention as stated in the immediately surrounding passage. The goal is that a student can apply the convention correctly by reading only the callout.

Write convention callouts in concise prose (or a few short labeled lines) and keep every line inside the callout prefixed with `>`. Do not introduce new conventions that are not supported by the text; if the passage is ambiguous, align with the nearest explicit convention already established in the chapter and add one clarifying sentence that resolves the ambiguity.

If the chapter uses multiple distinct conventions of the same “type” (for example, more than one sign convention depending on a defined direction), make the callout title specific (e.g., `> [!convention] Convention: Cell-reaction sign convention`) so it does not read like a generic “Convention” repeated many times.

## Questions

Some chapters use questions callouts (blocks beginning with `> [!Questions]`) to help students review the key ideas introduced in the passage that follows the callout.

When you see a questions callout, replace placeholder text with a set of short prompts that test recall and light application of the most important principles, assumptions, distinctions, and conventions in the immediately following passage (until the next major break such as a new subsection heading or a shift to a different topic).

Questions must be substantive: they should target transferable takeaways that a student can apply repeatedly when solving problems (assumptions, limiting cases, model-vs-device distinctions, sign/reference conventions, and “how to proceed” rules). Avoid trivia-style prompts that only test memorization (historical asides, citation numbers, incidental adjectives, or details that are not used later for reasoning).

Questions should be self-contained and should not include solutions. Do not introduce new symbols, definitions, or conventions that are not supported by the text that follows the callout; instead, use the chapter’s existing notation and terminology. It is fine for a questions callout to have only 1–3 prompts if that is what the passage warrants.

Do not “give away” the answer inside a review question. In particular, avoid writing the target equation (or a fully evaluated expression) directly in the prompt (e.g., “State Faraday’s law in the form $n(e^-)=Q/F$ …”); instead, ask the student to write the equation and define its symbols. Likewise, avoid repeating Question 1 as the premise of later questions; subsequent questions should build on earlier ones without restating their answers.

When a questions callout contains multiple prompts, number them `1.`, `2.`, `3.`, etc. (with each numbered line still prefixed by `>` so it remains inside the callout).

Use a specific title in the callout header (e.g., `> [!Questions] Questions: NHE as a standard vs. realizable electrodes`) so multiple question callouts do not all read as “Title.” Keep every line inside the callout prefixed with `>`.


## Problem Areas

Problem areas are delimited by `*==...==*` (italic + highlight). This markup flags prose that is unclear, inaccurate, or poorly structured and should be refined. Problem areas are often followed by an editing comment in square brackets that explains what to fix.

When you refine a problem area, preserve important content and structure: do not delete or break definitions, equations, callouts, or other marked-up material. If such elements are adjacent to (or embedded in) the flagged passage, rewrite the surrounding prose without changing their meaning or formatting. After revision, remove the `*==...==*` delimiters from the passage you fixed.

## Section Titles

Some sections may be left with placeholder headers like `#### ???` to indicate that a title is missing. Replace these with a clear, descriptive title that matches the surrounding material.

When adding or fixing a title, do not change the heading level. If the parent section uses a numbering scheme, include numbering while keeping the same level (e.g., under `### (c) ...`, use `#### (c.1) ...`, `#### (c.2) ...` for new subheadings). If the parent section has no such scheme, use an unnumbered descriptive title.

If a heading uses only a letter label (e.g., `### (c) ...`) and the parent section has an explicit numeric identifier in its title (e.g., `## 2.1.1 ...`), you may optionally prefix the letter with the parent numbering for clarity (e.g., `### (2.1.1.c) ...`). Keep the chosen convention consistent within the chapter.

## Definitions

Definitions in chapter text are indicated only by terms surrounded by double equals signs, like `==thermodynamically reversible==`. Other delimiter patterns (e.g., `*==...==*`, `**==...==**`) are emphasis or other markup and must not be treated as glossary terms unless the term itself is exactly wrapped in `==...==`.

Maintain a single glossary for the chapter you are editing, located in that chapter’s folder as `Glossary.md`. Add entries as they appear while editing, and keep the glossary alphabetized by term (case-insensitive).

Write each entry as a short, formal definition in the context of the surrounding material. Prefer reusable, chapter-wide meaning over local paraphrase, and avoid examples unless they are necessary to prevent ambiguity.

Format each entry as `## Term` on its own line, followed by one or more prose paragraphs defining the term. Preserve the term’s wording as it appears in the text (including capitalization), but place it in alphabetical order in the glossary.

Glossary headings must be unique and searchable. Never create a single heading that contains multiple alternative terms (no “Term A (or Term B)” headings). If several terms are used synonymously, choose one canonical heading for the full definition (usually the most precise or most frequently used), and create separate headings for each alternative term that say `See **Canonical Term**.`.

Do not “hide” synonyms by removing them from the chapter text. If the prose lists multiple synonymous terms, keep all of them in the passage so readers can recognize them later. When marking such synonyms for the glossary, prefer to wrap each term in its own `==...==` marker rather than wrapping a whole multi-term phrase in a single marker.

Be careful about scope and granularity. If the chapter uses an adjective as shorthand for a more specific concept (e.g., “electrochemically reversible” meaning an electrode-process behavior), make that explicit in the glossary entry, and put the precise term in its own heading (spelled out, not in parentheses). Do not redefine a broad adjective in a way that falsely implies it always refers to one specific object in every context.


## Symbol Index

Each chapter should maintain a `Symbol Index.md` file in the chapter folder. This file is a compact reference for the meaning of symbols used throughout the chapter, especially those appearing in important equations.

Important equations are typically marked with an equation callout (for example, a block that begins with `> [!equation]`). When you add or revise an important equation, scan it for symbols (including subscripts/superscripts, Greek letters, and named species like $\mathrm{O}$ and $\mathrm{R}$ in generic half-reactions) and add any missing symbols to the chapter’s symbol index. If a symbol is already defined in the index, do not duplicate it; instead, ensure the existing definition matches the chapter’s usage.

Keep the symbol index table sorted in alphabetical order by the symbol as written in the `Symbol` column (case-insensitive), and keep definitions consistent with the chapter’s conventions. Populate all columns: a short `Meaning`, a precise `Description` that reflects how the symbol is used in the chapter (including equation references when helpful), a `Value` when the symbol denotes a constant (leave blank otherwise), and `Units` (use `—` for dimensionless quantities or where units are not applicable).

## Problems

When editing chapters, each exercise must have a self-contained problem statement that reads like a textbook prompt. Write the problem statement inside the exercise callout (the block that begins with `> [!exercise] Exercise N`) and assume the prose and equations that follow the callout are the solution. The statement should supply only the minimum information needed to make the solution well-posed, and it must not include intermediate results or conclusions that the student is supposed to derive.

Match the solution’s notation exactly. Do not introduce new symbols, sign conventions, or reference states unless the solution already defines them. If the solution uses a figure or cell diagram already shown immediately below, you may refer to it (e.g., “Figure 1.1.1b”) rather than re-explaining it. If a numerical value, condition (standard state, temperature, pressure), or polarity assignment is essential to determine directions or signs in the solution, include it explicitly; otherwise omit it.

Prefer short, direct prompts that specify deliverables: what to compute, what to write (balanced net reaction, half-reactions, direction of electron flow, classification), and under what conditions. Use multipart structure only when the solution naturally breaks into distinct tasks; avoid adding extra subparts that are not used. Avoid hinting language (“show that,” “it can be shown,” “hence”) unless the goal is explicitly to verify a claim already stated in the text.

Formatting rules: every line of the problem statement, including display equations and blank lines, must be prefixed with `>` so it stays inside the callout. Replace placeholder text like “Contents” with the actual prompt. If the question has multiple parts, label them as bold headers on their own lines (e.g., `**Part A:** ...`, `**Part B:** ...`) and include at least one blank callout line (`> `) between parts so the separation is visible at a glance.

Self-contained rule: do not require the student to look below the exercise callout (into the solution) to retrieve essential information. If the prompt references an equation/reaction by number (e.g., “Eq. (2.1.69)”), include the needed equation(s) explicitly inside the callout. Likewise, if a figure or diagram is required for the prompt, include it in the callout (or restate the required information from it) rather than relying on the student to scroll into the solution.

Title rule: every exercise callout must have a skill-focused title in the callout header. Use the format `> [!exercise] Exercise N: <Skill Title>` where `<Skill Title>` is short and names the transferable skill (e.g., “Chemical Reversibility,” “Balancing Half-Reactions,” “Applying the Nernst Equation”), not the specific numerical answer or a reference to “this problem.”

### Lessons

When editing chapters, each exercise should have a “Lessons Learned” callout that captures general rules or principles a student can reuse throughout the chapter, not a recap of the specific numerical result. Prefer lessons that state reusable workflows (e.g., sign conventions, mapping between representations, order-of-operations rules, or classification criteria) and avoid lesson statements that depend on the particular figure or values in the exercise unless the chapter repeatedly relies on that same convention.

Do not repeat lessons that have already appeared earlier in the chapter unless repetition is essential for the chapter’s pedagogy. If a “Lessons Learned” panel would add no genuinely new, reusable principle, delete that panel rather than filling it with redundant content.

Formatting rules: write lessons inside a `> [!Lessons] ...` callout. You may include a short title after `[!Lessons]` if it summarizes the set. Number each item as `> **Lesson 1:** ...`, `> **Lesson 2:** ...`, etc., and include at least one blank callout line (`> `) between lessons so the separation is visible at a glance. Replace placeholder text like “Contents” with the actual lessons.






# Rules for Forming Multiple Choice Questions

Multiple choice questions (MCQs) must test the intended concept, not the student’s ability to spot giveaway options. Each item MUST have exactly one best answer. All distractors MUST be plausible to a prepared student who is making a specific, realistic mistake (a “near-miss”), not a random wrong statement.

The core design goal is _discrimination between mental models_: the correct option corresponds to the target concept, while each distractor corresponds to a distinct misconception that is close to the target but fails for one precise reason.

## House format

Write questions as plain numbered items.

- Put the stem first, then four options labeled A–D.
    
- Avoid special wrappers/delimiters (no callout blocks).
    
- Keep math in KaTeX-friendly notation (no code blocks).
    
- Put the answer key as a single grouped list at the very bottom: `Answers: 1. C, 2. D, ...`
    
- Do not include explanations unless explicitly requested.
    

## Concept coverage requirement

For each section, the MCQ set MUST cover every distinct examinable unit introduced or used in that section. A “concept” includes definitions, key distinctions, mapping/identity statements, notational conventions, “held constant” rules, order-of-operations warnings (e.g., “differentiate first, then substitute”), and any explicit transformations/derivations.

The item count is determined by the concept inventory, not a target number of questions. The set is complete only when each concept has at least one corresponding MCQ that directly depends on it.

## Required workflow (inventory → items → coverage check)

### Step 0: Build a concept inventory (required, may be internal)

Before writing any MCQs, extract a concept inventory from the section. This inventory MUST enumerate each examinable unit explicitly (even if kept internal while drafting). Include:

- Definitions and symbol meanings.
    
- Key distinctions (e.g., Eulerian vs Lagrangian, evaluate vs differentiate).
    
- Mapping direction statements and identities.
    
- “Held constant” rules and what is varying.
    
- Notational subtleties and warnings the text calls out.
    
- Any named transformations, derivation steps, or operator-order constraints.
    

### Step 1: Choose a single target skill per item

Each MCQ MUST test exactly one concept (one learning objective). Typical target skills include:

- Definition recall and symbol interpretation.
    
- Mapping between representations (e.g., (x_0 \leftrightarrow x), pullback/pushforward).
    
- Distinguishing evaluation from operation (e.g., “differentiate then substitute”).
    
- Identifying what is held fixed vs what varies.
    
- Selecting the correct expression, meaning, or statement under stated definitions.
    

### Step 2: Write the correct option first

Draft the correct option in its cleanest, least ambiguous form. Ensure it is correct _under the definitions stated in the stem and/or the section_.

### Step 3: Generate distractors by modeling realistic near-miss misconceptions

Each of the three distractors MUST correspond to a specific, plausible misconception. Do not generate “random wrong” options. Choose distractors from common near-miss families such as:

- **Wrong direction / inverse confusion:** using (\phi) instead of (\phi^{-1}), or swapping domain/codomain.
    
- **Held-constant confusion:** mixing derivatives at fixed (x) vs fixed (x_0); mixing partial vs material derivatives.
    
- **Order-of-operations mistake:** substituting before differentiating; treating an operator like evaluation.
    
- **Definition drift:** using a related but non-equivalent definition (almost right, subtly wrong).
    
- **Dropped term / missing contribution:** e.g., omitting convection term, missing chain rule component.
    
- **Overgeneralization:** applying a special-case identity as if it were general.
    
- **Sign / index / variable misplacement:** especially where students commonly misread indices or swap variables.
    

Each distractor MUST differ from the correct option by only one “errorful move” (one perturbation). Keep everything else as parallel as possible.

### Step 4: Normalize surface cues (anti-giveaway constraints)

Options MUST be matched in surface form so the correct answer does not “look” different.

- Similar length (do not let the correct option be systematically longer or more qualified).
    
- Similar grammar and voice (all statements or all expressions, not a mix).
    
- Similar symbol density and structure (same number of terms when plausible).
    
- Avoid making only one option “clean” while others are messy.
    
- Avoid unique keywords that only appear in the correct option.
    

### Step 5: Verify uniqueness and precision

- Exactly one option MUST be fully correct under the stated assumptions/definitions.
    
- The stem MUST specify enough context to make the question decidable.
    
- If ambiguity exists, fix the stem (define symbols/conditions) rather than letting multiple answers be arguably correct.
    

## Stems

Prefer stems that specify the task precisely without giving away the answer.

Use stems like:

- “Which expression correctly represents …?”
    
- “What does ( \cdot ) represent in this context?”
    
- “Which mapping direction is correct for …?”
    
- “Which variable is held fixed when …?”
    
- “Which statement is consistent with the definition of …?”
    

Avoid negative stems (“Which is NOT …”) unless there is a strong reason. If a symbol or operator could be interpreted multiple ways, define it in the stem or ensure it has already been defined in the section in an unambiguous way.

## No-filler quality gate (required)

Every question MUST be traceable to a specific concept in the inventory and must test a meaningful discrimination that a student could plausibly get wrong. If removing the question would not reduce conceptual coverage, delete it.

Conversely, if a concept in the inventory cannot be pointed to in at least one question whose stem and correct option depend on that concept, the set is incomplete and must be revised.

## Plausibility and difficulty calibration (what makes distractors “GRE-like”)

Distractors MUST be wrong for a _small, concept-tied reason_, not because they are nonsensical.

- Each distractor should be something a reasonably prepared student might choose if they have a specific misconception.
    
- Wrong options should often be “partly true” or correct in a different context/assumption (but not here).
    
- Avoid absurd statements, category errors, or options that violate obvious units/dimensions unless the _concept being tested_ is dimensional reasoning.
    

## Heuristic audit (required anti-pattern checks)

Before finalizing an item, run an audit to remove common giveaways:

- No option should be the only one with extreme words (“always,” “never,” “only,” “obviously”) unless the concept truly requires it and it appears symmetrically across options.
    
- Avoid “odd one out” formatting (only one option has parentheses, extra qualifiers, or a different type of object).
    
- Avoid systematically making the correct answer the longest/most precise option.
    
- Avoid options that are trivially eliminated by basic grammar matching with the stem.
    
- Avoid “all of the above / none of the above” unless explicitly requested.
    

## Internal drafting notes (must not appear in the final MCQ output)

While drafting, it is permitted to annotate each distractor with its misconception source (e.g., “wrong inverse map,” “held-constant confusion,” “substitute-before-differentiate”). These annotations MUST be removed from the final output unless the user explicitly requests explanations.

## Set-level completion check (required)

After drafting the full set:

1. Revisit the concept inventory.
    
2. For each concept, point to at least one item that directly depends on it.
    
3. If a concept is a known confusion point, write a second item: one direct and one near-miss/trap item.
    
4. Remove any item that does not map cleanly to an inventory concept.
    

---

If you want, paste one section of your material (even a short one), and I’ll show what the **concept inventory** looks like and then generate a small MCQ set where each distractor is explicitly tied to a realistic misconception (internally), while keeping the final output clean (no explanations).

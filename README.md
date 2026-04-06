# BRIDGE & RACCCA Frameworks Tool

An interactive evaluation tool for the AIETP 2026 training programme. Educators use the BRIDGE framework to select AI tools and the RACCCA framework to evaluate AI-generated outputs — all in one browser-based interface.

## What It Does

In Session 2, participants compare general-purpose LLMs (ChatGPT, Claude, Gemini, DeepSeek) with education-specific AI tools (MagicSchool AI, Eduaide.ai, Curipod, etc.). This tool gives them a structured way to score tools before use (BRIDGE) and assess outputs after generation (RACCCA), with built-in Before/After comparison to practise iterative prompt refinement.

## Features

**BRIDGE Tab — Tool Selection**
- Side-by-side scoring of two AI tools on six criteria (Building language skills, Reduce workload, Intuitive to use, Developing learning processes, Get students together, Extend learning)
- 1–5 scale for each criterion with automatic total calculation
- Visual comparison showing which tool scores higher and where
- Decision notes field to record reasoning
- Reset to start a fresh comparison

**RACCCA Tab — Output Evaluation**
- Rate AI-generated output on six quality criteria (Relevance, Accuracy, Completeness, Clarity, Coherence, Appropriateness)
- Before/After mode for iterative refinement: score the first output, revise your prompt, score again, and compare improvement
- Automatic identification of the weakest criterion to guide revision
- Reflection field to record what you changed and why
- Visual score comparison between Before and After rounds

**General**
- Two-tab interface switching between BRIDGE and RACCCA
- All scoring happens client-side with no data sent anywhere
- Fully responsive for laptop, tablet, and projected display
- Single self-contained HTML file with no external dependencies

## BRIDGE Framework

| Criterion | Question |
|-----------|----------|
| **B** — Building language skills | Does it support language learning goals? |
| **R** — Reduce workload | Does it save you meaningful time? |
| **I** — Intuitive to use | Can you and your students use it easily? |
| **D** — Developing learning processes | Does it support sound pedagogy? |
| **G** — Get students together | Does it enable collaboration? |
| **E** — Extend learning | Does it support learning beyond class time? |

## RACCCA Framework

| Criterion | Question |
|-----------|----------|
| **R** — Relevance | Does it match your teaching context and student needs? |
| **A** — Accuracy | Is the content factually correct and up to date? |
| **C** — Completeness | Does it cover all necessary components? |
| **C** — Clarity | Is the language clear and easy to understand? |
| **C** — Coherence | Is it well-organised and logically structured? |
| **A** — Appropriateness | Is it suitable for your students' level and context? |

Rate each criterion 1–5: **5** = classroom-ready, **3** = usable with edits, **1** = start over.

## How to Use

1. Open `index.html` in any modern browser (or visit the GitHub Pages URL)
2. **BRIDGE tab** — enter two tool names, score each on the six criteria, record your decision
3. **RACCCA tab** — score the AI output you generated, identify the weakest area, revise your prompt, regenerate, then score again using the Before/After comparison
4. Use the reflection field to capture what you changed and what improved

## Part of AIETP 2026

The Artificial Intelligence in English Teaching Project (AIETP) 2026 is a training programme for K-12 EFL educators in Turkey, funded by the Regional English Language Office (RELO), U.S. Embassy Ankara, and led by the School of Foreign Languages, Izmir University of Economics.

This tool is the core evaluation instrument for **Session 2: Determining Appropriate AI Tools & AI Tools for Lesson Planning**, used during the Live Demo, Tool Tasting, and RACCCA Before/After activities.

## Related Tools

- [PARTS Practice Tool](https://kel03tr-ai.github.io/PARTS-Model/) — Session 1: build structured AI prompts using the PARTS framework
- [BRIDGE Scoring Matrix](https://kel03tr-ai.github.io/BRIDGE-Scoring-Matrix/) — Session 2: facilitator-projected live scoring during Tool Tasting

## Licence

This tool is provided for educational use within the AIETP programme.

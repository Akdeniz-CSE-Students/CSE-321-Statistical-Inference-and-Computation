# CSE 321 — Statistical Inference and Computation

Akdeniz University · Computer Engineering (English)

**An open study archive for this course.** Lecture notes, both textbooks, practice
sets, past exam photographs, and the problem sets the instructor hands out before
each exam.

The instructor's slides are headed "CSE 321 Introduction to Probability Theory",
which is the lecturer's own title for the material. The taught schedule is the one
in [`resources/lecture-notes/00-course-info.pdf`](resources/lecture-notes/00-course-info.pdf),
and that is what [`weeks/`](weeks/) follows.

## Course

**Instructor:** Alper Bilge, PhD, Associate Professor · abilge@akdeniz.edu.tr
No office hours; reachable on MS Teams.
**Time:** Fridays 08:30-12:30 · **Location:** BB04

| Component | Weight |
|-----------|--------|
| Midterm | 40% |
| Final | 60% |

## Topics

The course is organized as eight topics, not fourteen weekly slots.

| # | Topic | Note |
|---|-------|------|
| 1 | Statistics, data, and statistical thinking | [weeks/01](weeks/01-statistics-and-statistical-thinking.md) |
| 2 | Methods for describing sets of data | [weeks/02](weeks/02-describing-sets-of-data.md) |
| 3 | Probability | [weeks/03](weeks/03-probability.md) |
| 4 | Discrete random variables | [weeks/04](weeks/04-discrete-random-variables.md) |
| 5 | Continuous random variables | [weeks/05](weeks/05-continuous-random-variables.md) |
| 6 | Sampling distributions | [weeks/06](weeks/06-sampling-distributions.md) |
| 7 | Inferences from one sample: confidence intervals | [weeks/07](weeks/07-confidence-intervals.md) |
| 8 | Inferences from one sample: tests of hypothesis | [weeks/08](weeks/08-hypothesis-testing.md) |

Topics 1-6 are the midterm scope; 7-8 are added for the final.

## How to study with this repository

**1. Open the topic you are on** in [`weeks/`](weeks/). Each note gives the goals,
the concepts with their actual formulas, what to read, and what to practice.

**2. Follow the reading links** — they open the book at the exact page:

> [McClave & Sincich — Ch. 6 (sampling distributions)](resources/books/mcclave-sincich-statistics-13e.pdf#page=312)

Each topic links three things: the official textbook, the supplementary Walpole,
and the instructor's own lecture note for that chapter.

**3. Practice with [`exams/prep/`](exams/prep/) first.** `problems-for-midterm.pdf`
and `problems-for-final.pdf` come from the instructor — they are the closest thing
to knowing what will be asked.

**4. Then [`exams/practice/`](exams/practice/)** for extra sets from other courses
and universities, and [`exams/past/`](exams/past/) for photographs of real papers.

**5. Write under `## My notes`** at the bottom of each topic note. Everything above
that line is shared; below it is yours.

## Layout

| Path | What it holds |
|------|---------------|
| [`weeks/`](weeks/) | The study plan, one note per topic |
| [`docs/`](docs/) | Course summary, resource map, glossary |
| [`resources/books/`](resources/books/) | McClave & Sincich (official), Walpole (supplementary) |
| [`resources/lecture-notes/`](resources/lecture-notes/) | The instructor's slides, chapter by chapter |
| [`resources/supplement/`](resources/supplement/) | Topic summaries, descriptive statistics through hypothesis testing |
| [`exams/prep/`](exams/prep/) | The instructor's pre-exam problem sets |
| [`exams/practice/`](exams/practice/) | Practice exams from elsewhere |
| [`exams/past/`](exams/past/) | Photographs of real papers |
| [`terms/`](terms/) | One folder per cohort — put your term's material here |

## Who changes what

| File | Who edits it | When |
|------|-------------|------|
| `weeks/NN-*.md` | **anyone** | Only when the course itself changes — a new topic, a better reading, a correction. Never for personal notes. |
| `docs/*.md` | **anyone** | When you learn something durable: a new exam pattern, a better source. |
| `terms/<your-term>/people/<you>/notes/week-NN.md` | **only you** | Every week. This is your notebook. |
| `terms/<your-term>/people/<you>/` | **only you** | Your assignments, projects, submissions. |
| `terms/<your-term>/course/` | **anyone in that term** | Slides, syllabus and lab sheets the instructor issued. |
| `exams/past/<term>/` | **anyone** | When you get hold of a new paper — blank or answered. Exam papers never go under `terms/`. |

Two students in different years never touch the same file except to improve the
shared plan — which is the point.

## Contributing

Taking the course now? Create `terms/<YYYY>-<YYYY>-<term>/` with a `README.md`
naming the instructor and dates, and put your notes, papers and photographs there.
Add new exam papers to `exams/past/<term>/`. Keep `weeks/` and `docs/` general —
they are the shared plan and should improve every year.

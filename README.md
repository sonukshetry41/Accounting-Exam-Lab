# Accounting Exam Lab

Static exam-practice website built from the supplied Data Analytics in Accounting course cases. Includes 13 exercises, original supporting datasets, a mixed timed exam, and a **method-and-evidence checkpoint**.

## Run locally

From this directory: `python3 -m http.server 8000` then open `http://localhost:8000`.

## Deploy with GitHub Pages

Create a public repository, upload all files and the `data` directory, then Settings → Pages → Deploy from branch → main / root. GitHub Pages supplies the live URL after publishing. Note: the large source datasets must fit GitHub's file-size restrictions.

## Improvement argument

The evidence checkpoint requires students to describe both the technique used and a validation result before recording a completed exercise. Unlike a completion checkbox, it helps distinguish having seen an answer from being able to explain and verify a reproducible analysis. This is especially relevant in accounting, where incorrect joins, dropped transactions and misleading regression interpretations can produce plausible-looking outputs. The site explicitly labels this self-reported reflection, not automatic grading; students can export their evidence for review. The teacher's site offers exam/question selection and tutoring, while the supplied improvement list mentions usage analytics and content validation but does not propose this student-side method-and-evidence record.

## Materials challenge

The supplied starting materials are not a ready-made question bank: they include diverse Excel workbooks, CSV files, SQLite databases, Word instructions, SQL exercises and answer documents. Creating credible exam practice requires identifying which dataset and tool each task depends on, preserving formula and data-transformation requirements, and avoiding answer claims that cannot be verified from the materials. The SQL and Excel tasks also differ from interpretation questions in how work is checked. That makes the case more difficult than earlier cases with a single dataset or a single clearly specified output.

## Limitations

Not an official exam bank. The evidence checkpoint does not execute SQL or inspect Excel formulas. The timed exam samples three tasks from the curated bank and is not guaranteed to reproduce the teacher's exam composition. Evidence is stored only in the current browser. No server or AI service is used.

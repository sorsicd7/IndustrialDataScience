# Syllabus: Industrial Data Science 1 (IDS 1)

*Version 1 · 2026-10-11 · built from the Moodle course page (course id 58885, read 11 Oct 2026) and the module handbook
(MD E2-21). No slides yet: add them to `materials/` after each lecture. Marked ⚠ = not confirmed.*

---

## 1. Course facts

| Item | Fact | Source |
|---|---|---|
| Module | **MD E2-21 "Industrial Data Science I"**, elective ("Applications"/"Methods" catalogue), **5 CP** (≈ 150 h), 2 + 1 SWS, English | handbook p. 40 |
| Lecture | **Fri 08:15–09:45, EF 50 HS 1**, from **Fri 16 Oct 2026** | Moodle |
| Exercise | **Fri 10:15–11:45, SRG 1 H001**, from Fri 16 Oct 2026 (first one: Introduction to R) | Moodle |
| Software | **R** in the exercises (introduction in the first session); one CS-only task accepts R or Python | Moodle |
| **Bonus** | **Midterm Fri 27 Nov 2026**, 10:15, 20 min (in the exercise, SRG 1 H001) + **endterm Fri 29 Jan 2027** (in the exercise). Voluntary. **≥ 70% in midterm + endterm together → your exam grade is improved** (if you pass the exam) | Moodle |
| **Exam 1** | **Mon 08.02.2027, 16:00**, HG II HS 1 (and HS 3–5) | Moodle |
| Exam 2 | **Wed 31.03.2027, 09:00**, HG II HS 1 (and HS 3, 5–7) | Moodle |
| Mock exam | **Fri 05.02.2027** in the exercise slot | Moodle |
| Contacts | indas@statistik.tu-dortmund.de (general); jakob.becker@tu-dortmund.de (data science / statistics questions) | Moodle |
| CS-only task | Exercise 3 Task 5 must be submitted by 19 Nov **only by Computer Science students** to qualify. You are a Data Science student, so it does not apply ⚠ (confirm in the first exercise) | Moodle |
| Unknown ⚠ | exam length and form (written?), allowed aids, whether Python is fine instead of R | – |

---

## 2. Topic map and schedule (from Moodle)

The exercise usually works on the **previous** week's lecture. **A** = core, **B** = important.

| ID | Date | Lecture | Exercise that day | Prio | Links to other courses |
|---|---|---|---|---|---|
| I01 | Fri 16 Oct | Introduction to Industrial Data Science | Introduction to R | B | – |
| I02 | Fri 23 Oct | Data in industrial contexts | (I01 follow-up) | B | – |
| I03 | Fri 30 Oct | Data analysis in industrial contexts | sheet: sensors, data series | B | – |
| I04 | Fri 6 Nov | Data management: introduction, database basics | data in industrial contexts | **A** | DS in Context (data management) |
| I05 | Fri 13 Nov | Data management: data warehousing, **MapReduce** | database sheet (mondial) | **A** | Big Data T02 (big data tools) |
| I06 | Fri 20 Nov | **Exploratory data analysis**, data visualisation | data warehousing | **A** | – |
| I07 | Fri 27 Nov | **Association and correlation** | **bonus midterm** + EDA | **A** | Inference (tests), NLP T12 (χ², MI) |
| I08 | Fri 4 Dec | **Data preprocessing**, **time series analysis** basics | association and correlation | **A** | NLP T04 (preprocessing) |
| I09 | Fri 11 Dec | **Model selection** concepts | preprocessing, time series | **A** | Big Data T01 (CV, bias–variance), Inference (MSE) |
| I10 | Fri 18 Dec | **Decision trees, random forests** | model selection | **A** | Big Data T03 |
| I11 | Fri 8 Jan | **Linear models, support vector machines** | decision trees (practice sheet) | **A** | Big Data T03, T07, T11 (kernels) |
| I12 | Fri 15 Jan | **Neural networks** | linear models, SVM | **A** | Big Data T09, NLP T17 |
| I13 | Fri 22 Jan | **Deep learning** | neural networks | **A** | Big Data T09, NLP T19–T20 |
| I14 | Fri 29 Jan | **Cluster analysis** | **bonus endterm** + guest lecture | **A** | Big Data T05, NLP T13 |
| I15 | Fri 5 Feb | Industrial data science in use (guest lectures) | **mock exam** | B | – |

**Big overlap with Big Data and NLP** (trees, SVM, neural nets, clustering, model selection). Learn each idea once,
deeply, in whichever course meets it first, and link the notes.

---

## 3. Exam analysis (to be filled)

Unknown: form, length, aids. Use the mock exam (5 Feb), the bonus tests and the example solutions on Moodle to see the
question style. Until then, prepare each topic for (a) definitions and comparisons, (b) small calculations
(correlation coefficients, impurity/Gini of a split, a k-means step, confusion-matrix measures), (c) reading R output.

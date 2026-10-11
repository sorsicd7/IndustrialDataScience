<!-- SYNCED COPY: do not edit here. The original is D:\TU Dortmund\MASTER-PLAN.md on the laptop;
     change it there (or note the change under "Cross-course notes" in progress.md) and run
     sync-master-plan.py. -->

# Master Plan · Winter Semester 2026/27

*Version 2 · written Sun 11 Oct 2026 from the five Moodle course pages, every file in the course folders and the
module handbook. This file joins the five courses; each course's detailed plan is in its own folder
(`semester-plan.md`). **One week numbering for everything: W1 = week of Mon 12 Oct 2026** (the plan starts that day; first
lectures Tue 13 Oct); H1/H2 = the two Christmas weeks. Online overview with a day view for any date (tablet, phone):
https://claude.ai/artifact/HWvuvfoN3XtLec2nHMRTa5*

---

## 0. The semester in one minute

- **5 courses, 31 CP:** NLP 9 · Big Data 9 · Inference 5 · **Industrial Data Science 1 5 (new)** · Data Science in Context 3.
- **Exams:** IDS **Mon 8 Feb 16:00** · Big Data **Wed 10 Feb 17:30** · NLP **Fri 12 Feb 9:00** · Inference **March**
  (date not out yet) · Data Science in Context: multiple-choice exam (date not out yet).
  Second dates: NLP Mon 8 Mar · Big Data Tue 16 Mar · IDS Wed 31 Mar.
- **Every week: about 40 hours of study + 4 gym mornings (3 h each, from home)**, in one fixed timetable (§3).
  Sunday afternoon is free.
- **The method:** learn every lecture **on the same day**, test yourself **every week**, fix each mistake until it is
  right twice, never let a gap grow.
- **Where you stand (11 Oct):** Inference is about one week behind (session 1B part 1 done), Python is at level 1 of 5.
  Both are fixed in the next two weeks (§5): Inference catch-up and a **5-session Python bootcamp**.

---

## 1. Facts (from Moodle, 11 Oct 2026)

| Course | CP | Classes | Exam | Format |
|---|---|---|---|---|
| **NLP** (Rieger) | 9 | Lectures Tue 8:30–10 (M/E 25) and Wed 8:30–10 (M/E 21), 13 Oct – 3 Feb · tutorial Tue 10:15–11:45 (CDI 121) from 20 Oct | **Fri 12 Feb 9:00–11:00**, HG II/HS 3 · 2nd Mon 8 Mar | written, 60 min theory + 60 min programming (Python) |
| **Big Data** (Bürkner, Marx) | 9 | Lectures Tue 16–17:30 (HG II HS 6) and Thu 14:15–15:45 (Chemistry HS 2) from 13 Oct · tutorial Thu 10–11:30 (CT HS ZE 02) from 29 Oct · voluntary sheets every Wed from 21 Oct | **Wed 10 Feb 17:30–19:30**, HG II HS 1 · 2nd Tue 16 Mar | 120 min; aids/style not announced |
| **Industrial Data Science 1** (new) | 5 | Lecture **Fri 8:15–9:45** (EF 50 HS 1) + exercise **Fri 10:15–11:45** (SRG 1 H001) from **16 Oct**; R | **Mon 8 Feb 16:00**, HG II HS 1 · 2nd Wed 31 Mar 9:00 | **Bonus:** midterm Fri 27 Nov + endterm Fri 29 Jan, ≥ 70% together improves the grade · mock exam Fri 5 Feb |
| **Inference** (reading course, Lamberti) | 5 | self-study · exam coaching Mon 16–18 (M/E 21) | **not out yet**; last semester's exam was Thu 10 Sep, near the end of the break → expect **March** | written, 56 min, 3 exercises, own cheat sheet |
| **Data Science in Context** | 3 | **Online (Zoom), Mon 14:00–16:00**, guest lecture series from **early November** (dates TBA) | not out yet | **multiple choice**, based on the lectures |

**Things to keep in mind**
1. **Big Data exam year:** Moodle still writes "10.02.**26**" / "16.03.**26**". Probably a typo for 2027: ask in lecture 1.
2. **Inference is an admission condition** (with Linear Models): it must be passed before the Case Studies (MD 4).
3. **Exam week W16 has three exams in five days** (IDS Mon, Big Data Wed, NLP Fri). The plan prepares for this from
   the start; the decision rule in §9 says what to move if it gets too much (IDS has the latest backup date, 31 Mar).
4. **NLP:** the programming half will be "fundamentally revised"; format not announced yet.
5. **IDS:** one exercise task is compulsory **only for Computer Science students**; check in the first exercise that
   it doesn't apply to Data Science.

---

## 2. Priorities and risks

| Risk | Why | What the plan does |
|---|---|---|
| **Programming (Python level 1)** | Half of the NLP exam is programming; IDS uses R; Big Data uses R/Python | **Python bootcamp** (5 × 90 min in W1–W2), then a coding drill every week without AI |
| **Big Data maths** | Assumes calculus, linear algebra, probability: your diagnostic gaps | Maths foundations every Monday, one week before each topic |
| **Inference behind + admission condition** | ~1 week behind on 11 Oct | Catch-up in W1 (Monday flex + free tutorial slots); the rest is absorbed by holiday week H1 |
| **Three exams in one week** | IDS, Big Data, NLP on 8, 10, 12 Feb | Mocks for all three in W13–W15; exam-week day plan (§9); decision rule on 25 Jan |
| **Load: 31 CP + gym** | ~40 h study + 12 h gym per week | One fixed timetable, Sunday afternoon free, minimum-week rule (§10) |

---

## 3. Your weekly timetable (with gym)

Gym is always **from home, in the morning** (less crowded): **Mon, Wed, Sat, Sun**. Tuesday and Thursday you are on
campus all day; Friday morning you have IDS.

**Monday** (home)
| Time | Block |
|---|---|
| 07:30–10:30 | **Gym** |
| 11:00–12:30 | **Inference A** · learn |
| 12:30–13:15 | lunch |
| 13:15–14:00 | **NLP** · pre-read this week's slides |
| 14:00–16:00 | **Data Science in Context** (Zoom, from early Nov). Until then: **FLEX** (catch-up) |
| 16:00–16:30 | DSiC: 1-page summary + MC flashcards (from Nov) · else break |
| 16:30–18:00 | **Big Data** · maths foundations |
| 18:00–18:30 | **Weekly planning** (read the week in this plan; check Moodle) |
| (16:00–18:00) | Inference exam coaching (M/E 21): only when you need it; it replaces the Big Data block that day |

**Tuesday** (campus, tablet)
| Time | Block |
|---|---|
| 08:30–10:00 | NLP lecture (M/E 25) |
| 10:15–11:45 | NLP tutorial (CDI 121), from 20 Oct |
| 11:45–12:30 | lunch |
| 12:30–13:15 | **NLP same-day review** |
| 13:30–15:00 | **Inference B** · learn + read |
| 15:00–15:45 | Big Data · today's slides / one derivation |
| 16:00–17:30 | Big Data lecture (HG II HS 6) |

**Wednesday**
| Time | Block |
|---|---|
| 08:30–10:00 | NLP lecture (M/E 21), then home |
| 10:45–13:45 | **Gym** |
| 13:45–14:30 | lunch |
| 14:30–15:15 | **NLP same-day review** |
| 15:15–16:00 | **Big Data review** of Tuesday's lecture |
| 16:00–17:30 | Big Data sheet, part 1 (new sheet every Wednesday from 21 Oct) |
| 17:45–19:15 | NLP sheet / coding, part 1 |

**Thursday** (campus, tablet)
| Time | Block |
|---|---|
| 08:15–09:45 | **Inference C** · drill |
| 10:00–11:30 | Big Data tutorial (CT HS ZE 02), from 29 Oct. Before: Big Data maths foundations |
| 11:30–12:15 | Big Data: fix what the tutorial showed |
| 12:15–13:00 | lunch |
| 13:00–14:00 | **IDS prep:** coming lecture's slides; finish last exercise |
| 14:15–15:45 | Big Data lecture (Chemistry HS 2) |
| 16:00–16:45 | **Big Data same-day review** |

**Friday** (campus morning, home afternoon)
| Time | Block |
|---|---|
| 08:15–09:45 | IDS lecture (EF 50 HS 1), from 16 Oct |
| 10:15–11:45 | IDS exercise (SRG 1 H001) |
| 11:45–12:30 | **IDS same-day review** (on campus) |
| 12:30–14:00 | home, lunch |
| 14:00–15:30 | NLP sheet / coding, part 2 |
| 15:45–17:15 | Big Data sheet, part 2 |
| 17:30–18:15 | **Inference D** · weekly test (timer, paper) |

**Saturday**
| Time | Block |
|---|---|
| 08:00–11:00 | **Gym** |
| 11:30–12:30 | **Inference E** · recap and repair |
| 12:30–13:30 | lunch |
| 13:30–15:00 | **Weekly quizzes**, closed book: NLP 40 min + Big Data 40 min + IDS/DSiC 10 min |
| 15:15–16:45 | **Coding block:** Python (bootcamp in W1–W2; later NLP drill 45 min + IDS R practice 45 min) |
| 16:45–17:15 | **Wrap-up:** say "Wrap up" in each repo you used this week |

**Sunday**
| Time | Block |
|---|---|
| 08:00–11:00 | **Gym** |
| rest of the day | **free** · only if you are behind: FLEX 17:00–18:30 |

| Hours per week | In class | Self-study | Total |
|---|---|---|---|
| NLP | 4.5 | ~7.5 | ~12 |
| Big Data | 4.5 | ~8.5 | ~13 |
| Inference | – | ~6.5 | ~6.5 |
| Industrial Data Science 1 | 3 | ~2.5 | ~5.5 |
| Data Science in Context (from Nov) | 2 | ~0.5 | ~2.5 |
| Planning + wrap-up | – | ~1 | ~1 |
| **Study total** | **~14** | **~26.5** | **~40** |
| **Gym** | | | **12** |

**Rules:** (1) **Same-day reviews** are the most important blocks: never skip them. (2) A missed block goes to the
next **FLEX** (Monday 14:00 until DSiC starts, then Sunday 17:00), never silently dropped. (3) Gym is fixed too: if a
gym morning is lost, move it to the next free morning, not to the evening. (4) Sleep 7–8 hours; no study after 19:30.

**Before all classes run** (the free slots are used like this):
| Slot | W1 (12–18 Oct) | W2 (19–25 Oct) | W3 (26 Oct–1 Nov) | from W4 |
|---|---|---|---|---|
| Mon 14:00–16:00 | FLEX: Inference catch-up | FLEX: Python bootcamp 4 | FLEX: Inference Gate 1 | DSiC Zoom (once it starts) |
| Tue 10:15–11:45 | Inference catch-up (tablet) | NLP tutorial | NLP tutorial | NLP tutorial |
| Thu 10:00–11:30 | Big Data F03 | Big Data F05 | Big Data tutorial | Big Data tutorial |
| Wed 16:00 / Fri 15:45 (BD sheet) | Big Data L1 + ISLP / Inference catch-up | sheet 1 | sheet 2 | sheets |
| Wed 17:45 / Fri 14:00 (NLP sheet) | Python bootcamp 1 / 2 | NLP sheet | NLP sheet | NLP sheet |

---

## 4. The semester calendar

**Inference runs one week behind its own plan until Christmas** (the topic planned for W1 is done in W2, and so on);
holiday week H1 absorbs the shift, and from W11 (4 Jan) it is back on its original dates.

| Week | Dates | Inference | NLP | Big Data | IDS 1 | DSiC · checks |
|---|---|---|---|---|---|---|
| **W1** | 12–18 Oct | **catch-up:** 1B part 2 → 2E (derivatives, distributions, E/Var) | L1–L2: intro, data, regex · Python bootcamp 1–3 | L1–L2: intro to ML · F01 check, F03 | **Fri 16:** I01 + Intro to R | Tue 13: first lectures · quizzes start Sat 17 |
| **W2** | 19–25 Oct | max/min, normal tables, CLT | L3–L4: preprocessing, POS, NER · tutorial from Tue 20 · bootcamp 4–5 | L3–L4: big data in R/Python · sheet 1 Wed 21 · F04, F05 | I02 data in industrial contexts | Plan review #1 (Mon 19) |
| **W3** | 26 Oct–1 Nov | **Gate 1 (Mon 26)** · ch. 1 + bias | L5–L6: tf-idf, Zipf, n-gram LMs, perplexity, PMI | L5–L6: supervised · tutorial from Thu 29 · F06 | I03 data analysis | DSiC pre-reading (optional) |
| **W4** | 2–8 Nov | MSE, BLUE | L7–L8: metrics, Naive Bayes, feature selection | L7–L8: supervised → optimisation | I04 databases | **DSiC starts (early Nov)** · NLP Checkpoint 1 (Sat 7) · Thu 5 Nov: Claude cloud credit ends |
| **W5** | 9–15 Nov | consistency · Self-test 1 · **Gate 2** | L9–L10: clustering, SVD/LSA, pLSA, LDA | L9–L10: optimisation · F07 eigenvalues | I05 data warehousing, MapReduce | BD Checkpoint 1 (Sat 14) · Plan review #2 (Mon 9) |
| **W6** | 16–22 Nov | MLE (regular cases) | L11–L12: topic-model evaluation, STM; neural nets | L11–L12: unsupervised · F08 SVD/PCA | I06 EDA · **midterm prep** | practice midterm (Sat 21) |
| **W7** | 23–29 Nov | non-regular MLE, method of moments · Self-test 2 | L13–L14: word2vec, GloVe, fastText, benchmarking | L13–L14: unsupervised → information theory · F09 | I07 correlation · **BONUS MIDTERM Fri 27** | NLP Checkpoint 2 (Sat 28) |
| **W8** | 30 Nov–6 Dec | estimation at speed · **Gate 3** | L15–L16: RNN, LSTM, attention | L15–L16: information theory → regularisation · F10 | I08 preprocessing, time series | BD Checkpoint 2 (Sat 5) · Plan review #3 (Mon 30 Nov) |
| **W9** | 7–13 Dec | Z-test, errors, interpretation | L17–L18: transformer | L17–L18: regularisation → Bayesian · F11 | I09 model selection | – |
| **W10** | 14–20 Dec | p-value, power, binomial test | L19–L20: transformer by hand; BERT | L19–L20: Bayesian inference · F12 | I10 trees, random forests | NLP Checkpoint 3 (Sat 19) |
| **H1** | 21–27 Dec | **asymptotic tests · Self-test 3 · mid-semester mock** (~6 h) | L21 Tue 22 Dec; consolidation 1.5 h/day | consolidation 2 h/day | 1 h: re-read I01–I10 | 4 gym mornings, rest otherwise |
| **H2** | 28 Dec–3 Jan | light; cheat sheet v2 | cumulative test (Sat 2 Jan) | cumulative test (Sat 2 Jan) | – | rest days around New Year |
| **W11** | 4–10 Jan | CIs, test ↔ CI duality · Self-test 4 · **Gate 5** (back on plan dates) | L22 Wed 6 Jan: LLMs, Adam, dropout | L21–L22: Bayesian → deep learning · F13 | I11 linear models, SVM | Plan review #4 (Mon 4) |
| **W12** | 11–17 Jan | LR and UMP tests · **Gate 6** | L23–L24: fine-tuning, annotation, few/zero-shot, PET, SetFit | L23–L24: deep learning · F14 | I12 neural networks | – |
| **W13** | 18–24 Jan | χ², t, F; one-sample t-test | L25–L26: PEFT, LoRA, quantization | L25–L26: self-supervised · F15 | I13 deep learning · endterm prep | **BD Mock 1 (Fri 22, 14:00)** · **NLP Mock 1 (Sat 23, 13:30)** |
| **W14** | 25–31 Jan | variance and two-sample tests | L27–L28: AdaSent, PETapter, DPO, evaluation | L27–L28: kernels, Gaussian processes | I14 clustering · **BONUS ENDTERM Fri 29** | **Exam-date decision Mon 25 (§9)** · Plan review #5 |
| **W15** | 1–7 Feb | light: "which test when", Self-test 5 | L29–L30, last lecture 3 Feb · **Mock 2 Wed 3 Feb, 14:30** | last lectures · **Mock 2 Sat 6 Feb, 13:30** | **mock exam Fri 5 Feb** | Sun 7: IDS final review |
| **W16** | 8–14 Feb | maintenance only | **EXAM Fri 12, 9:00** | **EXAM Wed 10, 17:30** | **EXAM Mon 8, 16:00** | exam week (§9) |
| **W17** | 15–21 Feb | **Mock B** (Mon 15) · **official example exam** (Thu 18) | exam view Wed 17 | – | – | Inference full-time |
| **W18** | 22–28 Feb | Mocks D and E · coaching | – | – | – | – |
| **W19** | 1–7 Mar | short mock · **exam (expected March)** | – | – | – | – |
| **W20** | 8–14 Mar | – | 2nd date Mon 8 Mar (if needed) | – | – | – |
| **W21** | 15–21 Mar | – | – | 2nd date Tue 16 Mar (if needed) | – | – |
| **W23** | 29 Mar–4 Apr | – | – | – | 2nd date Wed 31 Mar (if needed) | – |

NLP and Big Data lecture topics are forecasts; each course plan says how to shift them when the real lectures differ.

---

## 5. The next two weeks, day by day

**The plan starts Mon 12 Oct.** Install in Monday's planning slot (18:00–18:45):
`pip install pandas scikit-learn nltk spacy gensim jupyter`, and **R + RStudio** (for IDS).

### W1 · 12–18 Oct · first lectures + catch-up

| Day | Time | Block | Say / do |
|---|---|---|---|
| **Mon 12** | 07:30–10:30 | Gym | |
| | 11:00–12:30 | **Inference 1B part 2:** derivatives, chain rule, maximum, Q4 | Inference repo → "Let's continue" |
| | 13:15–14:00 | NLP: skim slides 1–43 (intro, data, regex) | `NLP/materials/last_year.pdf` |
| | 14:00–15:30 | **Inference 1C:** discrete distributions (FLEX) | "Let's continue" |
| | 16:30–18:00 | Big Data: F01 check (30 min) + ISLP ch. 2 (60 min) | BigData repo → "Foundations F01" |
| | 18:00–18:45 | Weekly planning + install Python packages and R + RStudio | read §3 and §5 |
| **Tue 13** | 08:30–10:00 | **NLP lecture 1** · ask the exam questions (NLP plan §8) | |
| | 10:15–11:45 | **Inference 1D test** (30 min) + 1E recap (45 min) | tablet |
| | 12:30–13:15 | NLP same-day review L1 | NLP repo → "Lecture review L1" |
| | 13:30–15:00 | **Inference 2A:** densities, integrals | |
| | 15:00–15:45 | Big Data: skim today's slides if online | |
| | 16:00–17:30 | **Big Data lecture 1** · ask: exam year/date, format, aids | |
| **Wed 14** | 08:30–10:00 | **NLP lecture 2** | |
| | 10:45–13:45 | Gym | |
| | 14:30–15:15 | NLP same-day review L2 | "Lecture review L2" |
| | 15:15–16:00 | Big Data review L1 | "Lecture review L1" |
| | 16:00–17:30 | Big Data: re-derive L1 + start F03 | |
| | 17:45–19:15 | **Python bootcamp 1:** values, types, strings, print | NLP repo → "Python bootcamp 1" |
| **Thu 15** | 08:15–09:45 | **Inference 2B:** Uniform, Exponential, Normal | |
| | 10:00–11:30 | **Big Data F03:** linear regression in matrix form | "Foundations F03" |
| | 11:30–12:15 | Inference error-log items (Σ c = N·c, finishing proofs) | |
| | 13:00–14:00 | IDS prep: read the Moodle page; bring the laptop on Friday if the R exercise is hands-on | |
| | 14:15–15:45 | **Big Data lecture 2** | |
| | 16:00–16:45 | Big Data same-day review L2 | |
| **Fri 16** | 08:15–09:45 | **IDS lecture 1** (EF 50 HS 1) | |
| | 10:15–11:45 | **IDS exercise 1: Introduction to R** · ask: exam form, aids, Python OK? | |
| | 11:45–12:30 | IDS same-day review | IDS repo → "Lecture review IDS L1" |
| | 14:00–15:30 | **Python bootcamp 2:** lists, loops, conditions | |
| | 15:45–17:15 | **Inference 2C:** E/Var of sums, X̄, partial derivatives | |
| | 17:30–18:00 | **Inference 2D test** (30 min) | |
| **Sat 17** | 08:00–11:00 | Gym | |
| | 11:30–12:30 | **Inference 2E** recap + error log | |
| | 13:30–15:00 | **Quiz 1:** NLP (T01–T03) + Big Data (intro ML, F01–F02) | "Weekly quiz" in each repo |
| | 15:15–16:45 | **Python bootcamp 3:** dictionaries, Counter, functions | |
| | 16:45–17:15 | Wrap-up | |
| **Sun 18** | 08:00–11:00 | Gym · then free | |

After W1: Inference's two catch-up topic weeks are done; it is now exactly one week behind its plan (absorbed in H1).

### W2 · 19–25 Oct · all courses running

| Day | Time | Block |
|---|---|---|
| **Mon 19** | 07:30–10:30 | Gym |
| | 11:00–12:30 | **Inference A:** distribution of max/min of a sample |
| | 13:15–14:00 | NLP pre-read slides 44–73 |
| | 14:00–15:30 | **Python bootcamp 4:** files, string methods, list comprehensions (FLEX) |
| | 16:30–18:00 | **Big Data F04:** gradients |
| | 18:00–18:30 | **Plan review #1** + weekly planning |
| **Tue 20** | 08:30–11:45 | NLP lecture 3 + **first NLP tutorial** |
| | 12:30–13:15 | NLP review L3 |
| | 13:30–15:00 | **Inference B:** normal distribution, all tables |
| | 15:00–17:30 | Big Data pre-read + lecture 3 |
| **Wed 21** | 08:30–10:00 | NLP lecture 4 |
| | 10:45–13:45 | Gym |
| | 14:30–16:00 | NLP review L4 + Big Data review L3 |
| | 16:00–17:30 | **Big Data sheet 1**, part 1 (out today) |
| | 17:45–19:15 | NLP sheet / coding, part 1 |
| **Thu 22** | 08:15–09:45 | **Inference C:** CLT + drill |
| | 10:00–11:30 | **Big Data F05:** logistic model, cross-entropy |
| | 11:30–12:15 | Big Data: re-derive L3 |
| | 13:00–14:00 | IDS prep for lecture 2 |
| | 14:15–16:45 | Big Data lecture 4 + review |
| **Fri 23** | 08:15–12:30 | IDS lecture 2 + exercise + review |
| | 14:00–15:30 | NLP sheet, part 2 |
| | 15:45–17:15 | Big Data sheet 1, part 2 |
| | 17:30–18:15 | **Inference D:** weekly test |
| **Sat 24** | 08:00–11:00 | Gym |
| | 11:30–12:30 | Inference E: recap |
| | 13:30–15:00 | **Quiz 2:** NLP + Big Data + IDS |
| | 15:15–16:45 | **Python bootcamp 5:** `re` basics + a small text task (45 min) · R basics for IDS (45 min) |
| **Sun 25** | 08:00–11:00 | Gym · then free |

From W3 on, every day follows the timetable in §3 with the week's topics from §4. The overview page shows the exact
day for any date.

**Admin (in the Monday planning blocks of W1–W2):**
- [ ] BOSS: exam registration and **de**registration deadlines for all five courses → phone calendar.
- [ ] Exam regulations: attempts per exam; can a passed exam be improved?
- [ ] Student council Discord: old exams / memory notes for NLP, Big Data, IDS, Inference.
- [ ] Paper notebook, timer, exam calculator.
- [ ] Watch Moodle: Inference exam date; DSiC first lecture date and speakers.

---

## 6. Foundations track (maths and programming, just in time)

| Week | Maths (Inference toolkit + Big Data foundations) | Programming |
|---|---|---|
| W1 | Inference catch-up: derivatives, distributions, E/Var · F01 check, F03 | **Python bootcamp 1–3** |
| W2 | Inference: max/min, normal, CLT · F04 gradients, F05 logistic model | **Python bootcamp 4–5** (incl. regex basics) · R basics for IDS |
| W3 | F06 convexity, Taylor, gradient descent | P03 preprocessing, P04 numpy/pandas |
| W4 | (F06 practice) | bigram LM, Naive Bayes from scratch |
| W5 | F07 **eigenvalues**, PSD, covariance | P05 scikit-learn pipeline |
| W6 | F08 **SVD**, PCA, multivariate normal | P06 gensim LDA |
| W7 | F09 entropy, KL, mutual information | P06 Word2Vec |
| W8 | F10 norms, ridge, lasso | P07 attention in numpy |
| W9 | F11 posterior, conjugacy, Monte Carlo | P07 self-attention from scratch |
| W10 | F12 backpropagation | P07 masks, P08 debugging |
| W11 | F13 variational inference (ELBO) | P07 Hugging Face |
| W12 | F14 kernels, Gaussian conditioning | P07 fine-tuning workflow |
| W13–W14 | F15 kernel ridge, GP posterior | LoRA counts, quantization; P08 timed tasks |

---

## 7. Learn once, use in several courses

| Idea | Inference | NLP | Big Data | IDS 1 |
|---|---|---|---|---|
| Maximum likelihood | W6–W8 (core) | n-gram, Naive Bayes estimates | logistic regression, EM | – |
| Bias, variance, MSE, model selection | W3–W5 | – | bias–variance, regularisation | I09 model selection |
| Derivatives, gradients | W1 | neural nets, word2vec | optimisation, backprop | I12 neural nets |
| Correlation, χ², tests | χ² tests (W13–W14) | feature selection (W4) | information theory | I07 association, correlation |
| Clustering, PCA/SVD | – | clustering, LSA (W5) | unsupervised (W6–W7) | I14 cluster analysis |
| Trees, SVM, kernels | – | – | supervised, kernels (W14) | I10, I11 |
| Neural nets, deep learning | – | W6, W8–W12 | W11–W12 | I12, I13 |
| Data management, big-data tools | – | – | T02 big data in R/Python | I04, I05 (databases, MapReduce) |

---

## 8. How you study

- **Test yourself instead of re-reading** (retrieval practice and spacing have the strongest research support:
  Dunlosky et al., 2013). That's why every week ends with closed-book quizzes and old mistakes come back.
- **Same-day review** beats a long weekend session.
- **Write by hand** for theory; **type the code yourself** for programming (no AI while drilling).
- **Gym helps learning**: exercise improves sleep and focus. Keep it in exam weeks too.
- **One Claude session per study block** in that course's repo: start with **"Let's continue"** (or the session name
  in §5), end with **"Wrap up"**. Ask any repo "What's my plan today?" for the day's plan.
- **After every lecture**, put the slides into that course's `materials/` and push (GitHub "Add files via upload" works
  on the tablet).

---

## 9. The exam period

**Default: write all three first dates.** IDS Mon 8 Feb (16:00), Big Data Wed 10 Feb (17:30), NLP Fri 12 Feb (9:00),
then Inference in March.

**Why:** a first date is an extra chance; the second dates (NLP 8 Mar, Big Data 16 Mar, IDS 31 Mar) are the repair.
If you skip a first date and fail the second, there is no other attempt this semester, and these courses run once a year.

**Exam weeks:**
| Day | Plan |
|---|---|
| Wed 3 Feb | 14:30–16:30 **NLP Mock 2** |
| Fri 5 Feb | IDS lecture + **IDS mock exam** (in class) |
| Sat 6 Feb | Gym · 13:30–15:30 **Big Data Mock 2** · 16:00–17:00 IDS review |
| Sun 7 Feb | Gym · 13:00–16:00 **IDS final review** (the one Sunday you study) |
| **Mon 8 Feb** | light IDS review in the morning (2 h) · **IDS exam 16:00** · rest |
| Tue 9 Feb | Gym · 12:30–17:30 Big Data review (derivation list, error log, one timed set) |
| **Wed 10 Feb** | light Big Data review in the morning · **Big Data exam 17:30–19:30** |
| Thu 11 Feb | Gym · 12:30–17:00 NLP review (error log, formula summary, two short timed sets) · early to bed |
| **Fri 12 Feb** | **NLP exam 9:00–11:00** · rest |
| Sat 13 – Sun 14 | Gym · rest. From Mon 15 Feb: Inference full-time |

**Decision rule (Mon 25 Jan, after BD Mock 1, NLP Mock 1 and the IDS midterm):**
- Every course ≥ 60% → keep all three first dates.
- One course < 60% → move that course to its second date (deregister in BOSS before the deadline).
- Two or more between 60% and 70% → move **IDS** to 31 Mar (its backup is the latest and easiest to fit).
- Assumes at least three attempts per exam: check the exam regulations.

---

## 10. Plan reviews, red flags, and the minimum week

**Plan reviews** (Monday planning block): W2 (19 Oct) · W5 (9 Nov) · W8 (30 Nov) · W11 (4 Jan) · W14 (25 Jan,
with the exam decision) · W17 (15 Feb).

| Signal | What happens |
|---|---|
| A weekly test < 60% in any course | That course's next block becomes a repair session |
| One course red two weeks in a row, another ≥ 85% | Move 1.5 h/week from the green course to the red one for 3 weeks |
| More than one block missed in a week | It goes to the next FLEX; if FLEX is full, apply that course's cut list |
| Less than 30 study hours two weeks in a row | Plan review: what is blocking? |
| Ill, overloaded, or sleeping < 7 h most nights | **Minimum week** for one week |

**Minimum week (~22 h study):** all lectures, tutorials and the IDS exercise · all same-day reviews · Inference A and D ·
one sheet per course · Saturday quizzes · **3 gym mornings**. Nothing else.

---

## 11. Open questions

1. **Inference exam date** → watch Moodle (expected March).
2. **Big Data:** exam year, format, aids → lecture 1 (Tue 13 Oct).
3. **NLP:** aids, sheets/bonus, format of the new programming half → lecture 1 / tutorial 1.
4. **IDS:** exam form and length, aids, Python instead of R, CS-only task → exercise 1 (Fri 16 Oct).
5. **DSiC:** lecture dates, speakers, MC exam date → Moodle.
6. **Exam regulations:** attempts per exam; grade improvement?

---

## 12. Where everything is

| Folder (GitHub repo) | Main files |
|---|---|
| `NLP/` (sorsicd7/NLP) | `syllabus.md` (T01–T29, P01–P08) · `semester-plan.md` · `progress.md` |
| `BigData/` (sorsicd7/BigData) | `syllabus.md` (T01–T12, F01–F15) · `semester-plan.md` · `progress.md` |
| `Inference/` (sorsicd7/Inference) | `semester-plan.md` (gates, mocks) · `syllabus.md` · `progress.md` |
| `IndustrialDataScience/` (sorsicd7/IndustrialDataScience, **to be created**) | `syllabus.md` (I01–I15) · `semester-plan.md` · `progress.md` |
| `DataScienceInContext/` (sorsicd7/DataScienceInContext) | `syllabus.md` · `semester-plan.md` · `progress.md` |
| this folder | `MASTER-PLAN.md` (this file). Every repo has a synced copy `master-plan.md`; after changing this file run `python sync-master-plan.py`. Course sessions log changes under "Cross-course notes"; say "update the master plan" on the laptop to fold them in. Online: **[semester overview page](https://claude.ai/artifact/HWvuvfoN3XtLec2nHMRTa5)** |

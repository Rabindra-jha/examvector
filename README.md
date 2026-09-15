# ExamVector

**A free, open-source exam engine for self-study professionals.**

No subscription. No account. No data leaving your machine. Author your own questions, build an exam, and test yourself — entirely in the browser.

🔗 **[Launch ExamVector](https://rabindra-jha.github.io/examvector/)**

---

## What it does

### Create Exam
Write your question bank in a structured `.txt` file — chapters, topics, subtopics, single and multi-answer questions, explanations, and exhibit images. Upload it, review every question in the visual builder, and export a clean JSON file ready for practice sessions.

### Take Exam
Load any exam JSON and configure a session your way:

- Select specific chapters or topics from your exam
- Set question count with a live pool counter
- Shuffle questions and options independently each session
- Filter by question type — single answer, multi answer, or both
- Choose your mode:
  - **Practice** — instant answer and explanation after each question
  - **Test** — all answers revealed at the end on submit
  - **Review** — flag uncertain questions and revisit them before submitting
- Set a countdown timer that locks the exam on expiry

Results include a percentage score, per-chapter breakdown, and one-click retry of wrong answers only.

### Experience it
Not sure where to start? The Experience page has three ready-made sample exams you can open directly — no file authoring needed. Try the full create or take exam workflow in seconds.

---

## Sample exams included

| Subject | Chapters |
|---|---|
| AWS Intro | 3 chapters covering cloud fundamentals, core services, IAM and pricing |
| CCNA Fundamentals | 4 chapters covering networking concepts, protocols, switching and routing |
| PMP | 3 chapters covering project management framework, processes and knowledge areas |

> AWS, CCNA and PMP are trademarks of their respective owners. ExamVector is not affiliated with or endorsed by Amazon, Cisco or PMI. Sample questions are independently authored for study purposes.

---

## Question file format

```
CCNA 200-301
Author: RJ

Chapter_001_Networking Fundamentals
001_001_Topic_OSI Model
001_001_001_Data Link Layer

Q1. Which layer is responsible for MAC addressing?
A. Network
B. Data Link
C. Transport
D. Physical
Answer: B
Explanation: The Data Link layer handles framing and MAC addressing.

________

Q2. Which two protocols operate at the Transport layer? (Choose two)
A. IP
B. TCP
C. UDP
D. ARP
Answer: B, C
Explanation: TCP and UDP both operate at Layer 4.
```

Full format reference is in the [Manual](https://rabindra-jha.github.io/examvector/manual) page inside the app.

---

## Getting started

### Use it online
Go to **[https://rabindra-jha.github.io/examvector/](https://rabindra-jha.github.io/examvector/)**

### Run it locally
Download the latest build from the [releases page](https://github.com/rabindra-jha/examvector/releases), extract the zip, then run:

```bash
npx serve dist
```

Open your browser at `http://localhost:3000` and ExamVector runs locally — no internet connection needed after the initial download.

---

## Built with

- **React** + **React Router** — SPA routing and UI
- **Tailwind CSS** — styling
- **Material Symbols** — icons
- **Vite** — build tooling

No backend. No auth. No external dependencies at runtime. All exam data stays in the browser.

---

## Why this exists

Certification prep platforms in this space are priced between $199–$499/month. ExamVector does the same core job — question banks, randomised sessions, timed tests, scored results — entirely in the browser, free forever, open source.

Any subject. Any certification. Any domain — if you can write the questions, ExamVector handles the rest.

---

## Support the project

If ExamVector helped you avoid a subscription or pass an exam, you can [buy me a coffee ☕](https://buymeacoffee.com/rabindra.jha)

---

## Contact

Questions or feedback — [rabindra.jha@hotmail.com](mailto:rabindra.jha@hotmail.com)

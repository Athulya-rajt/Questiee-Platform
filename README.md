#  Questiee — Gamified Skill Development Platform

Level up your technical skills through interactive, **quest-based learning**! Questiee bridges the gap between theoretical knowledge and practical execution in a fun, engaging, and challenging environment.

Built entirely with **static HTML, CSS, and JavaScript** — no server, no build step, no installation required. Just open a file in your browser and start playing.

---

##  Features

-  **Gamified learning** — complete quests across 5 technical domains
-  **3 escalating levels** per quest — from trivia fundamentals to live coding
-  **Live Python compiler** — write and run real Python code in your browser (powered by Pyodide)
-  **3 lives system** — protect your health bar to finish all 30 questions
-  **Skip lifelines** — strategically skip questions you're stuck on
-  **Hint system** — tailored hints for every question
-  **Solution reveal** — view the full solution after 5 failed attempts
-  **Progress saving** — game state persists in `localStorage` across page reloads
-  **Mobile-optimized** — clean, responsive card-based UI

---

## 🗺️ The Experiences

| File | Experience | Focus Topics |
|------|-----------|--------------|
| `main.html` |  **Questiee Hub** | Landing page linking to all quests & platforms |
| `index.html` |  **Data Analytics Quest** | Python, NumPy, Pandas DataFrames |
| `ccna.html` |  **CCNA & CCNP Networking** | OSI layers, Cisco IOS, subnetting, OSPF/BGP |
| `cyb.html` |  **Cybersecurity Recon** | Nmap, WHOIS, Sublist3r, OSINT |
| `dsml.html` |  **Data Science, ML & AI** | Scikit-Learn, PyTorch, neural networks |
| `fs.html` |  **Full-Stack Web Dev** | HTML/CSS/JS, Node.js, SQL, MongoDB |
| `mimini.html` |  **Mimini Assistant** | AI-style chat search over the 150-question knowledge base |

Each quest contains **30 interactive questions** across **5 total quests = 150 questions** in the knowledge base.

---

##  Gameplay Mechanics

Every quest follows the same progression:

- **Level 1 — Trivia & Terminology** (Questions 1–10): One-word answers on core concepts.
- **Level 2 — Core Concepts & Predictions** (Questions 11–20): Predict command output or behavior.
- **Level 3 — Live Coding** (Questions 21–30): Write real Python in the built-in browser compiler.

### Rules
- You start with **3 lives**. Each wrong answer costs one life.
- You have **3 skips per level** to bypass difficult questions.
- Every question includes a **hint**.
- After **5 failed attempts** on a question, a **"Reveal Solution"** button unlocks the full answer code.
- Progress is **saved automatically** — close the tab and resume where you left off.

---

##  How to Run

No installation or build step is needed. Simply open the landing page:

1. **Double-click** `main.html` (or any `*.html` file) to open it in your browser.
2. From the hub, click a quest card to launch its interactive workspace.
3. For **Level 3** questions, the Pyodide engine loads in the background to run your Python code.

> **Note:** Level 3 live coding requires an internet connection (it loads Pyodide via CDN). The rest of the platform works fully offline.

---
## Preview
[https://Questiee.netlify.app/]

##  Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5 + CSS** | Structure and styling |
| **Tailwind CSS** | Utility-first styling (via CDN) |
| **Pyodide v0.25.0** | In-browser Python interpreter (WASM) |
| **Alpine.js** | Interactive UI logic (Mimini assistant) |
| **Lucide Icons** | Clean, modern icons |
| **localStorage** | Persistent game progress |

---

## 📁 Project Structure

```
pyquiz/
├── main.html        # Questiee hub — landing page with all quest cards
├── index.html       # Data Analytics Quest (Pandas, NumPy, Python)
├── ccna.html        # CCNA & CCNP Networking Quest
├── cyb.html         # Cybersecurity Recon Quest
├── dsml.html        # Data Science, ML & AI Quest
├── fs.html          # Full-Stack Web Dev Quest
├── mimini.html      # Mimini — searchable knowledge assistant
└── README.md        # You are here
```

---

## 👤 Author

**Questiee Platform** — Created & developed by **Athulya Raj T**

-  GitHub: [@Athulya-rajt](https://github.com/Athulya-rajt)

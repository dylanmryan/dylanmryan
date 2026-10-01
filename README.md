## Dylan Ryan

Data Science @ Northwestern '27 — AI & Business Institutions minors · New York, NY

I build forecasting systems and test them honestly.  
Open to Summer 2027: quantitative research/trading · ML engineering · data engineering.

---

### Research

**[Calibrating the Crowd](https://github.com/dylanmryan/calibrating-the-crowd)** — prediction-market calibration · Northwestern BPF Undergraduate Research Grant, Summer 2026 · advised by Prof. Arend Kuyper

Do some betting markets predict the future better than others? I compared a regulated exchange, a crypto exchange and sportsbooks across **5,333 games**.

- All three forecast about equally well — where you bet matters less than people assume
- Trading costs ~**4.6%** per position, so a market can price things accurately and still be a bad deal
- Built a Python + DuckDB pipeline that snapshots prices across venues on a schedule and matches equivalent contracts automatically **99.3%** of the time
- **79** automated checks halt the analysis if the data looks wrong; claims that didn't survive a bigger sample were retracted in the open

Previously a research assistant on faculty MLB work, building the data pipelines behind it.

---

### Markets & forecasting

- **[mma-prediction](https://github.com/dylanmryan/mma-prediction)** — Predicts UFC fight outcomes. Forecasts are locked in before each event and graded automatically after, so the track record can't be tuned after the fact.
- **[cbb-kalshi-trading-system](https://github.com/dylanmryan/cbb-kalshi-trading-system)** — Trades college basketball on Kalshi end to end: model the game, scan the market, rank bets after fees, track the bankroll. One command-line tool, 142 tests.
- **[simplerulesbench](https://github.com/dylanmryan/simplerulesbench)** — Checks whether ML models actually beat simple trading rules. Often they don't, and the benchmark reports it.

### LLM systems & evaluation

- **[mementor](https://github.com/dylanmryan/mementor)** — Compares ways of giving an AI agent memory. Retrieval-based memory holds up; a sliding context window forgets a fact completely once it scrolls out.
- **[lucid](https://github.com/dylanmryan/lucid)** — A small model that watches an LLM make a plan and flags the moment its picture of the world stops matching reality.
- **[Mirage](https://github.com/dylanmryan/Mirage)** — Blocks prompt-injection attacks by checking risky actions outside the model, and routes the attacker into a decoy instead.
- **[prompt-typo-robustness](https://github.com/dylanmryan/prompt-typo-robustness)** — Measures how much typos in a prompt hurt accuracy. Smaller models suffer more: with 20% of the text corrupted, a 1B model loses 6.7 points and a 14B loses 2.7.

### Tools

- **[StyleGenerator](https://github.com/dylanmryan/StyleGenerator)** — Turns a board of images and links into a reusable front-end design system, with color contrast and spacing checked automatically.
- **[college_chatbot_v1](https://github.com/dylanmryan/college_chatbot_v1)** — Answers college-application questions from official sources only, and says it doesn't know rather than guessing.

---

### How I build

Test on data the model couldn't have seen · report how confident a model should be, not just how often it's right · subtract fees before claiming an edge · pinned environments, CI and tests that stop a bad run · limitations sections that argue against my own result.

### Stack

`Python` `pandas` `NumPy` `XGBoost / LightGBM` `PyTorch` `scikit-learn` `Streamlit`  
`DuckDB` `SQL` `Postgres + pgvector` `Kalshi / Polymarket APIs`  
`uv` `pytest` `ruff` `mypy` `Docker` `GitHub Actions` · `TypeScript` `Next.js` `R / Quarto`

---

[LinkedIn](https://www.linkedin.com/in/dylan-matthew-ryan) · dylanmryan23@gmail.com

# Hi, I'm Moulik Jain 👋
**Data scientist and ML engineer · Pennsylvania State University · building a career in football analytics**

I build models and the checks that keep them honest: leak-free backtests, tests fixed before the results are in, and write-ups that say what didn't work. I also run an established inventory business, so I care about the decision at the end of the analysis, not just the chart.

---

### ⚽ Football analytics

#### [Match prediction: Elo, form and the betting market](https://github.com/Moulik04/Football-Match-Prediction-Data-Fusion)
* **Tech:** Python, pandas, scikit-learn.
* **What it does:** predicts home win, draw or away win in Europe's top five leagues from pre-match information only, scored on later seasons the model never saw.
* **What it found:** Elo ratings built from 24 seasons of results do most of the work. The bookmakers' odds still beat every model built without them; adding Elo, form and starting-XI ratings to the odds only ties them.
* **Data fusion:** two match sources spell 80 of 164 clubs differently, so clubs are matched by the fixtures they played, not by spelling. All 14,585 shared matches join and every score agrees.
* **Rebuilt honestly:** my first version's form feature included the match being predicted. The repo now measures that leak and fixes it, and tests check that no match's inputs can see its result.

#### [FC Barcelona before and after Messi](https://github.com/Moulik04/FC-Barcelona-Reproducible-Performance-Analysis)
* **Tech:** R, R Markdown, ggplot2.
* Six La Liga seasons compared from match data and cross-checked against a second source: points per match barely moved (2.18 to 2.16), goals scored fell and goals conceded fell with them.

---

### 🚀 Machine learning and data science

#### [LedgerQL](https://github.com/Moulik04/LedgerQL)
Plain-English questions about company financials, answered by local open-weight models that write SQL over SEC filings. Every number in an answer has to appear in the query result, or the answer is withheld. The headline test (80 new questions) was fixed in advance and is still to be run.

#### [StockUp](https://github.com/Moulik04/stockup)
Demand forecasts that end in a reorder decision (how much, and when), judged in leakage-free backtests. On the M5 retail data, fixing the ordering policy was worth about 11 times more than choosing the best model; a pre-registered replication on a second business didn't reproduce that, and the README reports it.

#### [MemeGPT](https://github.com/Moulik04/memegpt) · [live](https://memegpt.app)
A chatbot that only replies in memes: LLM intent routing, retrieval over 120+ templates and a Pillow compositor, built with FastAPI and Next.js, with a Terraform-provisioned Google Cloud Run backend and CI/CD on GitHub Actions.

#### [Heterophily-aware GNNs for anti-money-laundering](https://github.com/Moulik04/aml-heterophily-gnn) (Penn State DS402)
H2GCN plus an XGBoost cascade on IBM's AML transaction data, compared with tabular models and standard GNNs.

#### [Calibrating injury-risk models](https://github.com/Moulik04/cutting-signature-acl) (Penn State DS340W)
Six ways of handling imbalanced data, compared. Cost-sensitive learning with isotonic calibration cut the Brier score by about a third. The public datasets look simulated, so it shows the methods, not real injury prediction.

---

### 📊 Earlier work
* [Tableau instructional manual](https://github.com/Moulik04/Tableau-Instructional-Design-Manual): selected as a course exemplar for beginners.
* [LA crime dashboard](https://github.com/Moulik04/LA-Crime-Data-Visual-Intelligence): an interactive Tableau dashboard for new residents, built from audience analysis through validation.
* [Graph theory and navigation](https://github.com/Moulik04/Graph-Theory-Navigation-Analysis): the routing maths behind map apps, from Dijkstra to A*.
* [Lake Baikal systems analysis](https://github.com/Moulik04/Pribaikalsky-Conservation-Analysis): 40 years of climate data alongside policy and tourism.
* [Fairness in résumé-screening AI](https://github.com/Moulik04/AI-Fairness-Resume-Screening) and [AI ethics and governance research](https://github.com/Moulik04/AI-Ethics-Governance-Research).

---

### 🛠️ Toolkit
* **Languages and data:** Python (pandas, NumPy, scikit-learn), SQL (DuckDB, Postgres), R.
* **ML:** gradient boosting, PyTorch and PyTorch Geometric, probability calibration, local LLMs (Ollama, vLLM).
* **Apps and infrastructure:** FastAPI, Next.js, Docker, Terraform, Google Cloud Run, Git.
* **Visualization:** Tableau, Matplotlib, ggplot2.

---

### 📫 Contact
* **Email:** moulikjain04@gmail.com
* **LinkedIn:** [Moulik Jain](https://www.linkedin.com/in/moulikjain04/)

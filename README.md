<div align="center">

# Soham Vyas

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2500&pause=1000&color=58A6FF&center=true&vCenter=true&width=550&lines=Data+Science+%26+AI+%40+IIT+Jodhpur;Symbolic+Computing+%26+Tensor+Algebra;Building+High-Concurrency+Systems" alt="Typing SVG" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-soham.lol-58A6FF?style=flat-square&logo=googlechrome&logoColor=white)](https://soham.lol)
[![SymPy Core](https://img.shields.io/badge/SymPy-Matrix_Expressions-e35b2e?style=flat-square&logo=python&logoColor=white)](https://github.com/sympy/sympy)
[![IIT Jodhpur](https://img.shields.io/badge/Institution-IIT_Jodhpur-0052cc?style=flat-square&logo=googleclassroom&logoColor=white)](https://iitj.ac.in)
[![Email](https://img.shields.io/badge/Email-hello@soham.lol-34d399?style=flat-square&logo=gmail&logoColor=white)](mailto:hello@soham.lol)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-vyassoham-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vyassoham)

<br/>

</div>

```yaml
identity:
  engineer: "Soham Vyas"
  affiliation: "Indian Institute of Technology Jodhpur (IITJ)"
  department: "Data Science & Artificial Intelligence"
  focus_areas: ["Symbolic Computing (CAS)", "Matrix Group Calculus", "Atomic Concurrency Systems"]
open_source:
  organization: "SymPy (sympy/sympy)"
  submodules: ["sympy.matrices.expressions", "sympy.assumptions"]
  track_record: "5 Merged Core PRs (Reviewed & merged by @sylee957)"
```

---

### 🔬 Open Source Engineering · SymPy

> Specializing in **Symbolic Matrix Expressions** (`sympy.matrices.expressions`) and **Predicate Assumption Dispatchers** (`sympy.assumptions`).  
> Core contributions reviewed and merged by lead matrices maintainer **S.Y. Lee ([@sylee957](https://github.com/sylee957))** · Commended by **Chris Smith ([@smichr](https://github.com/smichr))**.

* **Matrix Predicates & Invariants:** Added strict squareness verification to `MatrixBase` hermitian and antihermitian predicate handlers, extended `is_positive` predicate support, and registered predicate dispatchers for composite matrix expressions.
* **Symbolic Shape & Power Algebra:** Implemented algebraic return of `ZeroMatrix` for zero power of square matrices ($M^0 = I$), resolved `KroneckerProduct` power evaluation failures, and verified shape invariants.
* **Peer Code Review:** Active code reviewer on upstream matrix expressions and assumptions PRs (`[Contributor]` badge).

| Stream | Live Filter & Query | Real-Time Telemetry |
| :--- | :--- | :---: |
| **Merged Pull Requests** | `repo:sympy/sympy is:pr author:vyassoham is:merged` | [**View Live Merged PRs ↗**](https://github.com/sympy/sympy/pulls?q=is%3Apr+author%3Avyassoham+is%3Amerged) |
| **Active Pull Requests** | `repo:sympy/sympy is:pr author:vyassoham is:open` | [**View Active PRs ↗**](https://github.com/sympy/sympy/pulls?q=is%3Apr+author%3Avyassoham+is%3Aopen) |
| **Authored Issues** | `repo:sympy/sympy is:issue author:vyassoham` | [**View Authored Issues ↗**](https://github.com/sympy/sympy/issues?q=is%3Aissue+author%3Avyassoham) |

---

### ⚡ Featured Engineering Systems

#### 🛡️ [Cybersecurity Risk Analyzer](https://github.com/vyassoham/Cybersecurity-Risk-Analyzer) [![Stars](https://img.shields.io/github/stars/vyassoham/Cybersecurity-Risk-Analyzer?style=flat-square&logo=github&color=58A6FF)](https://github.com/vyassoham/Cybersecurity-Risk-Analyzer/stargazers)
`Python` · `Information Theory` · `NIST 800-63B` · `Streamlit`
* **Entropy Modeling:** Computes character distribution Shannon entropy ($H(X) = -\sum p_i \log_2 p_i$) to measure true credential randomness.
* **Crack-Time Lattice:** Models offline attack latencies across four computational tiers, from consumer single-GPU setups up to simulated Grover quantum search.

#### ⚡ [AI Rate Limiter Shield](https://github.com/vyassoham/ai-rate-limiter-shield) [![Stars](https://img.shields.io/github/stars/vyassoham/ai-rate-limiter-shield?style=flat-square&logo=github&color=58A6FF)](https://github.com/vyassoham/ai-rate-limiter-shield/stargazers)
`FastAPI` · `Redis` · `Atomic Lua` · `Isolation Forest` · `WebSockets`
* **Concurrency Core:** High-throughput rate-limiting proxy powered by an **atomic Lua sliding-window script** in Redis, eliminating race conditions under parallel traffic bursts.
* **ML Anomaly Detection:** An embedded **Isolation Forest** scores request inter-arrival intervals in real time to isolate non-human bot cadences.
* **Zero Database Overhead:** Completely relational database-free; validated under synthetic traffic spikes and live WebSocket attack telemetry.

#### 🔬 [SchemaGuard](https://github.com/vyassoham/SchemaGuard) [![Stars](https://img.shields.io/github/stars/vyassoham/SchemaGuard?style=flat-square&logo=github&color=58A6FF)](https://github.com/vyassoham/SchemaGuard/stargazers)
`Python` · `Pandas` · `pytest` · `Data Quality Engine`
* **Data Invariant Engine:** Validates high-volume tabular records across CSV, Excel, JSON, and PDF formats against pre-defined column schemas.
* **Drift & Null Protection:** Automatically computes null-rate thresholds, flags unexpected column drift, and enforces strict type coercion rules.
* **Test Rigor:** 100% test coverage backed by an automated **25-test `pytest` suite**.

#### 🗣️ [Neural TTS](https://github.com/vyassoham/neural-tts) [![Stars](https://img.shields.io/github/stars/vyassoham/neural-tts?style=flat-square&logo=github&color=58A6FF)](https://github.com/vyassoham/neural-tts/stargazers)
`Python` · `DSP` · `PyTorch` · `Acoustic Modeling`
* **Modular DSP Pipeline:** Decouples text normalization, phoneme alignment, acoustic feature synthesis, and neural vocoder inference.
* **Prosody Control:** Exposes fine-grained programmatic control over pitch contour, speaking rate, and timbre across multilingual checkpoints.

<details>
<summary>📂 <b>View Archive Tools & Experiments</b></summary>
<br/>

* **[MediPro](https://github.com/vyassoham/MediPro)** — Medicine composition, dosage, and contraindication reference with offline OCR lookup.
* **[SocialLogger](https://github.com/vyassoham/SocialLogger)** — Multi-platform content scheduler with automated publishing pipelines.
* **[Crypto Tracker](https://github.com/vyassoham/soham-crypto-tracker)** — Live cryptocurrency dashboard consuming CoinGecko API with Plotly visualizers.

</details>

---

### 🛠️ Technical Arsenal

**Core & Scientific Computing**  
![Python](https://img.shields.io/badge/Python_3.12-3776ab?style=flat-square&logo=python&logoColor=white)
![SymPy](https://img.shields.io/badge/SymPy-Matrix_CAS-e35b2e?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8caae6?style=flat-square&logo=scipy&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)

**Systems, Infrastructure & Concurrency**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis_Lua-dc382d?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-fcc624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-f05032?style=flat-square&logo=git&logoColor=white)

**Testing & Machine Learning**  
![pytest](https://img.shields.io/badge/pytest-0a9edc?style=flat-square&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088ff?style=flat-square&logo=githubactions&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?style=flat-square&logo=pytorch&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-f7931e?style=flat-square&logo=scikitlearn&logoColor=white)

---

### 📈 Activity & Contribution Telemetry

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=vyassoham&theme=tokyo-night&bg_color=0d1117&color=58A6FF&line=58A6FF&point=c9d1d9&area=true&hide_border=true" width="100%" alt="Soham's Contribution Graph" />
</p>

---

### 🎯 Goals & Collaboration

I am actively exploring:
* **GSoC 2027 Mentorship** in SymPy (`sympy.matrices.expressions` & `sympy.assumptions`)
* **Summer 2027 Research & Systems Internships** (Symbolic Computation, Mathematical AI, High-Performance Systems)
* Research discussions on computer algebra systems and formal mathematical verification

Direct Contact: **[hello@soham.lol](mailto:hello@soham.lol)** · **[LinkedIn](https://linkedin.com/in/vyassoham)** · **[Portfolio ↗](https://soham.lol)**

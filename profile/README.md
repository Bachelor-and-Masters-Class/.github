# Computer Science Coursework · WGU

**B.S. and M.S. in Computer Science, Western Governors University: 16 courses, one repo each, every one with working code or a full written deliverable.**

The work runs from C++ and data structures, through Java and full-stack development, into machine learning, deep learning and security governance. Each repo has its own README with the problem, the design choices and how to run it.

---

## Highlights

| | Project | Result |
|---|---|---|
| 🚚 | [**Package delivery router**](https://github.com/Bachelor-and-Masters-Class/Data-Structures-and-Algorithms-II-C950) · C950 | **40 of 40 packages delivered in 134.3 miles**, under the 140-mile limit, on a hash table written from scratch (no built-in dict) |
| 🚑 | [**Ambulance dispatch**](https://github.com/Bachelor-and-Masters-Class/Applied-Algorithms-and-Reasoning-D795) · D795 | Dijkstra with a binary heap picks the fastest unit for each call, highest severity first. Complexity analysed: O(A · (V + E) log V) per call |
| 🌫️ | [**Air quality and health risk pipeline**](https://github.com/Bachelor-and-Masters-Class/Implementing-and-Testing-AI-Solutions-D683) · D683 | Chronological split with `TimeSeriesSplit` so the model never trains on the future. Scored on RMSE, MAE and MAPE against a test set never seen in tuning |
| 🏥 | [**Medical center security assessment**](https://github.com/Bachelor-and-Masters-Class/Governance-Risk-Compliance-D486) · D486 | Reviewed a third-party SAR as the CISO, mapped the gaps to NIST SP 800-53 Rev. 5 and wrote the POA&M |

---

## All courses

### Machine learning and AI

| Course | Project | What it shows |
|---|---|---|
| [D797](https://github.com/Bachelor-and-Masters-Class/Artificial-Intelligence-and-Machine-Learning-Foundations-D797) | Clustering and prediction on Maryland COVID-19 data | K-Means as a derived feature, regression scored on RMSE |
| [D682](https://github.com/Bachelor-and-Masters-Class/AI-Model-Optimization-D682) | Six optimization techniques, tested head to head | Controlled experiment: fixed seed, split and metrics across every variant |
| [D684 · Task 1](https://github.com/Bachelor-and-Masters-Class/Task-1-AI-Model-Optimization-D684) | Baseline vs. tuned, threshold-tuned, bagged and stacked models | Ranked on F1 and ROC AUC, each technique isolated |
| [D682](https://github.com/Bachelor-and-Masters-Class/Implementing-and-Testing-AI-Solutions-D682) | Testable, command-line ML pipeline | Leakage-safe validation, reproducible artifacts |
| [D683](https://github.com/Bachelor-and-Masters-Class/Implementing-and-Testing-AI-Solutions-D683) | Air quality and health risk prediction | Tuned gradient boosting, feature importances, auto-generated reports |
| [D684 · Task 2](https://github.com/Bachelor-and-Masters-Class/Task-2-Product-Development-D684) | Taking an ML model to a product | Layered test and QA plan across data, model and app |

### Deep learning and NLP

| Course | Project | What it shows |
|---|---|---|
| [D802](https://github.com/Bachelor-and-Masters-Class/Deep-Learning-D802) | CIFAR-10 image classification prep | Decoding raw batches, normalization, reproducible train / validation / test splits |
| [D803](https://github.com/Bachelor-and-Masters-Class/Natural-Language-Processing-D803) | Amazon review sentiment | TF-IDF features, precision / recall / F1 per class, confusion matrix |

### Algorithms

| Course | Project | What it shows |
|---|---|---|
| [D795](https://github.com/Bachelor-and-Masters-Class/Applied-Algorithms-and-Reasoning-D795) | Ambulance dispatch | Dijkstra, priority ordering, complexity analysis |
| [C950](https://github.com/Bachelor-and-Masters-Class/Data-Structures-and-Algorithms-II-C950) | Package delivery router | Custom hash table, nearest-neighbor routing, time simulation |

### Software engineering

| Course | Project | What it shows |
|---|---|---|
| [D387](https://github.com/Bachelor-and-Masters-Class/Advanced-Java-D387) | Hotel reservations | Spring Boot REST API + Angular front end, paginated queries |
| [D288](https://github.com/Bachelor-and-Masters-Class/Back-End-Programming-D288) | Vacation booking backend | Cart and checkout, JPA persistence, JUnit |
| [D287](https://github.com/Bachelor-and-Masters-Class/Java-Frameworks-D287) | Parts and products inventory | Spring MVC + Thymeleaf, custom validation annotations, unit tests |
| [C867](https://github.com/Bachelor-and-Masters-Class/Scripting-and-Programming-Applications-C867) | Student roster in C++ | Object-oriented design, manual memory management |
| [D197](https://github.com/Bachelor-and-Masters-Class/Version-Control-D197) | Git workflow | Branching, merging, conflict resolution |

### Security and compliance

| Course | Project | What it shows |
|---|---|---|
| [D486](https://github.com/Bachelor-and-Masters-Class/Governance-Risk-Compliance-D486) | Fielder Medical Center assessment | FISMA, NIST SP 800-53 Rev. 5 controls, risk analysis, POA&M |

---

## How I work, across all of it

- **Measured, not claimed.** Fixed seeds, held-out test sets and before / after numbers, so a result can be re-run and checked.
- **Validation that fits the data.** Time-ordered data gets a chronological split, not a shuffle.
- **Cost stated.** Algorithms come with their time and space complexity.
- **Tested.** JUnit suites on the Java work; reproducible artifacts on the ML work.

## Stack

**Languages** Python · Java · C++ · SQL · TypeScript · JavaScript · HTML · CSS
**Frameworks** Spring Boot · Angular · Thymeleaf · scikit-learn · pandas · NumPy · JUnit · Maven
**Tools** Git

---

**Michael L. Williams II** · B.S. and M.S. in Computer Science, WGU
My professional work is identity and privileged access engineering: [@ChromeData](https://github.com/ChromeData)

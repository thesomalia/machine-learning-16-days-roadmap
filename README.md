# AI / DS / ML — 16-Week Roadmap

> *Rust-tracker energy, applied to gradients instead of window positions. Check things off as you learn.*

This repository contains the complete **16-Week AI/ML/DS Study Roadmap** and an interactive, single-page tracker web app ([`study-tracker.html`](file:///Users/elkenzi/learn/ml/study-tracker.html)).

---

## 📌 Overview

The roadmap is structured into **5 distinct phases** across **16 weeks**, designed day-by-day with milestone projects, rest days, and buffer periods.

- **Interactive Tracker**: Open [`study-tracker.html`](file:///Users/elkenzi/learn/ml/study-tracker.html) directly in your browser.
- **Features**: Automatic progress saving via browser storage, dark/light theme switching, and **Pip** the pixel-art mascot companion.

---

## 🗺️ Roadmap Overview

| Phase | Weeks | Focus Area |
| :--- | :--- | :--- |
| **Phase 1** | Weeks 1–3 | **Software Foundations** (Python, NumPy, Pandas, SQL & Pipelines) |
| **Phase 2** | Weeks 4–6 | **Math, Visualization & EDA** (Statistics, Linear Algebra, Calculus & Optimization) |
| **Phase 3** | Weeks 7–11 | **Core Machine Learning** (Regression, Classification, Ensembles & Boosting, Unsupervised Learning, Buffer/Consolidation) |
| **Phase 4** | Weeks 12–14 | **Modern AI & Specialization** (Deep Learning Basics, NLP Foundations, NLP & LLMs — Somali Language Project) |
| **Phase 5** | Weeks 15–16 | **Deployment** (MLOps & Capstone) |

---

## 📅 Full 16-Week Curriculum

### PHASE 1 — SOFTWARE FOUNDATIONS

#### Week 1: Python for someone who already codes
> *Note: You know Git, CLI, and APIs from JS/TS work — this week moves fast.*
- **Day 1**: Python syntax speedrun — variables, control flow, data structures
- **Day 2**: Python quirks vs JS/TS — dynamic typing, comprehensions, `*args`/`**kwargs`
- **Day 3**: OOP in Python — classes, dunder methods
- **Day 4**: Virtual envs (`venv`/`uv`), `pip`, project structure
- **Day 5**: Rest / buffer
- **Day 6**: Skim Python type hints (`mypy`)
- **Day 7**: 🎯 **MILESTONE** — Script pulling data from a public API (HDX / World Bank / ACLED) into local JSON/CSV

#### Week 2: NumPy & Pandas
- **Day 1**: NumPy arrays, broadcasting
- **Day 2**: NumPy vectorized ops
- **Day 3**: Rest / practice problems
- **Day 4**: Pandas — loading, filtering
- **Day 5**: Pandas — groupby, joins
- **Day 6**: Pandas — missing data, outliers
- **Day 7**: 🎯 **MILESTONE** — Clean a messy Somalia-relevant dataset (HDX/World Bank/FAO)

#### Week 3: SQL & Pipelines
- **Day 1**: SQL fundamentals — SELECT, WHERE
- **Day 2**: SQL — JOIN
- **Day 3**: Aggregations, subqueries, window functions
- **Day 4**: Rest
- **Day 5**: Connect SQLite to Python
- **Day 6**: Build a basic ETL pipeline
- **Day 7**: 🎯 **MILESTONE** — Pipeline cleaning your Week 2 dataset into SQLite

---

### PHASE 2 — MATH, VISUALIZATION & EDA

#### Week 4: Statistics & Visualization
- **Day 1**: Descriptive stats — mean, median, mode
- **Day 2**: Variance, distributions
- **Day 3**: Rest
- **Day 4**: Matplotlib basics
- **Day 5**: Seaborn basics
- **Day 6**: Storytelling with charts
- **Day 7**: 🎯 **MILESTONE** — EDA on your Somalia dataset, visualize key trends

#### Week 5: Linear Algebra
- **Day 1**: Vectors, matrices
- **Day 2**: Matrix multiplication
- **Day 3**: Rest
- **Day 4**: Vector spaces
- **Day 5**: Eigenvalues / eigenvectors — intuition first
- **Day 6**: Practice problems (3Blue1Brown)
- **Day 7**: Practice problems, review

#### Week 6: Calculus & Optimization
- **Day 1**: Derivatives
- **Day 2**: Gradients, chain rule
- **Day 3**: Rest
- **Day 4**: Gradient Descent theory
- **Day 5**: Implement gradient descent from scratch
- **Day 6**: Buffer / review Phase 2
- **Day 7**: Buffer / review Phase 2

---

### PHASE 3 — CORE MACHINE LEARNING

#### Week 7: Regression
- **Day 1**: Linear Regression
- **Day 2**: Cost functions
- **Day 3**: Metrics — RMSE, MAE, R²
- **Day 4**: Rest
- **Day 5**: 🎯 **PROJECT / MILESTONE** — Somalia-relevant regression (market prices / rainfall-crop yield)
- **Day 6**: Project — feature engineering
- **Day 7**: Project — write up results

#### Week 8: Classification
- **Day 1**: Logistic Regression
- **Day 2**: K-Nearest Neighbors
- **Day 3**: Precision, Recall, F1 — why they beat accuracy
- **Day 4**: Rest
- **Day 5**: 🎯 **PROJECT / MILESTONE** — Risk classifier (flood/drought or fraud signals)
- **Day 6**: Project — evaluate & tune
- **Day 7**: Project — write up results

#### Week 9: Ensembles & Boosting
- **Day 1**: Decision Trees
- **Day 2**: Random Forests
- **Day 3**: Gradient Boosting — XGBoost/LightGBM
- **Day 4**: More boosting practice
- **Day 5**: Rest
- **Day 6**: 🎯 **PROJECT / MILESTONE** — Apply SMOTE for class-imbalanced fraud/anomaly data
- **Day 7**: Project — evaluate & write up

#### Week 10: Unsupervised Learning
- **Day 1**: K-Means Clustering
- **Day 2**: Hierarchical Clustering
- **Day 3**: Rest
- **Day 4**: PCA for dimensionality reduction
- **Day 5**: PCA practice
- **Day 6**: 🎯 **PROJECT / MILESTONE** — Cluster regions by need/access indicators (HDX)
- **Day 7**: Project — write up results

#### Week 11: Buffer / Consolidation
> *Note: This is your GitHub 'build in public' week.*
- **Day 1**: Revisit weakest topic from Weeks 7–10
- **Day 2**: Revisit weakest topic (cont.)
- **Day 3**: Revisit weakest topic (cont.)
- **Day 4**: Polish one project's README
- **Day 5**: Clean up repo structure
- **Day 6**: Rest
- **Day 7**: Rest

---

### PHASE 4 — MODERN AI & SPECIALIZATION

#### Week 12: Deep Learning Basics
- **Day 1**: Neural net architecture, layers
- **Day 2**: Activation functions, backprop intuition
- **Day 3**: Rest
- **Day 4**: PyTorch or TensorFlow setup
- **Day 5**: Build a small classifier
- **Day 6**: 🎯 **PROJECT / MILESTONE** — MNIST digit recognizer (CNN)
- **Day 7**: Project — write up results

#### Week 13: NLP Foundations
- **Day 1**: Tokenization
- **Day 2**: Embeddings
- **Day 3**: TF-IDF
- **Day 4**: Rest
- **Day 5**: Buffer / practice
- **Day 6**: Intro to Transformer architecture (conceptual)
- **Day 7**: Intro to Transformers (cont.)

#### Week 14: NLP & LLMs — Somali language project
> *Note: This one can seed your actual research paper.*
- **Day 1**: Hugging Face basics — pipelines
- **Day 2**: Hugging Face — pretrained models
- **Day 3**: Rest
- **Day 4**: Explore existing Somali NLP resources
- **Day 5**: 🎯 **PROJECT / MILESTONE** — Somali-language text classification/sentiment task
- **Day 6**: Project — evaluate & iterate
- **Day 7**: Project — write up results

---

### PHASE 5 — DEPLOYMENT

#### Week 15: MLOps
- **Day 1**: Wrap a model in FastAPI
- **Day 2**: FastAPI — request/response handling
- **Day 3**: Rest
- **Day 4**: Docker basics for your model
- **Day 5**: Dockerize your model
- **Day 6**: MLflow for experiment tracking
- **Day 7**: MLflow practice

#### Week 16: Capstone
> *Note: Pick your strongest project — ideally the Somali NLP or risk-classification one.*
- **Day 1**: Select & scope capstone project
- **Day 2**: Productionize the model
- **Day 3**: Rest
- **Day 4**: Deploy Streamlit app + FastAPI backend
- **Day 5**: Deploy (cont.) — test end-to-end
- **Day 6**: Write GitHub README with research/business impact framing
- **Day 7**: 🎯 **MILESTONE** — Reflect: this becomes the empirical backbone of your Somalia paper

---

## 💻 How to Use the Interactive Tracker

Open [`study-tracker.html`](file:///Users/elkenzi/learn/ml/study-tracker.html) in your browser to interactively check off tasks day by day:

```bash
open study-tracker.html
```

Progress automatically persists in your browser storage.

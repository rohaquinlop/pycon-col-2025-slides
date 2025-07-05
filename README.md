# complexipy Workshop – PyCon Colombia 2025

**A hands-on deep dive into Cognitive Complexity and the `complexipy` toolkit.**

> Led by [Robin Hafid Quintero Lopez (@rohaquinlop)](https://github.com/rohaquinlop)

---

## 📋 Workshop Overview
`complexipy` is a high-performance (Rust-powered) tool for analysing Python code using the modern **Cognitive Complexity** metric. In this workshop we will move beyond traditional cyclomatic complexity, learn how to interpret cognitive scores, and integrate automated checks into everyday workflows.

By the end you will be able to analyse, visualise, and **reduce** complexity across your projects.

---

## 🎯 Learning Objectives
- **Differentiate** between Cyclomatic and Cognitive Complexity.
- **Audit** Python code with the `complexipy` CLI & library.
- **Automate** complexity gates in CI using GitHub Actions.
- **Refactor** high-complexity functions to improve readability.
- **Generate & interpret** reports to guide continuous improvement.

---

## 🛠 Prerequisites
| Requirement            | Details                                                                   |
| ---------------------- | ------------------------------------------------------------------------- |
| Python                 | 3.8 or newer installed on your laptop                                     |
| Basic Python knowledge | Comfortable with functions, control-flow, and the CLI                     |
| `uv` (optional)        | [uv](https://docs.astral.sh/uv/) for lightning-fast dependency management |
| Git & GitHub           | Clone the repo and push PRs for the CI section                            |
| Editor                 | Your favourite editor – the VS Code extension will be showcased           |

---

## 🚀 Quick Start
Clone the workshop repository (replace `YOUR_USER` if you fork it):

```bash
git clone https://github.com/YOUR_USER/complexipy-workshop.git
cd complexipy-workshop
```

### 1. Create & activate a virtual environment

With **uv** (recommended):
```bash
uv venv
source .venv/bin/activate
uv sync --frozen
```

With **pip / venv**:
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 2. Run your first audit
```bash
complexipy .
```
You'll receive a table of functions ordered by Cognitive Complexity.

---

## 🗺️ Agenda
| Module | Topic                                           |
| ------ | ----------------------------------------------- |
| **1**  | Foundations of Code Complexity                  |
| **2**  | Introducing **complexipy**                      |
| **3**  | Workflow Integration (VS Code & GitHub Actions) |
| **4**  | Practical Refactoring & Wrap-up                 |

Each module includes a short lecture followed by a hands-on lab ⚡️.

---

## 🧪 Labs at a Glance
1. **Basic Analysis** – run `complexipy` on a real code base.
2. **VS Code Extension** – get instant complexity feedback while you type.
3. **GitHub Actions** – add `complexipy-action` to block high-complexity PRs.
4. **Refactoring Sprint** – apply guard clauses, extract methods, and watch the scores drop.

---

## 📝 Resources
- Slides: https://github.com/rohaquinlop/pycon-col-2025-slides (PDF & online)
- `complexipy` Docs: https://rohaquinlop.github.io/complexipy/
- Cognitive Complexity Whitepaper: https://www.sonarsource.com/resources/cognitive-complexity/

---

## 🙌 Acknowledgements

> **Questions?** Reach out on [GitHub](https://github.com/rohaquinlop) or [LinkedIn](https://www.linkedin.com/in/robin-hafid/).

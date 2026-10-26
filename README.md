# Hi, I'm Aadyant

### Explainable ML · Data engineering · Full-stack development

I'm a computer science student in New Delhi. I build applications that connect useful interfaces with backend systems, data analysis and machine learning.

My recent work spans skin-lesion classification research, an interactive data-quality workspace, and shared-expense software. I care about the details behind the demo: exact calculations, clear evidence, reproducible results and documented tradeoffs.

## Selected projects

### [Skin Lesion Classification & XAI](https://github.com/Aadyant-7/attention-based-skin-lesion-classification-xai)
**Computer vision research with traceable evaluation.**

Seven-class HAM10000 classification using pretrained networks, ensemble inference, CBAM attention and Grad-CAM explanations.

- Final six-model ensemble with saved predictions, class metrics and experiment records.
- Separate exploratory and lesion-disjoint evaluation protocols, with their limitations documented.
- Branch-level explanation gallery and a saved Grad-CAM atlas.

[Results and evaluation](https://github.com/Aadyant-7/attention-based-skin-lesion-classification-xai#final-retained-method-and-status) · [Explanation gallery documentation](https://github.com/Aadyant-7/attention-based-skin-lesion-classification-xai/blob/main/results/final_s83_xai/v1/README.md)

### [Data Quality Studio](https://github.com/Aadyant-7/intelligent-data-quality-framework)
**Understand a dataset before trusting it.**

A workspace for profiling CSV and Excel data, assessing completeness and duplicates, checking retail rules, investigating unusual records and exporting PDF reports.

- FastAPI, pandas, scikit-learn and PostgreSQL behind a React and Plotly dashboard.
- IQR, Z-score and Isolation Forest signals with row-level evidence.
- Three read-only retail examples online; the local version supports uploads. Anomaly flags remain separate from confirmed quality errors.

[Live demo](https://intelligent-data-quality-framework.vercel.app/) · [Technical documentation](https://github.com/Aadyant-7/intelligent-data-quality-framework/blob/main/docs/Documentation.md)

### [SplitNest](https://github.com/Aadyant-7/splitnest)
**Shared expenses, from the interface to deployment.**

A full-stack application for households and travel groups: record expenses, calculate exact INR splits, import CSV/XLSX statements and track group balances and monthly budgets.

- React and TypeScript interface backed by Java 21, Spring Boot, PostgreSQL and Redis.
- Group permissions, rotating refresh sessions, background imports and persistent financial history.
- Docker Compose and local Kubernetes delivery, GitHub Actions, Argo CD, Prometheus and Grafana.

[Architecture](https://github.com/Aadyant-7/splitnest/blob/main/docs/architecture.md) · [Demo walkthrough](https://github.com/Aadyant-7/splitnest/blob/main/docs/demo.md) · [Verification](https://github.com/Aadyant-7/splitnest/blob/main/docs/evidence/verification.md)

## Tools I use

| Area | Technologies used in these projects |
| :--- | :--- |
| Applications | Java, Spring Boot, Python, FastAPI, React, TypeScript |
| Data & ML | pandas, NumPy, scikit-learn, PyTorch, Plotly |
| Storage | PostgreSQL, SQLAlchemy, Redis |
| Delivery & operations | Docker, Kubernetes, GitHub Actions, Argo CD, Prometheus, Grafana |

## How I approach a project

Build a complete workflow, test the behavior that matters, and leave enough documentation for someone else to run it and inspect the results.

Alongside these projects, I practice [data structures and algorithms in Java](https://github.com/Aadyant-7/neetcode-submissions).

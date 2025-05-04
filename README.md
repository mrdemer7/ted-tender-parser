# 🚀 Mini TED Tender Parser MVP

An AI-powered tender analysis system that extracts, processes, and matches TED-style tenders with internal references and displays them in a responsive Streamlit dashboard.

---

## 🔗 Google Colab Links

- **Testing Notebook**  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-0-L4kfnb8hzu7jQRMDgkEMUiQFW43FF#scrollTo=AJ73l1wOLp6O)

![Testing Notebook](https://i.imgur.com/djBvU5P.png)

- **Final Notebook (Fully Integrated)**  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10Hb246jX23ai9dThcC7VlzlaLEnuNoDK#scrollTo=eSYo7UrlKaRs)

![Final Notebook](https://i.imgur.com/xxBZlOP.png)
---

## ✨ Features

- **GPT-Powered Extraction** of:
  - Project Name
  - Location
  - Budget (Kostengruppen 300 + 400)
  - Project Type
  - Phases
  - Submission Deadline

- **Reference Matching**:
  - Cosine similarity-based scoring
  - GPT explanation for match reasoning (mocked or real)

- **Interactive Streamlit Dashboard**:
  - Filter tenders by location, project type, and budget
  - View detailed tender info and top 3 matches
  - CSV export for filtered tenders

- **Automation Simulation**:
  - Scheduled reprocessing of "new tenders" folder using Python `schedule` (bonus)

---

## 🎯 Objective

Build a simplified version of the TED Tender Parser system to demonstrate:

- Data parsing using GPT
- Reference matching using semantic logic
- Visual results in an interactive dashboard

---

## 🧪 Setup Instructions

1. **Clone the repo:**

```bash
git clone https://github.com/yourusername/ted-tender-parser.git
cd ted-tender-parser

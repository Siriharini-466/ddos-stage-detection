# 🚨 DDoS Attack Detection & Stage Classification using Random Forest

This project uses machine learning to detect Distributed Denial of Service (DDoS) attacks and classify them into stages — Early, Ongoing, and Intense — using the Random Forest algorithm. The system is built using flow-based network traffic analysis on the CICIDS2017 dataset.

## 📁 Folder Structure

```
ddos-complete-project/
├── README.md
├── notebooks/
│   └── ddos_stage_detection.ipynb
├── dataset/
│   └── friday_ddos_traffic.csv
├── docs/
│   ├── final_report.pdf
│   └── documentation_paper.pdf
├── presentation/
│   └── project_ppt.pptx
```

## 📄 Project Components

- ✅ Jupyter Notebook: Source code for preprocessing, model training, and stage classification.
- 📊 Dataset: Network traffic sample from CICIDS2017 used for training/testing.
- 📄 Final Report: Detailed documentation of project design, implementation, and results.
- 🧾 Documentation Paper: IEEE-style formatted research paper.
- 📽 Presentation: Project summary slides.

## 🚀 How to Use

1. Open the Jupyter notebook located in `notebooks/`.
2. Run all cells to load the dataset and classify traffic.
3. Review performance metrics and visualizations for the attack stages.
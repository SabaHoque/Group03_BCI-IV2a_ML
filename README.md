# Graph Neural Network-Based Motor Imagery EEG Classification Using BCI Competition IV Dataset 2a

This repository contains the implementation, reports, and experimental results for our Brain–Computer Interface (BCI) course project on **Motor Imagery EEG Classification** using the **BCI Competition IV Dataset 2a**. The project investigates **Graph Neural Networks (GNNs)** for classifying four-class motor imagery EEG signals and compares the proposed approach with several baseline models.



# 👥 Group Information

**Group:** Group03

**Department:** Computer Science and Engineering  
**University:** East West University

| Name | Email |
|------|-------|
| **Sababa Hoque Saba** | 2026-2-74-003@std.ewubd.edu |
| **Shayma Binte Hamid** | 2026-2-74-018@std.ewubd.edu |
| **Fathhur Rahman Sams** | 2026-2-74-016@std.ewubd.edu |



# 📊 Dataset

**Dataset:** BCI Competition IV – Dataset 2a

The dataset is a benchmark for **4-class Motor Imagery EEG Classification**.

## Dataset Summary

- **Classes:** Left Hand, Right Hand, Both Feet, Tongue
- **Subjects:** 9
- **Sessions:** 2 per subject
- **EEG Channels:** 22
- **EOG Channels:** 3
- **Sampling Rate:** 250 Hz
- **Training Files:** A01T.gdf – A09T.gdf
- **Testing Files:** A01E.gdf – A09E.gdf

**Dataset Link**

https://www.kaggle.com/datasets/thngdngvn/bci-competition-iv-data-sets-2a



# 🎯 Project Track

**Track 1 – Graph Neural Network (GNN)**

This project explores graph-based deep learning for EEG signal classification.

The workflow includes:

- Exploratory Data Analysis (EDA)
- Baseline Machine Learning Models
- Proposed Graph Neural Network
- Model Improvement
- Ablation Study
- Explainability Analysis (XAI)



# 📂 Repository Structure

```text
Group03_BCI_IV2a_ML/
│
├── README.md
│
├── report/
│   ├── task1/
│   │   └── Group03_BCI_IV_2a_task1_report.pdf
│   │
│   ├── task2/
│   │   ├── Group03_BCI_IV_2a_task2_report.pdf
│   │
│   ├── task3/
│   │   └── Group03_BCI_IV_2a_task3_report.pdf
│   │
│   └── task4/
│       └── Group03_BCI_IV_2a_final_report.pdf
│
├── code/
│   ├── task1/
│   │   └── Group03_BCI_IV_2a_task1_eda.ipynb
│   │
│   ├── task2/
│   │   ├── Group03_BCI_IV_2a_task2_baselines.ipynb
│   │   └── Group03_BCI_IV_2a_task2_proposed_model.ipynb
│   │
│   └── task3/
│       ├── Group03_BCI_IV_2a_task3_improvement_ablation.ipynb
│       └── Group03_BCI_IV_2a_task3_explainability.ipynb
│
├── related_work/
│   ├── Group03_BCI_IV_2a_related_work_table.pdf
│ 
└── models/
    ├── Group03_BCI_IV_2a_best.pth
    ├── checkpoint.pth
    └── label_map.json


# 🚀 How to Run

## 1. Clone the Repository

```bash
git clone https://github.com/SabaHoque/Group03_BCI-IV2a_ML.git
```

## 2. Navigate to the Repository

```bash
cd Group03_BCI-IV2a_ML
```

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 4. Download the Dataset

Download the BCI Competition IV Dataset 2a from:

https://www.kaggle.com/datasets/thngdngvn/bci-competition-iv-data-sets-2a

Extract the dataset into the appropriate data directory used by the notebooks.

## 5. Execute the Tasks

Run the notebooks in the following order:

### Task 1
- `code/task1/Group03_BCI_IV_2a_task1_eda.ipynb`

### Task 2
- `code/task2/Group03_BCI_IV_2a_task2_baselines.ipynb`
- `code/task2/Group03_BCI_IV_2a_task2_proposed_model.ipynb`

### Task 3
- `code/task3/Group03_BCI_IV_2a_task3_improvement_ablation.ipynb`
- `code/task3/Group03_BCI_IV_2a_task3_explainability.ipynb`

---

# 📈 Results

The proposed Graph Neural Network is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Cohen's Kappa
- Five-Fold Cross Validation

The performance is compared against baseline machine learning and deep learning models to demonstrate the effectiveness of the proposed approach.

The best trained model is stored in:

```
models/Group03_BCI_IV_2a_best.pth
```

---

# 📄 Reports

The repository contains reports for all project tasks:

| Task | Description |
|------|-------------|
| **Task 1** | Exploratory Data Analysis (EDA) |
| **Task 2** | Baseline Models and Proposed GNN |
| **Task 3** | Model Improvement, Ablation Study, and Explainability |
| **Task 4** | Final IEEE Journal-Style Report |



# 📚 Related Work

The `related_work/` directory contains:

- Literature review comparison table
- Five selected research papers
- Research gap analysis used to motivate the proposed GNN model


# 🧠 Trained Models

The `models/` directory contains:

- Best trained model (`.pth`)
- Training checkpoint
- Label mapping file (`label_map.json`)




## License

This repository is intended for academic and educational purposes.

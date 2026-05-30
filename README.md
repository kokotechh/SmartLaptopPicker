# 💻 SmartLaptopPicker

A machine learning project that classifies laptops into categories based on their hardware specs.
Built as a personal learning project to practice the full ML pipeline from data exploration to model evaluation.

---

## 📌 Project Goal
Given a laptop's specs (GPU, RAM, Processor), predict which category it belongs to:
- 🔴 High Gaming
- 🟠 Gaming
- 🟡 Gaming-Office
- 🟢 Office

---

## 📊 Dataset
- **Source:** [Brand Laptops Dataset - Kaggle](https://www.kaggle.com/datasets/bhavikjikadara/brand-laptops-dataset)
- **Size:** 991 laptops, 22 features

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (Random Forest Classifier)

---

## 🔄 ML Pipeline
1. Load & explore the data (EDA)
2. Create category labels using domain knowledge
3. Drop useless columns
4. One Hot Encoding for text columns
5. Split data (80% train / 20% test)
6. Train Random Forest Classifier
7. Evaluate the model

---

## 📈 Results
| Metric | Score |
|---|---|
| Overall Accuracy | 98.5% |
| Gaming F1-Score | 0.98 |
| Office F1-Score | 1.00 |

---

## ⚠️ Known Limitations
- High Gaming category has limited data (only 28 laptops) which affects recall (70%)
- Future improvement: collect more High Gaming laptop data or use SMOTE to balance classes

---

## 👩‍💻 Built by
**kokotechh** — learning ML one project at a time 💪

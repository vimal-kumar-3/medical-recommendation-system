#  Medical Recommendation System

This project is based on medical recommendation system that predicts possible diseases based on user-provided symptoms and provides:

-  Disease prediction  
-  Disease description  
-  Medicines  
-  Diet plans  
-  Workout suggestions  
-  Precautionary measures  

---

##  Technologies Used
- Python  
- Machine Learning (SVC Model)  
- scikit-learn  
- pandas, numpy, matplotlib  
- Jupyter Notebook  

---

##  Project Structure
```
Medical_Recommendation_System/
│
├── medical_recommendation.ipynb
├── svc.pkl
├── requirements.txt
├── README.md
│
└── Medical_Datasets/
├── Training.csv
├── precautions_df.csv
├── workout_df.csv
├── description.csv
├── medications.csv
├── diets.csv
├── symtoms_df.csv
```

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/medical-recommendation-system.git
   cd medical-recommendation-system
   
2. Install all dependencies:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook medical_recommendation.ipynb
```

4. Follow the on-screen prompts to enter symptoms and get predictions.

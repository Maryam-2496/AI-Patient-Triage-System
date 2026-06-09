🏥 AI Patient Triage System

An intelligent healthcare application that automates patient triage using Machine Learning. The system predicts patient urgency levels based on symptoms and provides the shortest hospital route using BFS pathfinding.

Features
🤖 Symptom classification using KNN
📝 TF-IDF text vectorization
🚨 Urgency prediction (Mild, Moderate, Critical)
🗺️ BFS-based hospital routing
📊 Patient records and analytics
🎨 Modern Streamlit dashboard
Technologies Used
Python
Streamlit
Scikit-Learn
Pandas
K-Nearest Neighbors (KNN)
TF-IDF Vectorizer
Breadth-First Search (BFS)
Project Structure
AI-Patient-Triage-System/
│
├── ai_app.py
├── bfs.py
├── train_model.py
├── ai_style.py
├── triage_dataset.csv
├── knn_model.pkl
├── vectorizer.pkl
├── confusion_matrix.png
└── README.md
Installation
1. Clone Repository
git clone https://github.com/yourusername/AI-Patient-Triage-System.git
cd AI-Patient-Triage-System
2. Create Virtual Environment
python -m venv venv

Activate:

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate
3. Install Dependencies
pip install streamlit pandas scikit-learn matplotlib
Train the Model (Optional)

If you want to retrain the model:

python train_model.py

This will:

Train the KNN classifier
Generate the confusion matrix
Save:
knn_model.pkl
vectorizer.pkl
Run the Application
streamlit run ai_app.py

After running, open:

http://localhost:8501
How It Works
Enter patient details and symptoms.
Symptoms are converted into numerical features using TF-IDF.
KNN predicts the urgency level.
Patients are categorized as:
Mild
Moderate
Critical
BFS algorithm finds the shortest route from Reception to the assigned department.
Results are displayed through the Streamlit dashboard.
Future Improvements
Deep Learning-based symptom analysis
Larger medical datasets
Real hospital floor mapping
Database integration
Doctor recommendation system
Multi-language support
Author

Developed as an Artificial Intelligence and Healthcare Informatics project demonstrating Machine Learning classification and graph search algorithms for hospital triage management.

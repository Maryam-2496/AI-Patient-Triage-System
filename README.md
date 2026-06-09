# 🏥 AI Patient Triage System

An intelligent healthcare application that automates patient triage using Machine Learning. The system predicts patient urgency levels based on symptoms and provides the shortest hospital route using BFS pathfinding.

---

## 🎥 Demo 

<img width="400" height="191" alt="Screen Recording 2026-06-09 115026" src="https://github.com/user-attachments/assets/6313641f-304d-4f49-80c9-bbb91c42c6e0" />

---

## 📸 Screenshots

### Home Dashboard

<img width="1898" height="907" alt="image" src="https://github.com/user-attachments/assets/6d0027fd-4d6c-435e-90ec-aece3042164b" />
<img width="1871" height="911" alt="image" src="https://github.com/user-attachments/assets/4089ea44-8e73-49a8-a333-e1b7749cef58" />


### Patient Triage Prediction

<img width="1882" height="887" alt="image" src="https://github.com/user-attachments/assets/1a7f3ee9-9696-4b7d-9125-6fbc6d1c6646" />
<img width="1878" height="882" alt="image" src="https://github.com/user-attachments/assets/762e5cab-af24-429a-b009-a2f4505f99ce" />


### Model Performance
<img width="1338" height="820" alt="image" src="https://github.com/user-attachments/assets/b24d6e6f-a11d-4c90-8f12-ae0b6b3e151d" />
<img width="1393" height="522" alt="image" src="https://github.com/user-attachments/assets/34e23337-0e8b-4c10-a8ea-b6748b9f222f" />

### hospital route

<img width="1217" height="277" alt="image" src="https://github.com/user-attachments/assets/db23ed5f-a3dc-4bc7-bfef-287d669922f8" />

---

##  Features

* 🤖 Symptom classification using KNN
* 📝 TF-IDF text vectorization
* 🚨 Urgency prediction (Mild, Moderate, Critical)
* 🗺️ BFS-based hospital routing
* 📊 Patient records and analytics
* 🎨 Modern Streamlit dashboard

---

## 🛠️ Technologies Used

* Python
* Streamlit
* Scikit-Learn
* Pandas
* K-Nearest Neighbors (KNN)
* TF-IDF Vectorizer
* Breadth-First Search (BFS)

---

##  Project Structure

```text
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
```

---

##  Installation

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/AI-Patient-Triage-System.git
cd AI-Patient-Triage-System
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install streamlit pandas scikit-learn matplotlib
```

---

##  Train the Model (Optional)

If you want to retrain the model:

```bash
python train_model.py
```

This will:

* Train the KNN classifier
* Generate the confusion matrix
* Save:

  * knn_model.pkl
  * vectorizer.pkl

---

##  Run the Application

```bash
streamlit run ai_app.py
```

After running, open:

```text
http://localhost:8501
```

---

##  How It Works

1. Enter patient details and symptoms.
2. Symptoms are converted into numerical features using TF-IDF.
3. KNN predicts the urgency level.
4. Patients are categorized as:

   * Mild
   * Moderate
   * Critical
5. BFS algorithm finds the shortest route from Reception to the assigned department.
6. Results are displayed through the Streamlit dashboard.

---

##  Future Improvements

* Deep Learning-based symptom analysis
* Larger medical datasets
* Real hospital floor mapping
* Database integration
* Doctor recommendation system
* Multi-language support

---

##  Disclaimer

This project is created for educational and learning purposes only. It is not intended for real medical diagnosis or healthcare decision-making.

---

## 👨‍💻 Author

Developed as an Artificial Intelligence and Healthcare Informatics project demonstrating Machine Learning classification and graph search algorithms for hospital triage management.

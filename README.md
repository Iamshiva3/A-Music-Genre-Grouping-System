# 🎵 SoundSort — Intelligent Music Genre Classification & Clustering

SoundSort is a machine learning-powered web application that analyzes audio characteristics and automatically groups music tracks into meaningful genre-based clusters. The system combines **K-Means Clustering**, **silhouette score optimization**, and **rule-based genre classification** to categorize songs using rhythmic and acoustic features such as tempo, energy, and danceability.

## 🚀 Features

### 🎯 Intelligent Music Clustering

* Uses **K-Means Clustering** to group tracks with similar audio characteristics.
* Automatically determines the optimal number of clusters using **Silhouette Score Analysis**.

### 🎼 Dynamic Genre Classification

* Assigns genre labels such as:

  * EDM
  * Rock
  * Pop
  * Chill
* Classification is based on audio features including:

  * Energy
  * Tempo (BPM)
  * Danceability

### 📊 Interactive Data Visualization

* Generates real-time cluster visualizations.
* Displays genre distribution through informative charts and graphs.
* Helps users understand relationships between different music groups.

### 📁 CSV Export Support

* Export processed datasets with predicted cluster and genre labels.
* Useful for further analysis and reporting.

## 🛠️ Technology Stack

| Category           | Technologies                           |
| ------------------ | -------------------------------------- |
| Backend            | Flask, Python                          |
| Machine Learning   | Scikit-learn                           |
| Data Processing    | Pandas, NumPy                          |
| Data Visualization | Matplotlib                             |
| Algorithm          | K-Means Clustering, Silhouette Scoring |

## 🏗️ Project Workflow

1. Upload a music dataset containing audio features.
2. Preprocess and clean the data.
3. Determine the optimal number of clusters using Silhouette Analysis.
4. Apply K-Means Clustering to group similar tracks.
5. Assign genre labels using rule-based classification logic.
6. Visualize clusters and genre distributions.
7. Export the final dataset with predicted labels.

## 📸 Key Outputs

* Cluster Visualization Plot
* Genre Distribution Chart
* Processed Dataset with Genre Labels
* Downloadable CSV Report

## ⚙️ Installation & Setup

### Prerequisites

* Python 3.8+
* pip

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

### Access the Application

Open your browser and navigate to:

```text
http://127.0.0.1:8080
```

## 📂 Project Structure

```text
SoundSort/
│
├── app.py
├── requirements.txt
├── static/
├── templates/
├── uploads/
├── outputs/
└── README.md
```

## 🎯 Future Enhancements

* Deep Learning-based genre prediction
* Audio file upload and feature extraction
* Real-time music recommendation engine
* Advanced dashboard with interactive analytics
* Support for additional music genres

## 👨‍💻 Author

Developed as a Machine Learning and Data Analytics project demonstrating clustering, classification, data visualization, and web application development using Python and Flask.

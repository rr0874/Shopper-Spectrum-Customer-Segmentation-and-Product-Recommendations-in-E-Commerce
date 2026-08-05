# Shopper-Spectrum-Customer-Segmentation-and-Product-Recommendations-in-E-Commerce
# 🛒 Shopper Spectrum

**Shopper Spectrum** is an E-Commerce intelligence project that combines customer segmentation and personalized product recommendations using machine learning.

Built with **Python, Scikit-learn, and Streamlit**, this project helps online businesses:
- Predict customer segments (based on RFM analysis)
- Recommend similar products (based on item-based collaborative filtering)

---

## 📌 Features

### 🎯 1. Customer Segmentation
- Inputs: **Recency**, **Frequency**, **Monetary** values
- Outputs: Cluster label (e.g., High-Value, Regular, At-Risk)

### 🛍️ 2. Product Recommendation
- Input: Product name (e.g., "WHITE HANGING HEART T-LIGHT HOLDER")
- Output: 5 similar products based on cosine similarity

---

## 🔧 Tech Stack

- **Streamlit** – Web app framework
- **Scikit-learn** – KMeans Clustering, StandardScaler
- **Pandas & NumPy** – Data manipulation
- **Joblib** – Model saving/loading
- **Collaborative Filtering** – For recommendation system

---

## 🚀 Getting Started

### 🔗 [Live App on Streamlit Cloud](https://your-username-shopper-spectrum.streamlit.app)

### Or Run Locally:

1. Clone this repository:

```bash
git clone https://github.com/your-username/Shopper-Spectrum.git
cd Shopper-Spectrum
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the app:

```bash
streamlit run app.py
```

---

## 📁 Project Structure

```
Shopper-Spectrum/
├── app.py
├── rfm_kmeans_model.pkl
├── rfm_scaler.pkl
├── rfm_clustered.csv
├── product_similarity_matrix.csv
├── product_description_map.csv
├── requirements.txt
├── README.md
```
---

## 🙋‍♀️ Team

- 👩‍💻 Radhika Raut (Developer & ML Engineer)
- ✨ Built as part of a Machine Learning Capstone Project

---



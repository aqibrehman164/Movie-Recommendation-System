# 🎥 Movie Recommendation System Portfolio Project

### By Malik Aqib Rehman

This project focuses on developing a robust **Movie Recommendation System** by leveraging cutting-edge machine learning and deep learning techniques. The system implements various recommendation methodologies and demonstrates their effectiveness through rigorous evaluation metrics.

---

## 🚀 Key Features

- **Content-Based Filtering**: Recommends movies based on similar attributes (e.g., genres, keywords, or metadata).
- **Collaborative Filtering**: Suggests movies based on user interactions and ratings.
- **Deep Learning Approach (Neural Collaborative Filtering - NCF)**: Uses neural networks to capture complex user-movie interactions.

---

## 🌟 Introduction

In the digital age, recommendation systems play a crucial role in personalizing user experiences. They drive engagement and satisfaction across various platforms, including:

- **40%** of app installs on Google Play are influenced by recommendations.
- **60%** of watch time on YouTube comes from suggested content.
- **35%** of Amazon purchases are based on recommendations.
- **75%** of Netflix views stem from personalized suggestions.

This project demonstrates the implementation of multiple recommendation approaches, including **Neural Collaborative Filtering (NCF)**, to deliver accurate and personalized movie recommendations.

---

## 📊 Methodology

1. **Loading Files and Libraries**:
   - Processed datasets including movie credits, keywords, ratings, and metadata.
   - Libraries used: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, and deep learning frameworks.

2. **Exploratory Data Analysis (EDA)**:
   - Performed in-depth analysis to uncover key insights.
   - Visualized relationships between features using correlation heatmaps and other tools.

3. **Data Preprocessing**:
   - Cleaned and prepared data for machine learning and deep learning models.

4. **Model Building**:
   - Implemented **Content-Based Filtering**, **Collaborative Filtering**.
   - Developed a **Neural Collaborative Filtering (NCF)** model for advanced recommendations.

5. **Evaluation**:
   - Compared models using metrics like RMSE and MAE.
   - Highlighted the strengths and weaknesses of each approach.

---

## 🧠 Model Performance and Insights

### 🔢 Predicted Ratings
- **NCF Model**: Predicted ratings are scaled between 0 and 1 using a sigmoid activation function.
  - Values closer to **1** indicate stronger recommendations.

### 📈 NCF vs Collaborative Filtering (CF) Using SVD
| Metric         | NCF Model | CF Model (SVD) |
|----------------|-----------|----------------|
| **RMSE**       | **0.1964**| 0.8403         |

- **Improvement**: The NCF model significantly reduces RMSE, showcasing its ability to capture complex user-movie interactions through non-linear transformations.

### 🔍 Recommendations and Insights
- **Model Accuracy**: The NCF model demonstrates superior predictive accuracy by leveraging latent factors and neural network architecture.
- **Diverse Recommendations**: Generates highly relevant suggestions tailored to user preferences across different genres.
- **Further Enhancements**:
  - Hyperparameter tuning (e.g., network depth, latent factors).
  - Integration of additional features (e.g., movie metadata, user demographics).

---

## 🛠 Installation Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Movie-Recommendation-System.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook Portfolio_Movie_Recommender_System_Cleaned.ipynb
   ```

---

## 📂 Project Files

- **Portfolio_Movie_Recommender_System_Cleaned.ipynb**: Main project notebook.
- **requirements.txt**: List of required Python libraries.
- **README.md**: Comprehensive documentation of the project.
- **Data Folder**: Contains processed and raw datasets (if available, specify download instructions).

---

## 🌍 Conclusion

The **Neural Collaborative Filtering (NCF)** model demonstrates superior performance, significantly outperforming traditional collaborative filtering methods like SVD. By leveraging neural network architectures, the NCF model effectively captures intricate user-item interactions, making it an ideal solution for personalized movie recommendations.

### Future Work
- Enhance model performance with additional hyperparameter tuning.
- Incorporate more features such as user demographics and advanced movie metadata.
- Explore reinforcement learning for dynamic, real-time recommendations.

---

### 📬 Contact

For questions, suggestions, or collaborations, feel free to reach out at [aqibrehman164@gmail.com].

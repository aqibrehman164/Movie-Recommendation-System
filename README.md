# Movies Recommender System Portfolio Project

### By Malik Aqib Rehman

This project implements various approaches to build a Movies Recommendation System, including:

- **Content Filtering**
- **Collaborative Filtering**
- **Deep Learning Approaches**: Neural Collaborative Filtering

## Introduction

In today's era of diverse entertainment choices, the role of a Movies Recommendation System cannot be overstated. This innovative system is designed to provide users with tailored suggestions for movies, music, and more, enhancing their overall experience. 

### Why Recommendation Systems Matter:
- **40%** of app installs on Google Play are influenced by recommendations.
- **60%** of watch time on YouTube is driven by suggested content.
- **35%** of purchases on Amazon come from recommendations.
- **75%** of movies watched on Netflix are recommended to users.

In this context, this project explores and implements four potent methodologies:
1. **Content Filtering** - Analyzing movie attributes to recommend similar ones.
2. **Collaborative Filtering** - Leveraging user interactions to suggest movies.
3. **Hybrid Approach** - Combining the strengths of both Content and Collaborative Filtering.
4. **Neural Collaborative Filtering** - Using Deep Learning techniques for enhanced recommendations.

## Methodology

1. **Loading Files and Libraries**
   - Various datasets were used, including movie credits, keywords, and ratings.
   - Libraries such as pandas, numpy, matplotlib, and scikit-learn were utilized.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed the structure and key trends in the data.
   - Visualized important relationships using correlation heatmaps, bar plots, etc.
   - Observed that variables like vote count and popularity had significant positive correlations with financial performance.

3. **Data Preprocessing**
   - Cleaned and transformed raw data to prepare it for analysis and modeling.

4. **Building the Models**
   - Implemented both traditional machine learning and deep learning techniques to create effective recommendation systems.

## Visualization and Insights

### Correlation Heatmap of Numerical Features:
Key insights:
- **Vote Count** and **Popularity** are positively correlated with better financial performance.
- The heatmap and analysis help guide decisions to fine-tune metrics for recommendations.

## Installation Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Movie-Recommendation-System.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Portfolio_Movie_Recommender_System_Cleaned.ipynb
   ```

## Project Files

- **Portfolio_Movie_Recommender_System_Cleaned.ipynb**: Main project notebook.
- **requirements.txt**: List of required libraries.
- **README.md**: Documentation for the project.
- **Data Folder**: Contains the datasets used (not included in this repository, provide instructions to download if applicable).

## Future Enhancements

- Extend the system to include real-time recommendation capabilities.
- Explore reinforcement learning techniques for recommendations.

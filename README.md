
# Swiggy Restaurant Recommendation System

## Project Overview
The **Swiggy Restaurant Recommendation System** leverages **Machine Learning and Streamlit** to help users find top restaurant recommendations based on **city, cuisine, rating, and cost**. By applying **K-Means clustering**, this project provides personalized suggestions for an enhanced dining experience.

## Features
- **Personalized Recommendations**: Suggests top restaurants based on user input.
- **Clustering with K-Means**: Groups restaurants based on similarity.
- **Streamlit Web App**: Interactive interface for users to input preferences and view recommendations.
- **Business Insights**: Helps restaurants and users make informed decisions.

## Tech Stack
- **Python**: Core programming language.
- **Pandas, NumPy**: Data manipulation and processing.
- **Scikit-Learn**: Machine learning algorithms for clustering.
- **Matplotlib, Seaborn, Plotly**: Data visualization.
- **Streamlit**: Web application for interactive UI.
- **Pickle**: Model and encoder serialization.

## Dataset
The dataset contains **148,455 restaurant records** with the following key features:
- **City**: Location of the restaurant.
- **Cuisine**: Type of food served.
- **Rating & Rating Count**: Customer reviews.
- **Cost**: Approximate cost for two people.
- **Restaurant Name, Address, Menu Link**.

## Implementation Steps
### Data Preprocessing
- Handled missing values and duplicates.
- Converted categorical features using **One-Hot Encoding** and **Label Encoding**.
- Scaled numerical features using **StandardScaler**.

### Model Training (K-Means Clustering)
- Used **Elbow Method** to determine the optimal **K=4**.
- Evaluated model performance using **Silhouette Score (0.6256 for K=4)**.
- Explored **K=100**, which had a slightly higher score (0.6677) but was less interpretable.

### Recommendation System
- Predicted the **restaurant cluster** based on user inputs.
- Mapped clustered recommendations back to the original dataset.
- Displayed **Top 10 personalized recommendations** with names and links.

### Streamlit Integration
- Built an **interactive UI** for seamless user experience.
- Users input preferences like city, cuisine, rating, and cost to get tailored recommendations.

## Project Demo
**Live Streamlit App**: 


## Business Use Cases:
- **Personalized Recommendations**: Help users discover restaurants based on their preferences.
- **Improved Customer Experience**: Provide tailored suggestions to enhance decision-making.
- **Market Insights**: Understand customer preferences and behaviors for targeted marketing.
- **Operational Efficiency**: Enable businesses to optimize their offerings based on popular preferences.


##  Future Enhancements
- Implement **Deep Learning models** for more refined recommendations.
- Incorporate **Collaborative Filtering** for user-based suggestions.
- Deploy the **Streamlit app** to cloud platforms.


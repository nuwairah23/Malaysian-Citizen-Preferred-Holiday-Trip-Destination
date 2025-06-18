# Malaysian Citizens Preferred Holiday Trip Destinations

## Project Overview

This project aims to assist Malaysian citizens in selecting their ideal domestic holiday destinations using machine learning techniques. The model classifies user preferences and recommends suitable local destinations based on responses to a survey. The final product includes a data analysis component and a K-Nearest Neighbors (KNN) classification model with an achieved accuracy of 82%.



## Objectives

- **Design** an application system that visualizes and recommends holiday destinations preferred by Malaysians.
- **Develop** the system using the K-Nearest Neighbors (KNN) classification algorithm.
- **Test** the system for performance and usability.

## Target Users

- Malaysian citizens planning local holidays
- Travel agencies aiming to better understand local preferences

## Dataset

- Collected via Google Forms from **698 respondents** between November 21–28, 2022
- Includes 17 questions (15 used for analysis)
- Features: Age, Budget, Activities, Preferred Destination Type, Transport, Accommodation, etc.
- Label: Preferred Destination Category (Island, Cultural Heritage, Town, Countryside)

## Tools and Technologies

- **Language**: Python
- **Platform**: Jupyter Notebook
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Data Analysis

Performed Exploratory Data Analysis (EDA) to extract insights:
- Budget vs. Age and Destination
- Stay duration across travel types
- Preferred activities and accommodations per destination
- Visualization tools: scatter plots, bar charts, line graphs

## Machine Learning Model

- **Algorithm**: K-Nearest Neighbors (KNN)
- **Preprocessing**:
  - Data cleaning and transformation
  - Label encoding for categorical variables
  - Manual train-test split (80:20)
- **Model Tuning**:
  - K-Fold Cross Validation
  - Feature Selection
  - Dataset balancing (oversampling and class reduction)

## Final Model Performance

| Dataset       | Accuracy |
|---------------|----------|
| Training Set  | 95.71%   |
| Testing Set   | 82.00%   |


## Key Findings

- Young Malaysians (<25) prefer islands.
- Cultural heritage sites are most preferred by users aged 25–45+.
- Leisure activities are popular across most destinations.
- Hotels are the most common accommodation, except on islands where resorts are much more preferred.

## Limitations & Recommendations

- Dataset was limited in class balance and quantity.
- Oversampling may risk overfitting.
- Future work should include collecting more data and exploring additional classification techniques for multi-class predictions.

## Team Members

- Nuwairah Aimi Binti Ahmad Kushairi
- Muhammad Taufeeq Hasnol
- Nur Eisyah Farihah Binti Mohd Dali
- Nur Amielia Natasha Binti Mohamad Nazli
- Aisyah Husna Binti Mohammad Jais


## License

This project is part of the **Special Topics in Computer Science (CSC649)** course and intended for academic purposes only.

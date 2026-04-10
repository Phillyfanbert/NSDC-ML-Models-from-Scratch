# "Homemade" Machine Learning

## Project Overview
Led a team of eight as the Project Lead to execute a comprehensive seven-week machine learning study. The objective was to build several core machine learning algorithms from scratch using only NumPy and implement them to predict the **Catch Rate** of Pokémon based on their base statistics (Attack, Defense, Speed, etc.). This "bottom-up" approach was designed to deepen understanding of algorithmic architecture and optimization.

## Tech Stack
* **Language:** Python
* **Environment:** Google Colab
* **Libraries:** NumPy (for algorithm implementation), Pandas, Matplotlib, Seaborn
* **Techniques:** Linear Regression, K-Nearest Neighbors (KNN), Decision Trees, Random Forest, Gradient Boosting, Heatmap Correlation Analysis

## Key Features & Workflow

### 1. Project Leadership & Management
* **Timeline Oversight:** Developed and maintained a strict seven-week project timeline, managing task delegation across two specialized sub-teams: Data Preprocessing/Visualization and Algorithm Implementation.
* **Stakeholder Reporting:** Acted as the primary liaison between the team and the project manager, incorporating feedback to ensure the project met club standards for the final showcase.

### 2. Data Exploration & Preparation
* **Sourcing:** Utilized a Pokémon dataset from Kaggle containing 721 entries and 22 distinct features.
* **EDA:** Conducted thorough exploratory analysis, identifying that **Total Stats** and **Special Attack** had the highest correlation with Catch Rate. Discovered that body type (e.g., bipedal with a tail) significantly influenced catchability.
* **Engineering:** Transformed categorical variables into longform numerical representations to ensure compatibility with regressor models.

### 3. "Homemade" Algorithm Implementation
Built the following models from the ground up using fundamental mathematical principles:
* **Linear & KNN Regression:** Developed using standard distance and gradient methods.
* **Decision Trees & Random Forest:** Built logic for tree splitting and ensemble aggregation (bagging) to reduce variance.
* **Gradient Boosting:** Implemented sequential boosting using weak learners (stumps) to capture residual errors.

### 4. Benchmarking & Evaluation
Compared the performance of the "Homemade" models against industry-standard `scikit-learn` implementations using **$R^2$** and **Mean Absolute Error (MAE)**:
* **Parity:** The homemade Linear Regression and KNN models achieved performance almost identical to `sklearn`.
* **Outperformance:** The custom **Random Forest** model outperformed the `sklearn` equivalent in this specific use case.
* **Refinement:** The Decision Tree and Gradient Boosting models showed slightly higher MAE than `sklearn`, identifying areas for further optimization in tree-depth logic.

## Summary of Findings
* **Model Effectiveness:** Random Forest emerged as the strongest predictor, effectively capturing complex feature interactions between Pokémon stats and catch rates.
* **Technical Insight:** Successfully demonstrated that custom-built algorithms can reach professional-grade accuracy, proving the effectiveness of the team's underlying logic and implementation.

## Repository Content
* `NSDC_Spring2025_MLProject.ipynb`: Complete implementation code for all "Homemade" models and comparison benchmarks.
* `NSDC Spring 2025 Project Showcase.pptx`: Professional slideshow detailing the methodology, visualizations, and comparative results.
* `Full Project Timeline.pdf`: The structural roadmap used to manage team milestones and deliverables.

---
*Developed as the Project Lead for the National Student Data Corps (NSDC) (March 2025 - May 2025).*

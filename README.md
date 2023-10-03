# Mall Customer Segmentation
Internship Task to segment custumers using machine learnin

> A comprehensive data analysis project for segmenting customers in a mall based on their spending behavior and demographics.


## Table of Contents

- [Mall Customer Segmentation](#mall-customer-segmentation)
  - [Project Overview](#project-overview)
  - [Key Objectives](#key-objectives)
  - [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Project Structure](#project-structure)
- [Data](#data)
  - [Data Source](#data-source)
  - [Data Description](#data-description)
- [Analysis](#analysis)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Data Preprocessing](#data-preprocessing)
  - [Feature Scaling](#feature-scaling)
  - [Dimensionality Reduction](#dimensionality-reduction)
  - [Clustering](#clustering)
- [Results](#results)
  - [Cluster Characteristics](#cluster-characteristics)
  - [Visualization](#visualization)
- [Marketing Insights](#marketing-insights)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

The Mall-Customer-Segmentation project is an in-depth exploration of customer data from a mall. The goal is to gain insights into customer behavior and preferences by segmenting customers into distinct groups based on their spending patterns and demographic information. This analysis enables targeted marketing strategies and personalized customer engagement.

---

## Key Objectives

- Segment customers into meaningful groups to better understand their behavior.
- Provide actionable insights for marketing strategies.
- Optimize customer engagement and satisfaction.

---

## Technologies Used

The following technologies and libraries were used in this project:

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- Yellowbrick

---

## Getting Started

### Prerequisites

Before running the analysis, ensure you have the following prerequisites:

- Python (version 3.x)
- Jupyter Notebook
- Required Python libraries (NumPy, Pandas, Matplotlib, Seaborn, scikit-learn, Yellowbrick)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Md-Awaf/Mall-Customer-Segmentation.git
   ```

2. Navigate to the project directory:

   ```bash
   cd mall-customer-segmentation
   ```

3. Install the required Python libraries if not already installed:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn yellowbrick
   ```

---

## Project Structure

The project directory is organized as follows:

- `customer_segmentation_analysis.ipynb`: Jupyter Notebook containing the analysis code.
- `Mall_Customers.csv`: download from [kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- `LICENSE`: MIT License file.
- `README.md`: Project README file (this file).

---

## Data

### Data Source

The dataset used for this analysis was obtained from [kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).

### Data Description

The dataset contains the following columns:

- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer (e.g., Male, Female).
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: A score assigned to the customer based on their spending behavior and other factors.

---

## Analysis

The analysis process includes the following steps:

### Exploratory Data Analysis (EDA)

- Initial exploration of the dataset to understand its structure and characteristics.
- Visualization of data distributions and relationships.

### Data Preprocessing

- Handling missing values (if any).
- Removing outliers that may impact the analysis.
- Encoding categorical variables (e.g., gender) for machine learning.

### Feature Scaling

- Standardizing features to ensure consistent scaling.

### Dimensionality Reduction

- Using PCA (Principal Component Analysis) for dimensionality reduction.
- Visualizing data in reduced dimensions.

### Clustering

- Utilizing K-Means clustering to segment customers into distinct groups.
- Determining the optimal number of clusters using the Elbow Method.
- Assigning cluster labels to each customer.

---

## Results

### Cluster Characteristics

The analysis identifies clusters with distinct characteristics:

- **Cluster 0**: Moderate Annual Income, Low Spending Score.
- **Cluster 1**: High Annual Income, High Spending Score.
- **Cluster 2**: Low Annual Income, Low Spending Score.
- **Cluster 3**: Moderate Annual Income, Moderate Spending Score.

### Visualization

- Visualizing the customer segments using scatterplots and cluster centers.
- Additional visualization using PCA (Principal Component Analysis) and t-SNE (t-Distributed Stochastic Neighbor Embedding).

---

## Marketing Insights

The analysis provides valuable marketing insights:

- Target high-income, high-spending customers in Cluster 1 with premium products and personalized offers.
- Encourage spending among customers in Cluster 0, who have moderate income but low spending, through discounts or loyalty programs.
- Consider customers in Cluster 3 for general marketing campaigns due to their moderate spending habits.
- Monitor opportunities in Cluster 2, where customers have low income and low spending, for lower-priced products or promotions.

---

## Contributing

Contributions to this project are welcome! If you have any ideas for improvements or enhancements, please submit a pull request or open an issue.

---

## License

Distributed under the MIT License. See `LICENSE` for more information.

---
Feel free to customize this README to suit your project's specific details and requirements.

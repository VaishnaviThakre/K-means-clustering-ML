# K-Means Clustering on College Data

Welcome to the K-Means Clustering on College Data repository! This project applies K-Means clustering to a dataset of colleges to classify them based on various features. The main goal is to explore the data, visualize important relationships, and evaluate the performance of the clustering model.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Installation](#installation)
5. [Results](#results)
6. [Interpretation](#interpretation)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

This project utilizes the K-Means clustering algorithm to classify colleges into clusters based on various features like the number of applications received, graduation rate, student-to-faculty ratio, and more. The repository includes the code to load the dataset, preprocess it, visualize data relationships, apply K-Means clustering, and evaluate the model's performance.

## Dataset

The dataset `College_Data.csv` contains 777 entries of different colleges with the following columns:
- **Private**: Whether the college is private or public.
- **Apps**: Number of applications received.
- **Accept**: Number of applications accepted.
- **Enroll**: Number of new students enrolled.
- **Top10perc**: Percentage of new students from the top 10% of their high school class.
- **Top25perc**: Percentage of new students from the top 25% of their high school class.
- **F.Undergrad**: Number of full-time undergraduates.
- **P.Undergrad**: Number of part-time undergraduates.
- **Outstate**: Out-of-state tuition.
- **Room.Board**: Room and board cost.
- **Books**: Estimated book cost.
- **Personal**: Estimated personal spending.
- **PhD**: Percentage of faculty with Ph.D.'s.
- **Terminal**: Percentage of faculty with terminal degrees.
- **S.F.Ratio**: Student-to-faculty ratio.
- **perc.alumni**: Percentage of alumni who donate.
- **Expend**: Instructional expenditure per student.
- **Grad.Rate**: Graduation rate.

## Installation

To run the code in this repository, you need to have Python installed along with the following libraries:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

Clone the repository to your local machine:

```sh
git clone git@github.com:VaishnaviThakre/K-means-clustering-ML.git
cd K-means-clustering-ML
```



## Results

The clustering model was evaluated using a confusion matrix and classification report:
- **Confusion Matrix**:
  ```
  [[ 74 138]
   [ 34 531]]
  ```
- **Classification Report**:
  ```
                precision    recall  f1-score   support

             0       0.69      0.35      0.46       212
             1       0.79      0.94      0.86       565

      accuracy                           0.78       777
     macro avg       0.74      0.64      0.66       777
  weighted avg       0.76      0.78      0.75       777
  ```

## Interpretation

- **Data Overview**: The dataset includes comprehensive statistics on various college attributes.
- **Visualization Insights**: Scatter plots show relationships between features, differentiating between private and public colleges.
- **Clustering Results**: The K-Means algorithm effectively clusters colleges, with a high precision and recall for private colleges.
- **Model Performance**: The clustering model performs better at identifying private colleges than public colleges, indicating room for improvement.


## Contributing

Contributions are welcome! Please fork the repository and submit pull requests for any improvements or new features. Make sure to follow the existing code style and include relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Thank you for exploring the K-Means Clustering on College Data repository! If you have any questions or feedback, feel free to open an issue or contact the repository owner.

Happy clustering! 🎓📊

---

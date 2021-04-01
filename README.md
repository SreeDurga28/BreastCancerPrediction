# BreastCancerPrediction
Breast cancer (BC) is one of the most common cancers among women worldwide, representing the majority of new cancer cases and cancer-related deaths according to global statistics, making it a significant public health problem in today’s society.

The early diagnosis of BC can improve the prognosis and chance of survival significantly, as it can promote timely clinical treatment to patients. Further accurate classification of benign tumors can prevent patients undergoing unnecessary treatments. Thus, the correct diagnosis of BC and classification of patients into malignant or benign groups is the subject of much research.

The dataset used in this project is publicly available in the UCI Machine Learning Repository. The dataset was created by Dr. William H. Wolberg, physician at the University Of Wisconsin Hospital at Madison, Wisconsin, USA. To create the dataset, Dr. Wolberg used fluid samples, taken from patients with solid breast masses and computed the following features of each cell nucleus.

1. radius (mean of distances from center to points on the perimeter)

2. texture (standard deviation of gray-scale values)

3. perimeter

4. area

5. smoothness (local variation in radius lengths)

6. compactness (perimeter² / area — 1.0)

7. concavity (severity of concave portions of the contour)

8. concave points (number of concave portions of the contour)

9. symmetry

10. fractal dimension (“coastline approximation” — 1)

In this project I have used all these above features to predict whether the tumor is Benign or Malignant. I have Support Vector Machine(SVM) Classifier to predict the same. It gives 95% accuracy.

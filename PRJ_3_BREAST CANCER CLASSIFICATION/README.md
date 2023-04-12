<h1>BREAST CANCER CLASSIFICATION</h1>
This project aims to develop and compare different machine learning classifiers for breast cancer diagnosis based on the features of the tumor. The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Dataset from the UCI Machine Learning Repository. The dataset contains 569 samples of malignant and benign tumor cells. The first two columns in the dataset store the unique ID numbers of the samples and the corresponding diagnosis (M=malignant, B=benign), respectively. The columns 3-32 contain 30 real-valued features that are computed from digitized images of the cell nuclei, which can be used to characterize the shape, size, texture, and symmetry of the cells.
<h3>ABOUT DATASET</h3>
The dataset used in this project was obtained from the University of California, Irvine Machine Learning Repository. The dataset contains information about the characteristics of breast mass detected by mammography, such as texture, perimeter, area, smoothness, compactness, symmetry, and fractal dimension. The dataset is split into a training set and a test set, with 569 instances in total.
The dataset is already pre-processed and does not contain any missing or duplicate values. However, the features are on different scales, so we will need to normalize them before training the machine learning model.
<h3>COLUMNS</h3>
id: A unique identification number assigned to each patient

diagnosis: The diagnosis of the breast mass, either 'M' for malignant or 'B' for benign

radius_mean: The mean radius of the breast mass

texture_mean: The mean texture of the breast mass

perimeter_mean: The mean perimeter of the breast mass

area_mean: The mean area of the breast mass

smoothness_mean: The mean smoothness of the breast mass

compactness_mean: The mean compactness of the breast mass

concavity_mean: The mean concavity of the breast mass

concave points_mean: The mean number of concave portions of the contour of the breast mass

symmetry_mean: The mean symmetry of the breast mass

fractal_dimension_mean: The mean fractal dimension of the breast mass

radius_se: The standard error of the radius of the breast mass

texture_se: The standard error of the texture of the breast mass

perimeter_se: The standard error of the perimeter of the breast mass

area_se: The standard error of the area of the breast mass

smoothness_se: The standard error of the smoothness of the breast mass

compactness_se: The standard error of the compactness of the breast mass

concavity_se: The standard error of the concavity of the breast mass

concave points_se: The standard error of the number of concave portions of the contour of the breast mass

symmetry_se: The standard error of the symmetry of the breast mass

fractal_dimension_se: The standard error of the fractal dimension of the breast mass

radius_worst: The worst (largest) radius of the breast mass

texture_worst: The worst (most irregular) texture of the breast mass

perimeter_worst: The worst (largest) perimeter of the breast mass

area_worst: The worst (largest) area of the breast mass

smoothness_worst: The worst (most irregular) smoothness of the breast mass

compactness_worst: The worst (most irregular) compactness of the breast mass

concavity_worst: The worst (most irregular) concavity of the breast mass

concave points_worst: The worst (most irregular) number of concave portions of the contour of the breast mass

symmetry_worst: The worst (most irregular) symmetry of the breast mass

fractal_dimension_worst: The worst (most irregular) fractal dimension of the breast mass

<h3>MODEL</h3>
The model used in this project is a Support Vector Machine (SVM) classifier, which is a popular machine learning algorithm used for classification tasks. SVMs are particularly useful for classification tasks where there is a non-linear relationship between the features and the target variable.
We used the Scikit-learn library in Python to build the SVM classifier. We trained the model on the training set and evaluated its performance on the test set. We used various evaluation metrics such as accuracy, precision, recall, and F1-score to assess the performance of the model.

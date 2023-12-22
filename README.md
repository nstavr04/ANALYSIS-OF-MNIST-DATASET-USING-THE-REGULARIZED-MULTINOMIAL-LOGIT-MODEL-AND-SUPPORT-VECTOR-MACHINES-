# ANALYSIS-OF-MNIST-DATASET-USING-THE-REGULARIZED-MULTINOMIAL-LOGIT-MODEL-AND-SUPPORT-VECTOR-MACHINES

### Purpose of the Study  

This study delves into the MNIST dataset, a very popular dataset in the domain of machine learning. The MNIST dataset, originally consisting of 70,000 images of handwritten digits, serves as a benchmark for evaluating machine learning models in the domain of image processing and classification. The primary aim is to perform a quality analysis of this dataset and different classification methods and derive insightful conclusions. 

### Overview of the Approach 

We start with an initial exploratory analysis where we investigate the dataset's characteristics, including the identification of any non-contributing variables and an assessment of class distribution. Statistical metrics such as mean, standard deviation, and 'total ink'—the aggregate of pixel intensities—were computed for each digit class. These metrics provided foundational insights into the characteristics of the dataset. Furthering the feature engineering process, an innovative approach was employed by segmenting each image into four quadrants. The 'total ink' for each quadrant was calculated, aiming to encapsulate the spatial distribution of pixel intensities within each digit. 

Two machine learning algorithms were central to this analysis – the regularized multinomial logit model employing the LASSO (Least Absolute Shrinkage and Selection Operator) penalty, and Support Vector Machines (SVMs). For each model, we focus on fine-tuning and identifying the best hyperparameters to optimize their performance in digit classification using cross validation. We then compare these models in terms of effectiveness and efficiency, and we employ statistical tests, with a focus on identifying any notable differences in their accuracy levels, offering a comprehensive view of their applicability to the MNIST dataset. 

This report details the methodologies adopted from data preprocessing to model evaluation. It aims to provide a clear, reproducible account of the findings, underlining the functions and settings used in the Python implementation. This approach aligns with the principles of empirical research, ensuring the transparency and reproducibility of the analysis. 

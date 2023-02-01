# Brenton Graham Portfolio

## Introduction  
My name is Brenton Graham and I am currently a Master's student (MS) studying Biostatistics at the University of Colorado, Anschutz Medical Campus (CU Anschutz). In this repository I organize machine learning and statistical inference work from research projects, personal projects, and course-related projects. 

As background, I am currently working as a Graduate Research Assistant in the Department of Biostatistics and Informatics at CU Anschutz. My work here has focused on multi-omics data (primarily 16S rRNA microbiome data) in the context of cystic fibrosis (CF) and rheumatoid arthritis (RA). As such, my work primarily focuses on biological data problems (e.g. multi-omics data, clinical data, etc), although I am interested in applying my skillset to non-biological problems. Programming languages include Python, R, and SAS.  

<br>

## Research at CU Anschutz
### ALTRA: A Rheumatoid Arthritis Biomarker Study
Anti-cyclic citrullinated peptide (anti-CCP, or CCP) antibodies and rheumatoid factors (RF) serve as a clinically valuable biomarkers in the diagnosis and prognosis of RA. In this project we explore the association between these biomarkers and microbiome (16S) data from sputum and stool specimens.

* Comparing microbial communities of CCP+ and CCP- groups with PERMANOVA and differential abundance analysis [[Repo](https://github.com/BrentonGraham/ALTRA/tree/main/inference), [Report](https://github.com/BrentonGraham/altra/blob/main/inference/altra-inference.md)]
* Classification of subject CCP status from stool microbiome (16S) data using Random Forest, Support Vector Machines, XGBoost, and Multi-Layer Perceptron classifiers [[Notebook](https://github.com/BrentonGraham/ALTRA/blob/main/ml/ccp%2B_vs_ccp-_classification.ipynb), [Models](https://github.com/BrentonGraham/ALTRA/tree/main/ml/models)]

### A Longitudinal Pulmonary Exacerbation Study in Cystic Fribrosis Patients
Pulmonary exacerbations (PEx) are a leading cause of morbidity in CF. In this study, CF patients are evaluated at three time points over the course of a PEx. Data include clinical outcome measurements, demographic information, and microbiome data from sputum samples.

* Analyzing treatment response trajectory over the course of a pulmonary exacerbation (PEx) using a longitudinal latent class mixed modeling approach [[Repo](https://github.com/BrentonGraham/inference-anschutz/tree/main/longitudinal-latent-class-analysis), [Report](https://github.com/BrentonGraham/inference-anschutz/blob/main/longitudinal-latent-class-analysis/reports/lca-final-report.pdf)]

<br>

## Other Projects  
### Machine Learning & Deep Learning
#### Biomedical Machine Learning  
This section includes work from a Biomedical Machine Learning course at CU Anschutz. Each assignment came with a provided data set (some clean, some not) and general assignment goals. No solutions were provided, however, and assignments were somewhat open-ended, so all code and work is original.  

| Topic | Description | ML Techniques | Code / Notebook |
| :---: | :---: | :---: | :---: | 
| Linear Regression | Predicting treatment response (systolic blood pressure) from baseline risk factors using simple OLS regression and non-linear regression techniques. | OLS Regression, Non-Linear Regression | [Notebook](https://github.com/BrentonGraham/biomedical-ml-anschutz/blob/main/1.%20Linear%20Regression/LinearRegression.ipynb) |
| Real World Regression | Determining useful predictors of cancer patient survival time using cell measurements. Non-linear regression used for prediction. Additional techniques used here include missing data, multicollinearity, and outlier handling, as well as feature selection. | Non-Linear Regression | [Notebook](https://github.com/BrentonGraham/biomedical-ml-anschutz/blob/main/2.%20Real%20World%20Regression/RealWorldRegression.ipynb) |
| Logistic Regression & Cross-Validation | Evaluating the feasibility of distinguishing pathologic cardiac hypertrophy (from physiological cardiac hypertrophy) using logistic regression. Additionally exploring the effect of varying the size of k in k-fold cross-validation. | Logistic Regression | [Notebook](https://github.com/BrentonGraham/biomedical-ml-anschutz/blob/main/3.%20Logistic%20Regression%20%26%20Cross-Validation/LogisticRegression%26CrossValidation.ipynb) |
| Classification | Predicting the risk of stroke using three types of binary classifiers (RF, SVM, LR). Report includes hyperparameter tuning, classifier evaluation, and model selection in the context of an imbalanced class problem. | Random Forest, Support Vector Machines (SVM), & Logistic Regression | [Notebook](https://github.com/BrentonGraham/biomedical-ml-anschutz/tree/main/4.%20Classification%20%26%20Model%20Selection) |
| Clustering | Comparing the performance of clustering algorithms (k-means, DBSCAN and OPTICS) on gene expression data. Additionally using PCA for dimensionality reduction. | K-Means, DBSCAN, OPTICS, PCA (Principal Component Analysis), LDA (Linear Discriminant Analysis) | [Notebook](https://github.com/BrentonGraham/biomedical-ml-anschutz/tree/main/5.%20Clustering) |
| Deep Learning: MLP | Building simple neural networks (single-layer and multi-layer perceptrons) to classify cancer from gene expression data. Additionally testing the performance of a linear classifier to evaluate similarities with the single-layer perceptron build. | Multi-Layer Perceptron (PyTorch) | [Notebook](https://github.com/BrentonGraham/biomedical-ml-anschutz/blob/main/6.%20Intro%20to%20Deep%20Learning/IntroDeepLearning.ipynb), [MLP.py](https://github.com/BrentonGraham/biomedical-ml-anschutz/blob/main/6.%20Intro%20to%20Deep%20Learning/NN_MultiLayer.py) |
| Deep Learning: CNN | Building a convolutional neural network (CNN) to classify skin lesion type from skin images (multiclass classification problem). Dataset comes from [MedMNIST](https://medmnist.com/) (DermaMNIST). | Convolutional Neural Network (PyTorch) | [Notebook](https://github.com/BrentonGraham/biomedical-ml-anschutz/blob/main/7.%20Convolutional%20Neural%20Networks/ConvolutionalNeuralNetworks.ipynb), [CNN.py](https://github.com/BrentonGraham/biomedical-ml-anschutz/blob/main/7.%20Convolutional%20Neural%20Networks/ConvNetwork.py) |

<br>

### Statistical Inference

#### Course-Related Statistical Analysis Projects 
This section includes projects from advanced statistical analysis and longitudinal data analysis courses at CU Anschutz.  

| Topic | Description | Code | Report |
| :---: | :---: | :---: | :---: | 
| Bayesian Regression | Evaluating the association between treatment response and hard drug use in HIV-1 positive subjects using both a frequentist framework (i.e., multiple linear regression) and a Bayesian framework (i.e., Bayesian regression with rjags). | [Code](https://github.com/BrentonGraham/inference-anschutz/tree/main/adv-methods-2-bayesian-inference/code) | [Report](https://github.com/BrentonGraham/inference-anschutz/blob/main/adv-methods-2-bayesian-inference/reports/bayesian-inf-report.pdf) |
| Survival Analysis | Identifying risk factors associated with stroke incidence and estimating 10-year probability of stroke using a LASSO-penalized Cox regression framework. | [Code](https://github.com/BrentonGraham/inference-anschutz/tree/main/adv-methods-3-survival-analysis/code) | [Report](https://github.com/BrentonGraham/inference-anschutz/blob/main/adv-methods-3-survival-analysis/reports/survival-analysis-report.pdf) |
| Variable Selection Comparison<br />(Simulation Study) | Using simulated data sets to compare the performance of automated variable selection methods (stepwise selection, LASSO, elastic net) | [Code](https://github.com/BrentonGraham/inference-anschutz/tree/main/adv-methods-4-variable-selection-sim/code) | [Report](https://github.com/BrentonGraham/inference-anschutz/blob/main/adv-methods-4-variable-selection-sim/reports/variable-selection-sim-report.pdf) |

<br>

## Additional Packages, Tools & Software
* [Google Review Webscraper](https://github.com/BrentonGraham/google-review-scraper): A python package that uses Selenium to webscrape google reviews
* [Southwest Check In](https://github.com/BrentonGraham/southwest-check-in): A python package that automates the Southwest check in process using Selenium


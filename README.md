# Comparative-Analysis-of-Different-Classification-Algorithms
This repository aims at implementing different machine learning classification algorithms on a selected dataset and analyzing the results in terms of comparison among the performance of those algorithms. After selecting a dataset, four classifications algorithm namely Decision Tree Induction, Random Forest Classifier, Naïve Bayes Classifier, and Support Vector Classifier were implemented to predict the class level. After implantation, the report containing accuracy has been generated for all the algorithm. In addition, confusion matrix, and ROC graph has been visualized. All the process has been done using both Weka tool and different Python libraries in Jupyter Notebook.

The data are MC generated to simulate registration of high energy gamma particles in a ground-based atmospheric Cherenkov gamma telescope using the imaging technique. Cherenkov gamma telescope observes high energy gamma rays, taking advantage of the radiation emitted by charged particles produced inside the electromagnetic showers initiated by the gammas, and developing in the atmosphere. This Cherenkov radiation (of visible to UV wavelengths) leaks through the atmosphere and gets recorded in the detector, allowing reconstruction
of the shower parameters. The available information consists of pulses left by the incoming Cherenkov photons on the photomultiplier tubes, arranged in a plane, the camera. Depending on the energy of the primary gamma, a total of few hundreds to some 10000 Cherenkov photons get collected, in patterns (called the shower image), allowing to discriminate statistically those caused by primary gammas (signal) from the images of hadronic showers initiated by cosmic rays in the upper atmosphere (background).

Data Set Characteristics: Multivariate
Number of Instances: 19020
Number of Attributes: 11
Source of the dataset: Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml].
Irvine, CA: University of California, School of Information and Computer Science.
Shortened link: https://bit.ly/2OZRIYd

Preprocessing:
The data has been preprocessed using standard scaler for SVM implementation. This method scales data in such a way that the mean value becomes zero and the standard deviation becomes 1. Another preprocessing used for implementing Naïve Bayes and that is Normalization. This process scales data in between 0 and 1. In addition, the Label Encoder has been used to encode the class labels from categorical to numerical values. The preprocessing called Test Train Splitting method has been used to implement all the algorithms.

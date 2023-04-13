# Fashion-MNIST-Image-Classification

Fashion MNIST dataset is a classic dataset used to analyze machine learning models on image recognition. Our objective was to implement several supervised and unsupervised machine learning models on dataset and attain better accuracy in classifying the images.

An important part of our work was to stack the individual models into a meta-model to achieve better performance. This was done by using the output labels from four learning models, namely, K-nearest neighbors, Random Forest Classifier, Support Vector Classifier and Light Gradient Boost, and training a meta Random Forest Classifier on these output labels as features. Having just 4 features (4 model outputs), this step is comparatively faster. This step was also tried with SVM in the stacked model. However, Random Forest performs marginally better than SVM. The overall accuracy of our stacked model comes to around 91.5%. Thus, we conclude that stacking different models can substantially improve the performance.

The confusion matrix for the classification using the stacked model is shown below:
![image](https://user-images.githubusercontent.com/88345694/231889973-802c13dd-ebd6-4f92-96dc-b6a8855c60f1.png)

The class-wise accuracy with the class labels is shown as under:
![image](https://user-images.githubusercontent.com/88345694/231890095-ee5a0624-c5cd-4885-b2be-4e7f7c07787c.png)


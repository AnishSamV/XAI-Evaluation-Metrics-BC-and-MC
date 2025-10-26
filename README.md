# XAI-Evaluation-Metrics-BC-and-MC
Two new XAI Evaluation metrics, Borda Count (BC) and Multiple Correlation with Borda Count (MC+BC) metric are proposed. 
XAI is used to explain the output of a model. There are several XAI methods available.
Our Metric is used in ranking the best perfroming XAI method. The results of XAI methods are evaluated using these metrics.
A Densenet121 model is used to predict the images of MNIST, CIFAR-10 and ImageNet datasets. 
XAI methods such as Partition SHAP, Gradient SHAP, GradCAM and GradCAM++ are used in all datasets to explain the prediction of model. 
The ranking based on the metric offers insights into which XAI method perform more effectively for a particular dataset.
A limited PyTorch Implementation was conducted to facilitate the use of captum and Quantus.
Standard packages like MatplotLib, Scikit Learn, Tensorflow, PyTorch and Specific libraries like SHAP, Captum and Quantus are required to run these notebooks. 


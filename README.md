# Histopathologic-cancer-detection-using-Deep-Learning

Introduction 

Analyzing an image and predicting whether it is cancerous cell or not , to analyze the degree of severity of the cancer cell. Also to work on a model which detects various type of cancer cell. Investigation of malignant cell growth and their characteristics by classifying the structure of the cell.
  Cancer cells can grow uncontrollably throughout the body by changing the genetically DNA forms. In biologically cells normally divide and grow multiple amount on each division.
  When this process applied on abnormal and damaged cells they grow multiple times then those form huge amount of tumors, but we have some benign tumors cells don’t grow back but they quite large  can cause the mild symptoms if in brain it may be life threatening and that can’t be removed but comes to malignant tumors are dangerous that spread throughout the body leads to removal of the whole part.
  To prevent this type of action we need to detect cancerous cell in the early stage will helps to take proper medicine that leads to probability of overcoming from the diseases is high. 

Architecture

CancerNet

To implement the CNN architecture we have used the Keras deep learning library and designed a network and appropriately named “CancerNet” which:
Uses exclusively 3×3 CONV filters, similar to VGGNet
Stacks multiple 3×3 CONV filters on top of each other prior to performing max-pooling (again, similar to VGGNet)
But unlike VGGNet, uses depthwise separable convolution rather than standard convolution layers
We are training our model in 19 layers. 



  Applications/Use cases

This capability is particularly well-suited to medical applications, especially those that depend on complex proteomic and genomic measurements.
As a result, deep learning is frequently used in cancer diagnosis and detection. More recently deep learning has been applied to cancer prognosis and prediction.
An advantage of RT-PCR is that it can detect very small numbers of cancer cells in blood or tissue samples that would be missed by other tests.


## Detecting Phishing Websites on IBM Cloud
PhishFinder - Detecting Phishing Websites using Machine Learning on [IBM Cloud](https://www.ibm.com/cloud) (Auto AI Feature)

### Objectives

  1. To create a dataset and apply necessary preprocessing followed by feature selection.
  2. To apply various machine learning models and compare them based on different metrics.
  3. To run all the algorithms in the selected cloud platform using IBM Cloud's AutoAI feature to validate the choose obtained previously.
  4. To implement and deploy the selected machine learning model onto a cloud based platform.
  5. To predict the probability of a website being legitimate or phishing based on the URL of the website.

### Flow Diagram

<div align='center'>
<img src = 'examples/flow-diagram.png' height="300px">
</div>

### IBM Cloud Implementation

Our project is implemented using the Free-Lite account of IBM Cloud. IBM cloud’s AutoAI feature is used to corroborate the results confirming that Logistic Regression is the best model for the use case.

<div align='center'>
<img src = 'examples/ibm.png' height="200px">
</div>

### Deployment

The deployment URL and keys obtained from IBM Cloud are placed within the python code of the web application obtaining the following results.

<div align='center'>
<img src = 'examples/true.png' height="200px">
<img src = 'examples/false.png' height="200px">
</div>

### Reference
  - [Research Paper](https://www.researchgate.net/publication/277476345_Phishing_Websites_Features) - Rami Mustafa, Phishing Website Features, 2015 


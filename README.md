### Multivariate Statistical Analysis
# Principle Component Analysis
- This project of [Jupyter Notebook](https://jupyter.org/) by [Python](https://www.python.org/) learn show how to create a complete system of **Multivariate Statistical Analysis**

### 1. Team Information
|No.| Members          | Email                         | Role                |
|---|------------------|-------------------------------|---------------------|
| 1 | Tri Nguyen Phan  | 20127578@student.hcmus.edu.vn | Team Leader         |
| 2 | Manh Hung Nguyen | 20127030@student.hcmus.edu.vn | Algorithm Developer |
| 3 | Hoang Minh Luu   | 20127048@student.hcmus.edu.vn | UI/UX Designer      |

### 2. Overview
- Support Software: Visual Studio Code, Google Colabotary, Github.
- One of the most common challenges in data analysis (text, image, video, etc.) is the multidimensionality and sparsity of the data. Instances often arise where the number of data points is very small, but each point has a large number of features.
- The MNIST dataset, part of a comprehensive database containing handwritten digit images, serves as an illustrative example. This dataset is widely utilized for training various machine learning models.
  - Number of training images: 60,000
  - Number of test images: 10,000

<img src="https://upload.wikimedia.org/wikipedia/commons/f/f7/MnistExamplesModified.png">

- Each image has a size of 28x28 pixels. The pixel values range from 0 to 255, representing the brightness or darkness of each pixel. The training dataset (.csv) consists of 785 columns. The first column represents the label, indicating which digit is depicted, and the remaining 784 values represent the pixel values of the image.

<img src="https://media.licdn.com/dms/image/C5112AQHIlfAil0puPQ/article-inline_image-shrink_1000_1488/0/1576237874564?e=1709769600&v=beta&t=SjVGbWIES8fsgInGsnpify9F8-oBtSODQzT-p93KTTo">

- It is evident from the illustrated example that although there are only ten data points (representing the ten handwritten digits from 0 to 9), each point has 28x28 = 785 pixels. In situations like this, constructing a model that captures all features to understand the essence of the data is infeasible. To overcome this, efforts are made to increase the number of data points or reduce the dimensionality of each point.
- In this context, the research will delve into Principal Component Analysis (PCA) as a dimensionality reduction method. PCA is a technique that transforms a high-dimensional dataset (a dataset with many features/variables) into a low-dimensional dataset.
- Given the provided statistics, when applying PCA to reduce the dimensionality to only two, we obtain the following graph:

<img src="https://i.imgur.com/TLwhbSk.png">

- With the graph above, the data has been transformed from 785 dimensions down to 2 dimensions. The data points of label 0.0 (dark blue points) exhibit significant differences compared to other labels. Understanding the nature of this data aids in making informed decisions. In this example, the handwritten digit images of label 0.0 have some unique characteristics compared to other data points.
- This serves as a fundamental example of the utility of PCA in data exploration, highlighting its ability to reduce dimensionality while retaining the most important features. This not only enhances the efficiency of data analysis but also simplifies the process of visualizing and interpreting the data.

### 3. General Framework:
|Phase| Framework                                                                             |
|---|-----------------------------------------------------------------------------------------|
| 1 |Import the necessary libraries to apply PCA algorithms to the provided data|
| 2 |Read data from the provided CSV file|
| 3 |Specify the required input parameters to run the program|
| 4 |Write individual functions to perform some basic multivariate analysis with visualization|
| 5 |Load the input parameters into PCA functions and print the results (a plot)|

### 4. Useful of PCA

|No.| Uses                                                                             |
|---|-----------------------------------------------------------------------------------------|
| 1 |Extract the most important information from the data set|
| 2 |Reduce data dimensionality with the ability to minimize information loss and maximize data variability|
| 3 |Solve the problem and analyze the correlation between variables in the original data using the new variables that the algorithm has found|

### 5. Team Contributions
- Firstly, the members of the team provided a clear explanation and a scientific formula for the Principal Component Analysis (PCA) problem, starting from its definition and purpose, and outlining the steps involved in its implementation. This explanation will be beneficial for anyone seeking to understand PCA, regardless of their foundational knowledge.
- Additionally, the application of PCA to a real-world problem, specifically the classification of the IRIS dataset, was discussed. This application is highly valuable in demonstrating how PCA can be utilized in practical scenarios to reduce the dimensionality of the dataset and improve classification accuracy.
- Last but not least, the team also presented visual aids to illustrate PCA concepts, including scatter plots of the original and transformed datasets, and an explained cumulative variance plot. These visuals are instrumental in comprehending the impact of PCA on the dataset and assessing the quality of PCA results.

### 6. User guide


- For further details, please visit the **Report.pdf** file provided above. Thank you very much and Have a nice day!

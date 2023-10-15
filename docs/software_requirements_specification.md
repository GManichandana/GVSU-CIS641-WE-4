# This document serves as the Software Requirements Specification (SRS) for the project(Diabetes Risk Prediction System). The purpose of this document is to provide a comprehensive overview of the functional and non-functional requirements for the software project, ensuring a clear understanding of what the software should do and how it should perform.

# Functional Requirements
### Data Import and Preprocessing: 
1. The system shall be capable of importing data from an external CSV file (e.g., 'diabetes.csv').
2. The system shall display the shape of the dataset, providing the number of rows and columns.
3. The system shall display the first few rows of the dataset to allow users to explore the data.
4. The system shall check for missing values in the dataset and report the count of missing values.
5. The system shall perform data standardization to prepare the data for modeling.


### Data Visualization: 
1. The system shall generate a correlation matrix heatmap to visualize the relationships between variables.
2. The system shall create a pie chart to display the distribution of diabetic and non-diabetic individuals.
3. The system shall generate a countplot to display the count of diabetic and non-diabetic individuals.

### Model Building and Evaluation: 
1. The system shall split the dataset into training and testing sets using a specified ratio (e.g., 80% training, 20% testing).
2. The system shall apply feature scaling to the training and testing data to ensure uniform ranges for features.
3. The system shall build a K Neighbors Classifier model with variable 'k' and report the accuracy scores for different 'k' values.
4. The system shall build a Support Vector Classifier model with various kernel functions (e.g., linear, poly, rbf, sigmoid) and report accuracy scores for each kernel.


# Non-Functional Requirements

### Usability: 
1. The system's user interface should be intuitive and user-friendly.
2. The software should provide clear visualizations and reports to help users understand the data and model performance.

### Performance: 
1. The system should efficiently handle large datasets and complex models.
2. Model training and evaluation should be performed in a reasonable amount of time.

### Scalability: 
1. The system should be scalable to incorporate additional data sources or features in the future.
2. It should allow for the easy integration of new machine learning algorithms.

### Reliability: 
1. The system should be robust and handle unexpected inputs gracefully.
2. It should provide accurate predictions and maintain high model accuracy.

### Security: 
1. The system should ensure the security and privacy of user data.
2. Access to sensitive information, if any, should be restricted to authorized personnel only.

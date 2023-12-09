# This document serves as the Software Requirements Specification (SRS) for the project(Diabetes Risk Prediction System). The purpose of this document is to provide a comprehensive overview of the functional and non-functional requirements for the software project, ensuring a clear understanding of what the software should do and how it should perform.

# Functional Requirements
### Data Import and Preprocessing:
* FR1 - The system shall be capable of importing data from an external CSV file (e.g., 'diabetes.csv').
* FR2 - The system shall display the shape of the dataset, providing the number of rows and columns.
* FR3 - The system shall display the first few rows of the dataset to allow users to explore the data.
* FR4 - The system shall check for missing values in the dataset and report the count of missing values.
* FR5 - The system shall perform data standardization to prepare the data for modeling.


### Data Visualization: 
* FR6   - The system shall generate a correlation matrix heatmap to visualize the relationships between variables.
* FR7   - The system shall create a pie chart to display the distribution of diabetic and non-diabetic individuals.
* FR8   - The system shall generate a countplot to display the count of diabetic and non-diabetic individuals.
* FR9   - It shall generate and display a correlation matrix to visualize the relationships between different variables.
* FR10  - The system shall calculate and display descriptive statistics, including mean, median, and standard deviation, for each column in the dataset.

### Model Building and Evaluation: 
* FR11 - The system shall split the dataset into training and testing sets using a specified ratio (e.g., 80% training, 20% testing).
* FR12 - The system shall apply feature scaling to the training and testing data to ensure uniform ranges for features.
* FR13 - The system shall build a K Neighbors Classifier model with variable 'k' and report the accuracy scores for different 'k' values.
* FR14 - The system shall build a Support Vector Classifier model with various kernel functions (e.g., linear, poly, rbf, sigmoid) and report accuracy scores for each kernel.
* FR15 - The system shall accept new input data in the form of a tuple or array and preprocess it in the same manner as the training data.

### K Neighbors Classifier
* FR16 - The software shall implement the K Neighbors Classifier.
* FR17 - The software shall determine the optimal number of neighbors through cross-validation.
* FR18 - The software shall display a plot of classifier scores for different values of k.
* FR19 - The software shall present the accuracy of the selected model on the test set.
* FR20 - The software shall generate and display predictions for new input data.

### Support Vector Classifier
* FR21 - The software shall implement the Support Vector Classifier.
* FR22 - The software shall evaluate and display the classifier scores for different kernel functions.
* FR23 - The software shall present the accuracy of the selected model with the best-performing kernel.
* FR24 - The software shall generate and display predictions for new input data.
* FR25 - The software shall verify model correctness against the selected model.

# Non-Functional Requirements
### Performance
* NFR1 - The model training process shall not exceed a specified time limit.
* NFR2 - The prediction time for new input data shall be within acceptable bounds.
* NFR3 - The software shall handle datasets of varying sizes efficiently.
* NFR4 - The memory consumption during model training shall be optimized.
* NFR5 - The software shall provide feedback on the training progress and completion time.

### Usability
* NFR6 - The user interface shall be intuitive and user-friendly.
* NFR7 - The software shall provide clear instructions for dataset loading and preprocessing.
* NFR8 - Visualizations and plots shall be easy to interpret.
* NFR9 - Error messages shall be informative and guide the user in resolving issues.
* NFR10 - The software shall have a responsive design for various screen sizes.

### Reliability
* NFR11 - The selected model shall achieve a minimum accuracy threshold on test data.
* NFR12 - The software shall handle unexpected input data gracefully.
* NFR13 - The models shall be retrainable with new data without significant performance degradation.
* NFR14 - Robustness tests shall be conducted to ensure stability under varying conditions.
* NFR15 - The software shall log and handle errors effectively to maintain reliability.

### Security
* NFR16 - The software shall handle sensitive health data securely.
* NFR17 - Access controls shall be implemented to restrict unauthorized access to the dataset.
* NFR18 - Data encryption shall be applied to protect stored and transmitted data.
* NFR19 - User authentication mechanisms shall be in place to control access to the software.
* NFR20 - The software shall comply with relevant data protection regulations.

### Scalability
* NFR21 - The software shall be capable of handling a growing number of users concurrently.
* NFR22 - The model training process shall scale efficiently with increasing dataset sizes.
* NFR23 - The software shall support parallel processing for improved performance.
* NFR24 - Scalability tests shall be conducted to identify and resolve potential bottlenecks.
* NFR25 - The system shall provide options for horizontal and vertical scalability.

# Change Management Plan
### How will you train people to use it?

People would first need to be educated about diabetes, including its forms, symptoms, and risk factors, before being trained in diabetes risk prediction analysis. An explanation of the instrument or method used for risk prediction, including its creation, guiding principles, and how to manage pertinent data such patient demographics and medical history, comes next. In-depth discussions of risk prediction models and algorithms, hands-on practice sessions, and advice on evaluating findings and coming to wise judgments would all be included in the program. In addition, emphasis would be placed on ethical issues, patient data protection, how to effectively communicate risk assessments to patients, and the value of ongoing education in this quickly developing sector. Frequent evaluations and comments would guarantee a thorough comprehension and utilization of the instrument in actual healthcare environments.
 
### How will you ensure it integrates within their ecosystem / software?

To guarantee a smooth integration of a diabetes risk prediction tool into an already-existing healthcare ecosystem, a comprehensive compatibility evaluation is necessary to detect any possible concerns related to compatibility and technology. It is necessary to carry out thorough testing and validation procedures to guarantee correct functionality and data integrity. For the instrument to function properly, personnel must receive regular maintenance and upgrades, as well as training and ongoing support. Important actions include thinking about scalability for future requirements and including important stakeholders at every stage of the integration process. Following integration, a feedback loop and ongoing monitoring assist in resolving any problems and enhancing the effectiveness of the system


### How will you ensure that any discovered issues are resolved?

A strong monitoring and reporting system is necessary to guarantee that any problems with the diabetes risk prediction tool are promptly fixed. Regular performance reviews, channels for user input, and procedures for reporting errors should all be part of this system. There should be a committed support staff in place that is knowledgeable about the tool's clinical and technical features so they can quickly identify and resolve problems. It is imperative to make ongoing upgrades and enhancements in response to consumer input and technology developments. Working together with IT experts, medical professionals, and the tool's creators is essential for a thorough knowledge and prompt problem-solving. Maintaining the tool's dependability and efficacy in the healthcare ecosystem also depends on taking a proactive stance to foresee and address such problems before they become more serious.>

# Tracebility Links
## Use Case Diagram Traceability
| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
| 1 | [UseCase1]
<li>
<a href="./artifacts/Activity and Use case.pdf" target="_blank">Activity and Use case Documents</a></li> | FR1-FR5,NFR16-NFR20 | 
</li>

# Software Artifacts
<ul>
            <li><a href="./artifacts/Activity and Use case.pdf" target="_blank">Activity and Use case Documents</a></li>
            <li><a href="./artifacts/CRC CARD, Object, class.pdf" target="_blank">CRC CARD, class, object Documents</a></li>
             <li><a href="./artifacts/Navigation_Diagram.png" target="_blank">Navigation Diagram</a></li>
            <li><a href="./artifacts/README.md" target="_blank">Artifacts README</a></li>
</ul>
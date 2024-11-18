## PREDICTING WHETHER AN ASTEROID IS HAZRDOUS OR NOT USING MACHINE LEARNING
This project develops a machine learning model using logistic regression to predict whether an asteroid poses a hazard to Earth, based on features like size, velocity, and orbital parameters. Gradient descent is used to optimize the model, and data preprocessing ensures accurate and efficient predictions. The model aims to improve asteroid risk assessment and strengthen planetary defense strategies.

## About
<!--Detailed Description about the project-->
This project develops a machine learning model to predict asteroid hazard risk to Earth using key features like size, velocity, and orbital parameters. Logistic regression is used for binary classification, determining whether an asteroid is hazardous or not. Gradient descent optimizes the model by adjusting the parameters to minimize prediction errors. Data preprocessing includes feature scaling and normalization to improve model performance, while cross-validation ensures robust and generalizable predictions. The model also applies feature selection to identify the most influential factors, aiming to enhance risk assessment and planetary defense strategies through accurate asteroid hazard predictions.
## Features
<!--List the features of the project as shown below-->
- Enhanced Hazard Detection
- Scalable and Data-Driven Approach
- Improved Risk Assessment,Faster Decision-Making,Continuous Improvement and Adaptation.
- Planetary Defense Strategy Support

## Requirements
<!--List the requirements of the project as shown below-->
Operating System: Requires a 64-bit OS (Windows 10 or Ubuntu) to ensure compatibility with machine learning frameworks and handle computational tasks efficiently.
Development Environment: Python 3.6 or later is essential for implementing the asteroid hazard prediction model and using machine learning libraries.
Machine Learning Frameworks: Scikit-learn for implementing logistic regression, gradient descent optimization, and cross-validation; optional use of TensorFlow if advanced techniques are explored.
Data Processing Libraries: NumPy and Pandas are required for data manipulation, preprocessing, and feature scaling to prepare the asteroid dataset.
Version Control: Git for collaborative development and effective management of code versioning and changes.
IDE: Use of VSCode or Jupyter Notebook for coding, debugging, and testing machine learning models.

## System Architecture
<!--Embed the system architecture diagram as shown below-->
- The architecture begins with historical asteroid data, which is subjected to processes such as data analysis, preprocessing, and feature selection to prepare the dataset for model development.
- The prepared data is split into training and testing datasets.
- The training dataset is used to develop and select a robust model, while the testing dataset is used to refine the model using gradient descent optimization. 
- The optimized model undergoes testing to evaluate its performance, and the final predictions are generated to classify asteroids as hazardous or non-hazardous. 
- This approach ensures reliable and accurate outcomes for asteroid hazard prediction.


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
## Output1 -Test Accuracy before using Gradient descent:
![image](https://github.com/user-attachments/assets/83c552a7-0802-4096-b3c3-5729602c7c58)




## Output2 -Test Accuracy after Gradient Descent :
![image](https://github.com/user-attachments/assets/cd24c358-aa6a-419b-8593-cfe439004d85)

#### Predicting Not-Hazardous:
![image](https://github.com/user-attachments/assets/b98b3df4-2b85-4408-a827-7db92f7a643a)
![image](https://github.com/user-attachments/assets/b9afb1a7-3d37-4c29-a6dd-cdc1ad841644)

#### Predicting Hazardous :
![image](https://github.com/user-attachments/assets/c6b37c33-43f2-46ce-a69f-e434fb10f398)
![image](https://github.com/user-attachments/assets/18e3e1f8-c13d-4eda-ab9c-44f561b8d09c)




Detection Accuracy: 95.31%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact:
<!--Give the results and impact as shown below-->
Results: The asteroid hazard prediction model, utilizing logistic regression and gradient descent optimization, achieves an accuracy score of 95.31%, demonstrating high precision in classifying asteroids as hazardous or non-hazardous. With the application of advanced data preprocessing techniques like feature scaling, normalization, and feature selection, the model efficiently processes asteroid datasets. Cross-validation and performance metrics, such as precision, recall, and F1-score, further validate the model's robustness.ble digital environment.

Impact:The project delivers a transformative contribution to planetary defense by providing an exceptionally accurate and automated solution for asteroid hazard classification. With an impressive accuracy of 95.31%, the model significantly enhances the precision of risk assessments, empowering space agencies and planetary defense organizations to identify hazardous asteroids with unparalleled reliability. This automation streamlines the process, drastically reducing the time and financial resources traditionally required for manual asteroid analysis, thereby offering a far more cost-effective and efficient approach to monitoring asteroid threats. Furthermore, the project contributes to the advancement of research in asteroid detection and hazard prediction, offering critical insights and laying a robust foundation for future innovations and developments in planetary defense frameworks.

## Articles published / Reference:
R. Bhavsar et al., "Classification of Potentially Hazardous Asteroids Using Supervised Quantum Machine Learning," in IEEE Access, vol. 11, pp. 75829-75848, 2023, doi: 10.1109/ACCESS.2023.3297498.

Kokhirova, G.I., Babadzhanov, P.B. Current Knowledge of Objects Approaching the Earth. Sol Syst Res 57, 467–485 (2023). https://doi.org/10.1134/S0038094623050039

Perna, D., Barucci, M.A. & Fulchignoni, M. The near-Earth objects and their potential threat to our planet. Astron Astrophys Rev 21, 65 (2013). https://doi.org/10.1007/s00159-013-0065-4





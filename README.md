# -Deep-Learning---Predicting-Diabetes-Progression-using-Artificial-Neural-Networks
Comprehensive Assessment 
<img width="685" alt="image" src="https://github.com/user-attachments/assets/63ae32d0-f572-4381-a1f7-dac9a53119c9">
<img width="286" alt="image" src="https://github.com/user-attachments/assets/ab8b1b5d-c9a5-4329-bfd7-1de6501a226f">
<img width="683" alt="image" src="https://github.com/user-attachments/assets/55f98928-5c05-4044-8693-d616305be97f">
<img width="641" alt="image" src="https://github.com/user-attachments/assets/cbb5899c-1c27-4991-8eac-4d8ff870cb14">
<img width="571" alt="image" src="https://github.com/user-attachments/assets/56445536-7194-482e-ad0e-3d199953ba9c">


Loading and Preprocessing: used the Diabetes dataset from sklearn to get data. Scaled the input data using StandardScaler to help the model perform better.
Exploratory Data Analysis (EDA): visualized the data using pair plots and a heatmap to see feature relation towards each other and the target variable (diabetes progression).
Building and training the ANN Model : A simple Artificial Neural Network (ANN) was created using the Sequential API in Keras. it has a few layers with ReLU activation and one output layer. the model was trained on the scaled data.
Evaluating the Model: tested the model on unseen data then calculated the Mean Squared Error (MSE) and R² Score to see the accuracy in the prediction of the progression of diabetes.
Improving the Model: created and trained a more complex version of the model containing more layers. showed slight improvement in the performance, MSE lowered and R² score increased.


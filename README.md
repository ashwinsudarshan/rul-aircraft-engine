# rul-aircraft-engine
This folder contains the final report for ENME 691 taken at the University of Maryland College Park duing the spring 2024 semester.
The test data results of all models are compiled in an XLSX fil titled "RUL_groundTruth_comparison.xlsx." Separate codes are included for each model with the name of the file corresponding to the ML model used in the code.
Any and all questions should be directed to ashwin23@umd.edu



Remaining Useful Life (RUL) prediction is a critical step in the protection and maintenance of modern machines. Failure to accurately predict how much longer a component can operate risks the life of the entire system as well as those operating it. Machine Learning (ML) is a powerful methodology which has shown repeated success in this field. In this work, five separate algorithms are trained to predict the RUL of an aircraft engine across six different operating regimes with run to failure data collected from 260 simulated engines. This included some deep learning models such as a traditional Recurrent Neural Network (RNN) and Long Short Term Memory RNN (LSTM) and a 1-D Convolutional Neural Network (CNN) as well as Support Vector Regression (SVR) and eXtreme Gradient Boosting (XGBoost). The average RMSE of the final prediction for all algorithms was 33.57 while the best and worst performing cases were 28.89 and 37.58 respectively for the LSTM and XGBoost respectively. Averaging the results of the last 5 predictions yielded a slight improvement with a best and worst case performance of 28.23 and 33.66 for the LSTM and RNN.

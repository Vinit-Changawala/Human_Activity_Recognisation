# Human_Activity_Recognisation
This project is to build a model that predicts the human activities such as High Diving, Horse Riding, Javelin Throw, Punch, Military Parade and Skate Boarding.


Testing of model is done with the use of Moving Average and without using Moving Average.

Moving Average: It takes every window_size(parameter) frames and averaged their probabilities predicted by model and display the class name which it belongs. In other words, Probability of bunch(window_size) of frames is taken and average on that probabilities is use to predict the class name.

Without using Moving Average: Probability of each frame is predicted by model and display the class name of each frame.







Results Without Using Moving Average:


https://user-images.githubusercontent.com/92297330/185452807-0c136469-3814-4dee-842d-46035f2e83d9.mp4












Results Using Moving Average:


https://user-images.githubusercontent.com/92297330/185452791-9f788927-6813-4a64-addf-70d150f36e4d.mp4






# Human_Activity_Recognisation
This project is to build a model that predicts the human activities such as High Diving, Horse Riding, Javelin Throw, Punch, Military Parade and Skate Boarding.


Testing of model is done with the use of Moving Average and without using Moving Average.

Moving Average: It takes every window_size(parameter) frames and averaged their probabilities predicted by model and display the class name which it belongs. In other words, Probability of bunch(window_size) of frames is taken and average on that probabilities is use to predict the class name.

Without using Moving Average: Probability of each frame is predicted by model and display the class name of each frame.




Results Without Using Moving Average:



https://user-images.githubusercontent.com/92297330/185450111-4fd333ac-4344-46a3-9278-f00ecdc11083.mp4






Results Using Moving Average:



https://user-images.githubusercontent.com/92297330/185450271-2fe19342-5ed2-4c3f-982a-c4f585fbd3a1.mp4


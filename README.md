# Digit-Recognition-Using-CNN-and-Gradio  
  
In this project, we have used a CNN model to predict the handwritten english digits from 0-9.
  
We have used MNIST database which contains 60000 training images and 10000 test images. It contains 28*28 number of features. We have loaded the dataset from the oython library named datasets.  
  
But the dataset is available on the internet in kaggle. Link :  https://www.kaggle.com/oddrationale/mnist-in-csv  
  
  
Requirements:  
  
  Mentioned in the requirements.txt  
  
Anoher requirment is GitBash (If you want to download the repository to run the code)  
  
  
File Descriptions:  
  
  
Digit Recognition.ipynb - This file loads the data, preprocesses the image into Sequential Model readable image. The CNN layer model has 3 layers - Convolution, MaxPooling and Activation along with 3 fully connected layers - Flatten, Dense and Activation. The input is taken as an image and output is given as a label from (0-9). It can also predict a handwritten image drawn in Paint and give output as a label.  
  
  The webapp is made with Gradio, which is an open source python library which lets us create customizable UI components. 
  
Steps of Execution:

		$ git clone https://github.com/debanjan611/Digit-Recognition-Using-CNN-and-Gradio.git
OR  
  
  1.Download the file and place it in a same folder.  
  2.Open jupyter notebook and run the code.  
  3.On the gradio app, draw any English digit from 0-9 and the output will be predicted as a label in the right hand side.  
    
 # <h2> Outputs:  
   
   
   <img width="960" alt="results" src="https://user-images.githubusercontent.com/68823461/135579046-7bb9711c-51f4-47fb-8e95-2bd902558996.PNG">

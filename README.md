# Computer-Vision
This repository includes codes related to Computer Vision such as Image Classification and Real Time Object Detection

1) Image Classification:\
   I tried classifying MNIST Handwritten Digits, Ants & Bees [(Dataset can be downloaded from here)](https://download.pytorch.org/tutorial/hymenoptera_data.zip), and [Butterfly Dataset](https://www.kaggle.com/datasets/gpiosenka/butterfly-images40-species)


   **Note**:\
   1.1) I used transfer learning for the Ants & Bees dataset, finetuning Resnet-18 model, so the model checkpoint is over 45MB and can't be uploaded in GitHub\
   1.2) The Butterfly Dataset that I used was different and only had around 31 classes. So I don't recommend you to load the dictionary I used. Instead, you can rerun the training model by changing the output classes to the actual number of classes in the link above. I'll train the model again and upload the model dictionary soon.


2) Real Time Object Detection:\
   I tried detecting objects in an imageo or video, by segmenting the object and then drawing a bounding box. I'll upload the Jupyter Notebook to GitHub **soon**

   **Note**:\
   

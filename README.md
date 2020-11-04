# Computer-vision-and-pattern-recognition


# Introduction:

   **In this project, we are going to use a pre-trained model which is called Keras-retinanet. Then We will take another pre-train model which is already trained using the weight of Keras-retinanet. we will also show how to train our own model using Keras-retinanet weight. Our main objective is to detect a number plate and create a bounding box along with the prediction score of a car using a custom dataset which is hosted in Kaggle. The custom dataset name is Indian number plates which is in JSON file. let's start and discuss the whole project step by step.**
   
   
   # Future work:

   **We will train several models instead of using the pre-trained model. We will discriminate our train model and choose the best one. We do it by changing the epochs, step, and batch size. Another thing that would be done is Automatic number plate localization after detecting the number plate.**
   
   
   
   
   # Conclusion:
**We use transfer learning in our project because in our dataset we have only 251 images. We train only 189 images in this project. It is nearly impossible to get expected accuracy without transfer learning. Transfer learning mainly used where the training dataset is not that much big but we need higher accuracy. We face some difficulties with the annotation file and format. After spending a lot of hours in this project we get a clear idea about annotation and how to handle the annotation while drawing the bounding box. Another thing is Keras Built-in function which helps us lot to build the project. Lot of work we have done only by calling Keras function. So it reduces our work.
Finally, we got our expected accuracy after doing a lot of hard work.**

# dogbreedclassifier

<ins>**Project Description**<ins>

A multiclass dog breed image classifier created using TensorFlow and the pre-trained InceptionV3 Model. The model is able to identify up to 120 breeds, and you can find a list of the breeds in the .ipynb file.


<ins>**Important Information on How to Run the Program**<ins>

This project was trained on a dataset of approximately 20,000 images and a CSV_file, both on which can be found at this link: https://www.kaggle.com/competitions/dog-breed-identification . 

It is important to download the required files from the link in order for the program to work properly.

In addition, a virtual environment should be set up so a custom kernel can be created and linked with this project, allowing it to run.

If you would like to use your own images for testing, then ensure that they are in the same directory as the data and the kernel as shown below: 

![image](https://github.com/dkaul09/dogbreedclassifier/assets/111927365/c85375f4-39f7-44ae-9c1c-18b5df289099)


<ins>**My Experience**<ins>

I decided to build this project in order to build my experience of developing classifiers. Last time, I built a classifier that was able to distinguish between cats and dogs (which can also be found on my GitHub profile), and then I wanted to build a classifier that could do something much more sopshicated: distinguish a dog's breed from an image. Moreover, I also saw this project as an opportunity to work upon the issues that I faced in my last project such as overfitting.

Overall, this project was a great learning experience as I was able to learn about concepts such as transfer learning and the different pre trained models available to use ranging from VGG 16 to InceptionV3, and tested them out to see which one I felt like was the best fit for this project. In addition, I learned and implemented many concepts such as EarlyStopping and DropOut, which played a huge role in preventing the model from overfittng.


<ins>**Possible Improvements**<ins>

One possible improvement I could have made for this project is train the model to recognize a bigger amount of dog breeds. At the moment, the model can classify up to 120 dog breeds as compared to the 350-400 that exist. To make this improvement, I can train the model on more data with these additional species. There will be at least 60 images per breed added to the dataset as all the 120 dogs have at least 60 images associated with them.

<



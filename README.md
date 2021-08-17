# Project: "Chubby, or not chubby, that is the question."
This GitHub is provided for course McGill Neural Networks and Deep Learning - YCNG 229. It is trying to solve a computer vision problem, using Kaggle CelebA dataset, Keras, and other Python libraries.

# Project summary
This project needs to answer this one fundamental question: am I chubby?

Classifying someone in the "chubby" or the "not chubby" category is one highly debatable topic. The bias of the observer is tainted by multiple factors of his environment. So when it comes to classifying a subject into one or the other category of weight perception, the observer doesn't have a clear and centralized method of making a choice. In other words, when I'm asking myself the question: "Am I chubby?", what I'm really asking myself is: "Are the members of my own culture classifying me as chubby when they observe me?".

That becomes a headache, because:

a) people tend to not disclose such observations to avoid being rude;<br> 
b) these observations are relative to the observers' background and culture.

But today, we will create a tool to attest if I'm chubby or not, according to cultural standards: celebrities.

Using the Kaggle CelebA dataset, which contains over 200,000 images of anonymized celebrities, we will train a CNN model to classify a face as Chubby=True, or Chubby=False. Hopefully, we will be able to use that model on my own picture, and know the truth about this fundamental question.

# Online documentation used in this research

The project was inspired by these generous researchers who share their knowledge and ideas for free on blog posts and websites. For students like me, reading these researchers' work is greatly inspiring to get better at exploring and creating within the infinite limits of the data science world. For this reason, from the bottom of my heart, thank you!
<br><br>
### DATASET:
- CelebFaces Attributes (CelebA) Dataset Version 2. Over 200k images of celebrities with 40 binary attribute annotations. Dataset owner is Jessica Li. Created and last updated on 2018-06-01. URL: https://www.kaggle.com/jessicali9530/celeba-dataset
<br><br>
### THIS PROJECT WAS INSPIRED BY: 
<br><br>
- Gender Detection using InceptionV3, 92.6% acc. Kaggle article and research authored by Nagesh Singh Chauhan. URL: https://www.kaggle.com/nageshsingh/gender-detection-using-inceptionv3-92-6-acc
- Facial Attribute Recognition using CNN https://www.kaggle.com/akshat0007/facial-attribute-recognition-using-cnn
- Generate Realistic Human Face using GAN. KD Nuggets article authored by Nagesh Singh Chauhan. URL: https://www.kdnuggets.com/2020/03/generate-realistic-human-face-using-gan.html
<br><br>
### USEFUL HOW TO ARTICLES: 
<br><br>
- CelebA face dataset, a translation of the Chinese blog post about the metadata of the CelebA dataset. URL: https://www.programmersought.com/article/35243862640/
- Load all images from a folder using PIL, Stackoverflow, May 27, 2018. URL: <br> https://stackoverflow.com/questions/50557468/load-all-images-from-a-folder-using-pil
- Move files python according value columns, Stackoverflow, February 25, 2019. URL: https://stackoverflow.com/questions/54862852/move-files-python-according-value-columns
- How to Load Large Datasets From Directories for Deep Learning in Keras, Machine Learning Mastery, by Jason Brownlee, April 10, 2019. URL: https://machinelearningmastery.com/how-to-load-large-datasets-from-directories-for-deep-learning-with-keras/
- Image data preprocessing, Keras. URL: https://keras.io/api/preprocessing/image/
- Building powerful image classification models using very little data, Keras blog, by François Chollet, June 05, 2016. URL:  https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html
- How to augment data using Keras, Towards data science, by Ravindu Senaratne, July 21, 2020. URL:  https://towardsdatascience.com/how-to-augmentate-data-using-keras-38d84bd1c80c
- Dropout Regularization in Deep Learning Models With Keras, Machine Learning Mastery, by Jason Brownlee, June 20, 2016. URL: https://machinelearningmastery.com/dropout-regularization-deep-learning-models-keras/
- How to set class weights for imbalanced classes in Keras?, Data science stack exchange, August 17, 2016. URL: https://datascience.stackexchange.com/questions/13490/how-to-set-class-weights-for-imbalanced-classes-in-keras

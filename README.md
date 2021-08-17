# Project: "Chubby, or not chubby, that is the question."
Computer vision problem. Using Kaggle CelebA dataset, Keras, and other Python libraries.

# Project summary
This project needs to answer this one fundamental question: am I chubby?

Classifying someone in the "chubby" or the "not chubby" category is one highly debatable topic. The bias of the observer is tainted by multiple factors of his environment. So when it comes to classifying a subject into one or the other category of weight perception, the observer doesn't have a clear and centralized method of making a choice. In other words, when I'm asking myself the question: "Am I chubby?", what I'm really asking myself is: "Are the members of my own culture classifying me as chubby when they observe me?".

That becomes a headache, because:

a) people tend to not disclose such observations to avoid being rude;<br> 
b) these observations are relative to the observers' background and culture.

But today, we will create a tool to attest if I'm chubby or not, according to cultural standards: celebrities.

Using the Kaggle CelebA dataset, which contains over 200,000 images of anonymized celebrities, we will train a CNN model to classify a face as Chubby=True, or Chubby=False. Hopefully, we will be able to use that model on my own picture, and know the truth about this fundamental question.

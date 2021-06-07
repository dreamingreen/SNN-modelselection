# SNN-modelselection
This is a notebook made for a kaggle challenge. We competed against other collegue students to get the best score at the end.
The dataset is a trained SNN (simple neural network), there are 3 datasets: before training, after training using 2 classes and after training using 4 classes. For this work of finding the best classifier with the best parameters, AT4 was used. This data was obtained from the research lab of our teacher, which made us work on real-life data that no one had touched before.

Here is more detail on how the dataset I used was generated:
https://www.kaggle.com/c/SMEMI309-final-evaluation-challenge-2020/overview
AFTER_TRAINING with 4 classes (AT4): obtained with the same network (trained with 2 classes), after a short STDP-based unsupervised training using all four classes

This part of the project is about selecting the best model with the best parameters, by choosing the classifiers of our choice, according (mainly!) to the training and testing accuracy for the dataset. The work also involves analyzing and explaining how each model acts. At the end, I explained why I chose the specific model.

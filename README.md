# Image-Classification-using-Transfer-Learning-and-optimal-Learning-Rate-Estimation
Classifying Images of 10 categories of animals, using VGG16, ResNet-50 and imagenet. Images have been collected from Google and launched in <a href=https://www.kaggle.com/alessiocorrado99/animals10>Kaggle Data sets</a>. Learning Rates for respective models is Estimated from Epoch Vs Learning Rate graph obtained using **Learning rate finder function.**
Optimal learning rate for VGG16 model is found to be 1e-4 and for ResNet50 as 5e-5. 
**VGG16** model gave a **training accuracy of 97.040 %** and **validation accuracy of 96.210 %.ResNet50** gave a **train accuracy=90.222 %,Val accuracy=90.170 %.**

<a href='https://github.com/naureen20/Image-Classification-using-Transfer-Learning-and-optimal-Learning-Rate-Estimation/blob/master/Animal_10.ipynb#step2'>Image Preprocessing</a> 
Includes Resizing, Reshaping, One-Hot vectorizing categories(animal names), Changing label names from Spanish to English, train-validation split and  Data Augmentation

<a href='https://github.com/naureen20/Image-Classification-using-Transfer-Learning-and-optimal-Learning-Rate-Estimation/blob/master/Animal_10.ipynb#step3.1'>Creating CNN Models with Transfer Learning </a>
Includes creating VGG16 and ResNet50 models, obtaining a graph of Learning Rate vs epochs using the defined <a href='https://github.com/naureen20/Image-Classification-using-Transfer-Learning-and-optimal-Learning-Rate-Estimation/blob/master/Animal_10.ipynb#step3.3'>Defining LEARNING RATE FINDER function </a>

<img src="https://github.com/naureen20/Image-Classification-using-Transfer-Learning-and-optimal-Learning-Rate-Estimation/blob/master/Resnet%20learning%20rate.png">
The above image gives optimal learning rate for ResNet50

<img src="https://github.com/naureen20/Image-Classification-using-Transfer-Learning-and-optimal-Learning-Rate-Estimation/blob/master/Vgg16LearningRate.png">
The above image gives optimal learning rate for VGG16.
>It is Observed that VGG16 gave better accuracy than ResNet50

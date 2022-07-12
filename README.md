# Deep-Learning

## Classification of ASL alphabets

1. Downloaded ASL alphabets image dataset from kaggle (link : https://www.kaggle.com/datasets/grassknoted/asl-alphabet)
    Used the downloaded dataset for training and validating the model.
2. For testing, we took images using our mobile camera. 9 images of each alphabet.
3. Trained three pretrained models:
      1. ALEXNET (https://towardsdatascience.com/alexnet-the-architecture-that-challenged-cnns-e406d5297951)
      2. VGG16 (https://www.geeksforgeeks.org/vgg-16-cnn-model/)
      3. RESNET (https://iq.opengenus.org/resnet50-architecture/)
4. After training the three models, RESNET gave the highest accuracy of the test set of images.

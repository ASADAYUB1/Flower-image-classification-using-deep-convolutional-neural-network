# Flower-image-classification-using-deep-convolutional-neural-network
In this project, I trained a deep learning model for flower recognition on a GPU. I employed a convolutional neural network with residual layers. The hyperparameters used were batch_size=128, arch='ResNet9', epochs=[5, 5, 5, 5], lrs=[0.001, 0.0001, 1e-4, 0.0001], opt=['Adam', 'Adam', 'Adam', 'Adam']. The model achieved an accuracy of 'val_loss': 0.551, 'val_acc': 0.815, 'train_loss': 0.339. 
The dataset is taken from Kaggle (https://www.kaggle.com/alxmamaev/flowers-recognition), consists of 4242 images showcasing various flowers. The collection is assembled from Flickr, Google Images, and Yandex Images. With five distinct classes—chamomile, tulip, rose, sunflower, and dandelion—the dataset offers approximately 800 photos per class. The images, each around 320x240 pixels, serve as valuable resources for plant recognition through photo analysis.



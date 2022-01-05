# Traffic-Sign-Classification
* Deep neural network model that can classify traffic signs present in the image into different categories.
* Read and understand traffic signs which are a very important task for all autonomous vehicles.
* [Dataset](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)
* The dataset contains more than 50,000 images of different traffic signs. It is further classified into 43 different classes.
* CNN model
2 Conv2D layer (filter=32, kernel_size=(5,5), activation=”relu”)
MaxPool2D layer ( pool_size=(2,2))
Dropout layer (rate=0.25)
2 Conv2D layer (filter=64, kernel_size=(3,3), activation=”relu”)
MaxPool2D layer ( pool_size=(2,2))
Dropout layer (rate=0.25)
Flatten layer to squeeze the layers into 1 dimension
Dense Fully connected layer (256 nodes, activation=”relu”)
Dropout layer (rate=0.5)
Dense layer (43 nodes, activation=”softmax”)
*   

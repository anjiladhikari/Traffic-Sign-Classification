# Traffic-Sign-Classification
* Deep neural network model that can classify traffic signs present in the image into different categories.
* Read and understand traffic signs which are a very important task for all autonomous vehicles.
* [Dataset](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)
* The dataset contains more than 50,000 images of different traffic signs. It is further classified into 43 different classes.
* CNN model <br />
2 Conv2D layer (filter=32, kernel_size=(5,5), activation=”relu”) <br />
MaxPool2D layer ( pool_size=(2,2))<br />
Dropout layer (rate=0.25)<br />
2 Conv2D layer (filter=64, kernel_size=(3,3), activation=”relu”)<br />
MaxPool2D layer ( pool_size=(2,2))<br />
Dropout layer (rate=0.25)<br />
Flatten layer to squeeze the layers into 1 dimension<br />
Dense Fully connected layer (256 nodes, activation=”relu”)<br />
Dropout layer (rate=0.5)<br />
Dense layer (43 nodes, activation=”softmax”)
*   

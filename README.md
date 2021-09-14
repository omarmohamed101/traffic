I tried around 20 different networks using different number of Convolutional, max-pooling, hidden layers.
using only one hidden layer the accuracy wasn't the best but using 2 hidden layers with 128 units each gave me +96% accuracy, i tried 3 hidden layers and 4 hidden layers also but the accuracy didn't rise anymore and i found a saturation level around +95%. 

rising the number of Convolutional filter also helped increasing the accuracy. but different kernel sizes didn't help rising the accuracy so 3X3 Convolutional layers and 2X2 max-pooling was good. also using 2 Convolutional layers followed by max-pooling each gave me a significant increase in the accuray. using one Convolutional and one max-pooling was around 5% accuracy which is bad

above and below 0.5 dropout didnt help so 0.5 was good

# APS360-Dog-Breed-Classifier - With transfer learning using ResNet, AlexNet, and EfficientNet!
The project deals with identification and classification of dogs into their respective breeds. The model should be able to give the breed of a dog given an image of one. 
As it can be seen in the code, the accuracy without the use of transfer learning was preety bad. With transfer learning, it improved to ~88%.
Pre-trained weights was imported and frozen to lessent the computation power needed. Therefore, the only trainable parameters were the ones in the fully connected layer.

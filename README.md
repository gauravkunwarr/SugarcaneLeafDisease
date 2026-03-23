# SugarcaneLeafDisease
IncepNet-MobiFusion combines pre-trained InceptionV3 and MobileNet without top layers, keeping weights frozen. Their features are extracted via Global Average Pooling, concatenated, and passed through dense layers with ReLU and dropout. The final softmax layer classifies five sugarcane leaf diseases, trained using Adam and categorical cross-entropy

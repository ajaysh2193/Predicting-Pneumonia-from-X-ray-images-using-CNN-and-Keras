# Predicting Pneumonia from X-ray images using CNN and Keras
## Problem
- Detecting penumonia from X-ray images
- Its a binary classification problem. The two classes are Normal and Pneumonia.
### Normal Patients X-ray images
![norma](https://user-images.githubusercontent.com/24571705/40785432-1bc72fe8-6506-11e8-8aa2-c69d7fbede70.png)
## Pneumonia effected X-ray images
![disease](https://user-images.githubusercontent.com/24571705/40785491-3467e272-6506-11e8-80b5-a85eb96c5db4.png)
## Source of Data
- https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
- The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal).
- There are 5,863 X-Ray images (JPEG) and 2 categories as '1' indicates to Pneumonia and '0' to Normal.
![labels](https://user-images.githubusercontent.com/24571705/40785506-3fc2c6aa-6506-11e8-9533-bec4696f9391.png)
## Results
### VGG16
![vgg16](https://user-images.githubusercontent.com/24571705/40785519-4cfa130a-6506-11e8-8dfa-0864162f52ce.png)
### ResNet50
![resnet](https://user-images.githubusercontent.com/24571705/40785532-5374f4d4-6506-11e8-8743-22cd3f9dd6b7.png)
### InceptionV3
![inceptionv3](https://user-images.githubusercontent.com/24571705/40785545-5e497e34-6506-11e8-9308-ef8b23cad849.png)
### InceptionResNetV2
![incepresnet](https://user-images.githubusercontent.com/24571705/40785562-6574dd48-6506-11e8-8749-2314a3962422.png)
### Xception
![xception](https://user-images.githubusercontent.com/24571705/40785568-6d12be9e-6506-11e8-8319-c55371153039.png)

![results](https://user-images.githubusercontent.com/24571705/40785578-74e0cc24-6506-11e8-968a-a29761fd5446.PNG)
#### VGG16 works best among all models with accuracy of 88.89%


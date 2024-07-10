# Transfer Learning: CIFAR100
This project deals with the **multi-class images classification** of images from the CIFAR-100 Dataset. <br />
### Dataset:
The CIFAR100 dataset has over 60000 32x32 images from 100 different classes. This dataset is split into 5:1 ratio for train and validation. <br />
I have performed data augmentation using "torchvision.transforms" library. In this i performed HorizontalFlipping and Normalization  <br />
### Models:
1) I first started by building a custom **VGG-16** Network with 13 Convolution Layers and a classifier Network.  <br />
2) I used the **EfficientNetB0** Model trained on 1 million+ images from ImageNet Dataset and finetuned it on our data.  <br />
3) Lastly I applied transfer learning on the pretrained **ResNet50 Model** <br />
 <br />
 ### Results:
 Test Accuracy :  <br />
 1) VGG-16: 49%  <br />
 2) EfficientNetB0 : 79%  <br />
 #### 3) ResNet50 : 97%  <br />
 ![172f7d37-7c62-432e-956f-867e928438a9](https://github.com/darKKnight14110/Image-Classfication-CIFAR100/assets/142472592/8567d55e-687b-4134-b117-6b7c8504fea9)
 <br />

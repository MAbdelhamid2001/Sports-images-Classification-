# Sports-images-Classification-
Classify different sports images to know the sport using Transfer Learning

the dataset can be found at:
 https://drive.google.com/file/d/1s07aL-7nvhO8ESJy_uTCZJMF5lw5LAGK/view

* General Techniques Used
  
   1. Different optimizers such as (Adam, SGD)
   2. Early stopping (avoid overfitting)
   3. L2 regularization (reduce overfitting)
   4. BatchNormalization (do normalization between layers, helps to speed 
  training )
   5. Dropout (to reduce overfitting by randomly turning off part of the network 
  and letting the rest of the network train)
   6. Bottleneck (to reduce the number of parameters between layers)
   Data Augmentation (ImageDataGenerator)

* Methodology
  For models such as mobile net v2, vgg19 and inception models,
  We build their architectures from scratch and then load their 
  weights whether from tensor hub or GitHub.
  To feed them to the models then make them unchangeable weights for training for our new data.


with using Mobile Net v2 model:

![image](https://github.com/MAbdelhamid2001/Sports-images-Classification-/assets/81767517/f8822031-cdbc-405c-b06a-a709f3dd237b)

 and VGG19 Model:

 ![image](https://github.com/MAbdelhamid2001/Sports-images-Classification-/assets/81767517/87154e0a-4eb1-4178-b941-c9a9e14940a2)





 
 

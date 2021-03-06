# Transfer_Learning_CNN
## About
Fashion Mnist and "recognize a speaker" datasets were utilized for image classification. For this classification task were tried to apply transfer learning from Mnist Fashion to "Recognize a Speaker" and transfer learning inside of Mnist Fashion. Two deep convolutional neural networks architectures, namely simple (Figure 1) and complex (Figure 2).
<br />
<br />
<br />

![image](https://user-images.githubusercontent.com/60938391/125195374-f8dcfc00-e25d-11eb-8cd0-53eecaddffb8.png)
<br />
```
Figure 1: Complex CNN architecture.
```
   



<br />
<br />
<br />

![image](https://user-images.githubusercontent.com/60938391/125195846-393d7980-e260-11eb-99b9-036e668c74d6.png)
<br />
```
Figure 2: Simple CNN architecture.
```


## Mnist Fashion  
Fashion-MNIST is a dataset of Zalando's article images consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.  
Labels = ['T-shirt', 'Trouser', 'Pullover', 'Dress', 'Coat', 'Sandal', 'Shirt', 'Sneaker', 'Bag' & 'Ankle boot']  
<br />
<br />
<br />
![image](https://user-images.githubusercontent.com/60938391/125195357-e6fb5900-e25d-11eb-86a0-dd968b832222.png)
<br />
```
Figure 3: Mnist Fashion samples.
```
#Recognize a speaker
Dataset that contains wav rec file from 5 different speakers. From the purpose of this project every wav sample were converted to melspectrogram (red scale).  
Labels = ['Benjamin_Netanyau', 'Jens_Stoltenberg', 'Julia_Gillard', 'Magaret_Tarcher' & 'Nelson_Mandela΄] 

![image](https://user-images.githubusercontent.com/60938391/125196052-fdef7a80-e260-11eb-9122-6e2b73e649ec.png)
<br />
```
Figure 4: Recognize a speaker samples.
```

## Transfer Learning  
  The two datasets were utilized for image classification. For this classification task were tried to apply transfer learning from Mnist Fashion to "Recognize a Speaker" and transfer learning inside of Mnist Fashion. Transfer learning (TL) is a research problem in machine learning (ML) that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem [West et.al. 2007]. Were utilized the 2 different CNN architectures for the same transfer learning experiments just for comparing. 
  
## Transfer Learning tasks  
•	Train Under5 labels Fashion Mnist.  
•	Pretrained (Under5 labels Fashion Mnist) & Train Over5 labels Fashion Mnist.  
•	Pretrained (Under5 & Over5 labels Fashion Mnist) & Train all labels Fashion Mnist.  
•	Pretrained (Under5 labels Fashion Mnist) & Train all labels Fashion Mnist.  
•	Pretrained (Under5 labels Fashion Mnist) & Train “Recognize a Speaker”.  
•	Pretrained (Under5 & Over5 labels Fashion Mnist) & Train “Recognize a Speaker”.  
•	Pretrained (Under5 & all labels Fashion Mnist) & Train “Recognize a Speaker”.  





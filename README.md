# LEDNet-Person-Portrait-real-time-efficient-segmentation

### Requirements 
 - Tensorflow 1.13  
 - Keras 2.2
 - OpenCV 3.4

### Some Results
<img src="https://github.com/anish9/LEDNet-Person-Portrait-real-time-efficient-segmentation/blob/master/Results/thumbs1.jpg" alt="Smiley Sface" height="600" width="800">
<img src="https://github.com/anish9/LEDNet-Person-Portrait-real-time-efficient-segmentation/blob/master/Results/thumbs3.jpg" alt="Smiley Sface" height="600" width="800">

# Watch it Real time below
[![IMAGE ALT TEXT HERE](https://github.com/anish9/LEDNet-Person-Portrait-real-time-efficient-segmentation/blob/master/Results/sshot.png)](https://www.youtube.com/watch?v=sVEN_rJeQkM)
[![IMAGE ALT TEXT HERE](https://github.com/anish9/LEDNet-Person-Portrait-real-time-efficient-segmentation/blob/master/Results/tys.png)](https://youtu.be/lzETTz1RV7c)

## To train follow the below link
https://github.com/anish9/LEDnet-keras

## To Run infernce 
##### Run inference.ipynb to test.
```
predict("/home/anish/test.jpg")

```

## Model Info
> Model file is just 21Mb which makes it compact for real world efficiency.(pre_trained weights is available on weights folder) 

> Trained for 50 epochs with batch size of 3 because of constrained GPU(Learning Rate decay Used) which is different from  original implementation.

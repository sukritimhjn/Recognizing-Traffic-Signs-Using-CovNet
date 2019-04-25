# Recognizing-Traffic-Signs-Using-CovNet
Given a color image of Traffic Sign, the model recognizes what signal it is

Dataset used : "German Traffic Sign Recognition Benchmark(GTSRB)", containing 40,000 images, related to 43 traffic signs; created by researchers of "Institue fur Neuroinformatik", Germany

The CNN architecure used :
1) 2D convolution, 5X5, 32 filters
2) 2D convolution, 5X5, 64 filters
3) Flattenizer
4) Fully connected layer, 1024 units
5) Dropout 40% (while training only)
6) Fully Connected layer, no activation
7) Softmax output
![image](https://user-images.githubusercontent.com/13365458/56727191-cd998f80-676d-11e9-970b-2ca5a8b2d7b0.png)

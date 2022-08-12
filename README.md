# Digit-Recognition
Programs to Identify the numbers/digit written on the mails, letterheads, etc

Automated handwritten digit recognition is widely used today. The dataset is taken from MNIST contains 1000 training examples which are 20x20 images which are unrolled into a 400 dimensional vector which gives us a 1000 x 400 matrix X. We used a neural network to recognize two handwritten digits, zero and one. We used two methods to predict using the tensorflow library [loss = BinaryCrossEntropy and optimizer = Adam with 0.001 were used] and second using vectorization in the numpy library. Both methods almost predicted the digits as they were given in the ‘y’ of the test dataset. 

In a variety of multimedia services, one of the useful techniques is image compression. Digitizing the image requires more bandwidth, which in turn increases the cost of data transmission. Therefore, neural networks are utilized to make effective use of bandwidth. Additionally, Deep Learning has recently advanced to the point where it is being utilized for image compression. Any color in the visible spectrum can be created by combining Red, Green, and Blue (RGB) in various proportions.

Using the MNIST (Modified National Institute of Standards and Technology) dataset, up-sampling and down sampling of an image is performed and I propose a Convolutional Auto encoder neural network for image compression. After up-sampling and down-sampling an RGB image, a compressed image is obtained that measures 28 by 28 pixels with noise. The final image should still have the original size of 28 by 28 after compression.

The main objective is to compress an image without affecting the quality of image radically.

TECHNOLOGY USED:

Tensorflow version 2.5.

Numpy version 1.2.2.

Open CV version 4.20.0.

Matplotlib version 3.3.4

Convolutional Neural Network

Adam Optimizer

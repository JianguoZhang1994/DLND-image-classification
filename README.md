# TensorFlow-image-classification-CNN

**Jianguo Zhang, March 7, 2017**

We build a **Convolutional Neural Network** to classify [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) with **60000** images
The dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 

The program written by [jupyter notebook](http://jupyter.org/) and run on [AWS EC2](https://aws.amazon.com/rds/aurora/) g2.2xlarge GPU instance type with 32GiB storage.  ![image](https://github.com/JianguoZhang1994/DLND2-image-classification-CNN/blob/master/intance_type.png)

 You can also run on your local GPU device with ***TensorFlow=1.0***, ***python=3.6***. If you run on local CPU device like macbook pro with 16G memory, it will be very slow. 
 
## For running the program, follow the steps:

**Set up** environment

`conda create -n dnld2-image-classification`

**Install** tools

`pip install tensorflow tqdm matplotlib numpy`

***Note in macOS/Linux, when you install tensorflow, it will install related tools like numpy, six, wheel automatically, but you may also need to install tqdm and some other tools if needed.***

**Run** dlnd_image_classification.ipynb 

`jupyter notebook`

The server home should open in your browser. By default, the notebook server runs at http://localhost:8888. If you aren't familiar with this, localhost means your computer and 8888 is the port the server is communicating on. As long as the server is still running, you can always come back to it by going to http://localhost:8888 in your browser.

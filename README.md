# DLND2-image-classification-CNN
We build a **Convolutional Neural Network** to classify [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) with **60000** images
The dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 

The program writted by [jupyter notebook](http://jupyter.org/) and run on [AWS EC2](https://aws.amazon.com/rds/aurora/) g2.2xlarge instance type with 32GiB storage.  ![image](https://github.com/JianguoZhang1994/DLND2-image-classification-CNN/blob/master/intance_type.png)

You can also run on your local GPU device with python=3.6, tensorflow=1.0. Following the steps:
**set up environment**
`conda create -n dnld2-image-classification`

**install tools**
`pip install tensorflow tqdm matplotlib numpy`
***Note in macOS, when you install tensorflow, it will install related tools like numpy, six, wheel automatically, but you may also need to install tqdm and some other tools needed.***

**run** dlnd_image_classification.ipynb 
`jupyter notebook`
The server home should open in your browser. By default, the notebook server runs at http://localhost:8888. If you aren't familiar with this, localhost means your computer and 8888 is the port the server is communicating on. As long as the server is still running, you can always come back to it by going to http://localhost:8888 in your browser.

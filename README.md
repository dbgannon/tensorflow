# Tensorflow ExperimentsThis directory contains several of the experiments described in the blog at www.esciencegroup.com.   ## k-meansthis is the ipython notebook for the k-means experiment.  k-nearest-improved is a revised version of the one first published in the blog.  This new one is based on the excellent example from Shawn Simister that is on github at https://gist.github.com/narphorium/d06b7ed234287e319f18.  Shawn's version is better documented and about 20% faster when N is 10000000. ##convolutional neural network experimentTwo files here.   One is exactly like the example in the Tensorflow tutorial except that it also saves the trained model to a file.   It also saves the test images for later use.The second file is the example described in the blog.   it reads the trained model and sets up the network so that it can be used to classify samples.
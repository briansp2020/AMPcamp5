# AMPcamp5 Hands-On Exercise
I'm currently taking [MOOC Introduction to Bit Data with Apach Spark](https://www.edx.org/course/introduction-big-data-apache-spark-uc-berkeleyx-cs100-1x). As an exercise to gain more experience, I'm also going through [AMP camp 5](http://ampcamp.berkeley.edu/5/) hands-on exercise using IPython notebook and posting it here. To run this note book, you need to download USB stick's content from [here](http://d12yw77jruda6f.cloudfront.net/ampcamp5-usb.zip). Then, extract the content to your machine and copy the notebook to the root directory of the USB file content.

I chose to use Anaconda python distribution 2.2.0 and Spark 1.4.0 on Ubuntu 14.04 LTS. This [blog post](http://blog.prabeeshk.com/blog/2014/10/31/install-apache-spark-on-ubuntu-14-dot-04/) has instruction on how to install Spark locally.

Once everything is setup, just type
>IPYTHON_OPTS="notebook" pyspark

from the root directory of the USB file content and select the notebook you want to run.

For the second lab, I used tachyon 0.6.4 prebuilt bindary from [here](https://github.com/amplab/tachyon/releases/download/v0.6.4/tachyon-0.6.4-bin.tar.gz). However, I have not been able to get the second part of the example working yet since the code was given in scala only.

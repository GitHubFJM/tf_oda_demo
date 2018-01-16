# tf_oda_demo
[0] tf object dection api

https://github.com/tensorflow/models

Please refer to the g3doc under research/object_dection folder.

If you're using windows, the recommend steps is
1. Anaconda 4.2 because you will only be able to use tf with python 3.5 on windows so far, Jan 2018. The installation path to anadonda should not contain any empty space. (i.e. please do not follow the default path "program files") Because some python app you need to build might throwing issue because it were designed for linux and cannot bypass this break.
I don't recommend you to use setup the mirror in Qinghua as some blog said, because anaconda 4.2 has covered everything I need to a demo but the mirror doesn't which lead to issues during pip install.
2. You'd better installing cuda8 with the cudnn which is matching your Navidia series. Per my exp to i5 cpu training and Geforce 840m training, cpu needs 22sec to a global step but gpu only need 2.4 sec based sdd model. It doesn't mean Titan X have a better score when comparing to Geforce 840m but if you want to train 100m data within 3 days, please buy one or multiple Titan X, to lend a cloud DL from vendor, or setup your own distribution training framework.
3. Install tensorflow-gpu with pip or tensorflow if you don't have an N-card.
4. Download the tf models.

[1] How to train data via existing model

http://blog.csdn.net/wei_guo_xd/article/details/78585555?locationNum=10&fps=1

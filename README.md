# tf_oda_demo
[0] tf object dection api
https://github.com/tensorflow/models

Please refer to the g3doc under research/object_dection folder
If you're using windows, the recommend steps is
1. Anaconda 4.2 because you will only be able to use tf with python 3.5 on windows. The installation path to anadonda should not contains empty space (i.e. please do not follow the default path "program files") to avoid some python tools or lib has call stack issue.
2. You'd better have cuda8 with the cudnn matches your gpu. Because the testing result is i5 cpu train has only 10% performance comparing to Geforce 840m. It doesn't mean Titan X have a better score but if we're talking about 100m dataset or your cnn config is exhausting gpu resource, I do believe cpu makes you suffer and you might regret not buying a computer with Navinder.
3. Install tensorflow-gpu with pip or tensorflow if you don't have an N-card. I don't recommend you to use setup the mirror in Qinghua, because anaconda 4.2 has covered everything I need to a demo and the mirror doesn't and not always matching your system.
4. Download the tf models.

[1] How to train data via existing model: 
http://blog.csdn.net/wei_guo_xd/article/details/78585555?locationNum=10&fps=1

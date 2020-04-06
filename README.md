1、如何知道当前pytorch当前的版本？<br>
import torch<br>
print(torch.__version__)<br>
2、三款Linux桌面环境下的网页制作工具<br>
Screem、Bluefish和Quanta Plus <br>
3、scikit-learn sklearn 0.18 官方文档中文版<br>
https://blog.csdn.net/chinachenyyx/article/details/75299043<br>
4、从github远程仓库抓取数据<br>
git fetch origin 会抓取从你上次克隆以来别人上传到此远程仓库中的所有更新（或是上次 fetch 以来别人提交的更新）<br>
![fromremotetolocal](https://github.com/Ryan-Lily/python-learning-notes/blob/master/images/Fetch-and-Pull.png)<br>
5、github中的README.md文件是使用Markdown语法编写的，基本语法的网址为：https://www.appinn.com/markdown/<br>
6、[使用github搭建网站](https://blog.csdn.net/pipisorry/article/details/51707366)<br>
7、pytorch在GitHub上的发布地址：https://github.com/pytorch/pytorch/releases  
8、linux的账号是记录在/etc/passwd文件里面的，而密码则是保存在/etc/shadow。  
9、sudo passwd 设置root的密码；passwd 设置自己的密码  
10、[pip 是一个流行的 Python 包管理工具，提供了对 Python 包的查找、安装、下载、卸载的功能。](https://blog.csdn.net/liuchunming033/article/details/39578019)  
11、如何查看python软件包(eg:torch)的安装位置：pip show torch  
12、如何查看python的安装位置：which python  
13、我们可以在bash中键入help来查看所支持的所有内置命令。内部命令是shell程序的一部分，通常在linux系统加载运行时加载并驻留在系统内存中。其执行速度比外部命令快，但功能简单。外部命令是linux系统中的实用程序部分，在需要时才将其调用内存。其功能通常都比较强大，但运行速度较慢。  
14、[linux命令中find、locate、which、whereis、type的区别](https://www.cnblogs.com/jycjy/p/6940544.html)  
15、[ubuntu系统安装pycharm的方法](https://www.jetbrains.com/help/pycharm/install-and-set-up-pycharm.html#linux)  
*使用snap安装管理软件包：sudo snap install <pycharm-professional·or·pycharm-community> --classic  
*源文件安装：下载源文件->解压->打开bin目录->./pycharm.sh  
16、运行python文件(eg:module1.py)的三种方法  
*作为程序运行：$ python module1.py  
*作为模块运行：1. $ python 2. >>> import module1  
*作为脚本运行：1. 在python文件首行增加代码：#!/usr/bin/python 2. 给文件赋予执行权限：chmod +x module1.py 3.执行脚本文件./module.py  
17、python中的分号(;)用来分隔一行中的多个语句，不建议使用，尽量每行只写一条语句。python中的逗号(,)用于构建元组。  
18、[ubuntu系统安装remarkerable的方法](https://blog.csdn.net/jq_ak47/article/details/54313983)  
19、[linux系统中安装google chrome的方法](https://blog.csdn.net/cv_you/article/details/77340262)  
20、[解决kaggle邮箱验证不能confirm的问题](https://blog.csdn.net/zs15321583801/article/details/79674741)  
21、[pip 安装包时超时（read timed out）问题解决办法](https://blog.csdn.net/github_37216944/article/details/69500990)  
22、[如何查看用pip命令安装的软件的安装路径](https://blog.csdn.net/jiangmengying01/article/details/78966174/)  
23、[pytorch可视化工具visdom启动失败解决方法](https://blog.csdn.net/qq_22194315/article/details/78827185)  
24、[the way over the wall](https://briian.com/7509/)  
25、[免费的黑客书籍-2018](http://omgfoss.com/best-ethical-hacking-pdf-books-free-download/)  
26、[免费的黑客书籍-2017](https://techviral.net/best-hacking-ebooks/)  
27、[2018年最佳黑客書籍盤點](https://tdaily.news/tech/88184)  
28、[RFC文档](https://www.rfc-editor.org/)  
29、[ubuntu系统设置开机自启动项](https://www.cnblogs.com/EasonJim/p/7573292.html)  
30、[ubuntu系统查看和结束进程](https://blog.csdn.net/caomin1hao/article/details/78700282)  
31、[medium网站的机器学习实战](https://medium.com/machine-learning-in-practice)  
32、全球十大人工智能领域科学家:  
*[Geoffrey E. Hinton](http://www.cs.toronto.edu/~hinton/)、[Yann LeCun](http://yann.lecun.com/)  
*[Yoshua Bengio](http://www.iro.umontreal.ca/~bengioy/yoshua_en/index.html)、[Michael I Jordan](https://people.eecs.berkeley.edu/~jordan/)  
*[Jeff Hawkins](https://numenta.com/)、[Sebastian Thrun](http://robots.stanford.edu/)  
*[Demis Hassabis](https://deepmind.com/)、[Jürgen Schmidhuber](http://people.idsia.ch/~juergen/)  
*[Terry Sejnowski](https://www.salk.edu/scientist/terrence-sejnowski/)、[Tom M. Mitchell](http://www.cs.cmu.edu/~tom/)  
33、[ubuntu下用conda安装opencv](https://blog.csdn.net/wds2435629591/article/details/78694463)  
34、bantu系统中鼠标变成十字不能移动的解决办法  
![image](https://github.com/Ryan-Lily/python-learning-notes/blob/master/images/ubuntu%E9%BC%A0%E6%A0%87%E5%8F%98%E6%88%90%E5%8D%81%E5%AD%97%E5%BD%A2%E7%8A%B6%E6%97%A0%E6%B3%95%E7%82%B9%E5%87%BB.png)<br>    
35、[PyTorch项目代码与资源列表](http://www.sohu.com/a/164171974_741733)  
36、深度学习研究人员：[何恺明](http://kaiminghe.com/)  
37、# torch.float()将该tensor投射为float类型：float_tensor = tensor.float()  
38、[colab中使用pytorch运行tensorboard的方法](https://medium.com/looka-engineering/how-to-use-tensorboard-with-pytorch-in-google-colab-1f76a938bc34)  
39、[TensorBoard in PyTorch](https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/04-utils/tensorboard)  
40、[tensorboardX](https://github.com/lanpa/tensorboardX)  
41、[TensorBoardColab](https://github.com/taomanwai/tensorboardcolab)  
42、[变分自动编码器的详细推导过程](https://blog.csdn.net/ustbfym/article/details/78870990)  
43、ubuntu系统中确定显卡信息：lspci |grep VGA  
44、[如何使用colab运行google云盘中的文件:1、from google.colab import drive 2、drive.mount('/content/drive/')](https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d)  
45、[linux系统中的V2ray安装教程](https://www.v2ray.com/chapter_00/install.html)  
46、[自建v2ray服务器教程](https://gitlab.com/Alvin9999/free/wikis/%E8%87%AA%E5%BB%BAv2ray%E6%9C%8D%E5%8A%A1%E5%99%A8%E6%95%99%E7%A8%8B  )
47、[免费IT书籍网站](http://www.allitebooks.org/)  
48、[ImportError: No module named conda.cli的解决方法：bash Anaconda3-2018.12-Linux-x86_64.sh -u](https://www.wandouip.com/t5i217365/)  
49、[v2ray的安装和使用教程-已墙](https://www.v2ray.com/chapter_00/install.html)  
50、[本地浏览器设置v2ray代理的方式](https://unixetc.com/post/v2ray-client-configuration-example-in-ubuntu/)  
![image](https://github.com/Ryan-Lily/python-learning-notes/blob/master/images/%E6%9C%AC%E5%9C%B0%E6%B5%8F%E8%A7%88%E5%99%A8v2ray%E8%AE%BE%E7%BD%AE.png)<br>   
51、pytorch中使用tensorboard需要的相关软件版本  
![image](https://github.com/Ryan-Lily/python-learning-notes/blob/master/images/tensorboard%E7%9B%B8%E5%85%B3%E8%BD%AF%E4%BB%B6%E7%89%88%E6%9C%AC.png)  
52、[UDACITY分享的免费课程《PyTorch深度学习实战》课程](https://cn.udacity.com/course/deep-learning-pytorch--ud188)    
53、[pip安装软件过程中的权限问题几解决方案](https://blog.csdn.net/zhe_csdn/article/details/99430519)   
54、[ Ubuntu 系统下 apt-get 彻底卸载软件包的方法 ](https://learnku.com/articles/16390)  
55、[ubuntu find 查找文件并删除](https://blog.csdn.net/jiao_zhoucy/article/details/8757564)  
56、[解决PIP下载安装速度慢](https://www.cnblogs.com/shengwang/p/9979764.html)  
57、[The system is running in low-graphics mode时解决方法](https://blog.csdn.net/qingfengxiaosong/article/details/83042724)  
58、ubutun系统清空终端屏幕命令：reset  
59、[Linux搭建V2Ray客户端](https://www.wandouip.com/t5i197953/)    
1.1 在线安装  
sudo su  
bash <(curl -L -s https://install.direct/go.sh)  
1.2 离线安装  
先到github上下载v2ray-linux-64.zip压缩包，并放在ubuntu的本地  
wget https://install.direct/go.sh  
sudo bash go.sh --local ./v2ray-linux-64.zip   
其中go.sh是安装自动化脚本，使用该脚本执行下载下来的离线安装包，安装过程需要root权限.  

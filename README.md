# python-dlib
python安装dlib存在很多问题，往往需要dlib-19.7.0-cp36-cp36m-win_amd64.whl文件或者dlib-19.19.0-cp37-cp37m-win_amd64.whl文件，这里给出这两种文件包，并说明操作方法

本步骤主要解决python的pip安装dlib库会存在许多问题，通常是采用下面步骤。
dlib-19.7.0-cp36-cp36m-win_amd64.whl是针对使用python36的朋友
dlib-19.19.0-cp37-cp37m-win_amd64.whl是针对使用python37的朋友
1.首先，将dlib-19.7.0-cp36-cp36m-win_amd64.whl文件或者dlib-19.19.0-cp37-cp37m-win_amd64.whl存放到任意文件夹
2.win+R 打开命令行窗口，通过cd指令进入存放该文件的文件夹
3.执行指令：pip install dlib-19.7.0-cp36-cp36m-win_amd64.whl
            或者pip install dlib-19.19.0-cp37-cp37m-win_amd64.whl
4.再次执行pip install dlib就ok了

### Pyh 模块不支持中文的解决方法

##### 1. 下载最新的pyh 模块

  ```
  ###从github 下载最新的Pyh模块, pyh-master.zip
  unzip pyh-master.zip
  cd pyh-master
  
  ###打开pyh.py文件
  vi pyh.py
  
  ###在f.write(doctype)下面添加一行
  f.write(charset)
  ```
  ![](https://github.com/yabolu/python-Pyh-chinese-garble/blob/master/pyh.png)
##### 2. 安装
  
  ```
  ###下面正常安装即可
  python setup.py install 
  ```

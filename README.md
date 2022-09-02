# linux
linux learning
# Lunix基本命令

## 基本功能

1. `pwd` [^ print working directory,展现你目前在哪里]



2. `/`  [^ 根目录]



3. `ls`[^ list，将当前环境的文件像列表一样列出来]

​        linux里面，所有皆为文件



4. `cd` [^ change directory，改变目录，将自己改变到想去往的路径]

example：cd home [^ 进入根目录]

此时写入pwd，结果是/home

5. `cd ..`[^朓回到上一级目录]



##  拓展功能

1. `ls /` [^ls命令后加一个空格，加上你想查询的路径，直接列出所需路径里的文件，自己却保持在目录里]

``` 相当于以下三条
*目前处于根目录
cd ..
ls
cd home 

*利用ls/
ls /
```

2. `cd/`[^ 直接进入目录中的目录]

   ```
    *目前处于home目录下
      cd ..      *回到根目录
      cd user   *进入user目录
      cd bin    *进入到user目录里的bin目录
   
    *利用cd /
      cd /user/bin  绝对路径的写法
      cd ./../user/bin 相对路径的写法 .是当前目录 ..是上一级目录
      cd ../user/bin  这样写也可以，系统自动识别了你在当前目录，故./可以不写
   ```



#  ls的进阶

1.  `ls -l /`  [^ -l指long，以长列表的形式展示信息,，以字节的方式展现]

2.  `ls -h /`[^ -h指human，以人类可读的形式展示]



# 如何自学命令

1. `命令 --help` [^ 看命令有啥用]

2. `man 命令` [^ man手册，看命令有啥用，按Q退出，enter翻页]

192.168.1.109

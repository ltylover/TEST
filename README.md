任务报告
我在8月底加入了先锋招新群，首次开始接触git
当时群里有过一次对git的讨论，虽然我都没答到点子上，但通过讨论加深了对git的理解
其中印象最深的是“快照”的描述，这也是git不同于其他版本控制最为特殊的一点
暑假里我下载git（现在下好了），总是出错，没能及时学习，但GitHub for windows成功下了下来，进行一定程度的学习

首先我注册了github账号，在git上建立自己的库
打开git，需要首先配置自己的信息
$ git config --global user.name"ltylover"
$ git config --global user.email"1192588363@qq.com"
然后检查配置信息
$ git config --list
建立git仓库
$ git init
后来又学到了克隆远程仓库
$ git clone https://github.com/ltylover/lty
然后git告诉我路径已存在，我？？？
我也学会了其他一些git的命令行操作
创建一个README.md
$ echo "lty">README.md
查看文件状态
$ git status
会发现一个文件给被修改
跟踪文件
$ git add README.md
再把它从文件暂存区提交到库
$ git commit -m"add a file"
查看记录
$ git log
试着操作并记住其他那个PDF上git的基础操作

后来发现自己的git并没有和远程建立联系
通过搜索引擎
$ ssh-keygen -t rsa -C "1192588363@qq.com"
回车后建立了联系
ssh  -T git@github.com
打了yes
这一块不太熟悉

目前正在学习c语言，图书馆借了书
只学到了运算符与表达式，我的visual c++绿色版老是抽风
我服了
但我国庆待在东北大学（嘿嘿嘿）



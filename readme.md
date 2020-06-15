git init 
git add *
git commit -m ' '
//配置本机与github链接用ssh密钥
//创建密钥文件，将生成的密钥写入文件中

//查看密钥 cat ~/.ssh/id_rsa.pub
- xxx.pub 文件表示的是  密钥文件

//第三部：来到github    [new ssh]将ssh密钥复制进去，建立电脑与github链接

如何将本地仓库添加到远程仓库
- 第一步：创建远程仓库  创建一个本地仓库（如有请忽略）
- 第二步：创建本地仓库与远程仓库的链接 
    git remote add origin git@github.com/xuetyan/my-items.git
    语法总结    git remote add origin
- 第三步：将本地仓库添加到远程仓库 git push -u origin master
   -    git push    添加
   -    -u  表示谁添加的
   -    origin  表示组织
   -    master  组织

如果说更改需要添加到远程
    git add ------->    git commit  ------> git push

注意：只有第一次 才需要建立电脑与github的链接
     只有是一个新的仓库 才需要建立  本地仓库与远程仓库的链接
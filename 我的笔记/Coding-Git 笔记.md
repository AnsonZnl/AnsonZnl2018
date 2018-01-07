## 第一次创建coding 仓库 实现线上线下同步
- 创建一个目录 已经创建则不用写``mkdir coding ``
- 进入这个目录``cd coding`` 在已创建的目录下右键打开git hsbh
- 初始化成git仓库``git init``
- 新建一个 介绍文档 便于别人了解项目``echo "# coding" >> README.md``
- 切换状态 ``git add README.md`` 由编辑文件切换成暂存文件
- ``git commit -m "first commit"``由暂存文件切换为分支文件(成品)
- 第一次提交与网上的仓库对应``git remote add origin https://git.coding.net/AnsonZnl/coding.git``
- ``git push -u origin master``把本地仓库内容传到网上 提示用户名和密码 提交成功 后续可省略-u

- 初始化成git仓库``git init``
- 切换状态``git add``
- 切换状态``git commit``
- 同步线上仓库的地址``git remote add origin URL ``
- 将本地仓库传至线上``git push ``
------------------------------------------------------
- ``git init`` 初始化成git仓库
- ``git status`` 查看状态 
- 编辑区  (出红色英文是中文编译后的格式)
- ``git add 要传的文件名`` 可由编辑区转入暂存区 如果都传上则 ``git add .``   同步  
- 暂存区  绿色 已经存到暂存区
- ``git commit -m"备注信息"``
- 分支(成品)
- ``git remote add origin +URL`` 同步线上仓库的地址(仅第一次)
- 指定远程主机
- ``git push -u origin master``
- ``git push origin master``(后续可不输-u)
- 同步到线上
----------------------------------------------------------------
## 我的另一台电脑怎么同步线上仓库的内容
* #### 我的另一台电脑怎么同步线上仓库的内容
- 首先 新建文件夹(最好英文)
- 在新建文件夹内 打开 git bush 
- 执行 ``git clone URL``URl 是你仓库里提供的url
- 私有的回车弹出请输入用户名和密码
- 公共的直接clone成功
- 输入正确则克隆成功
- 修改后也可提交线上仓库
- ``git config --global user.email "1160030724@qq.com"``
- ``git config --global user.name "AnsonZnl"``
- ``git add .``
- ``git add`` 要传的文件名 如果都传上则 ``git add .``   同步 
- ``git commit -m"备注信息"``
- ``git status`` 查看状态 
- 编辑区  (出红色英文是中文编译后的格式) 
- 暂存区  绿色 已经存到暂存区
- ``git commit -m"备注信息"``
- ``git push origin master``
- 同步到线上
## 源文件要与网上最新版本同步
- 回到原文件后如何与网上同步
- ``git pull`` (把线上的东西拉下来)
- 回车输入账户和密码
-------------------------------------
## 我同事怎么下载我的文件
- 共有仓库可直接进入仓库点击克隆
- 私有文仓库则:
- 添加你的私有项目成员 搜索账号或者邮箱添加
- 新建文件夹
- ``git clone URL`` 此URL是仓库的url 
- ^本地没有仓库可以通过clone命令下载远程仓库
- 回车弹出用户名和密码为 同事的 输入正确即可colne 成功
- ``git pull`` 如果本地有仓库 可以同步远程仓库的最新版本



![2017-11-21_143332](http://upload-images.jianshu.io/upload_images/7072486-f17a38158514ca0f.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/700)





上传不上去的文件去网页手动上传即可。或者也可以
```git add -f 要上传文件名```
- ``-f``强制上传

- 修改线上的厂库里的内容只需这几步 
- ```git clone URL```
- 克隆后修改。修改后
- ``cd 克隆的文件``
- ``git add .``
- ``git commit -m"注释内容"``
- ``git push origin master ``
输入账户密码就OK了
- 

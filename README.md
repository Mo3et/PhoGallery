# PhoGallery
Private PhoGallery

##### 获取图床外链的方法

> **将链接中的blob改为raw即可获得外链**  
**
例  https://github.com/Mo3et/PhoGallery/**blob**/master/image-20200429134721855.png  
修改为 https://github.com/Mo3et/PhoGallery/**raw**/master/image-20200429134721855.png  
获得https://**raw.githubusercontent.com**/Mo3et/PhoGallery/master/image-20200429134721855.png  
**
或者用Issues  直接把pho拖动到里面Write里面发布即可

##### Git  
git add .        （注：别忘记后面的.，此操作是把Test文件夹下面的文件都添加进来）

git commit  -m  "提交信息"  （注：“提交信息”里面换成你需要，如“first commit”）

git push -u origin master   （注：此操作目的是把本地仓库push到github上面，此步骤需要你输入帐号和密码）

1.  git init //初始化仓库

2.  git add .(文件name) //添加文件到本地仓库

3.  git commit -m "first commit" //添加文件描述信息

4.  git remote add origin + 远程仓库地址 //链接远程仓库，创建主分支

5.  git pull origin master // 把本地仓库的变化连接到远程仓库主分支

6.  git push -u origin master //把本地仓库的文件推送到远程仓库

### 9.Markdown 图片
Markdown 图片语法格式如下：

![alt 属性文本](图片地址)

![alt 属性文本](图片地址 "可选标题")
开头一个感叹号 !  
接着一个方括号，里面放上图片的替代文字  
接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的 'title' 属性的文字。

![My github image](https://avatars1.githubusercontent.com/u/34803812?s=460&v=4 "头像")

当然，你也可以像网址那样对图片网址使用变量  
这个链接用 1 作为网址变量 [Github image][1].  
然后在文档的结尾为变量赋值（网址）
[1]: https://avatars1.githubusercontent.com/u/34803812?s=460&v=4


Markdown 还没有办法指定图片的高度与宽度，  
如果你需要的话，你可以使用普通的 <img> 标签。

<img src="https://avatars1.githubusercontent.com/u/34803812?s=460&v=4" width="50%">
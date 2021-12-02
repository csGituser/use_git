一、clone代码

1.把大神的代码clone到本地，或者clone自己github上的代码，使用指令：

> git clone [https://github.com/yoyoketang/yoyoketang.git](https://links.jianshu.com/go?to=https%3A%2F%2Fgithub.com%2Fyoyoketang%2Fyoyoketang.git)

2.在本地随便建个文件夹，地址栏输入cmd打开，然后输入上面指令

![img](https:////upload-images.jianshu.io/upload_images/5702200-c385ec628f576055.png?imageMogr2/auto-orient/strip|imageView2/2/w/900/format/webp)

image.png

二、git status查看状态

1.查看当前的git仓库状态，可以使用git status

> git status

2.如果是在刚才新建的文件夹输入git status会出现下图1所示，git目录不对

3.先用cd 命令切换到yoyoketang这个repository目录

4.再输入git status可以看到On branch master，这个说明已经在master分支上了

![img](https:////upload-images.jianshu.io/upload_images/5702200-e5e39a6eda9b7a2b.png?imageMogr2/auto-orient/strip|imageView2/2/w/904/format/webp)

image.png

三、更新代码

1.在yoyoketang文件夹下更新东西，比如我上传2个资料文件

![img](https:////upload-images.jianshu.io/upload_images/5702200-029c2b50e61b463e.png?imageMogr2/auto-orient/strip|imageView2/2/w/832/format/webp)

image.png

2.更新后使用git add * (*是更新全部）

> git add *

3.接着输入git commit -m "更新说明“，commit只是提交到缓存区域

> git commit -m "更新说明“

![img](https:////upload-images.jianshu.io/upload_images/5702200-5e0784c703d80c4a.png?imageMogr2/auto-orient/strip|imageView2/2/w/889/format/webp)

image.png

4.如果是多人同时开发维护代码，得先git pull ,拉取当前分支最新代码

> git pull

5.最后git push origin master,最后一步才是push到远程的master分支上

(最好不要上传太大文件，要不然太慢了)

![img](https:////upload-images.jianshu.io/upload_images/5702200-189d9a731f2e3feb.png?imageMogr2/auto-orient/strip|imageView2/2/w/833/format/webp)

image.png

6.打开github界面就能看到同步了

![img](https:////upload-images.jianshu.io/upload_images/5702200-dac03add3ac53520.png?imageMogr2/auto-orient/strip|imageView2/2/w/1034/format/webp)





作者：Doggers
链接：https://www.jianshu.com/p/803be5f58caf
来源：简书
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。
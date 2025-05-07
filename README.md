# screeps-chinese-pack-release
screeps-chinese-pack-release（油猴插件的js，应用于steam汉化）

现在说的是screeps:world最新汉化解决方法，因为老方法通过在package.nw里面的index.html添加

```language-javascript
<script src="https://screeps-cn.gitee.io/screeps-chinese-pack-release/main.js" async defer></script>
```

的这个方法已经不行了,因为gitee挂了，已经翻译不了了

具体https://www.jianshu.com/p/a0aaff7204b0查看这个连接

![](https://i0.hdslb.com/bfs/article/0117cbba35e51b0bce5f8c2f6a838e8a087e8ee7.png)

接下来我说的是新方法

这边通过油猴脚本的翻译的代码解决的，这个油猴脚本是可以翻译screeps:world的网页版，那么只需要一点手段也可以翻译steam版本的screeps:world

https://greasyfork.org/zh-CN/scripts/416651-screeps-chinese-pack这个是油猴脚本的地址

![img](https://i0.hdslb.com/bfs/article/0260722077ee1ce04ca26e0dc9a564b11995158.png@1192w.webp)

这是脚本的代码

这里通过把油猴的脚本全部复制出来，粘贴到txt文本里面，如果上面的油猴脚本地址打不开，这边我把全部代码贴在教程的最下方，到时候复制就可以了

![img](https://i0.hdslb.com/bfs/article/a566197ec3fb2e852991adeb5889821f1995158.png@1192w.webp)

把代码复制到桌面新建的txt里面

这个文件夹随便命名，这边我就叫他fy.txt

然后把他的后缀txt改成js

![img](https://i0.hdslb.com/bfs/article/b74b7da4578fa576a73209839370da1f1995158.png@228w_216h.webp)

改成fy.js

接下来这边这个文件放在电脑哪里都没关系，到时候只要路径正确就可以了

这边我就把他放在这个游戏的根目录下面

D:\Program Files (x86)\Steam\steamapps\common\Screeps

![img](https://i0.hdslb.com/bfs/article/bdd512082f49f086fbc75eaa527cf1dc1995158.png@1192w.webp)

我放在这个目录下面

然后记住你放的目录的地址这个到时候就要贴在index.html的文件里面

接下来这里还是按照以前的步骤，用解压文件直接打开package.nw，但是不要解压

![img](https://i0.hdslb.com/bfs/article/7ee4b8651f064d23f00517be7b2904261995158.png@1192w.webp)



![img](https://i0.hdslb.com/bfs/article/db41b3c9685c60205c9923df87937e7a1995158.png@1192w.webp)

直接用解压软件打开

然后右键点击index.html文件，点击编辑

![img](https://i0.hdslb.com/bfs/article/7dde070d75e4bb4879d41d0310e55beb1995158.png@1192w.webp)

右键点击编辑

这时候把前面放的fy.js的文件的路径和文件名按照这个格式贴在这个的代码上面，也就是我红框圈出来的的这个地方

```language-javascript
<script type="text/javascript" src="file:///D:/Program%20Files%20(x86)/Steam/steamapps/common/Screeps/fy.js" async defer></script>
```

其中D:/Program%20Files%20(x86)/Steam/steamapps/common/Screeps/fy.js这一块就是你实际放的文件的路劲和你的实际的文件名，这里特别注意的是，如果的你的文件路径中文件夹的名字带有“空格”，就像我的Program Files (x86)这个路径中的这个文件夹名字，空格需要用“%20”代替

![img](https://i0.hdslb.com/bfs/article/4744bfc6e29bc86bd383222629eb39951995158.png@1192w.webp)

贴上你的文件路径和文件名字

贴上路径好了之后，就Ctrl+S保存下，关闭记事本

这时候你的解压软件就会提示你这个，这时候点“是”就应用了

然后就关闭解压软件就可以了

![img](https://i0.hdslb.com/bfs/article/4c113fc4a68ece182cc7b18818ba5ecb1995158.png@1192w.webp)

这时候steam打开游戏

点击这个按钮

![img](https://i0.hdslb.com/bfs/article/13c86459877c1a5fbd0a509dec9930ca1995158.png@1192w.webp)



![img](https://i0.hdslb.com/bfs/article/b1b9be2a35c2dfb3a77d5750d339a36a1995158.png@1192w.webp)

然后就会发现汉化成功了，就可以开始玩这个游戏了

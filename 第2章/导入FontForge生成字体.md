# 导入FontForge生成字体

```
如需交流，请加微信：goodfont（微信加好友，搜索微信名即可）
本教程由做字体网（www.zuoziti.com）友情提供！建议从序言部分开始阅读学习。
```

------

> ### **本节视频教程**

<iframe src="//player.bilibili.com/player.html?aid=431954399&cid=875198503&page=1&high_quality=1&danmaku=0" 
        width="100%" 
        height="400" 
        frameborder="no" 
        scrolling="no" 
        allowfullscreen>
</iframe>

> ### **FontForge导入步骤**

　　前面我们切割好了小图片，下面就要正式生成字体了。以下教程是用FontForge导入python脚本实现导入生成字体的，所以你的电脑如果没有安装python的话还要先安装这个。文末有免费下载地址。 

1. 先把小图片放进一个文件夹中，FontForge一次性导入的小图片不要太多，太多容易卡死，我是分成四个文件夹分批导入，每个文件夹最多放置3000个左右。而且这个软件貌似有个bug，就是第一个小文件夹放置多个小图片会导致不显示进度，所以不知道导入到第几个小图片了。我是这样解决的，第一个文件夹中只放置一个小图片，导入完第一个后再接着导入第二个文件夹，第二个文件夹就可以放置好几千个了，大家根据自己电脑性能琢磨下数量吧。  
   ![img](../images/daoru01.jpg)  
2. 打开FontForge，点击New，新建一个文件。  
   ![img](../images/daoru02.jpg)  
3. 点击Encoding→Compact（或者直接按住Alt，注意是按住，然后依次按N，C，注意是依次），这一步是清空界面，方便查看。  
   ![img](../images/daoru03.jpg)  
4. 点击File→Execute Script，导入脚本。（或者直接按住Alt，然后依次按F，X）  
   ![img](../images/daoru04.jpg)  
5. 把我们的导入脚本内容复制进去（**脚本文件在本文末有下载**），**这里打开的TXT文件先不要关闭，要不然复制不进去，很奇怪，巨坑**。  
   ![img](../images/daoru05.jpg)  
6. 注意把这里的小图片存放路径改成你自己的，还有单次最大导入数量，我这里设置了3436，如果你单次数量超过这个数了，也要改成你自己的哦，其他勿动。完成后点击OK。（或者直接按住Alt+O）  
   ![img](../images/daoru06.jpg)  
7. 开始工作了，这里是滚动的导入记录。  
   ![img](../images/daoru07.jpg)  
8. 本批次所有小图片导入完，也可以继续导入其他目录下的小图片。这里没继续导入，演示的是导出字体文件。点击File→Generate Fonts。（或者直接按住Alt，然后依次按F，G）  
   ![img](../images/daoru08.jpg)  
9. 这里是默认保存位置，初始格式为PS type1（pfb），我们需要TrueType（ttf）。所以把格式改成TrueType，把Validate Before Saving前面的钩取掉，不需要验证，点击Generate保存文件。  
   ![img](../images/daoru09.jpg)  
10. 这里选择Yes默认即可。这样就导出了TTF字体文件了。  
    ![img](../images/daoru10.jpg)  
11. 完成后就可以关闭软件了，选择保存还是不保存项目文件就看你了。我一般都是不保存，有字体文件了这个项目文件也没用了。  
    ![img](../images/daoru11.jpg)  
12. 导出的字体文件默认保存位置在此。（注意：分批制作字体导出文件时这里要改一下文件名，如：Untitled2.ttf，Untitled3.ttf等，要不然会覆盖前面导出的文件哦）大功告成！  
    ![img](../images/daoru12.jpg)  

> ### **下载本文相关软件及脚本**

　　本人是一个小白开发者，本人的原则是凡是网上能搜索到的软件本站一律不收费，只有本人原创的一些辅助小软件才酌情收费，本着量贩式的原则用到哪个下载哪个，当然你也可以用其他的一些软件去替代。开发软件很艰难、书写教程很辛苦，希望你能赏我一杯咖啡☕，多谢！  

**python本站版本免费下载地址：**https://wwno.lanzouf.com/b018c01xg 密码:fcrl   
**FontForge本站版本免费下载地址：**https://wwz.lanzouq.com/i3DjF05b7wwd 访问密码：6jb2  
**FontForge导入脚本下载地址：**https://mbd.pub/o/bread/ZZaUlJ9x

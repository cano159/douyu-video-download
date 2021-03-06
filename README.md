# 如何下载斗鱼直播回放视频？

> 说明：这里下载的是斗鱼视频（v.douyu.com），不是直播

有时候我们觉得斗鱼上的某些视频内容不错，想下载下来怎么办？这里提供两个方法。

方法一是使用手机浏览器自带的缓冲视频功能进行缓冲，方法二是使用下载工具下载视频文件。如果对其中某个不感兴趣的，可以略过。

## 方法一：手机浏览器缓冲视频

如果你不需要一个完整的视频文件而只是想要把某些视频保存下来的话，可以使用QQ手机浏览器/UC手机浏览器等，访问斗鱼视频页面，对视频进行缓冲。

**但是缓冲下来的视频只能在当前浏览器里观看，如果从手机的文件浏览器查看是不能直接播放的，你看到的也只是几十KB的m3u8文件，而不是完整的视频文件。而且不能传到电脑或者网盘里。**

**如果需要合并缓冲的文件，需要下载文件合并APP，请参考：[手机uc视频缓冲合并教程](http://jingyan.baidu.com/article/d2b1d1029b67a75c7e37d420.html "手机uc视频缓冲合并教程")**

### 方法步骤

这里假设使用QQ手机浏览器

#### 1、用QQ浏览器打开斗鱼视频播放页

可以直接访问[斗鱼视频](https://v.douyu.com/ "斗鱼视频")（https://v.douyu.com/） 或打开斗鱼APP并找到想要缓冲的视频，然后通过分享等方式得到视频链接。

####  #Q1 斗鱼APP的视频在哪里？

新版本（2.4.3.1）斗鱼APP的视频在发现->热门视频->更多里。

![斗鱼视频](https://dn-shimo-image.qbox.me/SjZUuW8lFJA1Y3Qt/douyu.jpg)

#### 2、点击视频播放并下载

打开页面后，需要点击视频开始播放，大概等待1-2秒后，可以看到视频的右下角出现一个下载的小图标，点击这个小图标即可开始缓冲（下载）视频。

![视频下载按钮](https://dn-shimo-image.qbox.me/6FQshjr6m0Iqemm3/douyu2.jpg "视频下载按钮")

开始下载后，在手机的通知栏里会出现下载进度条，也可以在浏览器中查看下载进度。

![浏览器下载功能](https://dn-shimo-image.qbox.me/pPZrKmNyPvMIMb46/douyu3.jpg "浏览器下载功能")

![浏览器下载列表](https://dn-shimo-image.qbox.me/4lARf5biztwEqK69/douyu4.jpg "浏览器下载列表")

其他手机浏览器也都大同小异，大部分都有相似的功能。

#### #Q2 手机百度为什么不行？

**如果你这平板电脑上使用手机百度，可能会出现这种情况：打开从APP分享过来的链接，结果发现页面中一直刷新，提示你网络未连接或网络错误。**

初步判断出现这种情况的原因是：

打开的视频链接是PC端的，当在平板上打开时，斗鱼将自动检测，发现是平板电脑，于是将链接重定向到手机版网页，而重定向之后，手机版网页也自动检测，发现不是手机访问，于是再次将网页重定向到PC版网页，于是将成了死循环，网页不停地重定向和刷新。

**解决方案：改用其他手机浏览器吧 ʅ（´◔౪◔）ʃ**


## 方法二：使用下载工具下载视频文件

**说明：此方法略复杂，可能会花费你一点时间。**

### 需要的工具

- Firefox火狐浏览器
- Ant.com video downloader 浏览器插件
- 记事本（Notepad）
- Excel
- 迅雷等下载工具
- CMD命令行工具

### 步骤

#### 1、打开火狐浏览器插件页，并安装Ant.com video downloader插件

![](https://dn-shimo-image.qbox.me/IysFxEJDF2kSOwUX/aa.jpg)


![插件详情](https://dn-shimo-image.qbox.me/2L4zJRfkYjgzO5Ip/image.png "插件详情")

插件安装完成之后，在浏览器右上角可以看到一个下载图标。

![视频下载插件](https://dn-shimo-image.qbox.me/cWHukWRwkwIhTTkR/image.png "视频下载插件")

#### 2、配置插件

点击插件下载图标旁的下箭头↓，选择Preferences（配置），其中：
- `Display Mode`改为`Toolbar`
- `Downloaded movies folder`可以改为想要保存视频的地址

> 说明：因为这款插件不能满足我们的所有需求，所以这里保存视频的文件夹在哪里关系不大，并不一定实际在这里保存所有视频。

#### 3、打开斗鱼视频详情页，获取视频真实地址

打开想要下载的视频详情页，如：https://v.douyu.com/show/rjNBdvnpJGmME2yw

页面加载完成之后，可以看到视频插件`download`图标有动画，点击`download`可以看到当前可下载的视频列表。

![](https://dn-shimo-image.qbox.me/BirY87VNJ24me9QG/image.png)

由于斗鱼的视频是分段的，一个视频会分成多个ts格式视频，所以在视频列表中可以看到多个文件。

鼠标左键点击列表倒数第二个，即开始下载。（这个文件是完整视频的第一段）

![插件中的视频列表](https://dn-shimo-image.qbox.me/4dFQ1eqQieUJsvuN/11.png "插件中的视频列表")

下载完成之后，可以在浏览器右上角找到已下载的文件。鼠标右键点击刚刚下载的文件，选择`复制下载链接`。

![浏览器下载文件列表](https://dn-shimo-image.qbox.me/EsyIEoAfWh4yBnRN/11.png "浏览器下载文件列表")

打开记事本，将复制的链接粘贴进去，大致是这样的：

```
http://vodhls1.douyucdn.cn/live/normal_live-740260rk8MibHW8n--20170110144756/d7311d31f6d44ab19591a128365be1db_0000000.ts?k=4b06eac9d87d0b3a52033045f305f5b9&t=587f7d4c&d=8FA98E9BC44E92B00EFF1EE78184E262&u=79712663&ct=web&vid=148236
```


这就是完整视频的第一段视频真实地址。

#### 4、视频地址拆解

地址可以拆解为三段：

```
#1
http://vodhls1.douyucdn.cn/live/normal_live-740260rk8MibHW8n--20170110144756/d7311d31f6d44ab19591a128365be1db
#2
_0000000.ts
#3
?k=4b06eac9d87d0b3a52033045f305f5b9&t=587f7d4c&d=8FA98E9BC44E92B00EFF1EE78184E262&u=79712663&ct=web&vid=148236
```

可以看到第二段地址为7个0，这表示序列号，从0开始顺序增加，每个视频总段数不相同：

```
_0000000.ts
_0000001.ts
_0000002.ts
_0000003.ts
...
```

打开一个Excel表格或下载这个表格（[Excel表格模板文件](https://shimo.im/api/file/rYiyYkZwtbw5sK0o/attachments/XhSzldrEXQQr3yE0 "模板Excel表格")），将第一段复制到`Sheet1`的`A3`单元格中，第三段复制到`A4`单元格中。

#### 5、视频总数计算

上面这个仅仅是完整视频的第一段，我试着下了一个两个多小时的视频，总共分了784段，怎么计算的呢？

如果有模板的可以在表格的`A6`单元格写入视频的时长分钟数，在`B6`单元格写入视频的秒数，如一个视频时长11分12秒，则分别写入11和12，再比如视频时长为2小时18分钟37秒，则分别写入138`（2*60+18）`和37。

写入之后，将自动在`C6`单元格计算出总秒数（小时X3600+分钟X60+秒），并在`D6`单元格计算出大概的视频总数。

不使用模板的也可以自己大致算一下。

视频的总秒数为小时X3600+分钟X60+秒：

```
=A6*60+B6
```

视频的总分段数为：总秒数/10，再取整

```
=ROUND(C6/10,0)
```

![视频总段数计算方法](https://dn-shimo-image.qbox.me/VLiUSeadkyQ0V0ac/11.png "视频总段数计算方法")

#### 6、分段视频地址获取

知道视频分段地址的规则和总分段数之后，剩下的就简单了。

已经下载模板的可以选择`Sheet2`，如果你已经按照上面的步骤做了，那么此时你只需要复制B列的地址即可。

假设计算出的视频总段数是10段，那么可以连续选择`Sheet2`的`B1`单元格到`B9`或`B10`单元格的内容，这些就是所有分段视频的地址。

![所有分段视频的地址](https://dn-shimo-image.qbox.me/alWDWIjO9c0IsCFm/11.png "所有分段视频的地址")

如果没有下载模板，也可以在Excel中选择`Sheet2`，在`A1`单元格中粘贴`_0000000.ts`，然后拖动单元格右下角，复制单元格内容，这样就可以在表格的`A列`中得到从0开始递增的结果，如上图A列一样。

然后选中`B1`单元格，写入函数：

```
=CONCATENATE(Sheet1!$A$3,A1,Sheet1!$A$4)
```

函数的含义就是将`Sheet1`表格的`A3`单元格、当前表格`Sheet2`的`A1`单元格和`Sheet1`表格的`A4`单元格进行字符串拼接。

函数写入之后，单元格内容将自动变化成视频地址。

同样的，需要将`B1`单元格内容拖动复制。

**你可以多复制几个地址，以防万一视频不完整，如果是多出来的，不存在的视频，肯定是下载不成功的。**

#### 7、下载分段视频

打开迅雷或其他的下载软件，将刚才复制的分段视频地址粘贴到任务中，开始下载。

![迅雷批量下载](https://dn-shimo-image.qbox.me/ije2nTSuykI1MMvC/11.png "迅雷批量下载")

因为每个视频都只有1、2M，比较小，所以下载起来比较快。

#### 8、合并文件

**下载完成之后，打开保存文件夹，将刚刚下载的所有视频文件（.ts格式）剪切到一个新的文件夹中，需保证此文件夹中的文件都是同一个视频的分段文件，而且是完整的。**

![下载的分段文件](https://dn-shimo-image.qbox.me/1Z94xmU2wkUtnCmx/11.png "下载的分段文件")

在这个文件夹的空白处按住`shift`键，并点击鼠标右键，选择`在此处打开命令窗口`，打开CMD命令行工具。

![](https://dn-shimo-image.qbox.me/dQmV3ljei5ApyqAE/11.png)

在打开的命令行工具中输入：

```
copy/b *.ts all.ts
```

![](https://dn-shimo-image.qbox.me/PVbt9q9O8YIh1CzS/11.png)

按下`Enter`键后命令将执行，这个命令的含义是：将当前文件夹中所有的`.ts`格式文件合并成一个文件`all.ts`，这个`all.ts`文件就是完整的视频文件了。

> PS：你可以复制上面的命令，然后在命令行工具中右键->粘贴。在命令行中，`Ctrl+V`是无效的。

合并文件的过程很快，当完成时，中命令行中也会提示你：

```
1 file(s) copied.
```

![](https://dn-shimo-image.qbox.me/aQKvE4jIoYQCCO7F/image.png)

这个时候，视频就合并完成了。除了这个合并的文件`all.ts`，其他的文件都可以删除了。(◡ᴗ◡✿)

> PS：刚才用火狐浏览器也下载了一段视频，也没用了，可以删掉。


## 参考

- [斗鱼网视频下载方法视频教程](http://v.youku.com/v_show/id_XMjIyMTM5NzUzMg==.html "斗鱼网视频下载方法视频教程")
- [UC浏览器（安卓版）如何下载或者缓存视频？](http://jingyan.baidu.com/article/f7ff0bfc196a312e26bb1315.html "UC浏览器（安卓版）如何下载或者缓存视频？")
- [手机uc视频缓冲合并教程](http://jingyan.baidu.com/article/d2b1d1029b67a75c7e37d420.html "手机uc视频缓冲合并教程")

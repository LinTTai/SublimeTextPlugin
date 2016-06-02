#如何安装Emmet到Sublime text 3?
***

>####[Emmet的Git地址](https://github.com/sergeche/emmet-sublime#readme)
>**Emmet的前身是大名鼎鼎的Zen coding,它使用防CSS选择器的语法来生成代码，大大提高了HTML/CSS代码编写的速度**
<br/>

##<font face="宋体">安装步骤
<font size="4">
**第一步：**
	

1. 下载<font color="#0099ff">sublime_piackage_control-master.zip</font> 
2. 解压命名文件夹为Package Control。(注意大小写)

**第二步：**


1. 下载sublime_package_control-python3.zip
2. 解压后覆盖到刚刚的Package Control中，完成插件API函数的更新。 

**第三步：**


1. 打开Sublime Text 3,
2. 选择菜单：Preference-->Browse Package... 浏览插件 点击进去跳到文件目录

![](http://a1.qpic.cn/psb?/V12kCjlT4GNOPp/agFqOtOQhZQLX0sJRj6yvNrVNIF0vRpSiMhCR2Z1CiU!/b/dOQAAAAAAAAA&bo=5gJ4AQAAAAADB78!&rf=viewer_4)
<br/>

**第四步：**


1. 将Package Control复制到打开的目录下
2. 重启Sublime Text 3
3. 查看Perferences菜单多出两个Package，说明安装成功
<br/>
![](http://r.photo.store.qq.com/psb?/V12kCjlT4GNOPp/URSkXIH4W9hf5LZM.K7NMac8*PjOhSRYc4MRw8sZd78!/r/dOEAAAAAAAAA)

**第五步：**

1. 点击菜单Preference--->Package Control 
2. 点击Install Package
<br/>
![](http://a2.qpic.cn/psb?/V12kCjlT4GNOPp/96gI5PfgpLRd25dWuMUGMQNo5mDdSKkvru8JQ*rOkyI!/b/dOUAAAAAAAAA&bo=ewJIAnsCSAIFCSo!&rf=viewer_4)
3. 输入emmet
<br/>
![](http://r.photo.store.qq.com/psb?/V12kCjlT4GNOPp/cwyrRIOc8EvMavLkFEbKC68znDfvYuKxkRhh9xDs06k!/r/dNoAAAAAAAAA)

**第六步：**

安装完成会屏幕显示如下:自动安装PyV，安装完成后重启Sublime Text 3
<br/>
![](http://r.photo.store.qq.com/psb?/V12kCjlT4GNOPp/TF9BoW3z3amw*hqgz3N3hjE0DmGEuOJPdZIkITV4Mdg!/r/dAsBAAAAAAAA)

**第七步：测试**

重启后还会看到左下角再次呈现Loading PyV8 的提示，待其载入完成，新建一个文档进行测试，输入命令（不行就重启）：
<br/>
ul#test>li*4
<br/>
按<font color="red">Ctrl+e</font> 生成
<br/>

	<ul id="test">
		<list></list>
		<list></list>
		<list></list>
		<list></list>
	</ul>

---
感谢这位仁兄，此篇借鉴于[如何将Emmet安装到到 Sublime text 3？](http://www.cnblogs.com/tinyphp/p/3217457.html)

至此安装结束啦~祝好运！
</font>

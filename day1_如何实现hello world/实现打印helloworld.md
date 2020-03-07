# 实现打印helloworld

## 1.在wxMEdit上输入二进制代码，生成helloworld镜像

1.第一步，打开wxMEdit软件点击按钮实现二进制到16进制的转变（方便书写）
![](image\Hex.jpg)

2.第二步，编辑文件，依次填入

![](image\code1.jpg)
![](image\code2.jpg)
![](image\code3.jpg)

其余空位一律填0

一共1440 * 1024 = 1474560个字节

随后另保存为hello_os.img(注意是.img镜像文件)

## 将hello_os.img加载至虚拟机

1.首先设置虚拟机属性

![](image\Floppy.jpg)

2.将hello_os.img添加至软盘

3.启动

4.便可得到如下界面
![](image\helloworld.png)
---
title: MarkDown编辑器及基础功能代码
description: 计算机中MarkDown相关的知识
published: true
date: 2023-03-03T05:57:36.031Z
tags: 计算机, markdown
editor: markdown
dateCreated: 2023-03-03T05:55:37.775Z
---


## Typora下载

[点击下载Typora](https://www.bilibili.com/read/cv17890918)

（里面有免费的序列号分享）

## 标题功能

采用 #+空格 表示标题

#表示一级标题（最大）

##表示二级标题

###表示三级标题

......以此类推（最多到六级标题）



## 字体功能

字体格式在Typora中可用*和~表示

> *Hello,world!*				斜体(前后*)
>
> **Hello,world!**			加粗(前后**)
>
> ***Hello,world!***			加粗斜体(前后***)
>
> ~~Hello,world!~~			删除线(前后~~)

## 引用功能

> 通过苦难，走向欢乐。——贝多芬

引用功能只需用 > 加上空格 即可实现

## 分割线功能

---

***

分割线可用---或***来快速实现



## 图片功能

要添加图片需用以下代码

```
![给图片取个名](里面填在线图片的链接或者本地图片的路径)
#如实现下面这张图片的添加可用此代码
![截图2](https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fsafe-img.xhscdn.com%2Fbw1%2F7782bbf1-f525-4a5c-95e8-6b3e265eef85%3FimageView2%2F2%2Fw%2F1080%2Fformat%2Fjpg&refer=http%3A%2F%2Fsafe-img.xhscdn.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1680413008&t=3544dd2add396d861c6cea209968547d)
```

![截图2](https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fsafe-img.xhscdn.com%2Fbw1%2F7782bbf1-f525-4a5c-95e8-6b3e265eef85%3FimageView2%2F2%2Fw%2F1080%2Fformat%2Fjpg&refer=http%3A%2F%2Fsafe-img.xhscdn.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1680413008&t=3544dd2add396d861c6cea209968547d)



## 超链接功能

[点击跳转到CSDN博客](https://www.csdn.net/)

[点击跳转百度](www.baidu.com)

```
#实现上述功能代码如下
[点击跳转到CSDN博客](https://www.csdn.net/)
[点击跳转百度](www.baidu.com)

#基本格式
[文本说明](该网站的地址)
```



## 列表功能

1. A
2. B

- A
- B

```
在1. 后跟空格，换行后即可自动出现2. (按逻辑顺序下去)
小黑圈用*后跟空格实现
```



## 表格功能

右键空白处——插入——表格     即可快速插入某行某列的表格

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |
|      |      |      |

```
名字|性别|生日|
--|--|--|
张三|男|2000.1.1|
```

用以上代码可生成如下表格

| 名字 | 性别 | 生日     |
| ---- | ---- | -------- |
| 张三 | 男   | 2000.1.1 |



## 代码功能

```java
//public class HelloWorld：
//HelloWorld是一个public的公有的类
 
public class HelloWorld {
 
    //HelloWorld {}：
    //花括号{}：表示了HelloWorld这个类的开始和结束
 
    //public static void main(String[] args)：
    //主方法，程序的入口
    //main(){}:方法的开始和结束
 
    public static void main(String[] args) {
 
        //System.out.println("HelloWorld");:
        //输出HelloWorld到屏幕
        //;代表程序结束
        
        System.out.println("HelloWorld");
    }
}

```

上面是一段JAVA的Helloworld代码

```
#输入TAB键上方的点号 ··· （输入三个点号后按下回车键 即可出现代码栏了）
```












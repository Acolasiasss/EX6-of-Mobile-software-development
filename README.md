# 2022年夏季《移动软件开发》实验报告



<center>姓名：张丁月  学号：20020007099</center>

| 姓名和学号？         | 张丁月，20020007099                 |
| -------------------- | -------------------------------- |
| 本实验属于哪门课程？ | 中国海洋大学22夏《移动软件开发》 |
| 实验名称？           | 实验6：安卓APP首页          |
| 博客地址？           | https://www.cnblogs.com/amonologue/p/16629254.html                          |
| Github仓库地址？     | https://github.com/Acolasiasss/EX6-of-Mobile-software-development                          |

（备注：将实验报告发布在博客、代码公开至 github 是 **加分项**，不是必须做的）



## **一、实验目标**

做一个APP首页，包括顶部图片、顶部菜单栏、中部消息模块、底部Tab按钮。学习 ScrollView, RelativeLayout，以及插件之间的穿插使用。



## 二、实验步骤

列出实验的关键步骤、代码解析、截图。
1.首先将页面上分为四个部分：顶部图片模块、顶部菜单模块、待办消息模块和底部Tab按钮
（示例如下）
![图片1.png](../_resources/图片1.png)

2.然后首先创建父布局，新建ScrollView ，创建ScrollView 内部父布局

![2.png](../_resources/2.png)

3.然后创建顶部首页显示栏，设置宽高、文字、字体样式、字体颜色和字体居中

![3.png](../_resources/3.png)

4.创建顶部图片，设置宽高，src加载图片，设置边距

![4.png](../_resources/4.png)

5.菜单栏模块
首先创建一个横向的LinearLayoutLinearLayout来作为菜单栏的父布局，再次创建一个LinearLayout作为单个按钮的父布局，创建上边的图片按钮,并设置其属性，设置按钮底部文字并赋予其属性

![5.png](../_resources/5.png)

6.消息模块
首先创建一个横向的LinearLayout来作为菜单栏的父布局，然后创建待办Textview，接着创建更多Textview

![6.png](../_resources/6.png)

7.底部Tab模块
首先创建一个横向的LinearLayoutLinearLayout来作为菜单栏的父布局，再次创建一个LinearLayout作为单个按钮的父布局

![7.png](../_resources/7.png)

## 三、程序运行结果

列出程序的最终运行结果及截图。
最终效果如下（可滑动）：

![8.jpg](../_resources/8.jpg)

![9.jpg](../_resources/9.jpg)

## 四、问题总结与体会

描述实验过程中所遇到的问题，以及是如何解决的。有哪些收获和体会，对于课程的安排有哪些建议。
本次实验难度较以前稍微有些大，难在如何去布局各板块以及如何定义各板块的属性（该选择LinearLayout还是ScrollView布局等），还有就是中间“待办”板块的创建，因为没有给出示例，所以自己花了一些时间摸索，但这也正好加深了我对此实验的印象。总的来说本次实验收获很大。
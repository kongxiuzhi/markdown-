# markdown语法学习
## 0.目录
* 1.斜体和粗体
* 2.分级标题
* 3.超链接
    * 3.1 行内式
    * 3.2 参考式
    * 3.3 自动链接
* 4.锚点
* 5.列表
    * 5.1 无序列表
    * 5.2 有序列表
    * 5.3 定义型列表
    * 5.4 列表缩进
    * 5.5 包含段落的列表
    * 5.6 包含引用的列表
    * 5.7 包含代码区块的引用
    * 5.8 一个特殊情况
* 6.引用
    * 6.1 引用的多层嵌套
    * 6.2 引用其它要素
* 7.插入图像
    * 7.1 行内式
    * 7.2 参考式
* 8.内容目录
* 9.注脚
* 10.LaTex公式
    * 10.1 $表示行内公式
    * 10.2 $$表示正行公式
* 11.流程图
* 12.表格
* 13.分割线
* 14.代码
    * 14.1 行内式
    * 14.2 缩进式多行代码
    * 14.3 用六个\`包裹多行代码
    * 14.4 HTML原始码
----
## 1.斜体和粗体
* 代码：
```
    1.*斜体*或_斜体_
    2.**粗体**
    3.***加粗斜体***
    4.～～删除线～～
```
* 显示效果：
    +  *这是以行斜体子*<br>
    +  **这是粗体字**<br>
    +  ***这是斜体加粗***<br>
    +  ~~这是删除~~
----
## 2.分级标题
* 第一种写法
```
    1.这是一个一级标题
    ===========================
    
    2.这是一个二级标题
    ------------------------------
```
* 第二种写法：<br>
```
    1. # 一级标题
    2. ## 二级标题
    3. ### 三级标题
    4. #### 四级标题
    5. ##### 五级标题
    6. ###### 六级标题    
```
----
## 3.超链接
```
Markdowm 支持两种形式的超链接语法： 行内式和参考式两种形式，行内式使用较多
```
* 行内式
    * 语法形式
```
        []里写链接文字，()里写链接的地址，()中的“”中可以为链接指定title属性，title属性是当 
        鼠标悬停在链接上时显示指定的title文字。
        语法： [链接文字](链接地址 "链接地址title") 注：链接地址后面有一个空格
```
* 代码
```
    1.欢迎来到[GITHUB](https://github.com/ "是一个面向开源及私有软件项目的托管平台")
```
* 效果显示
    + 1.欢迎来到[GITHUB](https://github.com/ "是一个面向开源及私有软件项目的托管平台")
* 3.2参考式
```
    参考式超链接一般用在学术论文上面，或者另一种情况，如果某一个链接在文章中多处使用，
    那么使用引用 的方式创建链接将非常好，它可以让你对链接进行统一的管理。
    语法说明：
        1.[链接文字][链接地址标记]
        2.在文中任意位置添加 [链接标记]：链接地址 “链接标题” 注意：链接地址后有空格
```
* 代码
```
      1.我经常使用的几个网站[BING][1]、[][2]以及[GITHUB][]，[stackoverflow][]是一个不错的网站
      2.
      3.[stackoverflow]:https://stackoverflow.com/ "解决问题的网站"
      4.[1]:www.bing.com "搜索网站"
      5.[2]:https://www.zhihu.com/ "中文社区"
      5.[3]:https://github.com/ "托管平台"
```

* 显示效果
    + 我经常使用的几个网站[BING][1]、[知乎][2]以及[GITHUB][3]，[stackoverflow][]是一个不错的网
   
   [stackoverflow]:https://stackoverflow.com/ "解决问题的网站"
   [1]:https://www.bing.com "搜索网站"
   [2]:https://www.zhihu.com "中文社区"
   [3]:https://www.github.com "托管平台"
   
* 3.3 自动链接

```
    语法说明：
    Markdown 支持以比较简短的自动链接形式来处理网址和电子邮件信箱，只要是用<>包起来， 
    Markdown 就会自动把它转成链接。一般网址的链接文字就和链接地址一样，例如：
    代码：
        1.<http://example.com/>
        2.<address@example.com/>
```
* 显示效果

<http://example.cmo/><br>
<address@example.cmo>

----
## 4.锚点

网页中，锚点其实就是页内超链接，也就是链接本文档内部的某些元素，实现当前页面中的跳转。<br>
比如我这里写下一个锚点，点击回到目录，就能跳转到目录。 在目录中点击这一节，就能跳过来。<br>
还有下一节的注脚。这些根本上都是用锚点来实现的<br>


----

## 5.列表

* 5.1 无序列表
    使用 *，+，-表示无序列表。

    **代码：**
```
    1.- 无序列表一
    2.- 无序列表二
    3.- 无序列表三
```
* 显示效果:
    
    - 无序列表一
    - 无序列表二
    - 无序列表三


    

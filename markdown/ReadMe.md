# 一级标题  
## 二级标题
### 三级标题
#### 这是h4
##### h5
###### h6
####### 大于6个#号无效

*这是斜体前后各一个星号*  
_这也是斜体，使用前后各一个下划线_  
**这是粗体，前后各两个星号**  
***这是粗体加斜体，前后各三个星号***  
~~这是删除线，前后各两个波浪线（左上角1旁边的）~~

文末后两个空格键表示换行  
文末后两个回车键表示下一个段落

新段落  

这是h1，在文本下方添加=号
==  
这是h2，文本下方两个-号。两个符号随意
--

>这是引用，使用一个大于符号
>>使用两个大于，表示引用嵌套

### 列表的操作

#### 无序列表：
* 使用一个星号和空格
+ 使用加号和空格
- 使用减号和空格


#### 有序列表：
1. 数字加英文句点和空格表示
2. 第二个

## 代码  
`使用反引号（左上角1旁边的）。代码中若有&、<和>都会自动转义。`  
**GitHub风格的代码引用：**
```
这是代码区域，使用3个独占一行的反引号。写上所属语言将生成特定代码样式
```    

## 分割线  
3个连续星号
***  
3个不连续星号
* * *
3个不连续减号
- - -
3个连续减号（换行否则变标题）

---

## 链接  
[栀墨赏读网](https://www.acdiost.ink)  
[栀墨赏读网](https://www.acdiost.ink "栀墨赏读网title")  

[1]:https://yunmian.netlify.com
[西红柿网络][1]  
<a href='https://www.acdiost.cc' target='_blank' title="标签链接" alt="博客">博客</a>  

## 图片  
![pic](/img/learn.jpg)  
[![pic](/img/learn.jpg "title 本地图片 带链接")](https://opensource.org/licenses/mit-license.php)  
![pic](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1550659649323&di=54be93ae6273a68849e4732984cf2820&imgtype=0&src=http%3A%2F%2Fpic.962.net%2Fup%2F2016-9%2F2016918165638676.jpg)  
<div align=center> ![这是一张图片](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1550659595566&di=6ca2f732a93e5ea4907fa1f70985f154&imgtype=0&src=http%3A%2F%2Fwww.5577.com%2Fup%2F2017-2%2F14866183837734587.jpg "居中")</div>
<div align=right> ![这是一张图片](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1550659595565&di=7cab6a8cdc773a412c17d0320c1d4d82&imgtype=0&src=http%3A%2F%2Fcdn.duitang.com%2Fuploads%2Fitem%2F201611%2F12%2F20161112095429_kZsnz.thumb.224_0.jpeg "居右且不支持调整大小，有的是支持的")</div>  
<img src='/img/learn.jpg' alt='描述' title='直接使用img标签改变大小' width='100' />  

## 转义 \  
\\  
\`  
\*  
\_  
\{}  
\[]  
\()  
\#  
\+  
\-  
\.  
\!  

## 内联HTML  
任何的html标签及其内容都会原样输出、不会做转义  
```html
<font color='red'>文字颜色示意</font>
```
<font color='red'>文字颜色示意</font>

## 表格  
**冒号决定了位置**  

|item|key|value|
|:-|-:|:-:|
|goods居左居左居左|id居右居右居右|price居中居中居中|
|goods|id|price|
|goods|id|price|

[表格生成网站](http://www.tablesgenerator.com/markdown_tables)


## 任务列表  
- [x] 已完成 (中括号小写字母x)
- [ ] 未做（中括号里有空格）

# 其他  
有部分功能只有少数的markdown编辑器支持。因此请视情况而定  
诸如流程图、LaTeX公式、UML图、[TOC]、标注以及其他基础markdown语法骚操作   
**工具：**
- [Pandoc](http://www.pandoc.org)
- [Gitbook](https://www.gitbook.com)
- [Rstudio-R_markdown](https://www.rstudio.com "knitr")

#### 作者和license [徽章生成](https://shields.io) | 不足之处还请指正！
## License
[![作者](https://img.shields.io/badge/%E4%BD%9C%E8%80%85-acdiost-orange.svg)](https://www.acdiost.cc)
[![License](https://img.shields.io/crates/l/markdown.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

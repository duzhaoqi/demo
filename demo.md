---
title: 普通的markdown语法
tags: Markdown
grammar_cjkRuby: true
---


## 标题Demo

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题


## 段落Demo

我的名字叫杜肇启，我是来自河南科技学院的一名没有毕业的通信专业的大学生，我喜欢开源社区，因此，我想加入到开源社区。    
我的QQ是不会告诉你的，哼！

## 强调Demo

**我是粗体**

*我是斜体*

***我是加粗斜体***

~~我是删除线~~

__我还是粗体__
_我是斜体_
___我还是粗斜体___


## 列表Demo

### 无序列表 

我的个人信息

- 姓名：杜肇启
- QQ：1147705876
- 年龄：66
- 性别：男
- 爱好：
  - 打球
  - 听歌
  - 玩游戏 

### 有序列表

1.  姓名：杜肇启
2.  班级：通信141
3.  学号：20141544117
4.  其他：
	1. 爱好：练球
	2. 音乐：哈哈

## 链接Demo

### 引用式链接

- 外部链接：[百度]
- 外部链接：[百度][baidu]
- 内部链接，仓库内链接：[index.html]
- 内部链接，页面内的链接：[标题Demo]

### 内嵌式链接

- 外部链接：[百度](www.baidu.com)
- 内部链接，仓库内链接：[index.html](index.html)
- 内部链接，页面内的链接：[标题Demo](###-标题Demo)


## 图片链接Demo

### 外部链接

![logo](http://www.duzhaoqi.top/wp-content/themes/JieStyle-Two/images/avatar.jpg  "logo")

### 内部图片链接

![tu](img/1.png "图片")

### 引用式链接

![logo][logo]


## 引用Demo

>土地是以它的肥沃和收获而被估价的；才能也是土地，不过它生产的不是粮食，而是真理。如果只能滋生瞑想和幻想的话，即使再大的才能也只是砂地或盐池，那上面连小草也长不出来的。 —— 别林斯基

>一层引用
>>二层引用
>>>三层引用

## 代码块Demo

- 行内代码

假如说，我们让`int x = 255`的话，就是不对的。

- 块式代码

```javascript
var a = 34
console.log(a)
```
- 另外一种

		var a = 34
		console.log(a)

<!--下面是引用式链接-->

[百度]: www.baidu.com
[baidu]: www.baidu.com
[index.html]: index.html
[标题Demo]: ###-标题Demo

[logo]: http://www.duzhaoqi.top/wp-content/themes/JieStyle-Two/images/avatar.jpg
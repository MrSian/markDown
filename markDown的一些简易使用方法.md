使用 Markdown 写文档真的是很方便啊 ！花十分钟来试试吧

## 标题

Markdown 里面使用#来表示标题。

### 二号标题两个井号

```text
# 大标题一个井号
## 二号标题两个井号
### 三号标题三个井号
```

**_温馨提示_** #号后面一般是需要加一个空格的！

## 强调

![](https://pic4.zhimg.com/v2-683ea62aadc376ad1459f9acc3fe66a2_b.jpg)

认真听课的娃儿在记老师强调的重点

### 斜体

_斜体_ 用一对\*筐住,

```text
*斜体*用一对*筐住,
```

### 加粗

**加粗** 用两对\*\*筐住,

```text
**加粗** 用两对**筐住,
```

### 高亮

高亮用两对==筐住, \[注: 貌似知乎显示不了高亮。接下来所有在知乎不能正常显示的，都通过阅读原文查看\]

```text
==高亮==用两对==筐住,
```

### 划掉

划掉用两对\~\~筐住.

```text
~~划掉~~用两对~~筐住.
```

简单又方便，有没有呢

## 列表

![](https://pic4.zhimg.com/v2-61972dfe9a1ca8a0e25db2a36e502c90_b.jpg)

### 有序列表

1.  有编号的列表
2.  使用：数字，点，空格，内容
3.  试试就会，非常简单
4.  还可以这样哦

5.  嵌套也是可以的
6.  只需要用 Tab 一下就
7.  可以开启嵌套的列表啦

```text
1. 有编号的列表
2. 使用：数字，点，空格，内容
3. 试试就会，非常简单
4. 还可以这样哦
    1. 嵌套也是可以的
    2. 只需要用Tab一下就
    3. 可以开启嵌套的列表啦
```

### 无序列表

- 无序列表
- 更简单
- 使用：-，点，空格，内容 就好啦
- 同样也可以嵌套

  - 就是这样的
  - 是不是简单到不行呢

```text
- 无序列表
- 更简单
- 使用：-，点，空格，内容 就好啦
- 同样也可以嵌套
    - 就是这样的
    - 是不是简单到不行呢
```

## 写公式

现在谁不写公式呢，怎么写？ MD 支持使用 Latex 的的格式写公式。

![](https://picb.zhimg.com/v2-cce1fcda608ceed913dfddbc3a359609_b.jpg)

写这么多公式来吓唬吓唬你！

### 行内公式

什么是**行内公式**呢？ 哈哈，就是将公式和描述的文字写在一行里面，比如说我们大家都知道的一个 公式是勾股定理：

![a^2 + b^2 = c^2](https://www.zhihu.com/equation?tex=a%5E2+%2B+b%5E2+%3D+c%5E2) . 它说的是直角边 ![a,b](https://www.zhihu.com/equation?tex=a%2Cb) 的平方和等于斜边 ![c](https://www.zhihu.com/equation?tex=c) 的平方和。 行内公式 只需要用一对\$ 将要写的公式筐起来就可以啦。

```text
$a^2 + b^2 = c^2$. 它说的是直角边 $a,b$ 的平方和等于斜边 $c$ 的平方和。
```

### 独行公式

独行公式就是将公式单独拿出来写作一行，只要用两对\$ 把公式筐起来就可以了。

![e^{x}=1+x+\frac{x^{2}}{2 !}+\frac{x^{3}}{3 !}+\cdots](https://www.zhihu.com/equation?tex=e%5E%7Bx%7D%3D1%2Bx%2B%5Cfrac%7Bx%5E%7B2%7D%7D%7B2+%21%7D%2B%5Cfrac%7Bx%5E%7B3%7D%7D%7B3+%21%7D%2B%5Ccdots)

```text
$$
e^{x}=1+x+\frac{x^{2}}{2 !}+\frac{x^{3}}{3 !}+\cdots
$$
```

有了 Latex：

1.  你只需要关注公式的关系，而不用去考虑各种符号的大小位置。因为 Latex 会自动 地帮你渲染出公式本来应该的样子；
2.  你写公式快的飞起来了 ‍♂️；
3.  优雅啊 。

## 写代码

MD 插入代码的方法也是很简单的哦。

![](https://pic1.zhimg.com/v2-127ea5c93d2fce89b8465af4c16f2184_b.jpg)

小明会中文，英文和 Python！

### 行内代码

且看我插入一行代码: `print('你瞅啥?')`， 只要使用一对反引号\`\`筐住就可以啦！`print('啥叫反引号？')`, `print('Tab上面那个啦 ')`

### 多行代码

厉害的你需要写多行代码，接下来就插入多行代码：

````python3
# 格式：
#  ```python
#  这里添加你的Python代码
#  ```
Year = 0
while Year < 10000:
    print('Love You.')
    Year += 1
````

````text
// 格式：
//  ```c
//  这里添加你的C语言代码
//  ```
#include <stdio.h>
void main()
{
    printf("知道啦知道啦!\n")
}
````

## 表格

\[注: 貌似知乎没有办法创建表格\]

```text
| 表格  |    |  |
| ---- |---| ---|
| 中文   | 狗 | 猫 |
| 日本語  | 犬 | ねこ |
| English | dog | cat |
```

## 链接

Markdown 支持链接 ，这一点非常受大家欢迎 ！ Hi, 大家好！ [way2ml](https://link.zhihu.com/?target=https%3A//www.way2ml.com/) 欢迎您！

```text
Hi, 大家好！ [way2ml](https://www.way2ml.com) 欢迎您！
```

链接--让你的文档变得灵活，这样的文档就像是一把 ，为别人开启了新世界的大门；

链接--让你与世界相关，编不下去了。总之，用就对了

## 图片

图片插入方法多，任选下面的一个！ 图片的链接可以是本地的链接，也可以是网络上的图片链接。

### 使用标准 Markdown 语法

![](https://pic4.zhimg.com/v2-0d05422f6e1675e4817645ce3a345b85_b.jpg)

可愛い女の子

```text
![女孩](/images/linux/linux_tools/markdown/girl1.png)
```

这里的图片链接既可以是本地的，也可以是网络链接哦。例如：你可以把你的图片上传到码云，然后得到一个图片的链接，再把它贴在这里就可以了。说到这里给大家推荐一个我觉得非常棒的图床引用--[uPic](https://link.zhihu.com/?target=https%3A//github.com/gee1k/uPic)。使用它就可以瞬间上传一张图片到码云等云端，然后立马得到一个图片链接，这种体验真的非常棒。

### 使用 HTML 语法

Markdown 最终是会被后台转化成 HTML 的，因此在写的时候就使用 HTML 的语法也完全是可以的。

```text
<img src='/images/linux/linux_tools/markdown/girl1.png' width='50%'>
```

使用 html 的方式可以调整图片的宽度占比。

有时我们还可能需要将图片居中，就像下面这样:

![](https://pic4.zhimg.com/v2-0d05422f6e1675e4817645ce3a345b85_b.jpg)

```text
<p align='center'>
<img src='/images/linux/linux_tools/markdown/girl1.png' width='50%'>
</p>
```

这样才符合强迫症的习惯嘛！ 女孩子要站在中间才更可爱嘛 ☃️。

## 分割线

我们可以在需要的地方添加分割线 \[注:下面的分割线是由知乎生成，MD 生成的有些不太一样\]

---

```abap
---
***
___
```

## 添加音频

添加音频直接使用 HTML 中的`audio`标签，指定音频位置就可以了！ 喏，就像下面这样\! 工作累的时候， 听听下面的歌曲放松一下吧！\[注: 知乎不支持放音频链接，下面的只是图片。\]

![](https://picb.zhimg.com/v2-9fc1cb07d56f1f01ebe8e81a258d1ef1_b.jpg)

```html
<p align="center">
<audio ref='themeSong' src="https://github.com/HuangJiaLian/DataBase0/blob/master/sound/My_Tree.mp3?raw=true" controls loop preload></audio>
</p>
```

## 添加视频

### 本地视频

其实直接在 Markdown 中添加 HTML 语句就可以了。来看看这段[有趣的视频](https://link.zhihu.com/?target=https%3A//crypko.ai/%23/)吧！

[![](https://pic4.zhimg.com/v2-045d029dc31c71dea26d80d51a95bcff.jpeg)使用生成对抗神经网络得到图像 https://www.zhihu.com/video/1231358193420693504](https://link.zhihu.com/?target=https%3A//www.zhihu.com/video/1231358193420693504)

```html
<video style="display:block; margin: 0 auto;" width="50%" controls>
<source src="/images/ml/GAN/female.mp4" type="video/mp4">
</video>
```

### Bilibili 或者 Youtube

使用 Bilibili, Youtube 的视频分享功能，可以得到一段`iframe`代码，将它复制到 Markdown 中就可以啦。 我们来看看自称 AI 的绊爱的[视频](https://link.zhihu.com/?target=https%3A//www.bilibili.com/video/BV1ox411S7Q7%3Ffrom%3Dsearch%26seid%3D1174880861663926912)吧！\[注: 知乎貌似也不能用 iframe\]

![](https://pic4.zhimg.com/v2-08207f8c4aa6d93b045ab212bacfdb36_b.jpg)

```html
<p align='center'>
<iframe width="560" height="315" src="//player.bilibili.com/player.html?aid=9800170&cid=16201929&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
```

## Markdown 编辑器

好的 Markdown 编辑器让你如虎添翼。我觉得很不错的编辑器有[Typora](https://link.zhihu.com/?target=https%3A//typora.io/)，推荐给大家！例外，Typora 也支持前面提到的图床应用 uPic 等哦。用着和不错了，感觉要飞起来了。哈哈。

## 结语

不多不少刚刚好，希望这篇文章能够帮助到你！

**参考**

1.  [Markdown Cheatsheet](https://link.zhihu.com/?target=https%3A//github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
2.  [小可愛表情 png from pngtree.com](https://link.zhihu.com/?target=https%3A//pngtree.com/so/%25E5%25B0%258F%25E5%258F%25AF%25E6%2584%259B%25E8%25A1%25A8%25E6%2583%2585)
3.  [女生 png from pngtree.com](https://link.zhihu.com/?target=https%3A//pngtree.com/so/%25E5%25A5%25B3%25E7%2594%259F)
4.  [crypko](https://link.zhihu.com/?target=https%3A//crypko.ai/%23/)
5.  [Full-body High-resolution Anime Generation with Progressive Structure-conditional Generative Adversarial Networks](https://link.zhihu.com/?target=https%3A//dena.com/intl/anime-generation/)

[阅读原文 ​www.way2ml.com](https://link.zhihu.com/?target=https%3A//www.way2ml.com/linux/linux_tools/markdown.html)

# 个人笔记系统

## 目录

[TOC]

## 笔记系统规划

### 笔记系统的意义

笔记系统用于KM（知识管理），将学过的知识点，疑难点等凝炼出来**进行储存**，便于回顾，避免学习无关紧要的知识。

### 纸质笔记和电子笔记的差距

我虽然很早就意识到电子笔记相比传统纸质笔记有很大的优势，但是于对纸质的执念，很大程度上导致我在纸质和电子笔记间来回使用，无法拥有统一的笔记本，因为回顾起来费劲所以笔记的作用没有发挥出来。

> 纸质笔记的致命缺点有：
>
> * 写好的笔记难修改，不容易辨认字迹和逻辑。
> * 储存不易，携带不易。

在学习专业知识的过程中，我有很深的感触：各学科知识都有很多共通点，所以建立一个**统一连贯的知识体系**，很有助于我们串联起各学科知识。展开来说，这对非专业的学习，比如阅读笔记，生活日记，经验总结等，也是很有帮助的。

### 笔记系统的结构

#### 时间结构

指做笔记的时间顺序，按照一般习惯，做快速笔记时逻辑还不清楚，需要进一步整理，最后需要串联成容易回顾的体系。所以我把它们分为三轮，开始都用同一[笔记模板](onenote:#✒快速笔记模板&section-id={53BAD259-77BB-4DD7-997C-142CFD2468B6}&page-id={9B6C43DE-0DB0-4CED-B44D-6FDB1C841D25}&end&base-path=https://d.docs.live.net/d2268c2c055e4f5e/Documents/搞点规划/笔记系统.one)，一轮轮加工。

##### 第一轮笔记：快速笔记

###### 定义

实时整理上课，阅读时的知识点。

###### 使用软件

* OneNote：听讲，阅读。
* Notability：针对有课件的课。
* MarginNote：文章，课本等。

有些无法马上软件记录的东西，比如**演算过程，公式，可先写出来用手机拍上，软件中做个记录**。

##### 第二轮笔记：整理逻辑

###### 定义

按照[颜色分级法和emoji标记法](onenote:#颜色分级法和emoji标记法&section-id={53BAD259-77BB-4DD7-997C-142CFD2468B6}&page-id={8FE228B2-1A1B-45FE-82FE-614B4A917833}&end&base-path=https://d.docs.live.net/d2268c2c055e4f5e/Documents/搞点规划/笔记系统.one)划分内容重点和类型，按照逻辑整理篇章结构。

###### 使用软件

* OneNote：重排版，整理来自Notability，手机相册等的笔记。
* draw.io：画图。

##### 第三轮笔记：用于发布

###### 定义

若基本确定不再修改，可以进一步筛选内容，按照整理好的逻辑生成定稿。**一般不需要**。

###### 使用软件

* Typora：写markdown，转PDF。
* XMind ZEN：画思维导图。

#### 类型结构

##### 笔记/日记/经验总结

都采用笔记系统的格式。

##### idea

记录突然想到的idea，目前没有机会实现的目标等，采用[idea模板](onenote:#💡idea模板&section-id={53BAD259-77BB-4DD7-997C-142CFD2468B6}&page-id={B9B6BB80-6B66-49C6-B0D5-07B0F68268E2}&end&base-path=https://d.docs.live.net/d2268c2c055e4f5e/Documents/搞点规划/笔记系统.one)。

## 笔记记录方法评价

### Windows上使用过的软件

#### OneNote

- 功能齐全，排版自由。
- 受限于电脑配置，目前不能用手写，需要用鼠标（甚至触摸板）来选取工具。
- **对代码不友好。**
- **对公式很不友好。**
- 不支持Markdown。

![OneNoteScs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\OneNoteScs.jpg.png)

这么说吧，**OneNote最适合在第一轮学习**中使用，将课堂讲解，所读书籍，所看讲义/课件最先记录下来。其次**也适合二次整理**，将散乱的第一轮笔记整理出自我归纳的二轮笔记。

#### Word

- 不是做笔记的软件，根本不要拉进来讨论是最好的。
- 分项整理麻烦，整理出多个笔记本还需要创建多个文档，每个文档还需要排版，不适合一轮二轮笔记，三轮也有更好的替代品。

#### Powerpoint

- 实质上是分页清晰的Word，不适合做笔记，更适合做记忆卡片（制作记忆卡片还麻烦嘞，不值得）。
- 其他缺点同Word。

#### Typora

- 基于Markdown语法，**对代码/公式友好**。
- **实时显示**，排版快捷且精致，不用面对前面输入的可观性较差的Markdown语句，而是立刻生成的排版效果。
- 支持自动补全。
- 支持拖放图片。
- 可直接导出PDF或者图片格式。

![TyporaScs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\TyporaScs.jpg.png)

需要特定语法来使用的Typora，虽然已经在排版上节省了很多时间，但是不适合快速笔记（一轮笔记），**最适合第三轮笔记**，生成自我规划好的，有成熟逻辑的“书籍”。

#### Visual Studio Code + Markdown

![VSCodeScs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\VSCodeScs.jpg.png)

- 黑色主题+Code是我心中的“白月光”。
- 也支持实时显示，但是新开窗口侧栏显示，转换视线稍微分神。
- 对公式的显示有点难看：

![公式Scs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\公式Scs.jpg.png)

同样对Markdown进行编辑排版，还是**Typora操作更得我心，第一因为自动补全，第二因为实时显示，第三因为查看Reference很方便**。

#### XMind ZEN

- 创建**思维导图**，操作简捷。
- 试用版目前存在水印，不过问题不大，其他局限目前还不清楚，等待摸索。

![XMindZENScs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\XMindZENScs.jpg.png)

思维导图对于做笔记有两个用处：

1. 制作计划。
2. 整理归纳知识点，便于记忆。

所以这款软件适用于第**二**/三轮笔记。

#### draw.io

- 画flowchart等，有大量模板。
- 浏览器中在线使用。
- 功能齐全且免费。

![drawioScs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\drawioScs.jpg.png)

适用于第**二**/三轮笔记。

### 手机端使用过的应用

手机端做笔记，操作麻烦，屏幕太小，姿势不好，真的是很费劲，不值得。唯一方便的是使用OneNote和OneDrive，随身可以查看笔记。但是**手机端OneNote查看emoji表情有乱码**。

### iPad使用的应用

#### XMind

好处就不多说了，支持云端同步，我在Windows上制作的思维导图可以在iPad上看到。

#### MarginNote

![MarginNoteScs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\MarginNoteScs.jpg.png)

- 知识管理的极佳应用。见知乎回答：

> 🖇为什么marginnote没有Windows版？ - 夏暮的回答 - 知乎 https://www.zhihu.com/question/54960645/answer/217326398

- **查看文献，书籍**时，利用电容笔随手制作笔记，同时生成outline或思维导图，颜色区分也很适于复习。

很遗憾，到现在这款应用还没有Windows版本，相关回答见知乎问题：

> 🖇为什么marginnote没有Windows版？ - 知乎 https://www.zhihu.com/question/54960645

#### Notability

- 结合电容笔进行**快速备注**。
- 拍照导入快捷。

![NotabilityScs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\NotabilityScs.jpg.png)

非常适合**提前下载课**件，然后上课时实时备注。

#### LaTeX Help

查看一些LaTeX指令，仅用于简单的查询，全部功能还是看Windows的TeXstudio，由于是做笔记，LaTeX像写书一样，我就不多说了，真正碰到公式，还是自己截图（Win+Shift+S）更省时间。

## 颜色分级法和emoji标记法

### 颜色分级法

算在二轮中。

| <font color=red>重点</font> | <font color=blue>次重点</font> | <font color=white>定义</font> | <font color=green>个人理解</font> | <font color=purple>例题</font> |
| --------------------------- | ------------------------------ | ----------------------------- | --------------------------------- | ------------------------------ |
| red                         | blue                           | white                         | green                             | purple                         |

### emoji标记法

只用自己熟悉的，节省时间。

💬注：按住Ctrl+Shift+B，可调出emoji表情栏。

 ![emojiScs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\emojiScs.jpg.png)

👍觉得很赞

💢生气

👀不了解的新东西

💬备注，注解

❤喜欢

💕很喜欢

✏定义

😐一轮笔记未开始

😀一轮笔记完成

😃二轮笔记完成

😎三轮笔记完成

✒笔记页

💡idea页

### Tags标记

直接利用OneNote自带的功能。

![TagsScs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\TagsScs.jpg.png)

## 其他小知识

### 自制笔记模板

每新建一个section，建立新一page，制作模板，将该页set as default template，就将模板适用于整个section。

![templateScs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\templateScs.jpg.png)

### 插入链接

给一段文字插入另一文字段或者page或者section甚至notebook的链接。先右键要提取链接的对象，copy link to xxx,

![copylinkScs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\copylinkScs.jpg.png)

然后选取文字段，Ctrl+K，粘贴链接。

![pastelinkScs.jpg](C:\Users\jinha\Documents\GitHub\notes-system\images\pastelinkScs.jpg.png)
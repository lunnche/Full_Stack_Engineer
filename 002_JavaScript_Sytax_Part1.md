# JavaScript Syntax,Part1  

目标：  

熟悉JavaScript基础  
1. 理解网络开发如何用到JavaScript  
2. 理解、练习JavaScript基本语法

为什么JavaScript流行，能拿来干啥？   

90年代，微软和网景在浏览器领域竞争支配地位，  
网景公司需要一个轻量脚本语言用于简单编程，这样才能让网络开发更易上手，想搞一个不像其他语言一样需要大量
学习训练才能掌握，的语言  
1995年，网景员工 Brendan Eich，花10天搞出了Mocha，即后来的JavaScript。  

HTML负责框架 CSS负责样式 JavaScript提供交互性  

JavaScript，一个程序员用十天时间写出来的语言为啥能风靡一时？因为它把网络浏览器变成了应用平台：  
1. JavaScript 前后端都能用  
2. JavaScript是标准化的，经常更新版本  
3. 简单地与HTML和CSS集成
4. 使得网站具有互动性：滚动切换、目标移动，现代浏览器为了最好的用户体验，仍在互相竞赛谁能更快地处理JavaScript，Chrome之所以成功就是因为它能更快地处理JavaScript  
5. 提供大量框架和库帮助开发者以较低开销构建复杂应用，程序员可以在他们的代码中引入框架和库来增加功能。  

## JavaScript for Servers  
2000年，Facebook和Google等公司开始在后端服务器逻辑中使用JavaScript来响应前端请求，JavaScript之所以能帮企业扩大规模是因为懂JavaScript的工程师可以将之应用于后端环境。  

用于服务器的JavaScript，也被称为server-side JavaScript。变得流行是因为它允许可扩展性。在服务器中，JavaScript可以和其他语言集成来与数据库通信。  

Node.JS 或者 叫 Node，是最流行的server-side JavaScript版本。  
Node被用于为NASA、eBay等开发大型平台，因为JavaScript 能不按顺序执行程序，Node可用来构建可扩展的网络应用，
短信平台，多人游戏，这就是为何Google云和Amazon网络服务依赖Node提供的一些服务的原因。 

## JavaScript 还能干什么  

除了网络，JavaScript还大量应用于跨平台应用。我们使用一些流行的独立桌面应用程序，比如Slack,GitHub,Skype,以及Tidal。他们是用JavaScript框架Electron.js构建的。Electron擅长构建跨平台跨操作系统的桌面应用。  

JavaScript有潜力扩展到其他创新技术，如虚拟现实和游戏。JavaScript可以用于动画、渲染和缩放。JavaScript甚至为物联网做出了贡献。JavaScript可以让简单的物品，比如你的冰箱，变得更智能。日常设备可以变成交互式的，并使用JavaScript库收集数据。  

掌握所谓的“vanilla”（最轻量的JavaScript框架），将帮助您处理更复杂的框架和库，使你成为一个有竞争力的开发人员。

可学学codecademy的javascript课程  https://www.codecademy.com/catalog/language/javascript  

# JavaScript版本：ES6及之前  

## 啥是ES6或者Javascript ES6  

在Javascript问世后，网景公司向标准制定组织Ecma international提交了JavaScript来制定脚本语言标准。  
1997年，Ecma International 发布了ECMA-262第一版ECMAScript脚本语言标准，简称ES。  

ECMAScript标准提供了JavaScript体系的规则。随着新的编程范式的出现和开发人员寻求新的特性，ECMAScript的新版本为新旧JavaScript版本之间的一致性提供了基础。要完全区分JavaScript和ECMAScript的区别:如果你想创建一个应用程序或程序，你可以使用JavaScript,如果你想创建一种新的脚本语言，你可以遵循ECMAScript中的指导原则

因此，当您看到ES6或JavaScript ES6时，这意味着该版本的JavaScript遵循了ECMAScript第6版的规范,您可能还会看到ES2015而不是ES6，但这两个术语都指的是2015年发布的ECMAScript第6版,下图显示了多年来JavaScript是怎么形成的

![javascript_timeline](https://raw.githubusercontent.com/lunnche/picgo-image/main/javascript_timeline.svg)

那么，ES7，ES8都出来了，重点描述ES6，是因为有什么重大更新吗  

好吧，尽管发布了新的版本，ES6实际上是自1997年发布的第一版以来对ECMAScript进行的最大更新  
一些开发人员甚至称ES6为“现代JavaScript”，因为它提供了所有主要的添加。为了帮助JavaScript开发者，添加了很多很棒的功能，包括:  
* 新的关键字，如let和const来声明变量  
* 使用Arrow函数的新函数语法  
* 创建了类  
* 具有默认值的参数  
*  异步操作的承诺  


最新的浏览器现在支持ES6的大部分特性，允许开发者充分利用这些新特性。ES6最终允许程序员节省时间并编写更简洁的代码。以函数表达式的es6前语法为例

```javascript
var greeting = function(){
  console.log('Hello World!');
};
```

使用ES6的箭头函数，我们可以将上面的表达式转换为  
```javascript
const greeting = () => console.log('Hello World');
```

然而，箭头函数不仅仅是简单的语法重写。与其他ES6特性一样，还有其他潜在的好处和权衡需要考虑。

尽管如此，ES6在开发社区中已经被广泛采用。新的ES6语法等优点使得利用流行的编程范式——面向对象编程(OOP)变得更加容易。这一改变允许使用OOP的其他语言的开发人员现在可以过渡到学习和使用JavaScript。

ES6流行的另一个原因与在React等流行框架中使用ES6有关。因此，如果您想学习最新的工具和框架，您必须在学习过程中学习ES6。  
话虽如此，我们不应该忽视遗留代码，即旧版本的JavaScript。事实上，仍然有许多项目是用遗留代码构建和维护的!如果你想要在任何类型的JavaScript项目上工作的能力和自由，你应该熟悉ES6和ES6之前的JavaScript语法  

选读JavaScript and JQuery,Introduction by Jon Duckett  

## JavaScript 如何使网页更有交互性  
1. 访问内容
可以使用JavaScript从HTML页面中选择任何元素、属性或文本，例如：
* 选择一个页面里所有`<h1>`标签里的文本  
* 选择任何具有class属性值为note的元素
* 找出在id属性值为email的文本输入中输入了什么  

JavaScript允许你在浏览网页时，访问和修改网页中使用的内容和标记，来使得网页更具交互性 

2. 修改内容  
你可以使用JavaScript在网页中增删元素、属性、文本，例如：  
* 在第一个`<h1>`元素后增加一段文本  
* 改变类属性值来触发这些元素的新CSS规则
* 改变`<img>`元素的大小和位置  

3. program rules  
为浏览器制定一系列操作步骤（如同菜谱一样），这些步骤将使浏览器访问或改变页面内容。例如：
* 图库脚本可以检查用户点击的图片，并显示一个更大的图片
* 抵押贷款计算器可以从表单中收集值、执行计算、显示还款
* 动画可以检查浏览器窗口的尺寸，并将图像移动到 可视区域的底部(也称为视口)

JavaScript包含许多传统变成规则，它通过响应用户行为使网页更具交互性。  

4.响应事件  
你可指定某一事件出现时，应该运行的脚本，例如：  
* 按下按钮
* 链接被点击  
* 鼠标在某元素上悬停  
* 在表格中添加信息  
* 一段时间过去了  
* 页面加载完毕  

## 浏览器中JavaScrip示例  
在HTML页面正在加载时去改变其内容。下面的例子依赖于JavaScrip的这些能力：  
* 访问页面内容  access content
* 修改页面内容  modify content
* 编辑浏览器可执行的指令  programming rules
* 响应用户或浏览器触发的事件  react to events

### SLIDESHOWS
Shown in Chapter 11  
Slideshows可以在一个空间内展示多张图片（或其他HTML内容），图片按顺序自动切换，也可手动切换。
* 响应：页面加载时脚本触发  
* 访问：从slideshow获取每个幻灯片  
* 修改：只展示第一张幻灯片（藏起所有其他）  
* 编程：设置计时器，何时展示下一张  
* 修改：修改展示哪张幻灯片  
* 响应：当用户针对不同幻灯片按鼠标  
* 编程：决定展示哪个幻灯片  
* 修改：展示请求的幻灯片  

### FORMS
Shown in Chapter 13  
当用户提交信息时，验证表单（检查它们是否填写正确）是很重要的。JavaScript允许你提醒用户错误。它也可基于输入数据进行复杂计算并把结果展示给用户。  
* 响应：用户输入姓名后按下提交按钮  
* 访问: 从表单域获取信息  
* 编程：检查姓名是否足够长  
* 修改：名字不够长的话显示警告信息  

## RELOAD PART OF PAGE  
Shown in Chapter 8  
当你只需要刷新显示页面的一小部分时，只刷新一小部分会显得你的网页响应很快。  
* React: 用户点击链接触发脚本  
* Access: 他们点击的链接  
* Program: 加载链接请求的新内容  
* Access: 找到页面上需要重置的元素  
* Modify: 重置内容  

## FILTERING DATA  
Shown in Chapter 12  
如果需要在一个页面上显示很多内容，可以提供过滤器来帮助用户快速找到他们所需。使用HTML标签`<img>`元素属性中的数据来生成按钮，当用户按下其中一个按钮时，他们会只看到相应内容

* React: 页面加载时触发脚本  
* Program：从图片收集关键字  
* Program: 把关键字做成按钮  
* React: 用户按下其中一个按钮  
* Program: 找到需要展示的图片子集  
* Modify: 展示使用那个tag的图片子集  

# Intro to Mozilla Developer Network  

学习一样东西的时候，直接去看官方文档会是有效的方法  

对于网络开发来说，一个很有用的东西就是“MDN”——Mozilla Developer Network,
上边有很多关于网络开发的东西。  

## Searching for MDN Articles  
MDN首页右上角搜索栏，注意搜出结果后没必要通读全文，关注对你来说最有意义的部分即可，定义下面紧跟demo，告诉你用法，有实时输出，可以互动，改代码，看看有什么变化。  
定义、demo之后是属性，用法说明（很重要，在处理不熟悉语法时，看看这个可以规避常见错误），如果不是太懂用法说明，别急，后边跟着示例代码段。在后面supporting section是一些不太必须但可以扩展你知识面或为你带来更深入理解的东西。再后面是Accessibility Concerns 和示例代码，再后面是specification，它链接一些更详细的东西，再后面是浏览器兼容性，（caniuse.com类似这块，但简单很多）  

## MDN Documentation  MDN Javascript  

https://developer.mozilla.org/en-US/docs/Web/JavaScript

有什么不会的查查这个文档  

# INTRODUCTION TO JAVASCRIPT  

## Console  

The console is a panel that display important messages,like errors,for developers.大部分的计算机对我们代码的操作我们都是看不见的，如果我们想看，可以用console来print 或者 log 

```
console.log(这是你想输出在屏幕上的东西)
```


建议每句后面以分好;结束，虽然它不是必须的，养成这个习惯，有助于在真正需要分号的时候不会遗漏。  

JS区分大小写  

## Comments  

单行注释 //  

/* 
多行注释
*/  

为何需要注释掉一段代码
1 为了提升代码段的效率，可注释掉原来的，编写新的，新的不行，就删新回复旧，新的可以，就删旧保留新  
2 为了追踪bug，注释掉一段，看剩下的有没有错，来看哪段代码出错  

## Data Types  

* Number  
* String   单引号或双引号括起来  
* Boolean  
* Null  
* Unefined  
* Symbol  
* Object  

## Arithmetic Operators  

1. Add: +  
2. Subtract: -  
3. Multiply: *  
4. Divide: /  
5. Remainder(modulo): %  

Note that while in most languages, ‘%’ is a remainder operator, in some (e.g. Python, Perl) it is a modulo operator. For positive values, the two are equivalent, but when the dividend and divisor are of different signs, they give different results. To obtain a modulo in JavaScript, in place of a % n , use ((a % n ) + n ) % n .
如上述，注意一个点：-5%20  不同语言结果不一样。JavaScript得-5，Python得15，这是取余与模 的区别。  

## String Concatenation  
+号可以用来连接两个字符串  

## Properties  
当向JavaScript程序中引入一段新数据时，浏览器将其保存为该数据类型的实例.每个字符串实例都有一个名为length的属性，用于存储该字符串中的字符数.您可以通过在字符串后附加句点和属性名称来检索属性信息.  

`.` is another operator.  We call it the dot operator.  

## Medthods  

`'example string'.methodName()`  



## How to Use Developer Documentation  

怎么用文档，以python文档为例，除了擅用右上角搜索，还要注意General Index,里边有所有函数、类。。。
举个例子，我想把一个python列表，里边是球队名，按字母顺序重新排序，我应该怎么做这件事：  
* Identifying the data type/structure you're working with --List  
* Find functions available that may help you manipulate your data/code  
* Search the documentation to find what you are looking for in this case -- LIST FUNCTIONS  

所以呢，按上述步骤我回到python documentation 搜索“list”，里边有各种method，如果你看不懂，那就做一个list，拿这些method来试验，实际看看有什么用，这能帮助你理解，  

另一种方法，不用搜索，而是用general index，点进去，点“L”，用浏览器自带的搜索功能，比如chrome就是Ctrl+F，输入“list",找到list(built-in class),  

OK,再看看MDN怎么用，MDN主要的重点是前端技术，如javascript,html,css,  

进入MDN网站，注意导航栏有两个值得关注的东西：Technologies,References&Guides,  

Technologies里面包含所有语言文档的列表，  

References&Guides 里面包含教程，开发者指引，  

看到10：52了 下面这个视频  
https://www.youtube.com/watch?v=s1PLS3SQHQ0

里面有CSS introduction,CSS tutorials,CSS reference   
其他语言的部分的structure基本也是这样，如果你对某个语言不是很自信，那么tutorial 部分非常棒，是可以和codecademy配套的很好的联系材料，  
reference是什么呢，点进去，首先，第一段给了你不同的链接，链接到后面不同的部分，然后下面有基本的语法示例，告诉你如何写一个style block  
再往下，就会看到keyword index，有各种关键字的列表，每个关键字点进去有可互动的介绍，可以进行各种操作来试验用法，右上角的reset可以进行重置，  

来看一个例子:  
```
nbateams=['Hawks','Lakers','Celtics','Raptors','Warriors','Heat']
```

我想搞个filter，使得上面队伍中只剩下六个及以上字母的队名
我要怎么做呢？  
* Identifying the data type/structure you're working with -ARRAY  
* Idnetifying the goal you have and aligning it with a particular function -FILTER  
* Search the documentation to find what you are looking for in this case -ARRAY FILTER  

## 啥是replit  

replitallows you to build and host your coding projects instantly with no setup and it provides you with a social browser-based ide where you can collaborate with others and share your work  

和他人合作时，可以use threads to annotate sections of code for them  

如果你想分享你的代码，但不允许别人编辑它，你可以使用左上角的spotlight,这将会打开一个url where 其他人可以run你的code，view 你的code  

可以把你的project 直接publish到apps gallery from your workspace by clicking publish   

注意 replit 的 docs   docs.replit.com  

## Built-in Objects  

除了console，还有其他的JavaScript内建对象  
比如Math对象  
```JavaScript
console.log(Math.random());//Prints a random number between 0(inclusive) and 1(exclusive)
```

取整：Math.floor  

## How to Build a (Web Dev) Portfolio  

为啥要建一个portfolio?  
* Perspective employers or clients want to see your current body of work.  
只跟你的雇主或者客户说相信我我能搞定是不够的，  

* A portfolio brings credibility because it showcases your work  
* This also has the benifit of being an online resume  

portfolio 我猜是类似作品集之类的玩意？  

Where should you start?  
* Codecademy Projects  
* Build a project on your own  
没有头绪的话，可以考虑重新设计别人的网站  
  Planning 
  Wireframe  remember the goal is improvement not perfection
* Keep building   
如果你发现没有好的项目idea，一个好办法是考虑为你已有项目增加xin feature.  
keep building 也意味着keep iteration:比如你第一个网站使用HTML和CSS做的，然后呢你可以往里面添加一些vanilla JavaScript,然后呢你第二个项目就可以考虑同时使用HTML,CSS,JavaScrip，再整个框架，比如react,然后呢第三个项目可以考虑把你的react项目用nodejs编出来  
* Clean up  
整理你的porfolio，移除老项目已经不能反映你技术水平的老项目，  

好吧，如果你不做前端工作呢？  
如果你做Python data sciece 或者 machine learning  
* You still want your completed code online   
* Make sure you include detail instructions on how the program works and what is the expected output  
* Do step-by-step writeups with Jupyter notebooks.  

所以应该把我们的portfolio放在哪？  
Hosting  
*Web Hosting  
*VPS virtual private server
*Dedicated  

推荐还是把Portfolio放在GitHub  

GitHub  
* GitHub ahould already be used to host your code  
* You can convert your front end code into a GitHub page.  
* Almost every major tech company used Git,this makes you more hireable.  

对于一个web developer来说，两件事佷重要：  
1 技术
2 一个证明你有技术的portfolio  

Review
Let’s take one more glance at the concepts we just learned:

Data is printed, or logged, to the console, a panel that displays messages, with console.log().

We can write single-line comments with // and multi-line comments between /* and */.

There are 7 fundamental data types in JavaScript: strings, numbers, booleans, null, undefined, symbol, and object.

Numbers are any number without quotes: 23.8879

Strings are characters wrapped in single or double quotes: 'Sample String'

The built-in arithmetic operators include +, -, *, /, and %.

Objects, including instances of data types, can have properties, stored information. The properties are denoted with a . after the name of the object, for example: 'Hello'.length.

Objects, including instances of data types, can have methods which perform actions. Methods are called by appending the object or instance with a period, the method name, and parentheses. For example: 'hello'.toUpperCase().

We can access properties and methods by using the ., dot operator.

Built-in objects, including Math, are collections of methods and properties that JavaScript provides.

## Variables  

variables label and store data in memory.there are only a few things you can do with variables:  
1. Create a variable with a descriptive name.  
2. Store or update information stored in a variable.  
3. Reference or "get" information stored in a variable.  

## 题外话 怎么记住你所学的东西  

彼此独立的知识点很难被记住，要把他们连接起来，
一些建议：  
1. focus on understanding  

focus on concepts and ideas  

We don't learn human languages well from just a dictionary,Instead we want to put our skills and learning into practice by working on projects.  

Don't focus on remembering code. Instead remember ideas.  

理解了底层概念和算法你将可以使用多种语言来编程  

2. Apply what you are leaning through working on projects.  

看这个视频  https://www.youtube.com/watch?v=aMzAjQ4uUag  
到3：26了  



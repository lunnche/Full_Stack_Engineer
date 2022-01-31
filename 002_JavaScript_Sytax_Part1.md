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

3. View other people's projects and codebase.  

4. Find a community to share,collaborate,to give and receive feedback on projects.  

be open to feedback on your work

5. Know where to find the answers to your questions.  

6. Compile good resources.

7. Take notes.  

8. 最重要的 PRACTICE  

---------

## VARIABLES  

### Create a Variable:var  

ES6版本更新引入了两个新关键字：let 和 const来创建和声明变量。此前程序员只能使用 var来声明变量。  

```javascript
var myName = 'Arya';
console.log(myName);
//Output:Arya
```

camel casing:In camel casing you group words into one,the first word is lowercase,then every word that follows will have its first letter uppercased.(e.g. camelCaseEverything).  

There are a few general rules for naming variables:  
* Variable names cannot start with numbers.
* Variable names are case sensitive,It is bad practice to create two variables that have the same name using different cases.  
* Variable names cannot be the same as Keywords.
查看Javascript的关键字： https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Lexical_grammar#keywords  

用let和const比var好，但很多ES6以前的项目里只有var，所有有必要懂。  
更多关于var的内容：https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var  

## Create a Variable:let  

`let` keyword signals that the variable can be reassigned a different value.  

```javascript
let meal = 'Enchiladas';
console.log(meal);//Output: Enchiladas
meal = 'Burrito';
console.log(meal);//Output:Burrito
```

when using `let`(and even `var`),we can declare a variable without assigning the variable a value.In such a case,the variable will be automatically initialized with a value of `undefined`:  

```javascript
let price;
console.log(price);//Output:undefined
price = 350;
console.log(price);//Output:350  
```

let 比 var好，因为它是block scoped.
具体解释参看：https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var  

简单说，看一个栗子🌰：  
```javascript
if (true){
    let letVariable = 'hello world';
    var varVariable = 'hello world';
    console.log(varVariable);
    console.log(letVariable);
}
console.log(varVariable);
console.log(letVariable);// syntax error or undefined
```

## Create a Variable:const  
栗子🌰
```javascript
const myName = 'Gilberto';
console.log(myName);//Output:Gilberto
```

const变量不能被reassigned,否则TypeError
声明const变量时必须赋值，用let可以不赋值，否则SyntaxErroe

## Mathematical Assignment Operators  
```javascript
w = w + 1;
等效于
w += 1;
```

同样的，有
```
*=
-=
/=
```

## The Increment and Decrement Operator  

```javascript
let a =10;
a++;

let b =20;
b--;
```

## String Concatenation with Variables  

```javascript
let myPet = 'armadillo';
console.log('I own a pet ' + myPet+'.');
//Output: 'I own a pet armadillo.'
```

## String Interpolation  

In the ES6 version of JavaScript,we can insert,or interpolate,variables into strings using template literals.  
```javascript
const myPet = 'armadillo';
console.log('I own a pet ${myPet}.');
//Output: I own a pet armadillo.   
```

* a `template literal` is wrapped by backticks \`
* Inside the template literal,you'll see a placeholder,`${myPet}`.The value of `myPet` is inserted into the template literal.  
* When we interpolate `I own a pet ${myPet}.`,the output we print is the string:`I own a pet armadillo.`  

One of the biggest benefits to using template literals is the readability of the code.  
Using template literals, you can more easily tell what the new string will be.  
You also don't have to worry about escaping double quotes or single quotes.  

***
**Why can't we use template literals (``) all the time instead of normal string quotes(""/'')?**

answer:

We can use back ticks on all strings, with a few exceptions.  
```
aString = `this is a valid string`  
```
***

***
```
why would you go through the trouble of adding the money sign and curly brackets when you could just use plus signs?
('My name is ’ + myName + ’ My favorite city is ’ + myCity);
the output is exactly the same. are there instances where the plus signs wont work and you have to us ${}?
```

answer:
```
No. Both will work, but sometimes the 'bla bla' + 'bla bla (' + someVariable +') bla bla' OR
"bla bla " + someVariable + " bla 'direct quote' " + "bla bla" OR
using variables to build a path to a file: 'C:\'+someUser+'\'+someFolder+'\'+someSubFolder+'\'+someFileName
Can all be confusing. You can use the method you prefer, but you should be familiar with both. Also in JavaScript the \ is an escape character, so the code I wrote above would not produce the desired outcome. You could use double \\ 's to produce a \, or this:
```
```
`C:\${someUser}\${someFolder}\${someSubFolder}\${someFileName}`
```

## typeof operator  
```javascript
const unknown1 = 'foo';
console.log(typeof unknown1);//Output: string
```
注意：不用加括号啥的，棒棒的  
注意：写成unknown1.typeof是不行的，因为in JS it is a unary operator and not a method or variable.All the unary operators are written in <font color="red">lowercase</font>  

该Review Variables了

## Review Variables  
* Variables hold reusable data in a program and associate it with a name.  
* Variables are stored in memory.  
* The var keyword is used in pre-ES6 versions of JS.  
* let is the preferred way to declare a variable when it can be reassigned,and const is the preferred way to declare a variable with a constant value.  
* Variables that have not been initialized store the primitive data type undefined.  
* Mathmatical assignment operators make it easy to calculate a new value and assign it to the same variable.  
* The + operator is used to concatenate strings including string values held in variables  
* In ES6,template literals use backticks ` and \${} to interpolate values into a string.  
* The typeof keyword returns the data type (as a string) of a value.  

## THE ABC OF PROGRAMMING  

### WHAT IS A SCRIPT AND HOW DO I CREATE ONE

A script is a series of instructions that a computer can follow to achieve a goal.

> * Scripts are made up of instructions a computer can follow step-by-step.  
> * A browser may use different parts of the script depending on how the user interacts with the web page.  
> * Scrips can run different sections of the code in response to the situation around them.  

### WRITING A SCRIPT

To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.  

when learning a new skill, we often break it down into smaller tasks, and learn one of these at a time. With experience these individual tasks grow familiar and seem simpler.   

Start with the big picture of what you want to achieve, and break that down into smaller steps.  

1. DEFINE THE GOAL
2. DESIGN THE SCRIPT
3. CODE EACH STEP

## DESIGNING A SCRIPT: TASKS

Once you know the goal of your script, you can work out the individual tasks needed to achieve it. This high-level view of the tasks can be represented using a flowchart.

![image-20220130105045043](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220130105045043.png)

Each individual task may be broken down into a sequence of steps. When you are ready to code the script, these steps can then be translated into individual lines of code.  

![image-20220130105208428](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220130105208428.png)



## FROM STEPS TO CODE

you need to get to grips with the:

* Vocabulary: The words that computers understand
* Syntax: How you put those words together to create instructions computer can follow

Along with learning the language itself, if you are new to programming, you will also need to learn how 

a computer achieves different types of goals using a programmatic approach to problem-solving.

## DEFINING A GOAL & DESIGNING THE SCRIPT



## SKETCHING OUT THE TASKS IN A FLOWCHART  

流程图  有空可以学学

![image-20220130141739530](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220130141739530.png)


## What is a script and how do I create one?  
* A script is a series of instructions that the computer can follow in order to achieve a goal  
* Each time the script runs, it might only use a subset of all the instructions.  
* Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task programmatically.  
* To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task(a flowchart can help).  

## HOW DO COMPUTERS FIT IN WITH THE WORLD AROUND THEM?

computers create models of the world using data.  

In computer programming,each physical thing in the world can be represented as an object.
Each object can have its own:
* Properties
* Events
* Methods

An event is the computer's way of sticking up its hand to say, "Hey, this just happened!"

## METHOD

what is a method
Method typically represent how people(or other thing) interact with an object in the real world.  

## HOW A BROWSER SEES A WEB PAGE

how a browser interprets the HTML code and applies styling to it.  
1. RECEIVE A PAGE AS HTML CODE
Each page on a website can be seen as a separate document.So, the web consists of many sites, each made up of one or more documents.  
2. CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY  
At the top of the model is a document object,which represents the whole document.Beneath the document object each box is called a node. Each of these nodes is another object. This example features three types of nodes representing elements, text within the elements, and attribute.  

![image-20220130152640050](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220130152640050.png)

3. USE A RENDERING ENGING TO SHOW THE PAGE ON SCREEN
If there is no CSS, the rendering engine will apply default styles to HTML elements. However, the HTML code for this example links to a CSS style sheet, so the browser requests that file and displays the page accordingly.  
When the browser receives CSS rules, the rendering engine processes them and applies each rule to its corresponding elements.This is how the browser positions the elements inthe correct place, with the right colors, fonts, and so on.  

All major browsers use a JavaScript interpreter to translate your instructions(in JavaScript) into instructions the computer can follow.  

## HOW DO I WRITE A SCRIPT FOR A WEB PAGE?  

### HOW HTML,CSS,& JAVASCRIPT FIT TOGETHER

![image-20220130154621149](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220130154621149.png)

## PROGRESSIVE ENHANCEMENT  
html css javascript这三层构成了一种被称为渐进增强的构建网页的流行方法的基础。

These three layers form the basis of a popular approach to building web pages called progressive enhancement.  

some people browse with JavaScript turned off, so you need to make sure that the page still works for them.  

![image-20220130160155791](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220130160155791.png)

## CREATING A BASIC JAVASCRIPT

书 看到 46页了

![image-20220131092156259](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220131092156259.png)

Here you can see the file structure that you will end up with when you finish the example.Always treat file names as being case-sensitive.  

## LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE  
When you want to use JavaScript with a web page, you use the HTML <script> element to tell the browser it is coming across a script. Its src attribute tells people where the JavaScript file is stored.  

![image-20220131094231199](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220131094231199.png)

注意：Internet Explorer sometimes prevents JavaScript runing when you open a page stroed on your hard drive. If this affects you, please try Chrome, Firefox, Opera, or Safari instead.  

## PLACING THE SCRIPT IN THE PAGE  

有时候你会看到把js代码直接插在页面里<script>和</script>标签之间，这种情况下就不用src属性了，因为js代码不在其他地方就在当前页面里，不过最好还是把js代码放到专属文件里。  

![image-20220131094648978](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220131094648978.png)

document.write()把内容写进文档（网页）里，这是一种简单的方法但并不总是最好的方法。  

## SUMMARY
how do I wrtie a script for a web page?  
* It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the .js extension  
* The HTML <script> element is used in HTML pages to tell the browser to load the JavaScript file (rather like the <link> element can be used to load a CSS file).  
* If you view the source code of the page in the browser,the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.  

## Kelvin Weather  

如果这个项目过程中，你卡住了，或者你想看看富有经验的开发者是怎么整的，点“Get Unstuck” ，可以看视频。  

## Dog Years  

## What are Conditional Statements?  

We'll covering the following concepts: 
* if ,else if, and else statements  
* comparison operators
* logical operators
* truthy vs falsy values
* ternary operators
* switch statement

## If Statement  
javascript还是用花括号的，注意格式：
```javascript
if(true){
  console.log('This message
will print!');
}
```

## If...Else Statements
主要还是看下格式：
```javascript
if (false) {
  console.log('The code in 
this block will not run.');
} else {
  console.log('But the code
  in this block will!');
}
```

## Comparison Operators  
Here is a list of some handy comparison operators and their syntax:
* Less than: \<
* Greater than:\>
* Less than or equal to:\<=
* Greater than or equal to:\>=
* Is equal to:\===
* Is not equal to:\!==

字符串也可以用\===
```javascript
'apples' === 'oranges'
```

## Logical Operators  

there are threee logical operators:  
* the and operator (\&&)
* the or operator (\||)
* the not operator, otherwise known
  as the bang operator (!)  

## Truthy and Falsy  
```javascript
let myVariable = 'I Exist!';

if (myVariable) {
   console.log(myVariable)
} else {
   console.log('The variable
does not exist.')
}
```

这种情况下myVariable的值为真  
when used in a boolean or conditional context, it evaluates to true because it has been assigned a non-falsy value.  

So which values are falsy- or evaluate to false when checked as a condition?The list of falsy values includes:
* 0
* Empty string like "" or ''
* null which represent when there is no value at all
* undefined which represent when a declared variable lacks a value.  
* NaN, or Not a Number  

## Truthy and Falsy Assignment  
来来来，有一种让代码变短的办法：
下面代码：
```javascript
let username = '';
let defaultName;

if (username) {
  defaultName = username;
} else {
  defaultName = 'Stranger';
}

console.log(defaultName);
```
可以转换成
```
let username = '';
let defaultName = username || 'Stranger';

console.log(defaultName);
```

This concept is also referred to as short-circuit evaluation.  



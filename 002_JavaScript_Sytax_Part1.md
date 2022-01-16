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



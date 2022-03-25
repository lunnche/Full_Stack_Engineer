# 开始全栈工程师之路  

1. 什么是程序  
2. 软件工程师工作时都要干什么  
3. 前后端的区别  

记得在论坛里的projiects category请求和给与代码审查，这能强化你的学习成果  

# 什么是程序  

变成是人与计算机的合作  

Put simply,programming is giving a set of instructions to a computer to execute.  

programming 和 coding的区别：  

While sometimes used interchangeably,programming and coding actually have different definitions.  
* Programming is the mental process of thinking up instrucions to give to a machine (like a computer).  
* Coding is the process of transforming those ideas into a written language that a computer can understand.  


让机器理解人的意图，需要把操作的每一步都明确无误的定义好，无遗漏无歧义，many tears have been
shed over a missing semicolon(;) a symbol that a lot of programming language use to denote the end
of a line.  

人与机器的关系并非老板和雇员的关系，而是合作的关系，人擅长的机器不擅长，机器擅长的人不擅长   

记住：  

While learning to program may initially be frustrating,if you choose to stick with it,you'll be able to 
make some brilliant things.  

# 做个软件工程师是怎样的  

you are going to acquire knowledge and know how to reproduce things   
your biggest values in engineer is being to think creatively in new contexts and be able to use the 
tools that you do know to kind of build a new strategy that you didn't have before   

你看到咖啡 比起想到怎样做咖啡或卖咖啡  更会想到如何定义一个咖啡类 它和顾客的关系如何 某种意义上 你能够抽象出咖啡店的关键要素 从而可以优化结构 提升效率  

# 前后端的区别  

后端主要针对远程服务器，要做很多格式化、存储数据，保证用户访问数据的响应速度，保证服务器向前端发送数据响应的表现满足要求，前端主要处理如何把信息展示给用户，所以通常来说，你从后端获取数据，然后你需要把它很好的展示出来  

## web developer应该学什么语言  

所有的初级网络开发者肯定需要学HTML、CSS，因为那是构建网站的砖块  
然后需要学javascript来增加互动性到前端，javascript也用于后端，然后呢
如果你想要一个存储数据的app，你需要学SQL，一种数据库语言可以实现数据存取，

## Internet

TCP/IP: transmission control protocal  / internet protocal  

![image-20220218164641741](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220218164641741.png)

## The World Wide Web  

internet和www 的区别：
现在来说，people often use the terms internet and world wide web interchangeably,
they actually refer to quite different things.

 internet是指计算设备连接在一起的实际网络。尽管互联网早在20世纪80年代就已经存在了，但对于大多数人来说，并没有一种直观的方式来浏览internet。internet只是将一台电脑产生的信息发送给另一台电脑。

 万维网是一个相互链接的网站和其他网络资源的集合。万维网，结合上世纪90年代网络浏览器的兴起，推出了一个用户友好的界面，使用户可以浏览多媒体内容，并与其他用户互动。

 the internet is a network that links computer devices worldwide, enabling people to share information with one another despite vast distances.

## Browsers and Servers  

http : hypertext transfer protocol  

https : the data is being transferred securely 

![image-20220218170247225](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220218170247225.png)

when the server sends back a response it sends a status code that accompanies the requested resource 
you might be familiar with scene 404 error message when browsing the internet.  
this is an http response code that indicates that the requested content wasn't found   

http provides reliable structure to the interplay between the client and the server .

statsus code 

![image-20220218171644121](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220218171644121.png)

## How Do Browsers Work  

most of the time,our devices aren't making a single request.Every time we load a webpage,our device sends a request for each file that makes up that page.So even wehn we're just loading one webpage,that page can make multiple requests in order to retrieve different pieces of content, like images.  

So how does this process work when we're making multiple requests simultaneously?  
All of following steps happen in a split second:
1. When a user types in a URL and presses enter, the server processes the request and sends the HTML file back to the client. HTML files hold the content of a website and they also contain links for any additional assets or code that are needed to display the site properly.
2. The browser will begin to search for elements in the HTML file and it will start to make additional HTTP requests for any other external resources used by the HTML file. This often includes:
* One or more CSS stylesheets. CSS stands for cascading style sheets; CSS creates the style and layout of a web page. The browser will request the CSS stylesheet, and when the server sends it back, the browser analyzes the CSS and starts applying the visual styles to the content of the site.
* The request-response cycle also sends website assets, like images and videos, from the server to the browser. If these files are large, there might even be a noticeable delay before they are rendered by the browser.
* One or more JavaScript files. JavaScript makes the webpage interactive. This programming language functions as the “behavior” of the web page. A webpage that does not use JavaScript is known as a static webpage.

In most modern browsers, these additional requests are made in parallel

The HTML will be displayed even if some of the other assets have not been received by the browser.  

以上的这些过程，一秒甚至更快就完成了，具体多块取决于：
* the speed of the user's connection
* the size of the website
* physical distance between the browser and the server.  

## Web 2.0  

A collection of advances in the early 2000s created a cluster of web applications that are often called “Web 2.0”. In comparison to early static websites, Web 2.0 applications are often defined by:
* Providing a dynamic user experience by offering content that responds to user input without forcing the page to reload. In the early web, user input would typically take the user to a new page — and they would have to wait for the new page to load. In Web 2.0, websites could just update selected regions of the page, avoiding the interruption caused by reloading.
* Emphasizing user-generated content and social sharing. In the early web, content was generally authored by a single source. The rise of blogging, social media, and wikis in web 2.0 meant that users could generate content and share it with their friends.

web2.0的技术进步：
1. jQuery是第一个可以在网页运行时获取数据的JavaScript框架。
2. 连接到数据库的web框架的兴起，如Spring、Django和Ruby-on-Rails，使用户生成的内容能够被有效地创建、存储和显示。  

web 1.0 和 2.0网页的区别

![image-20220221091319309](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220221091319309.png)

web 1.0 网页是静态的： 它不响应用户行为，内容对所有用户都是一样的。

web 2.0 网页是：
互动-你可以在页面上点赞和评论
动态-发布后（12小时内）无需重新加载整个页面就可以更新。
允许社交互动

移动互联网 

响应式网页设计  
响应式网页设计的兴起改变了网站的构建方式。响应式网页设计是通过添加到CSS语言来实现的，比如媒体查询和相关单元。这些增加的内容允许网站的显示根据窗口的大小进行调整。

## What is web development
主要用到的四种语言：
* HTML structures website content
* CSS applies styling to websites
* JavaScript adds interactivity to websites
* SQL allows your web application to store and retrieve data  

## What is HTML  

## HTML Markup  

HTML separates content and annotation by using HTML tags, which are denoted by angle brackets (also known as less-than and greater-than signs).  

## HTML Elements  

![image-20220221104016330](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220221104016330.png)

## Hypertext and the world wide web  

## Adding hyperlinks  

Reading and modifying code is an essential first step in learning to build things for the web.  

Links are created in HTML with something called the `href` attribute,which stands for hyperlink reference.

anchor tag 链接标记 `<a>`

例如：
```html
<a href="www.codecademy.com">Learn to code!</a>
```

## What is CSS
CSS is the language that provides style to the content of an HTML page.This includes colors,fonts,positioning,layout,and more!

为什么我们需要一种用于内容和表示的独立语言?这是计算机科学分离关注点原理的一个例子。当每个部分都有它试图解决的明显区别的问题时，大型代码库可以保持可维护性。

由于样式规则与内容本身是分开描述的，所以如果添加了更多段落、图像或其他形式的内容，她可以期望它们以与现有内容相同的方式进行样式设置。从长远来看，这将节省时间，特别是当她的网站变得越来越复杂的时候。

![image-20220301142318873](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220301142318873.png)

## Applying CSS

An HTML link tag is often used to create a connection between an HTML file and CSS file and tells the browser to apply the CSS styles to the HTML.

## what is JavaScript?
## JavaScript Functions
## What is SQL?

## Review
JavaScript was initially just a language for interacting with HTML, but JavaScript has expanded to be a general-purpose programming language that can be run outside of the browser. You can now build web applications, browser games, desktop applications, and even VR/AR experiences in JavaScript.

# introduction to HTML

Only content inside the opening  and closing body tags can be displayed to the screen.
```html
<body>
  <p>What's up, doc?</p>
</body>
```

## HTML structure  

Understanding HTML hierarchy is important because child elements can inherit behavior and styling from their parent element. 

## Headings  

## Divs

`<div>`s don' inherently have a visualrepresentation.  

div的意义是啥，它看不见，但对于自定义样式非常有用，div包起来的部分可以使用同样的style

## Attributes
🌰
```html
<div id="intro">
  <h1>Introduction</h1>
</div>
```

## Displaying Text
if you want to display text in HTML,you can use a paragraph or span:
`<p>`只能包含纯文本
`<span>`不只能包含纯文本，还有其他HTML元素，它们用于分隔与其他内容在同一行上的小段内容。
看个栗子

![image-20220309092634230](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220309092634230.png)

上面的`<span>`的用途是啥？将"Self-driving cars"与段落中其余文本分开。

## Styling Text
`<em>`  emphasizes text
`<strong>` highlights important text

你可以自己设置让浏览器如何展示`<em>`和`<strong>`标签
默认是：
The `<em>` tag will generally render as italic emphahsis.
The `<strong`> will generally render as bold emphasis.

## Line Breaks
`<br>`  只有starting tag ,没有 close tag

## Unordered Lists
🌰

![image-20220309095559692](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220309095559692.png)

## Ordered Lists
也是`<ol>`里面加`<li>`的样式

## Images
`<img>` tag is a self-closing tag.
self-closing tag 后边 加不加`/`都行
```html
<img src="image=location.jpg" />
```

src : uniform resource locator(URL).
A URL is the web address or local address where a file is stored.

## Image Alts

![image-20220314093730022](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220314093730022.png)

整`alt`还有这些意义：
1. 图片未正常加载，鼠标悬停显示文字（alt中设置的图片描述信息）


整`alt`还有这些意义：
1. 图片未正常加载，鼠标悬停显示文字（alt中设置的图片描述信息）


整`alt`还有这些意义：
1. 图片未正常加载，鼠标悬停显示文字（alt中设置的图片描述信息）
2. 借助屏幕阅读器，盲人可以听到你设置的图片描述
3. 提升你网站的ranking，搜索引擎搜不到图，但能搜到你alt中设置的图片描述信息

如果你的图片不表达有用信息，alt标签就留空  

## Videos
和`<img>`不同,`<video>标签要有开闭标签`,

![image-20220314095242660](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220314095242660.png)

上面controls 表示包含基本视频控制，比如暂停，播放等  

标签之间的文字"Video not supported"，只会在视频显示不出来的时候展示  

## Review

![image-20220314101300176](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220314101300176.png)

## Preparing for HTML
让浏览器知道我们在用HTML

在文档开始处进行声明
```html
<!DCOTYPE html>
```

## The `<html>` tag 

![image-20220314160625372](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220314160625372.png)

## The Head
The `<head>` element contains the metadata for a web page. Metadata is information about the page that isn’t displayed directly on the web page.

## Page Titles

![image-20220322110121921](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220322110121921.png)

## Linking to Other Web Pages

![image-20220322134339160](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220322134339160.png)

## Opening Links in a New Window

![image-20220322134854111](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220322134854111.png)

## Linking to Relative Page
网页是怎么储存的

![image-20220322135439208](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220322135439208.png)

用relative path来连接到同在根目录下的其他html文件

![image-20220322135616720](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220322135616720.png)

## Linking At Will

![image-20220322140251153](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220322140251153.png)

## Linking to Same Page
In order to link to a target on the same page, we must give the target an id, like this:

![image-20220322140818720](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220322140818720.png)
An id should be descriptive to make it easier to remember the purpose of a link. The target link is a string containing the # character and the target element’s id.

![image-20220322141137173](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220322141137173.png)

An id is especially helpful for organizing content belonging to a div!

## Whitespace
Programmers use two tools to visualize the relationship between elements: whitespace and indentation.

## Indentation
the W3C recommends 2 spaces of indentation when writing HTML code

## Comments

![image-20220322143634359](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220322143634359.png)

## HTML Tags
在这里查看所有的html tag：
https://developer.mozilla.org/en-US/docs/Web/HTML/Element

review what I learn:

![image-20220322144754653](https://raw.githubusercontent.com/lunnche/picgo-image/main/image-20220322144754653.png)

# Intro to Mozilla Developer Network
Learn how to search and use the Mozilla Developer Network documentation

MDN有关于网络开发的各种各样的文档，包括html，css，javascript

在MDN上搜索文章：
一般文章包括这些内容：
A definition and demo
Attributes
Usage notes
Examples
Accessibility concerns
Specifications
Browser compatibility
Related topics

没必要通读，没必要全搞懂，关注对自己最有意义的即可。
其中的Browser Compatibility 部分  类似于  caniuse.com 这个网站会less detailed 一些。

## HTML on MDN Web Docs:Debugging

HTML和DOM的区别

HTML represents initial page content, and the DOM represents current page content. When JavaScript adds, removes, or edits nodes, the DOM becomes different than the HTML.

Chrom DevTools 初步教程：https://developer.chrome.com/docs/devtools/dom/

因为HTML对错误比较宽容，会帮你自动修补你的有bug的代码，但这样可能导致意想不到的错误，一个好的办法是先在Markup Validation Service 中检查代码错误
the best strategy is to start by running your HTML page through the Markup Validation Service:https://validator.w3.org/

## Introduction to Tables



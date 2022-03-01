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



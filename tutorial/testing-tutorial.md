## 回归测试(Regression Testing)

>关于该主题的资源清单：视觉回归测试（A curated list of resources around the topic: visual regression testing）: https://github.com/mojoaxel/awesome-regression-testing

## 负载测试

#### [Locust](https://github.com/locustio/locust)

> 用Python编写的可扩展的用户负载测试工具(Scalable user load testing tool written in Python) http://locust.io

  - [【LocustPlus序】漫谈服务端性能测试](http://debugtalk.com/post/locustplus-talk-about-performance-test/)
  - [深入浅出开源性能测试工具Locust（使用篇）](http://debugtalk.com/post/head-first-locust-user-guide/)

#### [Cypress ](https://github.com/cypress-io/cypress)

>快速，简单和可靠的测试任何在浏览器中运行的任何东西。(The web has evolved. Finally, testing has too.Fast, easy and reliable testing for anything that runs in a browser.) https://www.cypress.io

#### [Webdriverio](https://github.com/webdriverio/webdriverio/)

这个库是 [Node.JS 的 Webdriver](https://w3c.github.io/webdriver/webdriver-spec.html) （浏览器自动化）模块。它使您可以在您最喜爱的BDD / TDD测试框架中编写超级简单的 [Selenium](https://en.wikipedia.org/wiki/Selenium_(software)) 测试，该测试框架可以使用 Sauce Labs，BrowserStack 或 TestingBot 在本地或云中运行。 http://webdriver.io

#### [Siege](https://github.com/JoeDog/siege)

> Siege is an http load tester and benchmarking utility

#### [Jmeter](https://github.com/apache/jmeter)

>Apache JMeter可用于测试静态和动态资源，Web动态应用程序的性能。它可用于模拟服务器，服务器组，网络或对象上的重负载，以测试其强度，或分析不同负载类型下的整体性能。

#### KITE

> KITE网络测试环境是由Keynote公司开发的一个基于云平台的网站性能和负载测试平台。

#### Tsung

>Tsung 是一个压力测试工具,可以测试包括HTTP, WebDAV, PostgreSQL, MySQL, LDAP, and XMPP/Jabber等服务器。

## 性能测试

## WebPagetest

>WebPageTest是一款非常强大的Web页面性能评测工具,最早是在AOL内部使用的，现在已经开源了。在该网站输入你的url，就会生成1个url加载的时间瀑布图，对所有加载的资源(css,js,image等等)列出优化的清单。

## 代码检查类

#### CSS Lint

>CSSLint 是一个用来帮你找出 CSS 代码中问题的工具，它可做基本的语法检查以及使用一套预设的规则来检查代码中的问题，规则是可以扩展的。

#### JSLint

>JSLint是一个JavaScript验证工具(非开源),可以扫描JavaScript源代码来查找问题


## 网页抓包

#### Fiddler

>Fiddler是最强大最好用的Web调试工具之一，它能记录所有客户端和服务器的http和https请求，允许你监视，设置断点，甚至修改输入输出数据。

#### Charles

>Charles是一个HTTP代理服务器，TTP监视器，反转代理服务器。它允许一个开发者查看所有连接互联网的HTTP通信。这些包括request，response现HTTP headers （包含cookies与caching信息）。


#### PageSpeed

>Page Speed 是开源 Firefox/Firebug 插件，网站管理员和网络开发人员可以使用 Page Speed 来评估他们网页的性能，并获得有关如何改进性能的建议。

#### Firebug

>Firebug 是firefox中最为经典的开发工具，可以监控请求头，响应头，显示资源加载瀑布图：

## Chrome 插件

#### [puppeteer](https://github.com/GoogleChrome/puppeteer)
>Puppeteer is a Node library which provides a high-level API to control headless Chrome over the DevTools Protocol. It can also be configured to use full (non-headless) Chrome.
>
>Most things that you can do manually in the browser can be done using Puppeteer! Here are a few examples to get you started:
>- Generate screenshots and PDFs of pages.
Crawl a SPA and generate pre-rendered content (i.e. "SSR").
- Scrape content from websites.
- Automate form submission, UI testing, keyboard input, etc.
- Create an up-to-date, automated testing environment. Run your tests directly in the latest version of Chrome using the latest JavaScript and browser features.
- Capture a timeline trace of your site to help diagnose performance issues.


#### [lighthouse](https://github.com/GoogleChrome/lighthouse)
>Lighthouse analyzes web apps and web pages, collecting modern performance metrics and insights on developer best practices.(灯塔分析网络应用程序和网页，收集现代性能指标和开发人员最佳实践的见解。)

#### Speed Tracer

>speed trace 是google chrome的1个插件，speed trace的优势点是用于监控JS的解析执行时间，还可以监控页面的重绘、回流，这个还是很强的(dynaTrace也能有这个功能)。

#### Chrome Dev Tools

>Chrome DevTools是一套内置于谷歌浏览器的网页编制和调试工具，帮助Web开发人员检查代码面板。

#### Chrome for Android

>Chrome for Android可在Android上远程调试Chrome浏览器。


#### PageSpeed Insights

>PageSpeed Insights是谷歌推出的一款性能优化工具，其目的是帮助站长优化页面，从而能够带来最佳的渲染性能，尤其实针对移动页面。

#### PhantomJS

>PhantomJS是一款前端自动化测试工具。它本质上是一个基于webkit内核的无界面浏览器，并可使用JavaScript或CoffeeScript进行编程。

#### Wappalyzer

>Wappalyzer插件可以告诉你当前正在访问的网页是采用什么软件搭建的。它能够检测出CMS和电子商务系统、留言板、javascript框架，主机面板，分析统计工具和其它的一些web系统。

#### Speed Tracer

Speed Tracer由Google开发的一款测试网页性能分析插件，而且开源。

## 其他

#### TestCafé

TestCafé是DevExpress最新开发的一款革命性的Web测试框架。它支持所有主流浏览器，操作系统和移动平台，支持远程设备，多浏览器并行测试。TestCafé内置一个可视化测试记录器，支持持续集成，脚本标记分析等强大功能。

#### VB Watch

VB Watch 是三种工具之一：Profiler, Protector 以及 Debugger. Profiler 衡量性能及测试覆盖率。 Protector 实现健壮的错误处理。 Debugger 有助于监控你的可执行文件。

#### Cuzillion

Cuzillion是一个很酷的工具，帮助你查看页面组件的交互，目标是帮助你在结构化页面的时候快速检查，测试和编辑web页面。

#### Performance Analyser

Performance Analyser可以自动分析网页性能，同时为你提供详细的性能指标。

#### ANTS Performance Profiler

NTS性能分析器是一种用于分析.NET框架支持的以任何语言编写的应用程序的工具。ANTS性能分析器能分析所有.NET应用程序，包括ASP.NET网络应用程序、Windows服务和COM+应用程序。

#### YSlow for Chrome

YSlow for Chrome是一款由Yahoo开发网站性能优化扩展，在十几个方面给你的网站提出优化建议，包括尽可能的减少 HTTP 的请求数 、使用 Gzip 压缩、将 CSS 样式放在页面的上方、将脚本移动到底部、减少 DNS 查询等十几条规则。


#### Wireshark

Wireshark(前称Ethereal)是一个网络封包分析软件。网络封包分析软件的功能是撷取网络封包, 并尽可能显示出最为详细的网络封包资料。

#### dynaTrace Ajax Edition

dynaTrace Ajax Edition 是一个强大的底层追踪、前端性能分析工具。您可以利用它来分析页面渲染时间、DOM方法执行时间，甚至可以看到JS代码的解析时间。

#### HTTP Archive

HTTP Archive可追踪网站的构建。HTTP Archive的代码开源，下载地址。

#### Weinre

Weinre代表We b In spector Re mote，是一种远程调试工具。举个例子，在电脑上可以即时 的更改手机上对应网页的页面元素、样式表，或是查看Javascript变量，同时还可以看到手机上页面的错误和警告信息。

#### Opera Dragonfly

Opera Dragonfly 是适用于 Opera 浏览器的跨设备、跨平台的调试环境 – 调试 JavaScript、检查和编辑 CSS 与 DOM,以及查看手机或计算机上的任何错误。

#### Apache Bench (ab)

ApacheBench 主要是用来测试阿帕奇服务器执行效率用的。

#### Show Slow

Show Slow是一个开源的基于web的工具，用来收集从Page Speed获得的性能参数。

#### Browserscope

Browserscope 是一个开源项目，用于测试Web浏览器的性能，如程序概要分析，存储和收集crowd-sourced数据等。

#### DOM Monster

DOM Monster 由script.aculo.us的作者开发的一个用于分析Web页面的DOM和其它特性。它能够检查HTML+JavaScript代码，并一些警告和建议如：减少使用样式属性的标签数量；查找JavaScript全局变量，并减少它们以便改进性能等。

#### Mobileperf Bookmarklet

Mobileperf Bookmarklet是针对于移动设备的Web调试器和分析器。

#### Redbot

这是一个机器人工具，帮助用户检查HTTP资源，可查看它的操作情况，指出常见的问题并提出改进。

#### Boomerang

Boomerang是由雅虎Exceptional Performance(异常性能)小组发布的网站性能监测工具，能从最终用户的角度来衡量网站性能，并将数据发送回服务器以便进一步分析。

#### Netalyzer

Netalyzer是一款用于搜集域名、跟踪路由器信息的小型工具。

#### Shunra NetworkCatcher Express

Shunra NetworkCatcher是一款高度灵活的、功能强大的网络监控工具，使企业能够轻松准确地记录、导入、重播真实网络行为，如延迟，丢包和可用带宽。

#### GTMetrix

Gtmetrix是国外的一个免费评测网页载入速度的服务,挺专业的,提供了详细报告,而且会保存每一个网站的记录,可以方便查看一个网站载入速度的历史变化。

#### Torbit Insight

Torbit Insight是一款面向网站运营者的免费工具软件，提供了一系列网站前端优化服务，以提高网站加载速度，留住访问用户。

#### Grunt.js

Grunt.js是一个Javascript Task Runner(Javascript任务运行器),其基于NodeJS,可用于自动化构建、测试、生成文档的项目管理工具。

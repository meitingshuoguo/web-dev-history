---
theme: apple-basic
colorSchema: "auto"
layout: intro-image
image: "/images/bkg.png"
defaults:
  layout: "bullets"
---

#

<div class="absolute bottom-48 text-right">
<h1>web前端技术发展简史</h1>
  <span class="font-300">
    何富康
  </span>
</div>
---

# 静态页面时代

- html (1990)
- css (1996)
- 这个阶段的网页还非常的原始，主要以 HTML 为主，是纯静态的只读网页。

---

# 动态页面的发展 ( PHP、JSP 和 ASP )

- Javascript (1995)

  跑马灯、浮动广告之类的特效和应用，让网页动了起来。但是网页真正开始向动态交互发展的开端，却是 PHP、JSP 和 ASP 为代表的后端动态页面技术的出现。

  这些服务器端的动态页面技术使得网页可以获取服务器的数据信息并保持更新，推动了 Google 为代表的搜索引擎和各种论坛的出现，万维网开始快速发展。

  服务器端网页动态交互功能的不断丰富，伴随的是后端逻辑的复杂度快速上升，代码越来越复杂。为了更好的管理后端逻辑，出现了大量后端的 MVC 框架。

<div class="flex justify-start pl-5">
<div class="pr-10" >
 
```html
<html>
	<body>
		This document has been prepared ahead of time.
		Regards.
	</body>
</html>
```
</div>
<div>
```html
<html>
	<body>
		Y2K? <?php echo time(); ?>
	</body>
</html>
```
</div>
</div>

---

# Ajax (2004)

2004 年前的动态页面都是由后端技术驱动的，虽然实现了动态交互和数据即时存取，但是每一次的数据交互都需要刷新一次浏览器。频繁的页面刷新非常影响用户的体验，这个问题直到谷歌在 04 年应用 Ajax 技术开发的 Gmail 和谷歌地图的发布，才得到了解决。

这背后的秘密就是 Ajax 技术中实现的异步 HTTP 请求，这让页面无需刷新就可以发起 HTTP 请求，用户也不用专门等待请求的响应，而是可以继续网页的浏览或操作。

Ajax 开启了 web2.0 的时代。
NetScape 在第一次浏览器之战中败给了 IE 之后，创办了 Mozilla 技术社区，该社区之后发布了遵循 W3C 标准的 firefox 浏览器，和 Opera 浏览器一起代表 W3C 阵营和 IE 开始了第二次浏览器战争。

不同的浏览器技术标准有不小的差异，不利于兼容开发，这催生了 Dojo、Mooltools、YUIExtJS、jQuery 等前端兼容框架，其中 jQuery 应用最为广泛。

---

# Node.js (2009)

2009 年，Ryan Dahl 以 Chrome 的 V8 引擎为基础开发了基于事件循环的异步 I/O 框架-Node.js。

Node.js 使得前端开发人员可以利用 javascript 开发服务器端程序，深受前端开发人员的欢迎。很快，大量的 Node.js 使用者就建构了一个用 NPM 包管理工具管理的 Node.js 生态系统。

Node.js 也催生了 node.webkit 等项目，拓展了 javascript 开发跨平台的桌面软件的能力。

---

# 前端 MV\*架构及 SPA 时代 (2010)

- AngularJS (2010)
- React (2013)
- Vue (2014)

---

# 移动 Web 和 Hybrid App ()

---

# ECMAScript6 (2015)

ECMAScript 6.0 发布，该版本增加了很多新的语法，极大的拓展了 javascript 的开发潜力。由于浏览器 ES6 语法的支持滞后，出现了 Babel 和 TypeScript 来把 ES6 代码编译成 ES5 等现有浏览器支持的代码。

## ES6 现已更名为 ES2015，以后每年会发布新的 ES 标准，这标志着 javascript 的发展将会更快。

# 今天

NPM 和 Yarn 为代表的包管理工具；ES6 及 Babel 和 TypeScript 构成的脚本体系；HTML5；CSS3 和相应的处理技术；React、Vue、Anjular 为代表的框架；Webpack 为代表的打包工具；Node.js 为基础的 Express 和 KOA 后端框架；Hybrid 技术。

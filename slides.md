---
theme: apple-basic
colorSchema: 'auto'
layout: intro-image
image: './public/images/bkg.png'
defaults:
  layout: 'bullets'
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
* html (1990)
* css (1996)
* 这个阶段的网页还非常的原始，主要以HTML为主，是纯静态的只读网页。

---


# 动态页面的发展 ( PHP、JSP和ASP )
* Javascript (1995)
  
  跑马灯、浮动广告之类的特效和应用，让网页动了起来。但是网页真正开始向动态交互发展的开端，却是PHP、JSP和ASP为代表的后端动态页面技术的出现。

  这些服务器端的动态页面技术使得网页可以获取服务器的数据信息并保持更新，推动了Google为代表的搜索引擎和各种论坛的出现，万维网开始快速发展。

  服务器端网页动态交互功能的不断丰富，伴随的是后端逻辑的复杂度快速上升，代码越来越复杂。为了更好的管理后端逻辑，出现了大量后端的MVC框架。
  
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
2004年前的动态页面都是由后端技术驱动的，虽然实现了动态交互和数据即时存取，但是每一次的数据交互都需要刷新一次浏览器。频繁的页面刷新非常影响用户的体验，这个问题直到谷歌在04年应用Ajax技术开发的Gmail和谷歌地图的发布，才得到了解决。

这背后的秘密就是Ajax技术中实现的异步HTTP请求，这让页面无需刷新就可以发起HTTP请求，用户也不用专门等待请求的响应，而是可以继续网页的浏览或操作。

Ajax开启了web2.0的时代。
NetScape在第一次浏览器之战中败给了IE之后，创办了Mozilla技术社区，该社区之后发布了遵循W3C标准的firefox浏览器，和Opera浏览器一起代表W3C阵营和IE开始了第二次浏览器战争。

不同的浏览器技术标准有不小的差异，不利于兼容开发，这催生了Dojo、Mooltools、YUIExtJS、jQuery等前端兼容框架，其中jQuery应用最为广泛。

---

# Node.js (2009)
2009年，Ryan Dahl以Chrome的V8引擎为基础开发了基于事件循环的异步I/O框架-Node.js。

Node.js使得前端开发人员可以利用javascript开发服务器端程序，深受前端开发人员的欢迎。很快，大量的Node.js使用者就建构了一个用NPM包管理工具管理的Node.js生态系统。

Node.js也催生了node.webkit等项目，拓展了javascript开发跨平台的桌面软件的能力。

---

# 前端MV*架构及SPA时代 (2010)
* AngularJS (2010)
* React (2013)
* Vue (2014)

---

# 移动Web和Hybrid App ()

---

# ECMAScript6 (2015)
ECMAScript 6.0发布，该版本增加了很多新的语法，极大的拓展了javascript的开发潜力。由于浏览器ES6语法的支持滞后，出现了Babel和TypeScript来把ES6代码编译成ES5等现有浏览器支持的代码。

ES6现已更名为ES2015，以后每年会发布新的ES标准，这标志着javascript的发展将会更快。
---
# 今天

NPM和Yarn为代表的包管理工具；ES6及Babel和TypeScript构成的脚本体系；HTML5；CSS3和相应的处理技术；React、Vue、Anjular为代表的框架；Webpack为代表的打包工具；Node.js为基础的Express和KOA后端框架；Hybrid技术。


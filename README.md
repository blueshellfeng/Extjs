# Extjs的学习
一、认识<br/>
1、ExtJS是用javascript、CSS和HTML的技术实现的主要用于创建用户界面，且与后台技术无关的前端Ajax框架，还被用来开发RIA（富客户端）的Web应用。以UI闻名于世。所有的ExtJS的UI组件中，  Grid组件是使用最频繁、功能最复杂，同时也是实现最好的。“无论是界面之精美，还是功能之强大”都无人能出其右的。<br/>
2、要成为事实上的标准，必须具备两个条件：1.适用范围非常广泛；2.要实现的非常完善，功能强大。<br/>
3、ExtJS来源于YUI（Yahoo！User Interface Library），是一个使用JavaScript编写的工具和控件库。<br/>
4、2006年初，Jack Slocum（杰克斯~洛克姆）的YUI-Ext，2007年初，改名为ExtJS。<br/>
5、Web应用的运行环境是浏览器，运行方式是以HTML、CSS和JavaScript方式运行的。<br/>
*初始阶段：纯以HTML、CSS展示信息，此时叫做网站（以CGI、ASP、JSP为代表的动态网页技术；以Java、.NET为代表的服务器端技术及各种应用框架；出现了以GWT-Ext、Wicket为代表的客户端与服务端全融合的技术）。<br/>
*发展阶段:动态页面技术，服务端技术（Web应用必须走向简化从而加以普及）。<br/>
*普及阶段：集成、可视化的开发工具。<br/>
6、ExtJS UI组件：由Component类定义，每种组件都有指定的xtype属性值，通过该值可以得到一个组件的类型或者定义一个指定类型的组件。<br/>


二、开始<br/>
1.ExtJS只是一套用JavaScript实现的界面层组件，所以在无须与服务器进行数据交换的情况下，在本地浏览器就能很好的运行。<br/>
2. ExtJS中的基本概念：<br/>
  • 面板Panel：放置各种组件的区域，各种组件的展现由面板管理。<br/>
  • 布局Layout：组件在一个容器中毒摆放方式。<br/>
  • 组件Component：已经预先实现好特定功能，并能够重用到编程中的代码段以及相关资源。<br/>
  • 渲染Render：含有ExtJS程序的页面下载完毕后在浏览器中完全展现出来的一个过程。（普通的HTML页面渲染是从HTML与CSS代码开始装载进浏览器到整个页面根据HTML与CSS规则完全显示出来的过程。）但是ExtJS的界面HTML与CSS不是从服务器下载的，而完全是有ExtJS的引擎动态生成而来。<br/>
  • 窗口Window：并不是一个真正的Windows窗口，在本质上只是一个层 利用CSS进行格式化，在外观和行为上都比较像真正的Windows窗口的显示区域。窗口组件继承于面板组件。<br/>
  • 对话框Dialog：本质也是利用CSS进行格式化的层。<br/>
3. ExtJS对JavaScript中的Array、Date、Function、Number和String 5个类进行了扩展。<br/>
  • Ext.Array：处理数组；<br/>
  • Ext.Date：处理日期；<br/>
  • Ext.Function：处理函数；<br/>
  • Ext.Number：处理数字；<br/>
  • Ext.String：处理字符串；<br/>
  • Ext.Object：处理对象。<br/>



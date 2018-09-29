# 初始篇
&emsp;&emsp;ionic是一个web主体型框架。用来开发混合手机应用的，开源的，免费的代码库。可以优化html、css和js的性能，构建高效的应用程序，而且还可以用于构建Sass和AngularJS的优化。为了解决其他一些UI库在手机上运行缓慢的问题，它直接放弃了 IOS6 和 android 4.1 以下的版本支持，来获取更好的使用体验。 

### ionic技术栈
** 1.UI前端控制层AngularJS **
&emsp;&emsp;Javascript MVC框架进阶的MVVM框架。View和Model之间没有联系，通过ViewModel进行交互，而且Model和ViewModel之间的交互是双向的，视图的数据的变化会同时修改数据源，而数据源数据的变化也会立即反应到View上。

<img src="/assets/demo1.png" width="100%" align="center"/>

** 2.UI样式预处理语言sass  **
Css预处理器，它的基本思想是，用一种专门的编程语言，进行网页样式设计，然后再编译成正常的CSS文件。它的同类有Less，Stylus

** 3.原生交互phonegap & cordova  **
&emsp;&emsp;PhoneGap是一个用基于HTML，CSS和JavaScript的，创建移动跨平台移动应用程序的快速开发平台。它使开发者能够利用IOS，Android，Palm，Symbian,WP7,WP8,Bada和Blackberry智能手机的核心功能——包括地理定位，加速器，联系人，相册，声音和振动等，此外PhoneGap拥有丰富的插件，可以调用。
&emsp;&emsp;Cordova是贡献给Apache后的开源项目，是从PhoneGap中抽出的核心代码，是驱动PhoneGap的核心引擎。你可以把它们的关系想象成类似于Webkit和Google Chrome的关系。使用cordova测试，发布app应用。

** 3.gulp工程优化工具  **
自动化构建工具，增强你的工作流程，主要用做文件迁移，文件合并，文件压缩、css编译器处理等。

### 优劣对比  
** 优势 **
&emsp;&emsp;ios 和 android基本上可以共用代码，纯web思维，开发速度快，简单方便，一次编码，到处运行，如果熟悉web开发，则开发难度较低。
文档很全，系统级支持封装较好，所有UI组件都是有html模拟，可以统一使用。
可实现在线更新 允许加载动态加载web js
文档多，开发者多，视频教程多 容易学习    遇到问题容易解决  技术成熟  

** 劣势 **
占用内存高一些（不过手机内存都大了不影响），不适合做游戏类型app，   web技术无法解决一切问题，对于比较耗性能的地方无法利用native的思维实现优势互补，如高体验的交互，动画等。
Ionic1.x接入的原生接口依赖工程创建sdk，版本低。有的移动端新功能无法使用。在高配移动端可能出现不支持兼容问题。Ionic2.x以上已有改善。



PHP Desktop Application
===
###PHP Desktop Application(PDA) 是PHP的桌面程序开发框架。
![](http://phpdesktop.sinaapp.com/manual/imgs/hello.png)  
author：goodook@163.com
QQ群：98752246 

本框架可以让php开发者，轻易地转移到桌面应用程序的开发，快速开发出优秀的桌面程序，（1天即可熟悉本框架的运用）。
框架特性：
---
####1. 界面和功能分离。 
基于HTML的UI，与基于PHP的功能配合，让程序开发更易模块化 (参考我的第一个程序)
####2. PHP直接调用 JS 代码  
  (参考$WIN->jsExec)
####3. PHP直接控制web页面元素  
  (参考UI对象，PHP代码允许直接内置于HTML内)
####4. JS 直接调用 PHP代码 
  (参考页面内php对象)
####5. web事件直接回调PHP代码 
(参考$WIN->AddEvent)
####6. PHP调用Winows Api 
(参考$APP->Win32API)
####7. PHP定时器，PHP多实例多线程  
(参考Task对象)
####8. 提供了 PHP，JS 的编译后运行
（可用于UI资源加密）  (参考加密章节)
####9. 支持php和JS的zend编译优化 
(参考加密)
####10. 断点调试
php基于xdebug的断点调试，JS基于ie内核断点调试

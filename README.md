# WebRunLocal
WebRunLocal(本网通)SDK可实现网页JS脚本和本地系统API的高效率双向互动，可充分发掘利用本地电脑的资源实现一些特殊的任务，彻底解决Chrome、firefox、safari、opera、Edge等浏览器网页中不能调用本地电脑大多数系统资源问题，操作系统兼容性：支持桌面系统Windows XP/Vista/7/8/10及服务器系统Windows Server 2003到2019版，在未来还将支持Linux及Mac等系统，期待有更多朋友能够参与其中，共同推进本项目的发展。

在Internet Explorer大行其道的时代，大家都知道实现网页和本地系统API双向互动的方法是使用ActiveX控件技术，然而这个技术不通用，也有很大的安全隐患，包括微软新的浏览器Edge都不再支持这个ActiveX控件，导致原来很多依赖ActiveX技术实现的一些业务在新版浏览器中无法继续使用，现在让WebRunLocal(本网通)SDK来帮您平滑过渡业务，实现浏览器全面兼容使用！

可能您有疑问，采用Node.js中的ffi同样可以实现在JavaScript中调用本地的DLL动态链接库实现业务逻辑，为啥还要用WebRunLocal(本网通)SDK呢？问题在于ffi只能调用C语言风格的模块，不是面向对象的接口方式，使用上还是很不方便。

使用WebRunLocal(本网通)SDK，您将获得以下好处：
1、本网通Windows版基于WebSocket和COM组件技术，提供面向对象的服务接口，开发集成非常容易；
2、本网通提供WebSocket服务的ActiveX控件，可以让Internet Explorer7/8/9同样可以使用Web Socket技术，极大提高您的技术方案适配性；
3、自定义的程序分发支持，方便基于本网通的第三方插件应用分发部署。

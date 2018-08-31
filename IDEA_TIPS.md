# IDEA 性能优化实践

IDEA 作为日常开发的主要工具，每天都会使用，但最近升级之后，CPU总是占用很高。So 开始 Googling， 得到如下解决方案：

---

1. 设置系统变量

   环境变量添加“IDEA_JDK”或者“IDEA_JDK_64”，值写已经安装的JDK路径

2. 通过设置选择当前已安装的JDK

   使用IDEA全局快捷键 

       Ctrl + Alt + A

    然后输入

        switch

	找到switch boot sdk，更改当前IDEA使用的JVM。

---

我的问题是按照上面的步骤解决的，如有  什么“其他声音”，请留言讨论。




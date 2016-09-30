# 使用Node.js搭建Web服务器

1、能显示以.html/.htm结尾的Web页面

2、形如http://xxx.com/a/b/ , 则查找b目录下是否有index.html,如果有就显示，如果没有就列出该目录下的所有文件及文件夹，并可以进一步访问。

3、形如http://xxx.com/a/b,  则作301重定向到http://xxx.com/a/b/ , 这样可以解决内部资源引用错位的问题。

启动项目：
cd 到项目根目录 
执行 node start.js
浏览器红访问 127.0.0.1


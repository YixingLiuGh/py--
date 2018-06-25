# py--
两个网站，wby和yuzhua的爬虫小案例
为避免麻烦，源代码存于https://gitee.com/YisenLiu/kolproject 上面，私人仓库

下面是简单的介绍
介绍一下requsets:
原文：Requests allows you to send organic, grass-fed HTTP/1.1 requests, without the need for manual labor. There’s no need to manually add query strings to your URLs, or to form-encode your POST data. Keep-alive and HTTP connection pooling are 100% automatic, thanks to urllib3.

百度翻译：请求允许您发送有机草食 HTTP / 1.1请求，而不需要人工。不需要手动向您的URL添加查询字符串，或者对您的POST数据进行表单编码。由于urllib3，保持活动和HTTP连接池是100％自动的。

requests的快速使用手册
http://docs.python-requests.org/zh_CN/latest/user/quickstart.html#、

实现思路，面对有验证码的页面，如果不想通过验证码训练的方式识别验证码，那就手动登录账号，在页面中获取cookie然后带着cookie去访问需要爬取内容的页面。如果只是静态的页面那就可以直接进行爬取，但是，这仅仅适用于没有反爬虫机制的网站。









应用实例：KOL红人信息列表获取
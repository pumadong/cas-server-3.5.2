cas-server-3.5.2
================

对于JasigCAS 3.5.2版本进行简化，只保留基本的功能，用JDBC方式验证，并使用Metronic模板美化界面，以达到可以直接在项目中使用的目的。

关于代码改动内容，很早之前写过一篇文章，如下；
http://blog.csdn.net/puma_dong/article/details/11564309

cas的java客户端也进行了小调整，让登陆之后自动返回到登陆之前的页面，不再使用p:service定义的值，并有一个客户端配置单点登陆的例子，如下：

https://github.com/pumadong/cas-client-3.2.1

# A Lightweight LaTeX Template For XJTLU EEE Students

这是采用 eeereport.cls 文件为核心的，使用 article 类型为基础的模板。
eeereport.cls 由 Feimax 为西交利物浦大学电子系和其他系同学精心制作的带有自定义命令的LaTeX模板类。该模板由基于 book 类型的模板改为 article，可以书写较短的Report或者其他文章。

在该次重大升级中，加入了封面，并增加了多种模式，详情请见代码。目前在网站中并没有彻底更新该版本的信息。之前的信息请参阅
http://blog.feieee.com/latex

**Update 2017-11-27**

+ 封面内容由固定内容改完可以自由修改的方式
+ 去掉了 xjtlu.sty 文件，不需要再使用 xjtlu Package，改由 eeereport.cls 文件来定义模板（和书写无关）
+ 在 documenclass 定义中增加了多项设置：包括字体风格、是否为打印件（hardcopy）以及是否为编辑模式（深色背景浅色文字和logo的颜色）
+ 增加了简单的程序代码添加方式
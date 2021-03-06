

> 作者：Tommy

# 注意事项
请将demo下载到本地后，路径里的中文要去掉！！

>  现在只把目录列出来，看到这里的朋友们可以提前关注下，每晚10点钟更新一节，长期更新（年假除外）。坑已经初步挖好！


# 为什么要写这个文档？
作为一名程序猿，面对新接触或使用的工具的时候会遇到太多坑。我们每次遇到问题不是问百度就是问谷歌，花了相当大的精力和成本在这上面，到头来发现原来有个人在某个点轻轻一点，我们就可以解决这些问题了。**可惜，很多时候并没有！**

我以前是CI的使用者，在[ThinkPHP](http://www.thinkphp.cn/)官方发布TP5以后，我的视线就被它吸引了。相比于国外的框架，如YII2、Laravel、CI等，thinkphp确实会有不够先进的地方，但TP5发布后，我决定在以后的学习和工作中使用ThinkPHP，因为：

* 相对于TP3.x版本，ThinkPHP V5.0是一个颠覆和重构版本，采用全新的架构思想，引入了很多的PHP新特性，优化了核心，减少了依赖，实现了真正的惰性加载，支持composer，并针对API开发做了大量的优化；
* 中文文档，相对于国外框架，使用TP5可以无障碍的查阅文档；
* 中文社区活跃，因为TP只有中文社区！几乎我们遇到的问题都可以在官方的社区里搜索到，无论这个问题有没有已经获得正确的解答了，至少，我们心里是踏实的：哦，原来不是我一个人遇到这个问题！算是一种苦中作乐吧！

* 最重要的一点：国人开发！
**我就是这样一个人，无论什么方面，当达到我的基本预期的时候，无条件的支持国产。**

> ThinkPHP团队无疑是一个值得我们尊敬和敬仰的团队，他们开发了国人喜爱的PHP框架，这几年一直不断努力进行改进。很多人一边用着TP，一边吐槽TP的某些方面，但这恰恰表示了我们对TP的热爱不是吗？

# 谁在编写这个文档？

大家可以叫我Tommy，是一个各方面均有涉猎的小小程序猿，这个文档是由我来主写，~~我的实习生能胜任的地方也会来写一写~~，我的几个朋友参与进来，我负主要负责TP5教程部分，dp负责PHP基础知识，我和小凯负责常用类库。当然我会严格查看和测试相关代码，力求让大家来这里是来学习和解决问题的，而不是越看越糊涂。

# 约定

* 我的开发环境使用的是Apache + mysql + php，如果使用Nginx在隐藏index.php和开启PATHINFO模式的时候会有坑，这个我后续会在“那些坑儿>nginx下的PATHINFO和隐藏入口文件”里会进行讲解；
* 所有讲解默认隐藏入口文件和开启PHTHINFO模式，隐藏入口文件等请参考[官方相关文档](http://www.kancloud.cn/manual/thinkphp5/118012)，当然我也会在第一章[先看到页面](http://www.kancloud.cn/liuzhen153/tp5-demo/259719)里说明怎样操作；
* 前端使用[bootstrap3](http://v3.bootcss.com/);
* 使用[最新核心版的TP5](http://www.thinkphp.cn/down.html)；

# 已更新内容列表

* 前言 2017-02-11
* 1.1只展示页面  2017-01-11
* 1.2给视图传递数据 2017-01-12
* 1.3使用公共模板 2017-01-13
* 1.4使用模板布局 2017-01-14
* 2.1查 2017-01-16
* 2.2增 2017-01-17
* 2.3查 2017-01-18
* 2.4删 2017-01-19
* 2.5链式操作 2017-01-22
* 2月14情人节特辑  2017-02-14
* PHP基础语法  2017-02-14
* 流程控制结构 2017-02-14
* PHP函数  2017-02-14
* 数组  2017-02-14
* 字符串  2017-02-14
* PHP正则表达式  2017-02-14
* PHPExcel表格导入 2017-02-15
* PHP的日期和时间 2017-02-15
* GD库图像处理 2017-02-15
* 文件处理系统 2017-02-15
* 文件上传和下载 2017-02-16
* 数据库之Mysql（概述）2017-02-16
* PHPExcel表格导出 2017-02-20
* 3.1注册 2017-02-22
* 5.1病房管理系统 2017-03-02
* 5.1.1病房管理系统-引导页 2017-03-02
* 5.1.2病房管理系统-公共模板 2017-03-02
* 5.1.3病房管理系统-登录 2017-03-02
* 5.1.4病房管理系统-功能引导页合集 2017-03-02
* 5.1.5病房管理系统-修改密码 2017-03-02
* 5.1.6病房管理系统-员工信息注册 2017-03-02
* 5.1.7病房管理系统-员工信息更新 2017-03-02
* 5.1.8病房管理系统-员工信息删除 2017-03-02
* 5.1.9病房管理系统-病人信息注册 2017-03-02
* 5.1.10病房管理系统-病人信息更新 2017-03-02
* 5.1.11病房管理系统-出院手续办理 2017-03-02
* 5.1.12病房管理系统-病人信息删除 2017-03-02
* 5.1.13病房管理系统-科室信息查询 2017-03-02
* 5.1.14病房管理系统-医护信息查询 2017-03-02
* 5.1.15病房管理系统-病房信息查询 2017-03-02
* 5.1.16病房管理系统-病历信息查询 2017-03-02
* 3.2登录
* 4.1操作SESSION
* 4.2操作Cookie
* 4.3文件上传
* 5_1集成wangEditor
* 5_2集成UEditor
* 6.1图片验证码
* 常用类库：PHP操作Python
* 常用类库：阿里大于短信验证码
* 常用类库：时间戳操作
* 常用类库：邮件发送
* 必看推荐阅读【不断更新】https://www.kancloud.cn/liuzhen153/tp5-demo/525809

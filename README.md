# 番茄三级分销旅游系统

挺多人下载的，就是没人Fork，清空仓，需要代码的可以加我微信 13538436848

#### 介绍
本系统是一款带分销功能的旅游系统，主要模块有游记分享，驴友自由开团，精选相册，多分类搜索，多级分销返利，领队申请，积分兑换，资讯模块，微信支付，活动订单。此版本为公众号版本。代码仅供学习研究，用于商业用途请联系我们。
#### 软件架构
采用Codeigniter框架开发，后台使用layui，前端用vue+vant+jq混合使用。


#### 安装教程

1. 导入根目录下的lv.sql 到你的数据。
2. 修改数据库链接，在apps->config目录下的database.php文件中修改用户名帐号和数据库名字即可。
3. 填写公众号数据，在apps->config目录下constants.php文件中填写您的公众号相应数据appid等...里面有说明。
4. 伪静态：如果你使用的是apache那就不用管了，根目录下已经放了静态规则。
nginx配置如下 <br>
` if (!-f $request_filename) {                
 			rewrite ^/.*$ /index.php last;
  }`
5. 开启调试模式在根目录下的index.php中，第一行修改production为development，即可
#### 演示
![输入图片说明](https://images.gitee.com/uploads/images/2019/0930/152018_b6815afd_430822.jpeg "qrcode_for_gh_014c66f6d601_258.jpg")


#### 友情链接
[番茄社交电商新零售系统](https://gitee.com/chaituan/fanqie_mall)

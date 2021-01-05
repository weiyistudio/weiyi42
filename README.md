# weiyi42
SSM洗衣网站的设计与实现

#### 介绍
本洗衣网站主要进行了有洗衣模块，用户模块，订单模块，购物车模块以及管理员模块的实现。基于SpringMVC框架实现了用户浏览洗衣商品，用户洗衣下单，用户管理个人信息，管理员对洗衣信息的增删该查，管理员对用户信息的管理，管理员对洗衣分类的管理，以及订单管理等功能。用户可以通过本网站实现上网浏览洗衣详情并最终通过本平台完成洗衣操作。


洗衣网站大致页面分为网站主页，用户注册页面，登陆页面，我要洗衣页面，洗衣详情页面，洗衣购物车页面等。
洗衣网站大致业务流程为匿名用户可通过网址访问游览网站主页，匿名用户可以游览网站主页，通过搜索洗衣进入到洗衣列表页面，首次访问洗衣列表页面需要进行登陆。新用户通过注册页面进行用户的首次注册，成功注册后的用户可通过洗衣网站登录页面提交登录信息来进入洗衣网站的洗衣列表页面。洗衣网站会对每一次成功登录的用户进行身份效验，如果效验通过，洗衣网站后端会记录这次用户登陆的信息，保存到服务器，并且重新跳转到洗衣首页。洗衣网站的核心业务模块分为用户模块，洗衣模块，购物车模块，洗衣订单模块，和管理员模块。

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/215644_24c9a075_4865385.png "屏幕截图.png")

 （1）洗衣模块
洗衣模块是洗衣网站的核心模块，其主要功能是用户在登录之后，点击我要下单之后跳转出具体的洗衣详情分类页面，用户可以在其中选择具体的分类，浏览每个分类下的洗衣详情。根据自己的洗衣需求进行下单。
（2）用户模块
用户模块作为洗衣网站的核心功能模块之一，其主要功能为储存洗衣网站的用户信息为用户做操作的一系列流程提供信息基础。用户模块需求为匿名游客可通过注册页面注册成为系统用户。匿名的未登录用户可利用笨登陆页面来登陆本系统。登录过后的系统用户可以在本系统当中自由的修改个人具体信息，其中包括了账号的密码以及用户个性签名，收货地址，以及其它一系列的内容。登录后的系统在用户退出登录时可以利用注销功能来退出系统。
（3）订单模块
订单模块作为洗衣网站的核心业务的功能模块之一，其主要功能为对用户购买的洗衣的订单信息进行储存记录的功能。评论模块的需求为系统用户可通过洗衣详情页面直接购买洗衣生成订单，也可以通过购物车页面购买洗衣生成订单。系统用户可以对自己已经生成的订单进行查看，删除等功能。已经登录了的系统当中的管理员可游览系统所有订单，并对订单来进一步的管理。
（4）购物车模块
购物车模块作为洗衣网站核心业务的功能模块之一，其主要功能为系统用户对想要购买却暂时不支付的洗衣进行临时存储的功能。购物车模块在用户模块与订单模块间加了一个步骤，起到耦合的作用，增加了用户对本系统购物的体验。购物车模块的主要需求为系统用户可通过洗衣详情页面的加入购物车按钮将想要购买却暂时不知福的洗衣加入到购物车。系统用户可查看自己加入购物车的所有洗衣，在购物车页面系统用户可通过提交订单并生成订单，用户可对加入购物车的洗衣进行自由的删除。
（5）管理员模块
管理员模块是我们的洗衣网之中最核心业务的功能模块的一部分，它的主要功能是针对系统管理的每个模块之间的功能。管理员这个模块主要的需求是为对订单的管整合，针对用户信息的管理，以及针对洗衣管理等等。

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/215707_ab538766_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/220340_a833ef3b_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/220346_decaed96_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/220355_c1336735_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/220407_093cb88a_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/220413_734f5f7d_4865385.png "屏幕截图.png")

工作室长期接单 招校园实力代理
需要源码请加我一下联系方式
联系Q：2762501186
![输入图片说明](https://images.gitee.com/uploads/images/2020/1119/003728_cd598bb9_4865385.jpeg "微信.jpg")

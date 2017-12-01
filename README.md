# 海信商城项目
项目名称：海信商城

项目内容：（1）首页：index.html
	  （2）二级页面：two-index.html
	  （3）商品详情页面：goods.html
	  （4）注册页面：register.html
	  （5）登录页面：login.html
	  （6）购物车页面：shoppingCar.html

项目已完成：6个页面，全部Gulp托管，二级页面css改用sass编写

项目未完成：模块化编程，其中5个页面的css未用sass

具体实现效果：

1.首页：（1）实现轮播图效果；
	 (2) 实现侧边栏效果；
	（3）动态加载商品列表以及给所有商品添加动画；

2.二级页面：（1）实现轮播图效果；
	     (2) 实现侧边栏效果；
	    （3）动态加载商品列表以及给所有商品添加动画；
	    （4）菜单栏展开收缩效果；
            （5）商品展示区域选项卡效果；
	    （6）商品展示区点击商品对比按钮，可进行商品对比；

3.商品详情页面：（1）商品图片的放大镜效果；
		（2）商品数量加减；
		（3）点击加入购物车，创建由商品描述、数量、图片、单价组成的cookie；
		（4）点击“为您推荐”下的图片，可动态改变商品；
		（5）商品详情、评价、规格等的选项卡效果；

4.注册页面：（1）用户名、手机号码、邮箱可验证
		（2）全部检测成功后点击注册，创建包含用户名、密码的cookie；

5.登录页面：（1）输入用户名，密码，取出注册时创建的cookie，对比判断；

6.购物车页面：（1）取出商品详情页创建的cookie，创建对应商品列表；
	      （2）改变购买数量，商品总价改变，相应cookie改变；
	      （3）点击删除按钮，删除对应商品，点击总计卡中的删除选中商品按钮，可删除当前呈选中状态的商品；
	      （4）“猜你喜欢”中的轮播图效果；
	

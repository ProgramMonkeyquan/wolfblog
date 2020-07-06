# 项目介绍：
  ## 一.该项目实现了一个简单的博客系统，具体功能包括：
    后台：后台管理系统，具体包括：文章管理、分类管理、标签管理、用户管理、活动通知管理等
    前台：用户注册登录、搜索文章、评价文章、点赞文章、图片上传、文章分页展示、文章分享等
  使用ssm（spring+springmvc+mybaits）+redis+elk作为后台技术，使用layui+jsp+ajax作为前端技术
  ### 技术亮点：
    1.注册登录时利用ajax对不合适的输入做出提示，并使用MD5+salt对密码进行加密;
    2.使用elk替换了原来mysql的模糊查询方式,实现对文章的标题,摘要,全文的搜索功能,并高亮展示;
    3.点赞功能由Redis来实现,将点赞数率先存入redis,然后再更新到mysql中;
    4.异步处理,利用生产者消费者模式将用户的点赞信息异步通知给用户;
    
  项目预览地址：http://hbquan.top(腾云博客)
  ## 二.项目前台和后台部分功能预览
  ### 1.首页效果展示:
  ![image](https://github.com/ProgramMonkeyquan/wolfblog/blob/master/img/QQ_20200706114610.png)
  ### 2.文章详情页展示:
  ![image](https://github.com/ProgramMonkeyquan/wolfblog/blob/master/img/QQ_20200706114741.png)
  ### 3.后台文章管理展示:
  ![image](https://github.com/ProgramMonkeyquan/wolfblog/blob/master/img/QQ_20200706114923.png)
  ### 4.后台写文章展示:
  ![image](https://github.com/ProgramMonkeyquan/wolfblog/blob/master/img/QQ_20200706115018.png)
  ### 5.后台评论管理展示:
  ![image](https://github.com/ProgramMonkeyquan/wolfblog/blob/master/img/QQ_20200706115103.png)
  ### 6.后台用户管理展示:
  ![image](https://github.com/ProgramMonkeyquan/wolfblog/blob/master/img/QQ_20200706115143.png)
  
  
  
  
  
  
  
	

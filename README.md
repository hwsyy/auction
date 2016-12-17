# auction
积分拍卖，基于微信端

2016-11-4
- 静态页面，还有诸多修改细节地方。

目录结构	        
    API    
     |------ilink  (中转文件：)
     |         |--index1.php                //跳转到首页
     |         |--index2.php                //跳转高
     |-------PM	  //主题文件
     |        |--admin                      //项目后台处理文件、后台控制端界面
     |        |     |--BC                   //后台控制端
     |   	  |     |  |--admin             //控制端界面功能后台
     |   	  |     |  |   |--gengxin.php   //用户列表更新功能
     |        |     |  |   |--jf-gx.php     //用户积分功能更新
     |        |     |  |   |--log.txt	    //后台操作日志（未完成）
     |        |     |  |   |--login.php     //登录功能
     |        |     |  |   |--login_.php    //登录功能
     |        |     |  |--css
     |        |     |  |--images
     |        |     |  |--js
     |        |     |  |--lib
     |        |     |  |--skin
     |        |     |  |--temp
     |        |     |  |--bingo_info.php    //获奖用户信息列表
     |        |     |  |--index.php         //后台控制端首页
     |        |     |  |--login.html        //登录页面
     |        |     |  |--product-list.php               
     |        |//商品展示界面（包括起拍、结束、重置功能）
     |        |     |  |--product-add.php   //新增商品
     |        |     |  |--user-list.php     //用户列表界面
     |        |     |  |--user_add.php      //用户积分更新界面
     |        |     |  |--user_list_c.php   //用户信息
     |        |     |--pc-show
     |   	  |     |     |--pc_result.php  // PC端中奖信息判断功能
     |   	  |     |     |--pc_show1.php
     |   	  |     |     |--pc_show2.php
     |        |     |--phpExcel             //phpexcel 功能模块
     |        |     |--uploadimg            //上传商品的图片位置
     |        |     |--check.php            //
     |        |     |--chujia.php           //手机出价功能
     |        |     |--fubu.php             //商品发布功能
     |        |     |--mb_home.php          //手机端局部刷新信息更新
     |        |     |--mb_home_max.php      //商品最高分判断
     |        |--config  //数据库连接类
     |        |       |--class.db.php
     |        |       |--class.input.php
     |        |       |--err.php
     |        |       |--statr.php
     |        |--css
     |        |--images
     |        |--img
     |        |--js
     |        |--pcshow                     //PC端
     |        |      |--PC.php              //PC端主页
     |        |--access_token.txt
     |        |--index.php                  //手机端首页
     |        |--issue.php	                //手机发布界面
     |        |--msg.php                    //个人信息页面
     |        |--PC-start.php               //手机端拍卖控制端
     |--user-msg.php                        //手机端个人中心界面
     |access_token.txt                      //实时生成的token口令
     |log.txt                               //日志
     |qydemo.php                            //企业号绑定的入口文件
     |qywechat.class.php                    //企业号接口功能类
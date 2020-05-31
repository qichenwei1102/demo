# demo
<<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style>
		*{
			padding: 0;
			margin: 0;
		}
		a{
			text-decoration: none;
		}
        li{
            list-style: none;
        }
        .clear:after{
        	content: "";
        	hright: 0;
        	display: block;
        	clear: both;
        }
        .header{
            heihgt: 32px;
            line-height: 32px

        }
        .container{
            width: 1179px;
            text-align: center;
            margin: 0 auto;
        }
        .nav{
        	cursor: pointer;
        	float: left;
        }
        li{
        	float: left;
          }
        a{
        	width:241px;
            height:18px;
            font-size:18px;
            font-family:Microsoft YaHei;
            font-weight:400;
            color:rgba(5,5,5,1);
        }
        p{
            width:170px;
            height:39px;
            font-size:40px;
            font-family:Microsoft YaHei;
            font-weight:bold;
            color:rgba(0,164,255,1);
            float: left;
        }
        .pp{
            top: 33px
            left: 369px;
        }
        .first{
            margin-left: 79px;
            margin-right: 36px;
        }
        .last{
            margin-left: 36px;
        }
        .form{
        	float: left;
        	top: 30px;
        	right: 463px;
            margin-left: 187px;    
        }
		.search{
			float: left;
			width:333px;
            height:40px;
            padding: 13px;
            border:1px solid rgba(0,164,255,1);
            margin-left: 31px;
		}
		.submit{
			float: left;
			width:50px;
            height:40px;
            background:rgba(0,164,255,1) url(fa-search.png)no-repeat center;
		}
        
        
		.lastlast {
			width:60px;
            height:12px;
            font-size:14px;
            font-family:Microsoft YaHei;
            font-weight:400;
            float: right;
            margin-left: 40px;
	        }
        .lastlast a{
            color:rgba(102,102,102,1);
            float: right;
           }
            .header-bottom{
                width:1920px;
                height:420px;
                background:rgba(28,3,108,1);
                margin: 0 auto;
                margin-top: 29px;
            }
            .banner{
                margin-left: 380px;
                position: relative;
            }
            .lianjie {
                position: absolute;
                width:190px;
                height:420px;
                background:rgba(0,0,0,1);
                opacity:0.3;
                top: 0px;
                left: 0px;

            }
            .lianjie li{
                position: absolute;
            }
            .lianjie a{
                position: absolute;
                top: 20px;
                left: 27px;
                font-size: 16px;
                color: #FFFFFF;
                display:block;
            }
            .nav2{
                width:1200px;
                height:60px;
                background:rgba(255,255,255,1);
                box-shadow:0px 2px 3px 0px rgba(118,118,118,0.2);
                margin-left: 360px;
            }
            .nav2 li{
                margin-top: 18px;
                 margin-left: 19px;
                  margin-right: 9px;
                 border-right: 1px solid rgba(191,191,191,1);
                 
        
            }
            .nav2 a{
             padding: 16px;
             background:rgba(255,255,255,1);
              margin-right: 16px;
            }
            .nav2 ul{
             margin-left: 34px;
            }
            .nav2 .last1{
                border: none;
            }
            .jing a{
                  color:#00A3FF;
            }
            .xiu{
                margin-top: 0px;
                font-size:16px;
                float: right;
            }
            .nav2 .xiu{    
                border: none;
                }
            .xiu a{
                   color: #00A3FF;
                   margin-top: 0px;
            }
            .zhongbu{
                 margin-top: 37px;
            }
            .zhongbu .jing{
                float: left;
                
            }
          .zhongbu .jing a{
                color:rgba(72,72,72,1);
                margin-left: 340px;
            }
            .zhongbu .cha{
                float: right;
                
            }
         .zhongbu .cha a{
            color:rgba(165,165,165,1);
             margin-right:280px;
         }
         .tupian li{
            center left;
            width:228px;
            height:270px;
            background:rgba(255,255,255,1);
            text-align: left;
            position: relative;
            margin-right:7px;
            margin-top:21px;
         }
         .tupian img{
            margin-right: 6px;
         }
         .tupian a{
            position:absolute;
            width: 185px;
            font-size: 14px;
            top: 180px;
            left: 7px;
            right: 10px;   
         }
         .tupian p{
            position:absolute;
            font-size: 14px;
            top: 240px;
            left: 0px;
            right:0px;   
         }
        .span1{
          font-size:12px ;
          color:#FF7C2D;
          position: absolute;
          left: 0px;
         }
        .span2{
          font-size:12px;
          color:#767676;
          position: absolute;
          right: 0px;
    }   
        .qianduan ul{
            center center;
            height: 77px;
            position: absolute;
            margin-left: 360px;
            margin-top: 20px
        }
        .qianduan a{
             padding: 0px;
             background:rgba(255,255,255,1);
             position: absolute;
             margin-right: 0px;
              float: left;
            }
        
            
        .qianduan0 p{
            color:#484848;
            font-size:20px 
            margin-left: 340px;
        }
        .chakan{
            width: 48px;
            height: 13px;
            font-size:12px;
            font-family:Microsoft YaHei;
            font-weight:400;
            color:rgba(165,165,165,1);
        }
        .chakan a{
            color:#A5A5A5;
            float: right;
        }
        h{
            color: #484848;
            font-size: 20px;
        }
        div.parent{
            margin-top:36px;
            margin-left:380px;
        }
        div.bi{
            margin-top:36px;
            margin-left:380px;
        }
        .bi li{
            margin-right: 3px;
        }
        div.bottom{
            width:1917px;
            height:417px;
            background:rgba(255,255,255,1);
            margin-top:36px;
            margin-left: 380px;
        }
	</style>
</head>
<body>
    <div class="header">
	<div class="container">
		<p class="pp">雪梨在线</p>	
	 <ul class="nav clear">
	 	<li class="first"><a href="#">首页</a></li>
	 	<li><a href="#">课程</a></li>
	 	<li class="last"><a href="#">职业规划</a></li>
     </ul>
	<form class="form clear">
		<input type="text" placeholder="输入关键词" class="search"/>
        <input type="button" class="submit" style="vertical-align: bottom;"/>
    </form>
    <ul class="clear">
    <li class="lastlast"><a href="#">个人中心</a></li>
	</ul>
	</div>
	</div>

    <div class="header-bottom">
    <div class="banner">
    	<img src="banner2.png" alt=""/>
    <div class="lianjie">
        <ul>
            <li><a href="#">后端开发</a></li> 
            <li><a href="#">移动开发</a></li> 
            <li><a href="#">人工智能</a></li>
            <li><a href="#">商业预测</a></li>
            <li><a href="#">云计算&大数据</a></li>
            <li><a href="#"> 运维&从测试</a></li>
            <li><a href="#"> UI设计</a></li>
            <li><a href="#"> 产品</a></li>
        </ul>
    </div>
    </div>
    <div class="nav2">
      <ul class="nav2 clear">
        <li class="jing"><a href="#">精品推荐</a></li>
        <li><a href="#">JQuery</a></li>
        <li><a href="#">Spark</a></li>
        <li><a href="#">MySQL</a></li>
        <li><a href="#">JavaWeb</a></li>
        <li><a href="#">MySQL</a></li>
        <li class="last1"><a href="#">JavaWeb</a></li>
        <li class="xiu"><a href="#">修改兴趣</a></li>
      </ul>
   </div>
    <div class="zhongbu">
        <ul class="clear">
            <li class="jing"><a href="#">精品推荐</a></li> 
            <li class="cha"><a href="#">查看全部</a></li> 
        </ul>
   
     <div class="tupian clear">
    <ul class="container">
    <li>
        <img src="矩形 1.1.png" alt=""/ clas="tupian1.1">
       <a href="#" class="wenzi1.1">Think PHP 5.0 博客系统实战项目演练</a> 
       <p><span class="span1">高级</span><span class="span2">· 1125人在学习</span></p>
    </li>
    <li>
        <img src="矩形 1.2.png" alt=""/ clas="tupian1.2">
       <a href="#" class="wenzi1.2">Android 网络图片加载框架详解</a>
       <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    <li>   
        <img src="矩形 1.3.png" alt=""/ clas="tupian1.3">
        <a href="#" class="wenzi1.3">Angular 2 最新框架+主流技术+项目实战</a>
        <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    <li>   
        <img src="矩形 1.4.png" alt=""/ clas="tupian1.4">
        <a href="#" class="wenzi1.4">Android Hybrid APP开发实战 H5+原生!</a>
        <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    <li>   
        <img src="矩形 1.4.png" alt=""/ clas="tupian1.4">
        <a href="#" class="wenzi1.4">Android Hybrid APP开发实战 H5+原生！</a>
        <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    </ul>
     </div>

<div class="tupian clear">
    <ul class="container">
    <li>
        <img src="矩形 1.1.png" alt=""/ clas="tupian1.1">
       <a href="#" class="wenzi1.1">Think PHP 5.0 博客系统实战项目演练</a> 
       <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    <li>
        <img src="矩形 1.2.png" alt=""/ clas="tupian1.2">
       <a href="#" class="wenzi1.2">Android 网络图片加载框架详解</a>
       <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    <li>   
        <img src="矩形 1.3.png" alt=""/ clas="tupian1.3">
        <a href="#" class="wenzi1.3">Angular 2 最新框架+主流技术+项目实战</a>
        <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    <li>   
        <img src="矩形 1.4.png" alt=""/ clas="tupian1.4">
        <a href="#" class="wenzi1.4">Android Hybrid APP开发实战 H5+原生!</a>
        <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    <li>   
        <img src="矩形 1.4.png" alt=""/ clas="tupian1.4">
        <a href="#" class="wenzi1.4">Android Hybrid APP开发实战 H5+原生！</a>
        <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    </ul>
     </div>
    


     <div class="tupian clear">
    <ul class="container">
    <li>
        <img src="矩形 3.1.png" alt=""/ clas="tupian1.1">
       <a href="#" class="wenzi1.1">微软人工智能-数据分析平台</a> 
       <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    <li>
        <img src="矩形 3.2.png" alt=""/ clas="tupian1.2">
       <a href="#" class="wenzi1.2">Unity Profiler入门     </a>
       <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    <li>   
        <img src="矩形 3.3.png" alt=""/ clas="tupian1.3">
        <a href="#" class="wenzi1.3">Cocos2d-x 引擎源码中的纹理优化</a>
        <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    <li>   
        <img src="矩形 3.4.png" alt=""/ clas="tupian1.4">
        <a href="#" class="wenzi1.4">Kami2首页界面切换效果</a>
        <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    <li>   
        <img src="矩形 3.5.png" alt=""/ clas="tupian1.4">
        <a href="#" class="wenzi1.4">Android Hybrid APP开发实战 H5+原生！</a>
        <p><span class="span1">高级 </span><span class="span2">· 1125人在学习</span></p>
    </li>
    </ul>
     </div>
    <div class="parent">
        <h class="niu">牛人推荐</h>
    </div>

    <div class="bi">
    <ul>
        <li><img src="毕业季.png" alt=""/ clas=""></li>
    <li>   
        <img src="人物1.png" alt=""/ clas="">  
    </li>
    <li>   
        <img src="人物2.png" alt=""/ clas="">  
    </li>
    <li>   
        <img src="人物3.png" alt=""/ clas="">  
    </li>
    </ul>    
     </div>
    </div>


    <div class="bottom">
        <h1><p class="pp">雪梨在线</p></h1>

    </div>
 </div>

</body>
</html>

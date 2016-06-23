title: 贪吃蛇大战
speaker: victor.Dong
url: https://github.com/codemonkey-victor/snakes
transition: move
date: 2015年12月20日
theme: dark


[slide style="background-image:url('/snakes-img/monitors.jpg'); background-size: contain; background-position: 50%;"]

[slide data-transition="earthquake"]
 
# 贪吃蛇大战

----

UX - FED - 董文枭

2016.6.23


[slide]

## 说明

<ul class="desc">
	<li>我:[<em>桌面应用,管理系统,广告系统,APP,游戏,网站等的开发工作</em>]</li> {:&.rollIn}
	<li>写这个游戏的目的：[<em>为了学习ReactJS</em>]</li> {:&.rollIn}
	<li>分享这个游戏的目的：[<em>技术交流,寻找感兴趣的伙伴儿</em>]</li> {:&.rollIn}
</ul>
<style type="text/css">
	.desc li{
		margin: 30px 0;
	}
  .desc em{
    font-size: .7em
  }
</style>


[slide]

## 先玩玩再说~

<iframe data-src="http://10.60.237.95:8000/" src="about:blank;" id="demoIframe"></iframe>
<style type="text/css">
	#demoIframe{
		width: 1000px;
		height: 600px;
	}
</style>

[slide]

## 设计思路 - 游戏

  - 场景 、 层 、 精灵(组件)  、 游戏管理员(GM) 、 摄像机(DOM) {:&.rollIn}
  - 游戏循环计算 [ checkDead 、 checkEat ... ] 
  - 对象(组件) [ 蛇 、 豆子 、地图 ... ]
  - 其他 [ 说明 、 统计 、 按钮 ... ]
  - 操作 [ 方向键 、 加速键 、 重玩 ... ]

[slide]

## 设计思路 - 技术

  - 界面 : ReactJS  [ Redux ] {:&.rollIn}
  - 服务端 : NodeJS
  - 通信 : Socket.io
  - 辅助 : Yeoman、Babel、Underscore、Webpack、Webpack-dev-server、Redux-dev-tool



[slide]

## 然后编码... 发现问题并解决

  - Cache, Redis or System cache {:&.rollIn}
  - 整体重绘与部分重绘
  - 夸组件状态管理
  - Webpack-dev-server 0.0.0.0

[slide]


## 探索

  - ReactJS + Redux + React Router 组合使用 {:&.rollIn}
  - React 做多人开发的大型项目如何架构
  - React Native 
  - React Canvas 



[slide]

 ## Javascript write anywhere ...

[slide style="background-image:url('/snakes-img/js.png'); background-size: contain; background-position: 50%;"]



[slide]

## 引用

  - https://github.com/codemonkey-victor/snakes
  - http://cn.redux.js.org/
  - http://yeoman.io/
  - http://underscorejs.org/
  - [Leo&Me]https://github.com/Solution-Sage/generator-html5-wechat-activity


[slide]

# Thanks
### 插件介绍：
* 一个代码高亮的插件
* 基于jquery
* 好看 = =

### 使用方法：
  * 下载附件中的文件
  * 在你的前端代码中引入
```javascript
//jquery 的版本最好不要太新 
<script src="http://cdn.bootcss.com/jquery/2.2.3/jquery.min.js"></script>
<script src="./js/lib/pretty/js/prettify.js" type="text/javascript"></script>
<link rel="stylesheet" type="text/css" href="./js/lib/pretty/css/prettify.css"/>
```
*  在body中添加
```javascript
<body onload="prettyPrint()">
```
*  在body后添加
```javascript
$("pre").addClass("prettyprint linenums");
prettyPrint();
```
* 上面步骤完成之后那个页面下的所有pre标签里的代码都是高亮的，当然你可以自己定义在哪里的pre标签高亮
* 可以在这个网站上更换自己喜欢的主题 [戳我戳我 = =](https://jmblog.github.io/color-themes-for-google-code-prettify/)，也可以自己定制主题
* 效果如下图：
![image](https://github.com/hongrunhui/prettify.js/blob/master/%E6%9C%AA%E6%A0%87%E9%A2%98-1.png)


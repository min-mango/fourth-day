# fourth-day
<!DOCTYPE html>
<html>
<head>
	<title>fourth day</title>
	<link rel="stylesheet" type="text/css" href="fourth day(1).css">
</head>
<body>
 <h1>背景、边框和列表样式概述</h1>
 <h2>背景</h2>
 <p>我们先通过一个链接来简单的了解<a href="https://developer.mozilla.org/zh-CN/docs/Learn/CSS/Styling_boxes/%E8%83%8C%E6%99%AF">背景样式的简单内容</a></p>
 <p>
 	<ol>
 		<li>backgroud</li>
 		<li>backgroud-color</li>
 		<li>backgroud-style</li>
 		<li>backgroud-position</li>
 		<li>backgroud-repeat</li>
 	</ol>
 </p>
 <h2>边框</h2>
 <p>我们先通过一个链接来简单的了解<a href="https://developer.mozilla.org/zh-CN/docs/Learn/CSS/%E4%B8%BA%E6%96%87%E6%9C%AC%E6%B7%BB%E5%8A%A0%E6%A0%B7%E5%BC%8F/Styling_lists">边框的简单内容</a></p>
<ol>
 		<li>border</li>
 		<li>border-color</li>
 		<li>border-style</li>
 		<li>border-image</li>
 		<li>border的上下左右</li>
 	</ol>
 <h2 class=first>列表</h2>
 <p>我们先通过一个链接来简单的了解<a href="https://developer.mozilla.org/zh-CN/docs/Learn/CSS/%E4%B8%BA%E6%96%87%E6%9C%AC%E6%B7%BB%E5%8A%A0%E6%A0%B7%E5%BC%8F/Styling_links">列表样式的简单内容</a></p>
 <ul>
 	<li>列表项目样式</li>
 	<li>阿拉伯数字</li>
 	<li>希腊字母</li>
 	<li>大小写英文字母</li>
 </ul>
</body>
</html>
html{
	font-family: Arial;
	font-size: 12Px;
	font-weight: 1.5;
}
h1{
	font-size:1.5rem;
	background-color:red;
	text-align:center;
}
h2,p,ul,ol{
	line-height: 1.5;
}

ol{
	background-image: url(1.jpg);
	background-repeat:no-repeat;
	background-position: 15px center;
	background-attachment: scroll;
}
a{
    outline:none;
    padding:2px 1px 0;
}
a:link {
	color: #FF0000;
} 
a:visited {
	color:red;
}
a:hover {
	border-bottom: 1px solid;
	background-color: blue;
}
a:active {
	color:gray;
	background-color:red; 
}
ul{
	border: 30px solid transparent;
	padding:20px;
	background-clip: padding-box;
	border-image-source:url(2.png);
	border-image-slice:30;
	list-style-type: upper-roman;
	list-style-position: inside;
}


github部署网站教程，注意事先准备好index.html文件

1. 首先需要注册一个github的账号，我们进到github.com官网点击sign up注册一个账号。 
	<img src="./image/github0.png" width = "1000"/>
	<img src="./image/github1.png" width = "1000"/>
2. 注册完成后自己登录就好了，登录后界面如下，当然如果没有创建过仓库好像不是这个界面，所有需要点击右上角加号处，下面的图箭头有点偏了。
	<img src="./image/github2.png" width = "1000"/>
3. 然后点击new repository进入新建仓库界面
	<img src="./image/github3.png" width = "1000"/>
4. 输入仓库名称，由于是网页仓库，需要和Github用户名保持一致,填写好后创建即可。
	<img src="./image/github4.png" width = "1000"/>
5. 然后上传文件，我这里显示的是已经上传过了的界面
	<img src="./image/github5.png" width = "1000"/>
6. 将你的html工程拖到上传区，按如下方式，写好说明即可上传
	<img src="./image/github6.png" width = "1000"/>
	<img src="./image/github7.png" width = "1000"/>
	<img src="./image/github8.png" width = "1000"/>

7. 点击settings，然后一直下滑直至Github Pages，因为网页就是利用github的这个功能，当然github也只能实现一些简单的静态网页，做个人博客再适合不过，按如下图片操作即可
	<img src="./image/github9.png" width = "1000"/>
	<img src="./image/github10.png" width = "1000"/>
	<img src="./image/github11.png" width = "1000"/>
	<img src="./image/github12.png" width = "1000"/>
**如果没有html文件，想先尝试是否可以部署网站怎么办，以下提供我个人写的简单html程序，供测试部署使用。**
	<img src="./image/github13.png" width = "1000"/>
**复制以下类容到index.txt,复制后保存，并将index.txt重命名为index.html即可**
	<img src="./image/github14.png" width = "1000"/>

index.html

	<!doctype html>
	<html>
	<head>	
	<meta charset="utf-8">
	<title>SEASKY系列教程</title>
		<style>
			.hello_git
			{
				width:500px;
				height:300px;
				background:black;
				margin: auto;
				margin-top:300px;
				border-radius: 10px;
			}
			.hello_git li
			{
				
				color: aliceblue;
				margin-top:10px;
				margin-left:40px;
			}
		</style>
	</head>
	<body>
		<div class="hello_git">
			<br><br><br><br>
			<ul>
				<li>Hello Github</li>
				<li>欢迎使用SEASKY教程</li>
				<li>SEASKY交流讨论群QQ:893445794</li>
			</ul>
		</div>
	
	</body>
	</html>

效果如下：
<img src="./image/github15.png" width = "1000"/>
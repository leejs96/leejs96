### Hi there 👋
😏
😂
🤭

<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans+KR:wght@300&display=swap" rel="stylesheet">
	
	<title>Insert title here</title>
	<meta name = "viewport" content = "user-scalable = no, initial-scale = 1">

	<style>
		* {
			margin : 0; padding : 0;
			font-family: 'IBM Plex Sans KR', sans-serif;
		}
		
		body {
			width : 1080;
			margin : 0 auto;
			background : #E6E6E6;
		}
		
		#page-wrapper {
			background : #FDF6EC;
			width : 80%;
			margin: 5% 10%;
			overflow: hidden;
		}
	</style>

	<style>
		#navigation {
			overflow: hidden;
		    height: 80px;
		}
		#nav-out {
			height: 90%;
		    margin: 0 auto;
		    display: block;
		    border-radius : 36px;
		}
		.nav-menu {
			list-style-type: none;
			float: left;
   		 	padding : 0 12%;
			padding-top: 2.7%;
   		 	color: #FDF6EC;
		    font-size: 22px;
		    font-weight: bolder;
		}
		
		a {
		    text-decoration: none;
    		color: #FDF6EC;
		}
		
		h1 {
		    color: #FDF6EC;
		    margin: 14%;
		    font-size: 92px;
		    text-align: center;
		}
	</style>
	
	<style>
		.box{
	      box-sizing:content-box;
	      width: 150px;
	      height: 150px;
	      margin: 10px;
	      padding: 30px;
	      text-align: center;
	      position: relative;
	    }
	</style>
	
	<style>
		#about {
			width : 80%;
			margin : 0 auto;
			padding: 10px;
   	 		overflow: hidden;
		}
		
		.right {
			float: left;
		    width: 30%;
		    margin: 5% 0 1% 15%;
		}
		
		 #img {
			margin: auto;
	    	display: block;
		 }
		 		 
		 .right table {
		 	   width: 100%;
		 	   font-size : 25px;
		 }
		 .right table tr {
				height: 50px;
		 }
		 
		 .right table th {
				width: 50%;
		 }
		 
	</style>
	
	<style>
		#skills {
		    width: 50%;
		    margin: 0% auto;
		    padding: 10% 0;
		    overflow : hidden;
		}
		
		.ski {
			float : left;
			margin-left : 10%;
		}
		
		table tbody tr{
			height: 70px;
		}
		
		.progress-bar {
		    width: 90%;
		    height: 25px;
		    background-color: #E5E4CC;
		    font-weight: 600;
		    font-size: .8rem;
		    float : left;
		    margin-top: 12px;
		}
	
		.progress-bar .progress {
		    height: 25px;
		    text-align: center;
		    background-color: #889E81;
		    color: #FDF6EC;
		}
	</style>
</head>

<body>
	<div id = "page-wrapper">
		<div style = "background : #D2E1C8; padding: 1%; height : 430px;">
			<div id = "navigation" style = "float : left; width : 50%;">
				<ul id = "nav-out">
					<li class = "nav-menu"><a href = "#me">About me</a></li>
				</ul>
			</div>
			<div id = "navigation" style = "float : right; width : 50%;">
				<ul id = "nav-out" style = "padding-left: 40%;">
					<li class = "nav-menu"><a href = "#skill">skills</a></li>
					<li class = "nav-menu"><a href = "#project">project</a></li>
				</ul>
			</div>
			<h1 style = "color : #FDF6EC;">안녕하세요 :)</h1>
		</div>
		
		<div id = "me" style = "overflow : hidden; height: 400px; margin-top: 86px;">
			<div class = "right">
				<table>
					<tr>
						<th>이름</th>
						<td>이재선</td>
					</tr>
					<tr>
						<th>생년월일</th>
						<td>1996.09.12</td>
					</tr>
					<tr>
						<th>이메일</th>
						<td>naver.com</td>
					</tr>
					<tr>
						<th>전공</th>
						<td>수학과</td>
					</tr>
					<tr>
						<th>취미</th>
						<td>태권도</td>
					</tr>
				</table>
			</div>
			<div style = "float : left; margin-left: 15%; margin-top: 5%;">
				<div class="box" style = "background-color:#FEE4A6; z-index: 2;"></div>
		    	<div class="box" style = "z-index: 8;left: 67px; top: -222px; font-size: 185px; color: #FDF6EC; font-weight: bolder;"><span>1</span></div>
		    	<div class="box" style = "z-index: 8;left: -16px; top: -449px; font-size: 32px; color: #FDF6EC; font-weight: bold;"><span>About me</span></div>
		    	<div class="box" style = "background-color:#F9EBC8; z-index: 1; left : 56px; top : -610px;"></div>
			</div>
		</div>
		
		<div id = "skill" style = "overflow : hidden; height: 400px;">
			<div style = "float : left; margin-left: 10%; margin-top: 9%;">
				<div class="box" style = "background-color:#B1BED5; z-index: 1; color: #EFD9D1;"></div>
		    	<div class="box" style = "z-index: 8;left: -44px; top: -244px; font-size: 32px; color: #FDF6EC; font-weight: bold;"><span>skill</span></div>
		    	<div class="box" style = "z-index: 8;left: 73px; top: -432px; font-size: 185px; color: #FDF6EC; font-weight: bolder;"><span>2</span></div>
		    	<div class="box" style = "background-color:#DFDFDF; z-index: 2; left : 56px; top : -599px;"></div>
			</div>
			
			<div id = "skills" style="float:left; padding-left:45px; margin-left : 35px;">
				<table style="width: 100%; padding-top: 20px;">
					<tr>
						<td style="width: 30%; text-align: center;"><img src = "./img/java.png" width = 50></td>
						<td style="width: 70%">
							<div class="progress-bar">
			  					<div class="progress" style = "width: 20%;"><span style="position: absolute;">20%</span>  </div>
							</div>
						</td>
					</tr>
					<tr>
						<td style="width: 30%; text-align: center;"><img src = "./img/mysql.png" width = 50></td>
						<td style="width: 70%">
							<div class="progress-bar">        
			  					<div class="progress" style = "width: 30%;"><span style="position: absolute;">30%</span>   </div>
							</div>
						</td>
					</tr>
					<tr>
						<td style="width: 30%; text-align: center;"><img src = "./img/html-5.png" width = 50></td>
						<td style="width: 70%">
							<div class="progress-bar">           
			  					<div class="progress" style = "width: 5%;"><span style="position: absolute;">5%</span></div>
							</div>
						</td>
					</tr>
				</table>
			</div>
		</div>
		
		<div id = "project" style = "overflow : hidden; height: 400px; margin-top: 86px;">
			<div class = "right">
			</div>
			<div style = "float : left; margin-left: 15%; margin-top: 5%;">
				<div class="box" style = "background-color:#F9E4C8; z-index: 2;"></div>
		    	<div class="box" style = "z-index: 8;left: 78px; top: -222px; font-size: 185px; color: #FDF6EC; font-weight: bolder;"><span>3</span></div>
		    	<div class="box" style = "z-index: 8;left: -16px; top: -449px; font-size: 32px; color: #FDF6EC; font-weight: bold;"><span>Project</span></div>
		    	<div class="box" style = "background-color:#CDC9C3; z-index: 1; left : 56px; top : -610px;"></div>
			</div>
		</div>
	</div>
</body>
</html>

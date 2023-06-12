# sungilhomepage
<br><br><br>
## 화면
![image](https://github.com/gkstmdrb/sungilhomepage/assets/114748816/ef9ca13f-b286-4f5f-bd36-f80ea427130a)
<br><br><br>
index.html
=============
```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<link rel="stylesheet" href="css/style.css" type="text/css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js" defer="defer"></script>
<script src="js/script.js" defer="defer"></script>
<title>Insert title here</title>
</head>
<body>
<div id="page">
	<header>
			<div id='top'>
				<ul class="main-menu">
					<a href="https://lostark.game.onstove.com/Main">
						<img class="logo" src="img/logo.png">
					</a>
					<li>
						<a href="https://lostark.game.onstove.com/News/Notice/List">새소식</a>
						<ul class="sub">
							<li><a href="https://lostark.game.onstove.com/News/Notice/List">공지사항</a></li>
							<li><a href="https://lostark.game.onstove.com/News/Update/List">업데이트</a></li>
							<li><a href="#">이벤트</a></li>
							<li><a href="#">리샤의 편지</a></li>
						</ul>
					</li>
					<li>
						<a href="#">게임정보</a>
						<ul class="sub">
							<li><a href="#">전투정보실</a></li>
							<li><a href="#">세계관</a></li>
							<li><a href="#">클래스</a></li>
							<li><a href="#">콘텐츠</a></li>
							<li><a href="#">월드맵</a></li>
						</ul>
					</li>
					
					<li>
						<a href="#">가이드</a>
						<ul class="sub">
							<li><a href="#">게임 가이드</a></li>
							<li><a href="#">아이템 사전</a></li>
						</ul>
					</li>
					<li>
						<a href="#">커뮤니티</a>
						<ul class="sub">
							<li><a href="#">자유</a></li>
							<li><a href="#">직업</a></li>
							<li><a href="#">길드 모집</a></li>
							<li><a href="#">공략</a></li>
							<li><a href="#">Q&A</a></li>
							<li><a href="#">갤러리</a></li>
						</ul>
					</li>
					<li>
						<a href="#">미디어</a>
						<ul class="sub">
							<li><a href="#">로아 상영관</a></li>
							<li><a href="#">공모전</a></li>
							<li><a href="#">OST</a></li>
							<li><a href="#">Artwork</a></li>
						</ul>
					</li>
					<li>
						<a href="#">거래소</a>
						<ul class="sub">
							<li><a href="#">거래소</a></li>
							<li><a href="#">경매장</a></li>
						</ul>
					</li>
					<li>
						<a href="#">웹 샵</a>
						<ul class="sub">
							<li><a href="#">SHOP</a></li>
							<li><a href="#">캐시</a></li>
							<li><a href="#">쿠폰</a></li>
						</ul>
					</li>
					<li>
						<a href="#">고객센터</a>
						<ul class="sub">
							<li><a href="#">FAQ</a></li>
							<li><a href="#">신고센터</a></li>
							<li><a href="#">보안서비스</a></li>
							<li><a href="#">클라이언트</a></li>
						</ul>
					</li>
					<li>
						<a href="#">E-SPORTS</a>
					</li>
					<li>
						<a href="#">테스터</a>
						<ul class="sub">
							<li><a href="#">공지사항</a></li>
							<li><a href="#">버그 건의</a></li>
							<li><a href="#">자유</a></li>
						</ul>
					</li>
					<li>
						<a href="https://accounts.onstove.com/login?inflow_path=lost_ark&game_no=45&redirect_url=https%3A%2F%2Flostark.game.onstove.com%2FMain">LOGIN</a>
					</li>			
				</ul>
				<img src="img/Logo.png">
			</div>	
		</div>
	</header>
<!-- 아이디 page의 끝 -->
</body>
</html>
```
<br><br><br>
## style.css
```
@charset "UTF-8";

* {
   padding: 0;
   margin: 0;
}

#page {
	   margin: 0 auto;
}

header {
	height: 120px;
	margin-top: 10px;
	
}

.logo {
	float: left;
}

li {
	list-style-type: none;
	 margin: 0 0 0 0;
    padding: 0 0 0 0;
    border : 0;
    float: left;
}

a {
	color: inherit;
	text-decoration: none;
	float: center;
}

.main-menu {
	height: 85px;
	margin-top: -10px;
	background-color: black;
	line-height: 80px;
	color: white;
	list-style:none;
}

.main-menu li {
	float: left;
	width: 140px;
	text-align: center;
}

.main-menu li:hover {
	color: white;
	background-color: black;
}

.sub {
	position: absolute;
	width: 150px;
	background-color: black;
	display: none;
	z-index: 1;
}

.sub li:hover {
	background-color: black;
	text-decoration: underline;
}

.clear {
	clear: both;
}


section {
	width: 995px;
	height: 240px;
	float: left;
	margin-top: 10px;
	align-content: center;
}

.imgs {
	width: 995px;
	height: 2220px;
	position: absolute;
	overflow: hidden;
}

.imgs>img {
	position: absolute;
	transition: all 2s;
}

.welcome {
	position: relative;
	text-align: center;
	margin: -35px 0 0 -350px !important;
	width: 750px;
	height: 50px;
	line-height: 50px;
	background-color: #cccccc;
	border-radius: 30px;
	left: 50%;
	top: 50%;
}


	
.table {
	width: 995px;
	border-collapse: collapse;
	font-size: 1rem;
	color: black;
}

.table tr>th {
	padding: 5px;
}

.table tr>td {
	padding: 5px;
	text-align:center;
}
```

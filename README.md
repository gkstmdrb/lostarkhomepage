# sungilhomepage
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
		<div id="Logo">
			<img src='img/logo.png'>
			<div id='top'>
				<ul class="main-menu">
					<li>
						<a href="#">학교소개</a>
						<ul class="sub">
							<li><a href="#">학교교연혁</a></li>
							<li><a href="#">교훈</a></li>
							<li><a href="#">교가</a></li>
							<li><a href="#">학교상징</a></li>
						</ul>
					</li>
					<li>
						<a href="#">학교생활</a>
						<ul class="sub">
							<li><a href="#">부사관과</a></li>
							<li><a href="#">미용학과</a></li>
							<li><a href="#">스마트웹과</a></li>
							<li><a href="#">소프트웨어개발과</a></li>
						</ul>
					</li>
					<li>
						<a href="#">게시판</a>
						<ul class="sub">
							<li><a href="#">공지사항</a></li>
							<li><a href="#">가정통신문</a></li>
							<li><a href="#">건의사항</a></li>
							<li><a href="#">Q&A</a></li>
						</ul>
					</li>
					<li>
						<a href="#">Members</a>
						<ul class="sub">
							<li onclick="winOpen1()"><a href="#">로그인</a></li>
							<li onclick="winOpen2()"><a href="#">회원가입 클릭</a></li>
						</ul>
					</li>
				</ul>
				<img src="img/Logo.png">
			</div>	
		</div>
	</header>
	<div class='clear'></div>
	
	<section>
				<div class="imgs">
					<img src='img/main_img.png'>
					<img src='img/main_img2.png'>
					<img src='img/main_img3.png'>
					<img src='img/main_img4.png'>
					<div class="welcome">
						<h2><span>성일정보고등학교에 오신 것을 환영합니다.</span></h2>
					</div>
				</div>
	</section>
	<div class='clear'></div>
	
	<div>
		<div class="notice">
			<h2>공지사항</h2>
			<table class="table">
				<tr>
					<th>내용</th>
					<th>날짜</th>
				</tr>
				<tr>
					<td><a href="#">철쭉제의 사진 모음</a>
					<td>2022-06-01</td>
				</tr>
			</table>
		</div>
	</div>
	<div>
		<div class="notice">
			<h2>공지사항</h2>
			<table class="table">
				<tr>
					<th>내용</th>
					<th>날짜</th>
				</tr>
				<tr>
					<td><a href="#">철쭉제의 사진 모음</a></td>
					<td>2022-06-01</td>
				</tr>
				<tr>
					<td><a href="#">여름방학이 시작됩니다.</a></td>
					<td>2022-08-01</td>
				</tr>
				<tr>
					<td><a href="#">가을이 시작됩니다. 단풍구경 하세요.</a></td>
					<td>2022-10-01</td>
				</tr>
				<tr>
					<td><a href="#">수학여행을 갑시다.</a></td>
					<td>2022-11-01</td>
				</tr>
				<tr>
					<td><a href="#">교정에 눈이 내렸습니다.</a></td>
					<td>2022-12-01</td>
				</tr>
			</table>
		</div>
	</div>
	<div class='clear'></div>
	
		<footer>
		<div id='address' align="center">
			<img src='img/address.png'>
		</div>
		
		</footer>
</div>	<!-- 아이디 page의 끝 -->
</body>
</html>
```
<br><br><br>
## login.html
```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Insert title here</title>
</head>
<body>
	<form>
		<p>
			<strong>ID</strong>
			<input type="text">	// 입력형태를 문자형으로
		</p>
		<p>
			<strong>Password</strong>
			<input type="password"> // 입력형태를 비밀번호로 하여 입력 시 문자가 안보이도록 함
		</p>
		<p>
			<input type="submit" value="확인"> // 확인 버튼 생성
			<input type="submit" value="취소"> // 취소 버튼 생성
		</p>
	</form>
</body>
</html>
```
<br><br><br>
## join.html
```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Insert title here</title>
	<style>
	body {
		font-size: 14px;
		font-family: 돋움;
	}
	table {
		width: 800px;
		margin: 0 auto;
	}
	table, tr, th, td {
		border: 1px solid black;
		border-spacing: 0;
	}
	th, td {
		padding: 10px 15px;
	}
	th {
		text-align: right;
	}
	#btn {
		float: right; // 버튼 오른쪽 정렬
	}
	strong {
		color: red;
	}
	caption {
		text-align: right; // 문자 오른쪽 정렬
	}
	span {
		color: red;
	}
</style>
</head>
<body>
	<form action="join.jsp" method="post" name="form">	
		<table>
			<caption>(*)표시는 <strong>필수입력</strong> 사항입니다.</caption>
			<tr>
				<th><span>*</span>회원유형</th>
				<td>학생</td>
			</tr>
			<tr>
				<th><span>*</span>이름(실명)</th>
				<td>홍길동</td>
			</tr>
			<tr>
				<th><span>*</span>아이디</th>
				<td><p><input type="text"></p>
					<p>6~15자의 영문소문자, 숫자만 가능합니다.</p>
				</td>
			</tr>
			<tr>
				<th><span>*</span>비밀번호</th>
				<td><p><input type="password"></p>
					<p>비밀번호는 <strong>영대문자, 영소문자, 숫자, 특수문자의 조합</strong>으로 이루어져야합니다.<br> 
					// strong: 따로 효과를 넣고 싶은 문자를 strong으로 분리하여 효과 넣기 <br>
						- 조합이 2종류 이상인 경우 10자리 이상, <br>
						- 조합이 3종류 이상인 경우 8자리 이상 가능합니다.
					</p>
				</td>
			</tr>
			<tr>
				<th><span>*</span>비밀번호 확인</th>
				<td><p><input type="password"></p></td>
			</tr>
			<tr>
				<td colspan="2"><p>학교 홈페이지에 가입하시겠습니까?<span id="btn"><input type="password"></span>
			</tr>	
	</table>
</form>
</body>
</html>
```

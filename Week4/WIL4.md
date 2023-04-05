<HTML과 WEB>
HTML => Hyper Text Markup Language
tag + attribute

<!Document html> : document의 타입이 HTML
<html lang="ko"> : 웹 페이지의 언어
<html></html>: 밖에서는 작성하지 않는 것이 좋음.

# 구조

<head></head> : 문서의 머리
- title을 제외한 작성내용이 화면에 나오지 않음.
- 컴퓨터에게 주는 정보들이 적혀 있는 곳
- 검색 엔진이 좋아하며 문서 파악에 도움을 주는 곳
- 인코딩이나 웹 사이트를 설명하는 데 쓰임. ex: keywords, description, author, utf-8

<body></body> : 문서의 몸통
- 우리가 실제로 볼 수 있는 내용이 담겨있음. 

<title> : 문서의 타이틀, head안에 작성되는 내용 중 우리에게 보이는 내용

<meta> : 정보에 대한 정보 작성 - 문서에 대한 정보, 메타적인 정보
- <meta charset: >: HTML 문서의 인코딩 방식 명시

<h1> ~ <h6> : 문서의 제목 정의 시 사용
- h1: 가장 중요한 제목 정의
h 뒤의 숫자가 커질수록 폰트 크기도 달라지고 하위 계층의 제목을 의미.

<p> 내용 </p> : 문단 작성, 이 태그를 사용하면 문단 묶음으로 작성 가능, 문단 사이 간격은 큼.

<br/> : 우리가 키보드에서 엔터를 쳐도 출력되는 값은 이어져서 나오는데, 이 태그를 사용하면 다음 줄로 넘어감.

<input placeholder = "내용"> : <input> 요소에 입력될 값에 대한 짧은 힌트를 명시함.

<table border = "1"> : border가 1인 table 생성

 <form action = "action_page.php" method="get"></form> 
 - form (): 입력 양식 전체를 감싸는 태그
 - action : form을 전송할 서버 쪽의 script 파일 지정
 - method : 전송방식 선택 (get = "256~4096 byte까지만 전송 가능)

# 글씨체, etc

<strong> 내용 </strong> : 글씨가 굵어짐
<U> 내용 </U> : 밑줄 친 글씨
<mark> 내용 </mark> : 형광펜 쳐진 글씨

&bull : 가운데 위치한 굵은 점
$middot : 가운데 위치한 그냥 점

<div style = "text-indent: 30px;"> : 30px만큼 들여쓰기 가능
<td></td> : 기본 글씨체, 왼쪽 정렬로 표 내용 작성 가능 (셀 만드는 역할)
<th></th> : 굵은 글씨체, 가운데 정렬로 표 내용 작성 가능 (표의 제목을 쓰는 역할)
<tr></tr> :기본 글씨체, 왼쪽 정렬 (가로줄을 만드는 역할) 
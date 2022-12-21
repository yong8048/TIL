# 💡 Semantic Tag?
- 컴퓨터가 정보를 읽고, 이해, 가공하여 새로운 정보를 만들어 낼 수 있도록 만든 지능형 웹

### Layout Tag
#### `<header>`
- 일반적으로 웹 페이지의 가장 윗부분에 위치함
- 웹 페이지의 제목이나, 상단바 혹은 검색창 등이 포함됨.
#### `<nav>`
- navigation의 약자로, 사이트의 탭을 포함하고 있음
- `<nav>` tag안에 list tag들을 넣어 사용
#### `<main>`
- 사이트의 메인 콘텐츠를 포함
#### `<section>`
- 웹 페이지의 섹션을 나타내는 Tag
- 페이지를 Part별로 나누기 위해서도 사용됨
#### `<aside>`
- 본문이 끝나고 추가 내용을 포함하는 Tag
- 광고 등이 들어가기도 함
#### `<footer>`
- 보통 페이지의 가장 하단부에 위치
- CopyRight 및 라이센스 등이 포함됨

### 👉 예시
>```
> <!DOCTYPE html>
>   <html lang="ko">
>   <head>
>     <meta charset="utf-8">
>     <title>FastCampus</title> // 페이지 제목
>   </head>
>   <body>
>  	 <header>
>  	   <h1>Megabyte School</h1> // 사이트 제목
>      <h2>HTML</h2> // 사이트 부제목
>  	   <nav>
>     	 <ul>
>   	   <li>HTML 이란?</li>     // 메뉴1
>   	   <li>HTML Tags</li>     // 메뉴2
>		   <li>Semantic Tags</li> // 메뉴3
>         </ul>
>	   </nav>
>	 </header>
>	   <main>
>	     <p>HTML 설명</p> // 본문 내용
>	   </main>
>	   <aside>
>	     광고..등등
>	   </aside>
>	   <footer>
>	  	 <p>LICENSE</p>
>	   </footer>
>	</body>
> </html>
>```
<!DOCTYPE html>
<html lang="ko">
	<head>
		<meta charset="utf-8">
	</head>
	<body>
		<header>
			<h1>Megabyte School</h1>
			<h2>HTML</h2>
			<nav>
				<ul>
					<li>HTML 이란?</li>
					<li>HTML Tags</li>
					<li>Semantic Tags</li>
				</ul>
			</nav>
		</header>
		<main>
			<p>HTML 설명</p>
		</main>
		<aside>
			광고..등등
		</aside>
		<footer>
			<p>LICENSE</p>
		</footer>
	</body>
</html>

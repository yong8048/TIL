# 💡 HTML이란..

- Hyper Text Markup Language
- 웹 문서를 만들기 위하여 사용하는 기본적인 웹 언어의 한 종류이고, 하이퍼텍스트를 작성하기 위해 개발됨

# 🧾 HTML의 구조
- EX)
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<body>
  <h1>오늘의 날씨</h1>
  <p>많이 추워지니 따듯하게 입으세요!</p>
  <br>
</body>
</html>
```
###  !DOCTYPE
- 문서 형식을 정의
- `HTML5`는 현재 HTML의 최신 규격
- `!DOCTYPE HTML`은 `HTML5`를 표현

###  lang
- 웹문서의 전체 또는 일부에 관련 언어를 지정하는 속성

### 기본 구조
- `<html>` Tag는 `<head>`와 `<body>`로 구성 
- `<head>`
  - HTML의 속성이 포함되어있는 Tag, 제목이나 정보등이 들어있음
- `<body>`
  - HTML의 구조를 담고있는 Tag
  - 표현할 웹 페이지의 레이아웃이 포함되어 있음
---
## head 관련 Tag
#### `<meta>`
- 웹 페이지의 부가 정보들을 표기하는 Tag
#### `<title>`
- 웹 페이지의 제목을 설정하는 Tag
#### `<link>`
- 다른 파일들과 연결을 하는 Tag
- 대표적으로 **CSS**, **파비콘** 등이 있음
---
## 텍스트 관련 Tag

#### `<h[1~6]>`
- 제목 관련 Tag
- 보통 `<h1>` 부터 `<h6>` 순으로 중요도를 표현

```
<h1>제목1<h1>
<h2>제목2<h2>
<h3>제목3<h3>
<h4>제목4<h4>
<h5>제목5<h5>
<h6>제목6<h6>
```

#### `<p>`
- 문단을 표현하는 Tag
- `<p>` Tag 안에서는 줄바꿈을 하여도 하나의 문단으로 인식
```
<p>P 태그 안에서는
줄바꿈을 하여도 하나의 문단으로
인식한다.</p>
```
#### `<b>`
- **굵은 글씨 효과를 주는 Tag**

#### `<ins>`
- <ins>밑줄 효과를 주는 Tag</ins>
#### `<del>`
- <del>취소선</del> 효과를 주는 Tag
#### `<br>`
- 문단 내의 줄바꿈 Tag

---
## 목록 관련 Tag

#### `<ul>`
- Unordered list, 순서가 **없는** 목록

>```
><ul>
>  <li>1번</li>
>  <li>2번</li>
></ul>
<<출력>>
- 1번
- 2번

#### `<ol>`
- Ordered list, 순서가 **있는** 목록

>```
><ol>
>  <li>1번</li>
>  <li>2번</li>
></ol>
>```
<ol>
  <li>1번</li>
  <li>2번</li>
</ol>

#### `<li>`
- list item, 항목 Tag
---

## 링크 관련 Tag
#### `<a>`
- Anchor, 하이퍼링크 Tag
`<a href="https://www.google.co.kr">구글</a>` <a href="https://www.google.co.kr">구글</a>
#### `<img>`
- image Tag
`<img src="https://www.google.com/favicon.ico" alt=구글 로고">`
<img src="https://www.google.com/favicon.ico" alt="구글 로고">
#### `<svg>`
- SVG 형식의 그래픽 Tag
- 별도의 파일 없이 HTML 안에서 코딩으로 넣을 수도 있음
---

## 테이블 관련 Tag
#### `<table>` 
- 테이블을 만드는 Tag
#### `<tr>`
- Table row, 테이블의 행을 뜻하는 Tag
#### `<td>`
- Table data, 테이블의 내용, 즉 셀을 표현
>```
<table>
　　<tr>
　　　　<td>A</td>
　　　　<td>B</td>
　　　　<td>C</td>
　　</tr>
　　<tr>
　　　　<td>D</td>
　　　　<td>E</td>
　　　　<td>F</td>
　　</tr>
</table>
>```
<table>
　　<tr>
　　　　<td>A</td>
　　　　<td>B</td>
　　　　<td>C</td>
　　</tr>
　　<tr>
　　　　<td>D</td>
　　　　<td>E</td>
　　　　<td>F</td>
　　</tr>
</table>

#### `<th>`
- Table heading, 테이블의 행
- Default로 가운데 정렬이고 굵은 글씨로 표시됨
>```
<table>
　　<tr>
　　　　<th>A</th>
　　　　<th>B</th>
　　　　<th>C</th>
　　</tr>
　　<tr>
　　　　<td>a</td>
　　　　<td>b</td>
　　　　<td>c</td>
　　</tr>
</table>
>```
<table>
　　<tr>
　　　　<th>A</th>
　　　　<th>B</th>
　　　　<th>C</th>
　　</tr>
　　<tr>
　　　　<td>a</td>
　　　　<td>b</td>
　　　　<td>c</td>
　　</tr>
</table>


  






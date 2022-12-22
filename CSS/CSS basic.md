# CSS
- 웹 문서의 전반적인 스타일을 미리 저장해 둔 Style Sheet이다
- HTML로 작성된 문서의 표현되는 방법을 정해준다

### 기본 문법
- 스타일을 적용할 대상
- 선택자 {속성: 값;}
```
div {
    color: red;
    padding: 10px;
}
```

---

## 선언 방식

### 내장 방식

- `<style></style>` 내용으로 스타일을 작성하는 방식

```
<style>
  div {
  color: red;
  padding: 10px;
}
</style>
```

### 인라인 방식

- 요소의 **style** 속성에 직접 작성하는 방식
- 선택자가 없다

```
<div style="color: red; padding: 10px;"></div>
```

### 링크 방식

- 외부 CSS파일을 가져와서 연결하는 방식

```
<link rel="stylesheet" href="./main.css">
```

### import 방식

- CSS의 @import 규직으로 CSS파일 안에서 다른 CSS파일을 가져와 연결하는 방식

``` 
@import url("./box.css");
```

---

## 선택자

### 전체 선택자

- *(asterisk) : 모든 요소를 선택

```
* {
  color: red;
}
```

### 태그 선택자

- 태그의 이름으로 요소를 선택하는 선택자

```
li {
  color: red;
}
```

### 클래스 선택자

- HTML 파일 내, class속성의 값으로 선택하는 선택자
- 클래스 선택자를 의미하는 "."을 class이름 앞에 붙혀준다

```
.class_value {
  color: red;
}
```

### 아이디 선택자

- HTML 파일 내, id속성의 값으로 선택하는 선택자
- 아이디 선택자를 의미하는 "#"을 id이름 앞에 붙혀준다

```
#id_value{ +
  color: red;
}

```
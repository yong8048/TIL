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

### 선언 방식

#### 내장 방식

```
<style>
  div {
    color: red;
    padding: 10px;
  }
</style>
```

- `<style></style>` 내용으로 스타일을 작성하는 방식

#### 인라인 방식

```
<div style="color: red; padding: 10px;"></div>
```

- 요소의 **style** 속성에 직접 작성하는 방식
- 선택자가 없다

#### 링크 방식

```
<link rel="stylesheet" href="./main.css">
```

- 외부 CSS파일을 가져와서 연결하는 방식

#### import 방식

```
@import url("./box.css");
```

- CSS의 @import 규직으로 CSS파일 안에서 다른 CSS파일을 가져와 연결하는 방식
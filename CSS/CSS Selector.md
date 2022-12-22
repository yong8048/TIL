# 선택자 (Selector)

## 기본 선택자

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
#id_value{
  color: red;
}

```

---

## 복합 선택자
- 기본 선택자를 조합하여 선택하는 선택자

### 일치 선택자 (Basic Combinator)
- 선택자 A,B를 동시에 만족하는 요소를 선택하는 구조

```
EX) class의 값이 "value"인 span tag내의 요소
span.value {
  color: red;
}
```

### 자식 선택자 (Child Combinator)
- 선택자 A의 자식요소 B를 선택하는 구조
- ">"가 선택자의 기호이다

```
EX) class의 값이 "value"인 ul의 자식요소
ul > .value{
  color: red;
}
```

### 하위(후손) 선택자 (Descendant Combinator)
- 선택자 A의 하위요소 B를 선택하는 구조
- "띄어쓰기"가 선택자의 기호이다

```
EX) class의 값이 "value"인 div의 하위요소
div .value {
  color: red;
}
``` 

### 인접 형제 선택자 (Adjacent Sibling Combinator)
- 선택자 A의 **다음** 형제요소 B를 선택하는 구조
- "+"가 선택자의 기호이다

```
EX) class의 값이 "value"인 요소의 바로 다음 div 요소 **하나**
.value + div {
  color: red;
}
```

### 일반 형제 선택자 (General Sibling Combinator)
- 선택자 A의 **다음** 형제요소를 모두 선택하는 구조
- "~"가 선택자의 기호이다

```
EX) class의 값이 "value"인 요소의 다음 div 요소 모두
.value ~ div {
  color: red;
}
```

---

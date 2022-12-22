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

### 일치 선택자
- 선택자 1,2를 동시에 만족하는 요소를 선택

```
EX) tag & class 선택자
span.value {
  color: red;
}
class의 값이 `value`인 span tag내의 요소
```
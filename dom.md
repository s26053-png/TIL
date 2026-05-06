# DOM 조작

## 1. DOM

DOM(Document Object Model)은 HTML 문서를 JavaScript에서 조작할 수 있도록 객체 형태로 표현한 것이다.

JavaScript를 사용하면 HTML 요소를 선택하거나 수정할 수 있다.

---

# 2. 요소 선택

## document.querySelector()

하나의 요소를 선택한다.

```javascript
const box = document.querySelector(".box");
```

---

## document.querySelectorAll()

여러 요소를 선택한다.

```javascript
const items = document.querySelectorAll(".item");
```

---

# 3. 요소 생성

## createElement()

새로운 요소를 생성한다.

```javascript
const div = document.createElement("div");
```

---

# 4. 요소 추가

## appendChild()

생성한 요소를 추가한다.

```javascript
document.body.appendChild(div);
```

---

# 5. 요소 내용 수정

## innerHTML

HTML 태그까지 적용된다.

```javascript
box.innerHTML = "<h1>Hello</h1>";
```

---

## textContent

텍스트만 변경한다.

```javascript
box.textContent = "Hello";
```

---

# innerHTML vs textContent

| innerHTML | textContent |
|------|------|
| HTML 태그 적용 가능 | 텍스트만 출력 |
| 태그 해석 O | 태그 해석 X |

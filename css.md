# CSS
## 1. CSS
- 웹 페이지의 디자인(스타일)을 담당하는 언어
- 색상, 크기, 배치 등을 설정
---
## 2. 기본 문법
```css
선택자 {
    속성: 값;
}
```
---
## 3. 선택자 (Selector)
- 태그 선택자 -> p, div
- 클래스 선택자 -> .class이름
- 아이디 선택자 -> #id이름
```
.box {
    background-color: blue;
}

#title {
    color: green;
}
```
---
## 4. 주요 속성
  ## 색상 & 배경
  -  color: 글자 색
  - background-color: 배경색
  ## 크기 & 여백
  - width, height: 크기
  - margin: 바깥 여백
  - padding: 안쪽 여백
  ## 텍스트
  - font-size: 글자 크기
  - twxt-align: 정렬
  ---
  ## 5. 박스 모델
  - 모든 요소는 박스 형태

  #### maergin -> border -> padding -> content
  ```
  id="6z2c1n"
  ```
  ---
  ## 6. 레이아웃 (배치)

  ### flex (가장 많이 사용)
  ``` css 
id="6uj7t5"
.container {
    display: flex;
    justify-content: center;
    align-items: center;
}
```
---
## 7. 적용 방법
1) 인라인
```
<p style="color:red;">텍스트</p>
```
2) 내부 스타일
```
<style>
    p { color: red;}
    </style>
```

3) 외부 파일
```
<link rel="stylrsheet" href="style.css">
```

---

## 8. 핵심 정리
- CSS: 디자인
- 선택자: 스타일 적용 대상
- flex: 레이아웃 핵심
---
## 9. 한 줄 요약

- CSS는 웹을 꾸미는 언어이다.

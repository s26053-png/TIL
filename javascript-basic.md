# JavaScript 기본 문법
## 1. 변수 (Variable)
### let
값 변경이 가능한 함수
---
### const
값 변경이 불가능한 변수
```JavaScript
const age = 20;
```
---
## 2. 조건문 (Condition)
조건에 따라 다른 코드를 실행
---
## 3. 반복문 (Loop)

## for
반복 횟수가 정해져 있을 때 사용한다.
```JavaScript
for(let i = 0; i < 5; i++) {
    console.log(i);
}
```
---
## while
조건이 true인 동안 반복한다.
```JavaScript
let i = 0;

while (i<5) {
    console.log(i);
    i++;
}
```
---
## 4. 함수 (Function)

###  함수 선언
```JavaScript
function hello() {
    console.log("Hello");
}
```
---
## 5. 자료구조 (DAta Structure)

### 배열 (Array)
여러 값을 순서대로 저장한다.
```JavaScript
const arr = [1, 2, 3];
```
---
### 객체 (object)
키와 값을 저장한다.
```JavaScript
const user = {
    name: "Tom",
    age: 20
};
```
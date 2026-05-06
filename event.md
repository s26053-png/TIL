# 이벤트 처리

## 이벤트(Event)란
이벤트는 사용자의 동작이나 브라우저에서 발생하는 행동을 의미한다.

예:
- 클릭
- 입력
- 변경

JavaScript는 이벤트를 감지하여 특정 동작을 실행할 수 있다.

---

# 2. addEventListener()
이벤트를 등록할 때 사용한다.
```javascript
button.addEventListener("Click", () => {
    console.log("클릭");
});
```

---

# 3. 주요 이벤트

## click
요소를 클릭했을 떄 실행된다.

## input
입력값이 변경될 때 실행된다.

## change
입력이 완료되어 값이 변경되었을 때 실행된다.

---

# 4. 이벤트 객체(Event object)
이벤트가 발생하면 이벤트 정보를 담은 객체가 전달된다.

## Event.target
이벤트가 발생한 요소를 확인할 수 있다.

---

# event vs event.target

| event | event.target |
|------|------|
| 이벤트 정보 전체 | 이벤트가 발생한 요소 |
| 객체 형태 | HTML 요소 |
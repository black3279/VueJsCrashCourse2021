# VueJsCrashCourse2021
For study

## 1. Watch 속성
- watch 속성은 감시하는 역할로 데이터가 변경되었을 때, 실행되는 속성이다.
- watch 속성은 체크하고싶은 데이터를 명시하고 해당 데이터를 함수로하여 (value, oldValue) 와 같은 형태로 실행하고 싶은 내용을 명시하면 된다.
- oldValue 의 경우, 해당 체크하고 있던 데이터의 변경 전 값을 나타나게 된다.
- value 나 oldValue 의 경우 객체나 배열의 경우, 이전 값과 현재 값이 같은 값이 나올 수 있기 때문에 primitive 타입만 써주는 것이 좋다.
- watch 속성의 경우, 
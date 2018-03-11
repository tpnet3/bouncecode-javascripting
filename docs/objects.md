[&EXEC]: # (touch objects.js && javascripting select objects && bouncecode editor-reset && bouncecode editor-open objects.js)
[&RUN]: # (node objects.js)
[&TEST]: # (javascripting select objects && javascripting run objects.js && javascripting verify objects.js)

객체는 배열과 비슷한 값의 목록입니다. 배열과 다른 점은 정수 대신 키를 사용해 값을 확인하는 점입니다.
예제를 보세요.
```js
var foodPreferences = {
  pizza: 'yum',
  salad: 'gross'
};
```
## 도전 과제
`objects.js`라는 파일에 이렇게 `pizza`라는 변수를 정의합니다.
```js
var pizza = {
  toppings: ['cheese', 'sauce', 'pepperoni'],
  crust: 'deep dish',
  serves: 2
};
```
`console.log()`를 사용해 `pizza` 객체를 터미널에 출력합니다.
파일을 저장하고 프로그램이 올바른지 실행하세요.
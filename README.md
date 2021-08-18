# 조건문 (If statement)

# If

if문은 조건이 참일 경우 명령문을 실행 거짓일 경우 다른 명령문이 실행

## 문법

```javascript
const a = 4;

if (a > 3) {
  console.log("a는 3보다 큽니다");
} else {
  console.log("a는 3보다 작습니다");
}
```

# else if

두개 이상의 조건식을 사용하고싶을때 사용

```javascript
if (A) {
  console.log("A"); // A가 true면 A를 출력
} else if (B) {
  console.log("B"); // B가 true면 B를 출력
} else if (C) {
  console.log("C"); // C가 true면 C를 출력
} else {
  console.log("."); // 저 셋다아니면 . 출력
}
```

# Switch

여러개의 if 조건문을 switch문으로 바꿀수있다<br>
Switch문을 사용한 비교법은 특정 변수를 다양한 상황에서 비교할 수 있게 해준다<br>
코드 자체가 비교 상황을 잘 설명한다는 장점도 있다

## 문법

```javascript
const a = 4;

switch (a) {
  case 1:
    console.log("a는 1보다 큽니다");
    break;
  case 2:
    console.log("a는 2보다 큽니다");
    break;
  case 3:
    console.log("a는 3보다 큽니다");
    break;
  case 4:
    console.log("일치합니다");
    break;
  default:
    console.log("일치하는것이 없습니다");
}
```

# 반복문 (For statement)

## for문

### for (시작조건; 종료조건; 변화조건) {}

for 반복문은 어떤 특정한 조건이 거짓으로 판별될 때까지 반복합니다.

## 문법

```javascript
let num = 1;

for (let i = 0; i < 4; i++) {
  num = num + i;
}
console.log(num);
// 결과 7
```

# Context API에 대해 설명해주세요.

Context API는 리액트에서 상태를 전역적으로 관리하기 위한 기능을 제공하는 API입니다. 이를 통해 상위 컴포넌트에서 하위 컴포넌트로 props를 전달하지 않고도 상태를 공유하고 업데이트할 수 있습니다.

그러나 하위 컴포넌트로 props를 전달하는 방식에는 몇 가지 문제점이 있습니다.

Prop Drilling이 발생할 수 있습니다. 컴포넌트 계층이 깊어질수록 props를 전달하는 과정이 복잡해지기 때문에 유지보수가 어려워집니다. 그리고 컴포넌트 간의 데이터 흐름을 이해하기 어려워지고, 디버깅이 어려워질 수 있습니다.

또한 컴포넌트 간에 props를 전달하는 것은 결합도를 증가시킵니다. 만약 중간 컴포넌트에서 다른 컴포넌트로 props를 전달해야 하는 경우, 중간 컴포넌트가 의도하지 않은 변경에 영향을 받을 수 있습니다. 이는 재사용성과 유연성을 저하시킬 수 있습니다.

---

### 꼬리 질문

- [Context API와 Redux를 비교해주세요.](https://github.com/DataCodeLiteracy/Interview-Questions/blob/main/React/Context%20API%20vs%20Redux.md)

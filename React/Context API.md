# Context API에 대해 설명해주세요.

Context API는 리액트에서 상태를 전역적으로 관리하기 위한 기능을 제공하는 API입니다. 이를 통해 상위 컴포넌트에서 하위 컴포넌트로 props를 전달하지 않고도 상태를 공유하고 업데이트할 수 있습니다. 또한, 중첩된 컴포넌트 구조에서도 효과적으로 데이터를 전달하고 사용할 수 있습니다.

하지만 과도한 사용은 컴포넌트 간의 결합도를 높일 수 있으므로 신중하게 사용해야 합니다.

구성요소로는 Context, Provider, Consumer 등이 있습니다.

Context는 데이터를 공유하기 위한 컨테이너 역할을 하는 객체입니다. Context 객체를 생성하고 해당 객체를 통해 데이터를 제공합니다.

Provider는 Context 객체에서 제공하는 데이터를 실제로 전달하는 역할을 합니다.

Consumer는 Provider에서 제공한 데이터를 사용하기 위한 컴포넌트입니다. Consumer 컴포넌트는 Context 객체를 구독하고 해당 데이터를 사용할 수 있습니다.

---

### 꼬리 질문

- [Context API와 Redux를 비교해주세요.](https://github.com/DataCodeLiteracy/Interview-Questions/blob/main/React/Context%20API%20vs%20Redux.md)

# Virtual DOM이 무엇인지 설명해주세요.

Virtual DOM은 주로 리액트(React)와 같은 Virtual DOM 기반의 라이브러리나 프레임워크에서 사용됩니다.

Virtual DOM은 실제 DOM과 유사한 구조를 가진 가상의 DOM입니다. 실제 DOM에 접근하면 브라우저는 레이아웃을 재계산하고, 변경된 요소들의 배치를 업데이트해야 합니다. 하지만 Virtual DOM에 변경 사항을 적용하면, 리액트는 Virtual DOM과 실제 DOM의 차이점을 비교하여 실제 DOM을 효율적으로 업데이트합니다. Virtual DOM은 실제 DOM과 별개로 동작하기 때문에, 변경 사항을 모아서 한 번에 업데이트하므로 배치와 레이아웃 계산을 최소화할 수 있습니다.

[Virtual DOM의 리렌더링 주기는 어떻게 동작하나요?](https://github.com/DataCodeLiteracy/Interview-Questions/blob/main/React/Virtual%20DOM's%20reRendering.md)

[Virtual DOM에서의 batching이란 무엇인가요?](https://github.com/DataCodeLiteracy/Interview-Questions/blob/main/React/batching.md)

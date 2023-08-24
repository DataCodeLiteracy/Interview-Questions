# PureComponent 에 대해 설명해주세요.

PureComponent는 React에서 제공하는 성능 최적화를 위한 컴포넌트 유형입니다. 이 컴포넌트는 변경사항을 검사하여 필요한 경우에만 렌더링되도록 설계되었습니다. PureComponent는 내부적으로 shouldComponentUpdate 메서드를 구현하여 이전 state 및 props와 현재 state 및 props를 비교하여 렌더링을 결정합니다.

PureComponent는 클래스 컴포넌트로 구현되며, 얕은 비교를 사용하여 내부 state 및 props를 비교합니다. 이로 인해 불필요한 렌더링을 방지하고 성능을 향상시킬 수 있습니다. 

단, PureComponent를 사용할 때 주의해야 할 점은 내부 state나 props가 객체나 배열과 같은 참조 타입인 경우, 내부의 값이 변경되지 않아도 참조가 변경되면 렌더링이 발생할 수 있습니다. 이런 경우에는 불필요한 렌더링을 막기 위해 깊은 복사를 사용하거나 shouldComponentUpdate 메서드를 직접 구현해야 할 수 있습니다.
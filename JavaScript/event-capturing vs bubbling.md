# 이벤트 캡처링과 버블링에 대해 설명해주세요.

DOM 트리 상에 존재하는 DOM 요소에서 발생한 이벤트는 DOM 트리를 통해 전파되는데 이를 이벤트 전파라고 합니다. 이벤트가 발생할 때 생성된 객체는 이벤트를 발생시킨 DOM 요소인 이벤트 타깃을 중심으로 DOM 트리를 통해 전파됩니다. 이때 이벤트 객체가 전파되는 방향에 따라 3단계로 구분됩니다.

상위 DOM 요소에서 하위 DOM 요소로 전파되는 걸 캡처링 단계, 이벤트가 타깃에 도착하는 걸 타깃 단계, 다시 하위 DOM 요소에서 상위 DOM 요소로 전파되는 걸 버블링 단계라고 합니다. 

보통 상위 DOM 요소의 여러 개의 자식 하위 DOM 요소 중에 이벤트가 발생한 타깃에 대해서 이벤트 처리를 일일히 해줘야 하는 경우에 상위 DOM요소에 이벤트리스너를 등록해 하위 DOM 요소에 이벤트 발생시 이벤트 객체가 전파되면서 이벤트 타깃을 캐치해낼 수 있도록 하는 방법을 통해 효율적으로 이벤트 처리를 할 때 사용하게 됩니다.

---
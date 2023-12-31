# 렉시컬 환경에 대해 설명해주세요.

렉시컬 환경은 스코프와 변수 검색을 관리하는 자바스크립트 엔진의 핵심적인 구성 요소입니다.

렉시컬 환경은 실행 컨텍스트를 구성하는 중요한 요소 중에 하나이며 환경 레코드와 외부 렉시컬 환경 참조라는 두 가지 핵심 컴포넌트로 구성됩니다.

1. 환경 레코드(Environment Record): 실제 변수와 함수 등의 식별자와 그들의 현재 값에 대한 매핑 정보를 담고 있습니다. 환경 레코드는 블록 스코프 내의 변수와 함수를 관리하는 데 사용됩니다.
2. 외부 렉시컬 환경 참조(Outer Lexical Environment Reference): 현재 렉시컬 환경과 연결된 상위 스코프의 렉시컬 환경에 대한 참조를 가집니다. 이를 통해 스코프 체인을 형성하여 변수의 스코프를 검색할 수 있게 됩니다.

렉시컬 환경은 함수가 정의된 위치(렉시컬 스코프)에 따라 결정되며, 함수가 호출될 때마다 새로운 렉시컬 환경이 생성됩니다. 이러한 렉시컬 스코프에 따라 변수와 함수의 유효 범위가 정해지게 되고, 클로저와 같은 자바스크립트의 중요한 기능들이 가능해집니다.

클로저는 실행 컨텍스트의 렉시컬 환경과 관련하여 함수가 자신의 렉시컬 스코프 외부의 변수에 접근하는 현상을 말합니다. 클로저를 통해 함수는 선언된 곳이 아닌 다른 곳에서도 해당 함수가 생성될 때의 환경 정보에 접근할 수 있습니다. 이를 통해 함수가 자유 변수를 유지하고, 비동기 처리나 함수를 반환하는 등의 유용한 패턴을 구현할 수 있습니다.
# 실행 컨텍스트에 대해 설명해주세요.

---

- 실행 가능한 코드가 실행되기 위해 필요한 환경정보들을 모아놓은 객체입니다. scope, hoisting, this, function, closure 등의 동작원리를 담고 있는 자바스크립트의 핵심 원리입니다. 실행 컨텍스트는 자바스크립트 엔진이 코드를 실행하기 전에 생성되며, 함수가 호출될 때마다 새로운 실행 컨텍스트가 스택에 추가되고 실행이 끝나면 스택에서 제거됩니다. 이러한 실행 컨텍스트의 동작 방식으로 인해 자바스크립트는 동적으로 변수와 함수를 생성하고 관리할 수 있게 됩니다.

---

1. Scope(스코프): 실행 컨텍스트는 스코프 체인을 통해 변수와 함수의 유효 범위를 파악합니다. 변수나 함수가 어떤 스코프에 선언되었는지 확인하고, 해당 스코프에서 변수를 검색합니다.
2. Hoisting(호이스팅): 실행 컨텍스트는 변수와 함수 선언을 런타임 이전에 먼저 처리하여 호이스팅이 발생합니다. 변수는 선언 단계에서 메모리에 할당되고 undefined로 초기화되며, 함수는 정의 단계에서 메모리에 할당됩니다.
3. This(디스): 실행 컨텍스트는 함수가 호출될 때 this가 어떤 객체를 참조하는지 결정합니다. this를 바인딩하여 해당 함수가 호출되는 객체에 동적으로 접근할 수 있도록 합니다.
4. Function(함수): 실행 컨텍스트는 함수를 실행하여 함수 호출을 관리합니다. 함수를 호출할 때마다 새로운 실행 컨텍스트가 스택에 추가되고, 함수의 실행이 끝나면 스택에서 제거됩니다.
5. Closure(클로저): 실행 컨텍스트는 클로저가 발생하는 환경을 만들어냅니다. 클로저는 함수가 자신의 렉시컬 스코프 외부의 변수에 접근하는 현상을 의미하며, 실행 컨텍스트가 이를 관리하여 함수가 적절한 변수에 접근할 수 있도록 합니다.
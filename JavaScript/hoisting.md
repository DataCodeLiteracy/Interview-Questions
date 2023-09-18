# 호이스팅에 대해 설명해주세요.

자바스크립트는 코드 실행을 위해 평가와 실행 단계를 거치는데, 평가 단계에서 자바스크립트 엔진은 코드를 순차적으로 평가합니다. 이 때 변수와 함수 선언을 찾아서 메모리 공간에 등록하고 초기화합니다. 이렇게 메모리에 미리 등록한 선언문이 실행 단계 이전에 마치 끌어올려진 것처럼 보인다고 해서 호이스팅이라고 합니다. 변수든 함수든 선언문만 호이스팅 되므로 변수와 함수의 동작 과정에서 차이가 발생합니다. 변수는 보통 값을 할당해서 사용하기 때문에 선언문만 호이스팅 되는 변수를 할당 이전에 참조하려고 하게 되면 원하는 할당값을 호출할 수 없게 됩니다. 반면에 함수 선언식은 선언문 전체가 호이스팅 되기 때문에 선언 이전에 호출하게 되도 함수를 정상적으로 호출해서 사용할 수 있습니다.

---
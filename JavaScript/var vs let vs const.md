# var, let, const의 차이를 설명해주세요.

var와 let은 변수 선언 키워드, const는 상수 선언 키워드 입니다. var의 사용을 지양해야 하고, let과 const의 사용을 고려해야 합니다. 그 이유는 var의 몇 가지 문제점이 있기 때문입니다. var는 중복선언이 가능하기 때문에 기존 값을 덮어씌울 수 있습니다. 또한 let, const는 블록 스코프로 동작가능하지만 var는 함수 스코프로만 동작하기 때문에 복잡한 함수 안의 여러 블록들 안에서 var를 사용하게 되면 정확한 변수의 범위 파악이 어렵고 의도치 않은 변수 누출이 발생할 수 있습니다. 그리고 자바스크립트는 실행 단계 이전에 평가 단계에서 선언문을 모두 등록하게 됩니다. 이때 선언문이 마치 끌어올려진 것처럼 보이는 것을 호이스팅이라고 하는데, var의 경우 선언 전에 참조가 가능해 악성 코드를 만들 수 있지만 let, const의 경우 TDZ에 의해 선언 전에 참조할 경우 에러를 발생시킵니다.

그리고 추가적으로 const는 선언과 동시에 반드시 값을 할당을 해야하고 재할당이 불가능하며 let은 선언과 동시에 할당을 하지 않아도 되며 재할당이 가능하다는 차이점이 있습니다.

---

- [함수 선언문과 함수 표현식에 대해서도 설명해주세요.](https://github.com/DataCodeLiteracy/Interview-Questions/blob/main/JavaScript/function%20declarations%20and%20expressions.md)
- [var 호이스팅과 함수의 호이스팅은 같나요?](https://github.com/DataCodeLiteracy/Interview-Questions/blob/main/JavaScript/hoisting-var%20vs%20function.md)

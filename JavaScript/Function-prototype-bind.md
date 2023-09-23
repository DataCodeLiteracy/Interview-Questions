# Function.prototype.bind을 설명하세요.

Function.prototype.bind() 메서드는 JavaScript에서 함수를 생성하고, 해당 함수 내에서 this 키워드가 특정한 객체를 참조하도록 만들어주는 역할을 합니다. 이 메서드는 새로운 함수를 반환하며, 원본 함수와 동일한 코드를 가지고 있지만, this의 바인딩이 bind의 인자에 전달한 객체로 변경됩니다. 주로 이벤트 핸들러, 콜백 함수, 함수의 this 컨텍스트를 유지해야 하는 경우에 활용됩니다.

---

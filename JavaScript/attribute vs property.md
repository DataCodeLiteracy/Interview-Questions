# attribute와 property의 차이점에 대해 설명해주세요.

Attribute와 Property는 둘 다 속성이라는 뜻을 가지고 있습니다. 하지만 둘은 엄연히 다른 특징을 가지고 있습니다. Attribute는 HTML 요소의 속성을 뜻하고 Property는 DOM 요소의 속성을 나타냅니다. 따라서 Attribute는 정적으로 변하지 않고 Property는 동적으로 그 값이 변할 수 있습니다. 예를 들어 HTML input태그에 value 기본값 0을 선언하면 그때의 value는 Attribute 이며, DOM으로 해당 input 요소를 querySelector해서 value 값을 10으로 변경하는 코드가 있다고 할 때 DOM의 input.value 값은 Property입니다. 이처럼 Property는 자바스크립트를 통해 동적으로 변경이 가능합니다. 하지만 Property를 변경한다고 해서 input태그의 value Attribute가 변하는 것은 아닙니다. 둘은 연결되어 있지만, 엄연히 다른 차이점이 존재합니다.

---

# 실행 컨텍스트에 대해 설명해주세요.

실행 컨텍스트는 JS 코드가 실행되기 위해 필요한 환경정보들을 모아놓은 객체입니다. 환경정보에는 식별자 정보와 this 바인딩, 외부 환경 참조에 대한 정보를 담고 있습니다. 실행 컨텍스트는 자바스크립트 엔진이 코드를 실행하기 전에 생성되며, 함수가 호출될 때마다 새로운 실행 컨텍스트가 스택에 추가되고 실행이 끝나면 스택에서 제거됩니다. 이러한 실행 컨텍스트의 동작 방식으로 인해 자바스크립트는 동적으로 변수와 함수를 생성하고 관리할 수 있게 됩니다. 실행 컨텍스트의 구조는 크게 변수 환경, 렉시컬 환경, this 바인딩으로 나눌 수 있습니다. 변수 환경에 현재 컨텍스트에 대한 식별자들의 정보와 외부 환경 참조 정보가 저장되고 렉시컬 환경에 이런 정보들의 변경 사항이 실시간으로 반영됩니다. this 바인딩에는 현재 실행 컨텍스트가 바라봐야하는 this 값을 관리합니다.

---

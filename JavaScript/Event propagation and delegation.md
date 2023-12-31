# 이벤트 전파와 위임에 대해 설명해주세요.

이벤트 전파는 DOM 요소에서 발생한 이벤트가 상위 요소로 전달되는 프로세스를 나타냅니다. 이벤트는 버블링과 캡처링 단계로 나뉘며, 버블링은 하위에서 상위 요소로 이벤트가 전달되고, 캡처링은 그 반대입니다. 이벤트 전파를 이해하면 특정 요소에서 발생한 이벤트를 그 부모 요소에서도 감지하거나 처리할 수 있습니다.

이벤트 위임은 이벤트 전파를 활용하는 패턴 중 하나로, 상위 요소에 이벤트 리스너를 하나만 등록하여 여러 하위 요소의 이벤트를 처리하는 것을 의미합니다. 이렇게 하면 많은 요소에 개별적인 리스너를 등록하는 것보다 더 효율적이고 성능이 향상됩니다. 이벤트 위임은 동적으로 생성되는 요소에도 적용할 수 있어 유용합니다.

---

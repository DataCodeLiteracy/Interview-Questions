# useMemo와 useCallback에 대해 설명해주세요.

useMemo와 useCallback은 React에서 성능 최적화를 위해 사용되는 훅입니다. 두 훅은 모두 메모이제이션을 활용하여 불필요한 계산이나 함수 생성을 방지하여 성능을 향상시킵니다.

useMemo는 함수의 반환 값을 메모이제이션하고, 의존성 배열의 값이 변경되었을 때에만 함수를 재실행합니다. 만약 의존성 배열이 변경되지 않았다면, 이전에 계산한 값을 재사용합니다.

useCallback은 콜백 함수 자체를 메모이제이션하여 동일한 함수를 재사용합니다. 이를 통해 자식 컴포넌트에게 전달되는 콜백 함수가 동일한 함수를 참조하여 불필요한 렌더링을 방지하고 성능을 향상시킵니다.

즉, useMemo는 값을 메모이제이션하고 , useCallback은 함수를 메모이제이션합니다.

---

[메모이제이션에 대해 설명해주세요.](https://github.com/DataCodeLiteracy/Interview-Questions/blob/main/React/Memoization.md)

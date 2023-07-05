# useEffect와 useLayoutEffect의 차이점에 대해 말씀해주세요.

리액트에서 useEffect와 useLayoutEffect는 컴포넌트가 렌더링될 때마다 실행되는 훅입니다.
하지만 useEffect는 렌더링이 완료된 후에 실행되는 반면, useLayoutEffect는 렌더링이 시작되기 전에 실행됩니다.

useEffect는 비동기적으로 실행되며 주로 렌더링에 영향을 미치지 않는 작업을 수행하는 데 사용됩니다.
예를 들어, API에서 데이터를 가져오거나 컴포넌트의 상태를 업데이트하는 작업은 useEffect에서 수행할 수 있습니다.

useLayoutEffect는 동기적으로 실행되며 주로 렌더링에 영향을 미치는 작업을 수행하는 데 사용됩니다.
예를 들어, 컴포넌트의 크기를 조정하거나 위치를 변경하는 작업은 useLayoutEffect에서 수행할 수 있습니다.

---

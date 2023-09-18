# Promise와 async/await의 차이점에 대해 설명해주세요.

Promise와 async/await은 비동기 작업을 다루는 서로 다른 접근 방식입니다.

Promise는 .then() 및 .catch() 메서드를 사용하여 비동기 작업의 성공 및 실패를 처리합니다. 여러 개의 비동기 작업을 메서드로 체이닝해서 사용할 수 있기 때문에 콜백 함수로 비동기 작업을 처리하면서 발생한 콜백 지옥을 방지하고 가독성을 향상시키는 데 사용할 수 있습니다. 그러나 Promise또한 메서드 체이닝이 중첩적으로 너무 길어지게 되면 이 또한 가독성이 안 좋아질 수 있는데, 이때 async/await를 사용하면 좀 더 가독성이 높게 코드를 작성할 수 있습니다.

async/await는 함수에 async 키워드를 사용하면, await 키워드를 통해 비동기 작업을 동기식으로 작성하면서 처리할 수 있습니다. 따라서 기존에 동기식 코드를 작성하면서 비동기 작업을 수행하기 때문에 Promise 처럼 메서드 체이닝이 길게 이어질 필요가 없기 때문에 좀 더 가독성이 높게 코드를 작성할 수 있습니다. 그리고 오류 처리는 try… catch 블록을 사용합니다.

---
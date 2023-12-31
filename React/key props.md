# 리액트에서 key props를 사용하는 이유는 무엇인가요?

리액트에서는 map과 같은 반복구조에서 key를 사용해서 각 엘리먼트를 고유하게 식별해서 변경된 부분만을 추적하여 해당 부분만을 업데이트하고, 나머지는 재사용하여 성능을 향상시킬 수 있습니다.

리액트의 조화 과정(Reconciliation)에서 key는 각 엘리먼트의 고유 식별자로 사용되며, 엘리먼트의 추가, 수정, 삭제 등을 추적하는 데 중요한 역할을 합니다. key가 없는 경우, 리스트나 반복 구조에서 엘리먼트의 순서가 변경되면 리액트는 해당 구조 전체를 다시 렌더링합니다. 이는 비효율적인 동작을 초래할 수 있으며, 업데이트 성능에 영향을 줄 수 있습니다.

key를 지정할 때에는 엘리먼트의 고유 식별자인 것이 이상적입니다.그러나 데이터의 고유 식별자가 없는 경우에는 인덱스를 key로 사용할 수도 있지만, 이는 성능에 영향을 줄 수 있으므로 주의해야 합니다.

---

- [인덱스를 key로 사용하는 것이 성능에 영향을 줄 수 있는 이유는 무엇인가요?](https://github.com/DataCodeLiteracy/Interview-Questions/blob/main/React/index%20key.md)
- [반복 구조에서만 키가 유용한가요?](https://github.com/DataCodeLiteracy/Interview-Questions/blob/main/React/Keys%20in%20Iterated%20Structures.md)

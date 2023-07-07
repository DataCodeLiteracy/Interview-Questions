# Virtual DOM에서의 batching이란 무엇인가요?

Virtual DOM에서의 batching은 변경 사항을 한 번에 모아서 처리하는 방식입니다.

변경 사항을 실제 DOM에 반영하는 과정은 비용이 큰 작업입니다. 따라서, 변경 사항을 모아서 한 번에 처리함으로써 불필요한 실제 DOM 조작을 최소화하고 성능을 개선할 수 있습니다.

batching은 리렌더링 주기에 밀접하게 관련되어 있으며, 변경 사항을 추적하고 업데이트 작업을 수행하는 시점은 주로 이벤트 루프의 틱(tick)이나 프레임의 시작과 끝에 배치됩니다. 이를 통해 가상 DOM은 최적의 업데이트 방식을 찾아내고, 변경 사항을 효율적으로 처리할 수 있습니다.

[이벤트 루프의 틱(Tick)이나 프레임(Frame)은 무엇인가요?](https://github.com/DataCodeLiteracy/Interview-Questions/blob/main/React/Tick%2CFrame.md)

# 미션 - 숫자 야구

### 구현할 기능목록

**3자리수 생성**

- [ ]  1에서 9까지의  서로 다른 수로 이루어진 3자리 숫자를 생성한다.

**사용자 입력**

- [ ]  사용자에게 중복없는 세자리 숫자를 입력 받는다

**야구 게임 진행**

- [ ]  랜덤 생성한 세자리 숫자와 사용자에게 입력받은 세자리 숫자를 비교한다.
- [ ]  같은 숫자가 같은 자리에 있을 때 스트라이크를 출력한다
- [ ]  같은 숫자이지만 다른 자리에 있을 때 볼을 출력한다
- [ ]  일치하는 숫자가 하나도 없을 경우 낫싱을 출력한다

예시:

```
낫싱

```

- [ ]  볼과 스트라이크과 동시에 있을 경우 볼 스트라이크 순서로 출력한다

예시:

```
1볼 1스트라이크

```

- [ ]  3개의 숫자를 모두 맞힐 경우 3스트라이크 와 게임 종료 메시지를 출력한다

예시:

```
3스트라이크
3개의 숫자를 모두 맞히셨습니다! 게임 종료

```

**게임 진행 & 종료-사용자 입력**

- [ ]  게임이 끝났을시 재시작 여부를  확인한다
    - [ ]  1이면 재시작, 2면 종료

### 예외처리

**3자리 숫자 입력 부분**

- [ ]  3자리 숫자가 아닌 경우
- [ ]  중복된 숫자가 들어가는 경우
- [ ]  0이 들어가는 경우

**재시작 여부 입력 부분**

- [ ]  1또는 2가 아니면 예외처리
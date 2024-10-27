# 자동차 경주 게임 🏎

## 구현 기능 목록

1. 자동차 이름 입력 및 검증

- 사용자로부터 쉼표(,)로 구분된 자동차 이름을 입력받는다.
- 이름은 5자 이하만 가능하고, 공백이 없어야 한다.
- 입력된 이름이 유효하지 않다면 [ERROR]로 시작하는 메시지를 출력하고 프로그램을 종료한다.

2. 자동차 객체 생성

- 유효한 이름 리스트로 { name, position: 0 } 형식의 자동차 객체를 생성하여 배열에 저장한다.

3. 시도 횟수 입력 및 검증

- 사용자가 시도 횟수를 입력한다.
- 입력된 시도 횟수가 정수이고 1 이상일 때만 유효하다고 판단한다.
- 유효하지 않은 시도 횟수일 경우 [ERROR]로 시작하는 메시지를 출력하고 프로그램을 종료한다.

4. 전진 조건 확인 및 이동

- 각 시도마다 모든 자동차에 대해 0에서 9 사이의 무작위 숫자를 생성한다.
- 숫자가 4 이상이면 해당 자동차의 position 값을 +1 한다.

5. 진행 결과 출력

- 각 시도 후 자동차들의 현재 상태를 출력한다.
- 자동차 이름과 position에 해당하는 - 문자를 함께 출력한다.
- 차수별로 각 자동차의 진행 상황을 줄바꿈하여 출력한다.

6. 우승자 판별

- position 값이 가장 큰 자동차(들)를 우승자로 선정한다.
- 공동 우승자가 있을 경우 쉼표로 구분하여 출력한다.
- 최종 우승자를 최종 우승자 : [이름1, 이름2...] 형식으로 출력한다.

7. 에러 핸들링

- 사용자 입력값에 대해 유효성 검사를 수행하고, 유효하지 않은 경우 [ERROR]로 시작하는 메시지와 함께 프로그램을 종료한다.

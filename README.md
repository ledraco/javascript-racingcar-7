# javascript-racingcar-precourse

# 🚗 자동차 경주

## 💡 핵심 기능 한 줄 정리
사용자로부터 **자동차 이름**과 **시도 횟수**를 **입력**받아, 주어진 횟수만큼 **자동차**들이 **경주**를 진행한 뒤 **우승자**를 판별하고 결과를 **출력**한다.

| **핵심 기능** | **명세** |
| --- | --- |
| 입력 | 사용자로부터 자동차 이름과 횟수를 입력받는다. |
| 자동차 | 자동차는 이름과 현재 위치(전진 횟수)를 가진다. 자동차는 무작위 값에 따라 전진 또는 멈출 수 있다. |
| 경주 | 주어진 횟수 동안 n대의 자동차가 전진 또는 멈출 수 있다. |
| 우승자 | 경주를 완료한 후 우승자를 판별한다. |
| 출력 | 각 차수별 결과를 출력하고, 우승자를 출력한다. |

## 구현 기능 목록

### 🌟 핵심 기능
- [x] 사용자로부터 형식에 맞춰 자동차 이름을 입력받는다.
- [x] 사용자로부터 형식에 맞춰 시도할 횟수를 입력받는다.
- [x] 자동차는 이름과 현재 위치(전진 횟수)를 가진다.
- [x] 자동차는 무작위 값에 따라 전진 또는 멈출 수 있다.
- [x] 주어진 횟수 동안 n 대의 자동차는 전진 또는 멈출 수 있다.
- [x] 차수별 결과를 출력한다.
- [x] 경주를 완료한 후 우승자를 판별한다.
- [x] 우승자를 출력한다.

### 🛠️ 입력 검증
- [x] 자동차 이름 입력은 공백일 수 없다.
- [x] 자동차 이름 입력에 쉼표(,) 이외의 특수문자, 공백은 입력될 수 없다.
- [x] 자동차 이름은 중복될 수 없다.
- [x] 자동차 이름 입력은 1~5자 이하의 문자로 구성되어야 하며, 쉼표(,)로 구분되어야 한다.
- [x] 시도 횟수 입력은 공백일 수 없다.
- [x] 시도 횟수 입력은 1 이상의 숫자를 입력해야 한다.

### 🩺테스트
  **입력 검증 함수 테스트**
  - [x] 자동차 이름 입력은 공백일 수 없다.
  - [x] 자동차 이름 입력에 쉼표( `,` ) 이외의 특수문자나 공백이 포함될 수 없다.
  - [ ] 자동차 이름은 중복될 수 없다.
  - [x] 자동차 이름 입력은 1~5자 이하의 문자로 구성되어야 하며, 쉼표(,)로 구분되어야 한다.
  - [x] 자동차 이름이 유효한 형식일 경우 에러를 발생시키지 않아야 한다.
  - [x] 시도 횟수 입력은 공백일 수 없다.
  - [x] 시도 횟수 입력은 1 이상의 숫자를 입력해야 한다.
  - [x] 시도 횟수 입력이 유효한 형식일 경우 에러를 발생시키지 않아야 한다.

  **사용자 입력 테스트**
  - [x] 유효한 자동차 이름을 입력하면 자동차 이름의 배열을 반환한다.
  - [x] 유효하지 않은 형식의 자동차 이름을 입력하면 에러를 발생시킨다.
  - [x] 유효한 시도 횟수를 입력하면 숫자를 반환한다.
  - [x] 유효하지 않은 형식의 시도 횟수를 입력하면 에러를 발생시킨다.
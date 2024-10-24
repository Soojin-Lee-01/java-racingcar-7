# 🔥 자동차 경주

## 과제 진행 요구 사항
- 미션의 시작은 '자동차 경주' 저장소를 포크하고 클론하는 것으로 시작한다.
- 기능 구현 전, README.md에 구현할 기능 목록을 정리한다.

## 기능 요구 사항

1️⃣ 입력값 처리
- 경주할 자동차 이름과 이동 횟수 n을 입력받는다.
- 자동차 이름을 쉼표 기준으로 구분하고, 공백을 제거한다.
- 구분된 자동차 이름이 각각 5글자 이하인지 확인한다.

2️⃣ 자동차 전진
- 각 자동차가 전진할 것인지, 멈출 것인지 무작위 값을 받는다.
- 만약, 무작위 값이 4이상일 경우에는 전진하고 아니라면 멈춘다.
- 실행 과정을 출력한다.

3️⃣ 우승자 출력
- 최대 전진한 자동차들을 구한다.
- 쉼표를 이용하여 구분하고 출력한다.

4️⃣ 예외 처리
- 사용자가 잘못된 값을 입력할 경우에는 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료한다.
- ex) 경주할 자동차 이름이 5글자 초과일 경우, n을 입력하지 않았을 경우

## 프로그래밍 요구 사항 1
- JDK 21 버전에서 실행 가능해야 한다.
- 프로그램 실행 시작점은 Application의 main()이다.
- build.gradle은 변경할 수 없고, 제공된 라이브러리 이외의 외부라이브러리는 사용하지 않는다.
- 프로그램 종료 시 System.exit()를 호출하지 않는다.
- 프로그래밍 요구 사항에서 달리 명시하지 않는 한 파일, 패키지 등의 이름을 바꾸거나 이동하지 않는다.
- 자바 코드 컨벤션을 지키면서 프로그래밍한다.

## 프로그래밍 요구 사항 2
- indent depth는 3이 넘지 않도록 구현해야 한다. 2까지만 허용한다.
- 3항 연산자를 사용하지 않는다.
- 함수 또는 메서드는 한 가지 일만 하도록 최대한 작게 만든다.
- Junit 5와 AssertJ를 이용하여 정리한 기능 목록이 정상적으로 작동하는지 테스트 코드로 확인한다.

## 최종 체크 리스트
- 변수명이 의미있는지 확인한다.
- 테스트 실패 시 또는 코드 변경 시, 수정한 내용은 의미있는 commit 메시지로 push 한다.
- 테스트 케이스를 추가해보자.
- 자바 객체 지향을 최대한 지키며 코드를 작성했는지 확인한다.
<구현할 기능 목록>



1. Car 클래스 정의
class Car {
  constructor(name) {
    자동차 이름 선언
    자동차 위치 초기화
  }

  2. 전진 조건 판단
  isForward() {
    0 ~ 9 사이의 정수 중 랜덤으로 한 개 반환
    랜덤 값이 4 이상일 경우 true 반환
  }

  3. 전진 메서드
  moveForward() {
    if true면 자동차 위치 증가
  }

} // car class 닫음

4. App 클래스 정의
class App {
  constructor() {
    자동차 객체 배열
    시도할 횟수
    우승자 배열
  }

  5. 게임 시작 메서드
  async play() {
    자동차 이름, 시도할 횟수 입력받기, 이름 유효한지 체크하기
    실행결과 출력
    게임 시작
    우승자 찾기, 우승자 출력
  }

  6. 게임 실행 메서드
  runGame() {
    차 전진
    차 출력
  }

  7. 우승자 찾기 메서드
  findWinners() {
    최대 위치 값 구하기
    최대 위치와 같은 자동차들을 우승자 배열에 추가
  }

  8. 우승자 출력 메서드
  showWinners() {
    우승자들의 이름 배열 찾기
    우승자들의 이름을 쉼표로 구분하여 출력
  }
} // App class 닫음

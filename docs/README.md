# 구현 기능 목록

---

### 1. 자동차 이름 입력, 세팅

* "경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)" 출력
* 입력 받기
  * [예외] 입력이 없는경우
  * [예외] 인력에 문자, 숫자, 쉼표 외에 다른 것이 들어온 경우
* 자동차 이름들을 리스트로 저장
  * [예외] 자동차 이름 길이가 0인경우
  * [예외] 자동차 이름 길이가 5자를 넘는경우
  * [예외] 같은 이름이 있는경우
* 예외발생 시 처음부터 실행

### 2. 시도 횟수 입력&세팅
* "시도할 횟수는 몇회인가요?" 출력
* 입력값 받기
  * [예외] 입력값이 없는경우
  * [예외] 입력값에 숫자 외에 다른 것이 들어온 경우
* 입력값을 정수로 저장
* 예외발생 시 처음부터 실행

### 3. 자동차 생성
* 자동차 이름 생성하기
* 자동차 이동거리 생성하기
* 자동차 전진함수 생성하기
  * 0에서 9사이에서 무작위 값을 구하기
  * 무작위 값이 4이상일 경우 이동거리 +1

### 4. 자동차 목록 생성
* 자동차 목록 생성하기 
* 자동차 목록에 자동차 추가하기
* 모든 자동차 라운드 결과 알려주는 함수 생성하기
* 우승자 목록 알려주는 함수 생성하기

### 5. 레이싱 게임 실행
* 자동차 목록 생성
  * 자동차 생성
* 차수 수 만큼 반복
  * 자동차 전진시키기
  * 차수별 실행 결과 출력
* 우승자 목록 생성
  * 우승자 목록 출력
    * 우숭자가 한명일 경우 그대로 출력
    * 우승자가 여러명일 경우 쉼표(,)를 이용하여 구분해 출력

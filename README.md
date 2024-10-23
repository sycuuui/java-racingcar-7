# 과제2 - 자동차 경주
## 구현 기능 목록
<hr>

### 입력
- 경주할 자동차 이름 입력
    - camp.nextstep.edu.missionutils.Console의 readLine()활용
    - 쉼표(,) 기준으로 구분
    - 이름은 1~5자 조건 판단
      - 이름이 0 또는 5자 초과할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료
    - 이름마다 참가자 객체 생성 
    - 참가자 객체 배열 생성

- 시도할 횟수 입력

### 자동차 경주 게임
1. 사용자가 입력한 시도할 횟수만큼 게임 진행
2. 참가자마다 0~9까지 무작위 값 부여
   - camp.nextstep.edu.missionutils.Randoms의 pickNumberInRange()활용
   - 값이 4이상일 경우에만 전진
     - 전진인 경우 참가자 거리 업데이트

3. 게임 종료 후 전진한 거리  우승자 추출

### 출력
- 각 실행 결과 출력
    - 참가자마다 전진한 횟수 출력
- 우승자 출력
    - 여러 명일 경우 쉼표(,)로 구분
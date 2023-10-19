# 구현 해야할 기능 목록

- [ ] 숫자 입력 전에 미리 컴퓨터가 랜덤한 숫자 3개 선택
  - Random.pickNumberInRange() 활용
- [ ] 숫자 입력 (아예 최초 시작이라면 `숫자 야구 게임을 시작합니다.`라는 멘트가 나와야 함)
  - [ ] 잘못된 값(문자, 3개의 숫자가 아닌 값 등)을 입력하면 `throw`문을 사용해 예외를 발생시키고 종료
- [ ] 스트라이크, 볼, 낫싱을 판단하고 결과를 출력
  - [ ] 맞출 때까지 반복
  - [ ] 맞추면 게임을 다시 시작할 지(1), 완전히 종료할 지(2) 선택
    - 여기서 숫자를 또 입력 받아야 함
    - ```
      멘트
      3개의 숫자를 모두 맞히셨습니다! 게임 종료
      게임을 새로 시작하려면 1, 종료하려면 2를 입력하세요.
      ```
  - [ ] 못맞추면 스트라이크, 볼, 낫싱 중 하나를 출력하고 숫자를 재입력 받아야 함
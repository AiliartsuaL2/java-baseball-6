### 기능 요구사항
- 최초 출력
    - 숫자 야구 게임을 시작합니다.
- 반복
    - 사용자 입력 유도용 문구 출력
        - 숫자를 입력해주세요 :
    - 사용자 입력시 출력
        - 잘못된 값 입력시 IllegalArgumentException 후 애플리케이션 종료
        - 힌트 제공
            - 같은 수가 같은 자리에 있으면 스트라이크, 다른 자리에 있으면 볼
            - 같은 수가 전혀 없으면 낫싱
            - ex : n볼 n스트라이크
        - 정답인 경우
            - 3개의 숫자를 모두 맞히셨습니다! 게임 종료
            - 게임을 새로 시작하려면 1, 종료하려면 2를 입력하세요.
- 종료
    - 정답 이후 사용자 2 입력 > 반목문 종료 > 어플리케이션 종료.

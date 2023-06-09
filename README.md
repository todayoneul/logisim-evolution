# Logisim-Evolution -> Time-limited Tic-Tac-Toe
digital - logic (2023 project) - Time-limited Tic-Tac-Toe

시간제한이 있는 Tic-Tac-Toe 시뮬레이터입니다.

# Poster
![image](https://github.com/todayoneul/logisim-evolution/assets/104894811/cc30466b-862f-404e-8c9e-0750bef8f976)

프로젝트의 컨셉과 참고 회로는 poster를 참고하세요.



[Time-limited Tic-Tac-Toe - 22100757 이규한.pdf](https://github.com/todayoneul/logisim-evolution/files/11704122/Time-limited.Tic-Tac-Toe.-.22100757.pdf)

# How to play
다음은 구현 영상입니다.

https://youtu.be/MyAw0jT6R6U


- 구현 영상을 글로 정리하면 아래와 같습니다.
- 1. downcounter창으로 이동해 clock을 작동시킨다.
- 2. 다시 main창으로 돌아와 restet 버튼으로 이전 게임의 저장상태를 초기화시킨다.
- 3. GAME_START 스위츠를 내려 비활성화 시키면 새로운 게임이 시작된다.
- 4. 오른쪽 timer 의 time out이 0이 되는 순간 다른 player에게 순서가 넘어간다.
- 5. 버튼을 눌러 한줄의 빙고를 먼저 맞추는 player가 이긴다.
- clock은 downcounter 창에서 작동시킬 수 있으며, Auto-tick Frequency에 더 빠른 시간내에 공격권이 상대에게 넘어가므로 난이도가 상승한다.

#### tmux 사용법

##### 세션 관리
- `tmux`: 새로운 tmux 세션 시작
- `tmux new-session -s 세션_이름`: 새 세션 시작
- `tmux list-sessions`: 현재 세션 목록 보기
- `tmux attach-session -t 세션_이름`: 기존 세션에 다시 연결

##### 창 관리
- `Ctrl-b c`: 새 창 생성
- `Ctrl-b ,`: 창 이름 변경
- `Ctrl-b n`: 다음 창으로 이동
- `Ctrl-b p`: 이전 창으로 이동
- `Ctrl-b 0-9`: 특정 번호의 창으로 이동
- `Ctrl-b l`: 최근에 사용한 창으로 이동

##### 창 분할
- `Ctrl-b %`: 수직 분할
- `Ctrl-b "`: 수평 분할
- `Ctrl-b o`: 다음 패널로 이동

##### 패널 관리
- `Ctrl-b 화살표키`: 패널 사이 이동
- `Ctrl-b {`: 현재 패널을 왼쪽 패널과 교체
- `Ctrl-b }`: 현재 패널을 오른쪽 패널과 교체
- `Ctrl-b z`: 현재 패널 전체 화면으로 확대/축소

##### 기타 명령어
- `Ctrl-b d`: tmux 세션 떠나기 (백그라운드로 전환)
- `tmux ls`: 실행 중인 세션 목록 표시
- `tmux attach -t 세션_이름`: 특정 세션에 다시 연결
- `tmux kill-session -t 세션_이름`: 세션 종료

##### 도움말 보기
- `Ctrl-b ?`: tmux 단축키 목록 표시

<br>
<br>

![new-york-city-edted](https://github.com/ImKunYoung/ImKunYoung/assets/46955032/14779003-8189-41a7-835d-421d6a697422)





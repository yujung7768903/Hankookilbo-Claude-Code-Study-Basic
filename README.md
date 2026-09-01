# Claude Code 설치 가이드

비개발자를 위한 **Claude Code · Git 설치 가이드**입니다. 터미널 여는 법부터 로그인까지 다룹니다.

## 보기

**https://yujung7768903.github.io/Hankookilbo-Claude-Code-Study-Basic/**

상단 탭으로 **Windows**(12장)와 **macOS**(11장)를 오갈 수 있습니다.

## 내용

| | Windows | macOS |
|---|---|---|
| 터미널 | Win + X → 터미널 (PowerShell 기준) | ⌘ Space → 터미널 |
| Git | `winget install --id Git.Git -e` | `git --version` 확인 후 필요 시 설치 |
| Claude Code | `irm https://claude.ai/install.ps1 \| iex` | `curl -fsSL https://claude.ai/install.sh \| bash` |
| 관리자 권한 | Git 설치 시 승인 창 1회 | 불필요 (sudo 사용 금지) |

설치 직후 `claude --version` 이 동작하지 않는 경우(터미널을 껐다 켜야 하는 문제)와 그때의 문제 해결 순서를 각각 한 장씩 다룹니다.

## PDF로 뽑기

브라우저에서 인쇄(⌘P / Ctrl+P) → **배경 그래픽** 체크 → 저장하면 1000×563 슬라이드가 한 장씩 떨어집니다. 인쇄 시 탭 바는 빠지고 **현재 보고 있는 덱만** 출력되므로, 둘 다 필요하면 탭을 바꿔 두 번 인쇄하세요.

## 참고

- 화면 그림은 실제 캡처가 아니라 재현한 예시이며, 각 그림에 `화면 예시`로 표시돼 있습니다.
- macOS 설치 확인 화면(07쪽)의 출력값은 실제 실행 결과입니다.
- 버전 숫자는 계속 올라가므로 자료와 다르게 보이는 것이 정상입니다.

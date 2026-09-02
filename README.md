# 비개발자 대상 Claude Code 스터디

강의자료와 설치 방법을 한 페이지에 모은 사내 스터디 자료입니다.

## 보기

**https://yujung7768903.github.io/Hankookilbo-Claude-Code-Study-Basic/**

상단 탭으로 **강의자료**(23장) · **설치방법-Windows**(12장) · **설치방법-macOS**(11장)를 오갈 수 있습니다.

## 강의자료

| | 내용 |
|---|---|
| 강의 35분 | ① 채팅과 뭐가 다른가 ② 뭘 할 수 있을까? ③ 내 Claude는 왜 말을 안 들을까? ④ UI를 여러 번 수정해야 할 땐 |
| 실습 85분 | ① 터미널 기초 명령어 ② Claude Code 기본 명령어 → 실습 1·2·3 |
| 참고 | 알아두면 좋은 개념(MCP·SKILL·플러그인) · 스킬 예시 · Confluence MCP 연결 |
| 번외 | 코드 분석용 `~/.claude.md` · 작업용 대시보드 |

## 설치 방법

| | Windows | macOS |
|---|---|---|
| 터미널 | Win + X → 터미널 (PowerShell 기준) | ⌘ Space → 터미널 |
| Git | `winget install --id Git.Git -e` | `git --version` 확인 후 필요 시 설치 |
| Claude Code | `irm https://claude.ai/install.ps1 \| iex` | `curl -fsSL https://claude.ai/install.sh \| bash` |
| 관리자 권한 | Git 설치 시 승인 창 1회 | 불필요 (sudo 사용 금지) |

설치 직후 `claude --version` 이 동작하지 않는 경우(터미널을 껐다 켜야 하는 문제)와 그때의 문제 해결 순서를 각각 한 장씩 다룹니다.

## PDF로 뽑기

브라우저에서 인쇄(⌘P / Ctrl+P) → **배경 그래픽** 체크 → 저장하면 1000×563 슬라이드가 한 장씩 떨어집니다. 인쇄 시 탭 바는 빠지고 **현재 보고 있는 탭만** 출력되므로, 여러 개가 필요하면 탭을 바꿔 그만큼 인쇄하세요.

## 참고

- 설치 방법의 화면 그림은 실제 캡처가 아니라 재현한 예시이며, 각 그림에 `화면 예시`로 표시돼 있습니다. 강의자료의 스크린샷은 실제 캡처입니다.
- macOS 설치 확인 화면(07쪽)의 출력값은 실제 실행 결과입니다.
- 터미널 기초 명령어는 **PowerShell 기준**으로 맞췄습니다. PowerShell에서 `cd` 만 입력하면 현재 위치가 출력되는 게 아니라 홈 폴더로 이동합니다([Set-Location 문서](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/set-location)). 현재 위치는 `pwd` 로 확인합니다.
- 버전 숫자는 계속 올라가므로 자료와 다르게 보이는 것이 정상입니다.

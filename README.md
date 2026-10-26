# 오솔길 (OSOGIL) — Pixel Arcade

직접 제작한 웹게임들을 모아 보여주는 레트로 네온 아케이드 게임 포털입니다.

## 현재 버전: v0.5

- 반응형 PC/모바일 화면
- 게임 카드, 메인 배너, 검색, 장르별 필터, 즐겨찾기
- 게임 상세 보기 및 실제 게임 링크
- DICE ARENA와 WHO AM I? 정식 게임 링크 활성화, 4개 게임 모두 플레이 선택 가능
- CSS, JS, 픽셀아트 이미지가 포함된 **단일 index.html** (별도 서버와 빌드 불필요)

## 등록 게임

| 게임 | 상태 | 링크 |
| --- | --- | --- |
| BATTLESHIP — Naval Command | 기존 게임 연결 | https://battleship-naval-command.onrender.com |
| QUIZ ARENA 15 | 기존 게임 연결 | https://quiz-arena-15-online.onrender.com |
| DICE ARENA | 정식 플레이 링크 | https://dice-arena-online.onrender.com |
| WHO AM I? | 정식 플레이 링크 | https://who-am-i-wixa.onrender.com |

> 위 Render 주소는 코드에 등록된 링크이며 **실제 서버 가동/접속 상태를 보증하지 않습니다**. 별도로 확인해야 합니다. 무료 서비스가 절전 모드에서 깨어나는 동안 최초 접속에 시간이 걸릴 수 있습니다.

## GitHub Pages로 공개하기

1. GitHub 저장소 **Settings → Pages**로 이동합니다.
2. **Build and deployment → Source: Deploy from a branch** 를 선택합니다.
3. **Branch: main**, **Folder: /(root)** 를 지정하고 **Save** 합니다.
4. GitHub Pages 배포가 완료되면 다음 주소에서 페이지가 열립니다.
   https://real1031001.github.io/Osolgil/

**주의:** 저장소 이름이 `Osolgil`이므로 URL 경로의 대문자 O를 유지하세요.

향후 저장소가 비공개로 바뀐다면 GitHub Free에서는 **Settings → General → Danger Zone → Change repository visibility → Public** 전환 후 Pages를 사용할 수 있습니다. GitHub Pro 등 일부 유료 플랜은 비공개 저장소에서도 Pages를 사용할 수 있습니다.

사이트는 정적이며 기존 게임 서버, 정답 데이터 및 로비 코드는 변경하지 않습니다. 방문자 로그인, 공통 랭킹, 유료 상점 등은 아직 구현되지 않았습니다.

## 파일 구성

- `index.html` : 완전한 포털 웹페이지
- `README.md` : 배포 및 프로젝트 설명
- `.github/workflows/quality.yml` : 최소 HTML 파일 검증

## 향후 작업

- 실제 배포 URL 열림 확인
- 외부 게임 서버 링크 실제 플레이 확인
- 게임별 대표 화면 및 공지 콘텐츠 업데이트
- 신규 게임 추가 및 UI 확장

Copyright © OSOGIL.
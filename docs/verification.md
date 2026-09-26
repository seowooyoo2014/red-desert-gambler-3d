# 실행 검증

2026-09-25 로컬 복사본 기준. 전체 캠페인 검증 결과가 아닙니다.

## 확인됨

- 정적 빌드 성공. 새 게임 선택과 도입 컷신 표시 확인. Three.js 및 BufferGeometryUtils 모듈을 로컬 경로로 연결.
- `python3 tools/build_site.py` 완료. 배포 대상 HTML의 로컬 파일 경로 점검에서 누락 없음.

- 깨끗한 Git worktree checkout에서 `python3 tools/build_site.py`가 성공하고 `dist/index.html`이 생성됨.

## 아직 확인 필요

- 탐험·도박 진행, 저장·재시작은 아직 확인하지 못함.


## 공개 배포 확인 (2026-09-26)

GitHub Actions 배포 성공. 공개 주소에서 새 게임, 도입 이야기 진행, 여정 화면, Space로 오아시스 진입과 낚싯대 던지기를 확인했습니다. 브라우저 콘솔 오류·경고는 기록되지 않았습니다. 전체 결투·엔딩과 저장 복원은 미검증입니다.

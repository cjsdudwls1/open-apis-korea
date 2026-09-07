# RunAway (가제)

- 러닝 AR 추격 게임 + 운동 앱
- 지도 위 실제 지형에 배치된 가상 추격자를 피해, 앱이 지정한 목적지까지 타임어택으로 달림

## 상태

- 단계: PRD 작성 전, 결정 사항 수집 중
- 다음 할 일: `docs/prd/00-questionnaire.md` 질문에 답하기 (P0부터)

## 문서

| 파일 | 내용 |
|---|---|
| docs/prd/00-idea.md | 원본 아이디어 |
| docs/prd/00-questionnaire.md | PRD 질문지. 우선순위(P0/P1/P2), 선택지, 추천 기본값 |
| docs/prd/01-research.md | 경쟁사, 기술, 법률/안전 리서치 |
| docs/prd/02-prd.md | (예정) PRD |

## 핵심 컨셉

- 지도 위에 내 위치 표시
- 가상 적이 실제 도로망 위에서 추격
- 제한 시간 안에 지정 목적지 도착
- 난이도 = 추격자 종류 (치와와 느림, 사자 매우 빠름)
- 음성 생성 AI 내레이션으로 긴박감
- 리더보드 경쟁, 워치/스마트 글래스 지원

## 레포 이름 변경

- API로 불가. GitHub에서 수동 변경
- 경로: Settings > General > Repository name > Rename
- 옛 URL은 자동 리다이렉트
- 로컬 원격 주소 갱신:

```bash
git remote set-url origin https://github.com/cjsdudwls1/<새-이름>.git
```

- 추천 이름과 대안: 질문지 NAM 섹션 참고

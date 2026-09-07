# RunAway (가제) — 쫓기며 달리는 러닝 AR 게임

> **"달려서 도망쳐."** 지도 위 실제 지형에 배치된 가상의 추격자(좀비, 사자, 치와와…)를 피해, 앱이 지정한 목적지까지 타임어택으로 달리는 러닝 게임 + 운동 앱.

## 상태

- **단계:** PRD(제품 요구사항 문서) 작성 전, 결정 사항 수집 중
- **다음 할 일:** [`docs/prd/00-questionnaire.md`](docs/prd/00-questionnaire.md)의 질문에 답하기 (P0부터)

## 문서

| 파일 | 내용 |
|---|---|
| [docs/prd/00-idea.md](docs/prd/00-idea.md) | 원본 아이디어(원문 보존) |
| [docs/prd/00-questionnaire.md](docs/prd/00-questionnaire.md) | PRD 작성을 위한 질문지. 우선순위(P0/P1/P2)·선택지·추천 기본값 포함 |
| [docs/prd/01-research.md](docs/prd/01-research.md) | 경쟁사·기술·법률/안전 사전 리서치 노트 |
| `docs/prd/02-prd.md` | (예정) 질문 답변을 바탕으로 작성될 PRD |

## 핵심 컨셉 (아이디어 단계)

1. 지도 위에 내 위치가 보인다.
2. 가상의 적들이 실제 도로망 위에 배치되어 나를 쫓아온다.
3. 적을 피해 앱이 지정한 목적지까지 제한 시간 안에 도착해야 한다.
4. 난이도는 추격자 종류로 표현한다. 치와와(느림) → … → 사자(매우 빠름).
5. 음성 생성 AI로 만든 긴박한 내레이션이 러닝을 몰아붙인다.
6. 리더보드로 경쟁하고, 워치·스마트 글래스에서도 동작한다.

## 레포 이름

이 레포는 원래 `open-apis-korea`였고 새 프로젝트로 전환 중입니다. GitHub 레포 이름 변경은 API로 할 수 없어 수동으로 해야 합니다.

GitHub → 레포 **Settings** → **General** → **Repository name** → 새 이름 입력 → **Rename**. 옛 URL은 GitHub가 자동으로 리다이렉트합니다. 변경 후 로컬 클론에서는 아래처럼 원격 주소를 바꿔 주세요.

```bash
git remote set-url origin https://github.com/cjsdudwls1/<새-이름>.git
```

추천 이름과 대안은 질문지의 **NAM(네이밍)** 섹션을 참고하세요.

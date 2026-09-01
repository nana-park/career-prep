# Career Prep

AI PM 취업준비의 운영 원칙과 반복 워크플로를 관리하는 저장소입니다. 개별 실행 능력은 별도의 [`skills`](https://github.com/nana-park/skills) 저장소에서 관리하고, 이 저장소는 어떤 상황에서 어떤 스킬과 소스를 사용할지 조정합니다.

## 역할 분리

- `career-prep`: 취업준비 원칙, 소스 정책, 스킬 라우팅, 반복 작업 정의
- `skills`: 여러 도메인에서 재사용 가능한 개별 Codex 스킬
- Notion: 공고, 지원 상태, 일정의 운영 데이터
- Google Drive: 경력·프로젝트 원본
- 로컬 취업준비 폴더: 작업본, 제출본, 분석 결과

## 문서

- [기본 원칙](./docs/PRINCIPLES.md)
- [스킬 라우팅](./docs/SKILL_ROUTING.md)
- [스킬 의존성](./skills.yaml)
- [소스 연결 설정 예시](./sources.example.yaml)
- [Work 히스토리 조회 규칙](./docs/WORK_HISTORY.md)
- [소스 원장 예시](./source-ledger.example.yaml)

## 사용 방식

1. 요청이 사용자 경험에 관한 것인지, 공고 시장 분석인지, 특정 지원서 작성인지 분류합니다.
2. [스킬 라우팅](./docs/SKILL_ROUTING.md)에 따라 필요한 스킬만 불러옵니다.
3. 경험 사실이 필요하면 Drive 원문을 읽고, 공고 분석이면 Notion DB를 읽습니다.
4. 원본과 개인 데이터는 이 저장소에 복사하지 않습니다.

## 로컬 소스 연결

`sources.example.yaml`을 구조 기준으로 사용하고, 실제 URL과 프로젝트 식별자는 Git에서 제외되는 `sources.local.yaml`에 둡니다. 작업을 시작할 때 `sources.local.yaml`이 있으면 이 파일을 우선 읽습니다.

Work 프로젝트의 과거 대화는 매번 읽지 않습니다. [Work 히스토리 조회 규칙](./docs/WORK_HISTORY.md)에 따라 현재 입력으로 부족할 때만 관련 대화를 확인하고, 조회 결과의 최신성은 Git에서 제외되는 `source-ledger.local.yaml`로 관리합니다.

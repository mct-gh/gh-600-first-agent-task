## 정리

에이전트에게 일을 맡기고, 계획을 검토하고, 승인해서 머지했습니다.
한 바퀴를 다 돈 것입니다.

### 무엇을 했나

| 단계 | 수명 주기 | 남은 증거 |
| --- | --- | --- |
| 이슈 할당 | Plan | 에이전트가 만든 계획과 draft PR 설명 |
| 에이전트 작업 | Act | `copilot/` 브랜치와 커밋 |
| 리뷰와 머지 | Evaluate | 리뷰 기록, 체크 결과, 머지 커밋 |

이 세 가지가 GitHub 에 그대로 남습니다. 그래서 GitHub 을 에이전트의
**system of record** 이자 **control plane** 이라고 부릅니다.
일이 벌어진 기록이 남는 곳이자, 무엇을 허용할지 강제하는 곳입니다.

### 꼭 기억할 것

- 도우미는 제안하고 멈춘다. 에이전트는 목표를 유지하며 지속되는 결과물을 만든다
- 에이전트는 워크플로를 대체하지 않는다. 참가자로 들어온다
- 에이전트는 `copilot/` 브랜치에 draft PR 을 **자동으로** 연다. 하지만 머지는 자동이 아니다
- 책임은 실행과 함께 옮겨가지 않는다. 작업을 정의하고 권한을 정하고 승인한 사람이 책임진다
- 기여자 모델 여섯 항목 — Intent, Scope, Evidence, Ownership, Policy, Fallback

### 최소 감사 추적 여섯 가지

에이전트 기여에는 이만큼이 남아야 합니다. 하나라도 없으면 나중에 무슨 일이
있었는지 재구성할 수 없습니다.

1. 목표 (이슈 링크 또는 PR 설명)
2. 검토 가능한 계획
3. 범위가 한정된 변경 (브랜치와 커밋)
4. 자동 증거 (워크플로 실행과 아티팩트)
5. 사람의 판단 (리뷰와 승인)
6. 명확한 결과 (머지, 되돌림, 또는 에스컬레이션)

### 시험에서는

이 실습은 **영역 1 — 에이전트 아키텍처 및 SDLC 프로세스 준비 (15~20%)** 에 해당합니다.

관련 문항 유형
- 에이전트가 수행할 단계를 식별한다
- 에이전트의 입력, 출력, 성공 기준을 정의한다
- 흔한 안티패턴을 찾아 완화한다
- 자율 에이전트에 사람의 개입을 어디에 둘지 정한다

### 더 볼 것

- [Foundations of Agentic AI in GitHub](https://learn.microsoft.com/ko-kr/training/modules/foundations-agentic-ai/)
- [Copilot cloud agent 소개](https://docs.github.com/ko/copilot/concepts/agents/cloud-agent/about-cloud-agent)
- [GH-600 시험 학습 가이드](https://learn.microsoft.com/ko-kr/credentials/certifications/resources/study-guides/gh-600)

### 다음 실습

**[실습 2 — 계획 게이트와 도구 경계](https://github.com/mct-gh/gh600-plan-gate)**

이번에는 계획이 없는 PR 이 아예 머지되지 못하도록 시스템으로 막아 봅니다.

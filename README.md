# 실습 1 — 에이전트에게 첫 일을 맡긴다

_이슈 하나를 Copilot cloud agent 에게 넘기고, 계획을 검토하고, 승인해서 머지합니다._

## 이 실습에 대하여

- **대상**: GitHub 은 써봤지만 AI 에이전트에게 실제로 작업을 맡겨 본 적이 없는 분
- **배우는 것**: 도우미와 에이전트의 차이, plan → act → evaluate 수명 주기,
  기여자 모델로 에이전트 결과물을 평가하는 법
- **만드는 것**: 에이전트가 작성한 Pull Request 하나와 그것을 검토한 기록
- **필요한 것**:
  - GitHub 계정
  - **Copilot 유료 플랜** (Pro, Pro+, Max, Business, Enterprise). Free 로는 진행할 수 없습니다
  - 조직 계정이면 관리자가 cloud agent 정책을 켜 두어야 합니다
- **소요 시간**: 20분

진행 순서

1. 이슈를 Copilot 에게 할당하고 에이전트가 계획을 세우는 것을 지켜본다
2. 에이전트가 연 draft Pull Request 의 계획을 기여자 모델로 검토한다
3. 승인하고 머지해서, 결정은 사람이 내린다는 경계를 확인한다

## 시작하는 법

아래 버튼으로 이 실습을 여러분 계정에 복사한 뒤, **20초 정도** 기다렸다가
페이지를 **새로고침** 하세요. 첫 단계 안내가 담긴 이슈가 만들어집니다.

[![](https://img.shields.io/badge/Copy%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=mct-gh&template_name=gh600-first-agent-task&owner=%40me&name=gh600-first-agent-task&description=GH-600+Lab+A+-+Assign+your+first+task+to+Copilot&visibility=public)

<details>
<summary>문제가 있나요? 🤷</summary><br/>

복사할 때 권장하는 설정입니다.

- 소유자는 개인 계정 또는 여러분이 관리하는 조직을 고르세요.
- **공개(public)** 로 만드는 것을 권장합니다. 비공개는 Actions 사용 시간이 차감됩니다.

20초 뒤에도 준비되지 않으면 [Actions](../../actions) 탭을 확인하세요.

- 작업이 실행 중일 수 있습니다. 조금 더 걸리기도 합니다.
- 실패한 작업이 보이면 강사에게 알려주세요.

</details>

> [!IMPORTANT]
> **Fork 하지 마세요.** 위 Copy Exercise 버튼을 눌러야 채점이 동작합니다.
> 그리고 `.github/workflows` 안의 파일은 수정하지 마세요. 실습이 멈춥니다.

## 시험 대응

**영역 1 — 에이전트 아키텍처 및 SDLC 프로세스 준비 (15~20%)**

## 관련 학습 자료

- [Foundations of Agentic AI in GitHub](https://learn.microsoft.com/ko-kr/training/modules/foundations-agentic-ai/)
- [GH-600 학습 가이드](https://learn.microsoft.com/ko-kr/credentials/certifications/resources/study-guides/gh-600)
- [실습 모음으로 돌아가기](https://github.com/mct-gh/gh-600-labs)

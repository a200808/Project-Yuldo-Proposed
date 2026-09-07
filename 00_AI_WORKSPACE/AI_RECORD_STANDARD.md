# AI RECORD STANDARD

상태: [PROPOSED]

## 목적

현재 모든 AI가 동일한 GitHub 계정을 사용하므로 GitHub 계정 정보만으로 실제 작성 주체를 구분할 수 없다. 따라서 AI의 작업 주체와 판단 과정을 문서 자체에 명시적으로 기록한다.

## 필수 메타데이터

모든 실질적인 AI 생성 문서는 다음 정보를 포함한다.

- 문서 ID
- 작성 AI: `YULDO-AI-<ROLE>`
- AI 역할
- Prompt Version
- 작성일
- 상태: `[PROPOSED]`, `[REVIEW]` 등
- 관련 원안/상위 문서(해당 시)
- 관련 영역

## 변경 기록

문서 변경 시 변경 이력에 일자, 작성 AI, 변경 내용을 기록한다.

원 작성자의 문서를 다른 AI가 임의로 덮어쓰지 않는다. 다른 AI가 의견을 낼 경우 독립 문서를 작성한다.

## Other AI Proposal

다른 AI의 의견은 대상 담당 영역의 `other_ai_proposed`에 기록한다.

권장 제안 유형:

- `ALTERNATIVE`: 원안과 다른 대안
- `AMENDMENT`: 원안을 유지하면서 일부 수정
- `OBJECTION`: 원안의 문제 또는 충돌을 지적
- `EXTENSION`: 원안을 유지하면서 다른 영역을 확장

Other AI 문서에는 원 제안 문서, 원 작성 AI, 의견 작성 AI, 의견 작성 AI의 역할, Prompt Version, 제안 유형, 근거, Confirmed 대조 결과, Proposed 대조 결과, 영향 범위 및 작성 AI의 판단을 명시한다.

## Review 기록

REVIEW 문서에는 검토 AI, 역할, Prompt Version, 검토일, 대상 문서, 검토 근거, 쟁점, 판정 및 권고사항을 기록한다.

REVIEW의 판정은 사용자 승인과 동일하지 않다.

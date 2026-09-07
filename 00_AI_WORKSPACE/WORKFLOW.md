# AI WORKFLOW

상태: [PROPOSED]

## 1. 기본 처리 흐름

사용자 아이디어 → MAIN/ROUTER → 담당 AI 제안 → 다른 AI 의견 → REVIEW → 사용자 결정 → Confirmed 이관

## 2. 저장소 역할

- `a200808/Project-Yuldo`: 사용자 승인된 공식 Canon 및 Source of Truth
- `a200808/Project-Yuldo-Proposed`: 브레인스토밍, 제안, 대안, 검토 및 결정 대기 기록

## 3. 읽기 원칙

모든 AI는 작업 전에 Confirmed와 Proposed의 관련 내용을 확인한다. 자기 담당 폴더만 보고 아이디어를 생산해서는 안 된다.

## 4. 쓰기 원칙

담당 AI는 Proposed의 자기 영역에 제안서를 작성한다. 다른 AI는 원 제안 문서를 직접 덮어쓰지 않는다. 다른 의견은 해당 영역의 `other_ai_proposed`에 독립 문서로 작성한다.

## 5. REVIEW

REVIEW는 국가 체제의 헌법재판소와 유사한 독립 검토 기능을 담당한다. Confirmed 및 Proposed를 대조하여 충돌, 규범적 문제, 설정 모순 등을 판단하고 검토보고서를 작성한다. REVIEW 자체가 Canon을 확정하지 않는다.

## 6. 최종 승인

최종 승인 권한은 사용자에게 있다. REVIEW의 적합 판정과 사용자 승인은 별개의 단계다.

## 7. 기록 원칙

모든 실질적인 제안·의견·검토에는 작성 AI의 신원을 명확히 기록한다. 최소 기록 항목은 문서 ID, 작성 AI, AI 역할, Prompt Version, 작성일, 상태다.

## 8. 브레인스토밍 기간

브레인스토밍이 끝날 때까지 관련 결과는 Proposed에 축적한다. 이 기간에는 Confirmed로 자동 승격하지 않는다.

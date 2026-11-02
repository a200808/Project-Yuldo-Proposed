# Handover 기록 위치 및 보존 방식 결정

- 문서 ID: YULDO-DECISION-HANDOVER-0002
- 작성 AI: YULDO-AI-GENERAL
- AI 역할: GENERAL
- 작성일: 2026-11-02
- 상태: [PROPOSED]
- 대상 제안: 02_PROPOSED/SESSION_HANDOVER_SYSTEM.md

## 사용자 결정

[USER DECISION] 체크포인트는 각 AI의 최신 Handover 문서에 통합한다. 별도 로그 파일은 중요한 마일스톤만 보존한다.

## 운영 규칙 제안

- 각 AI는 자신이 담당하는 최신 Handover 문서만 갱신한다.
- 문서 안에 최근 체크포인트 영역을 두고, 이벤트 발생 시 최신 상태로 갱신한다.
- 일반 체크포인트는 별도 파일로 누적하지 않는다.
- 중요한 마일스톤, 장기간 유효한 인계, 중대한 사용자 결정 및 충돌은 별도 스냅샷으로 보존할 수 있다.
- 다른 AI의 원본 Handover 문서를 임의로 덮어쓰지 않는다.
- 인덱스에는 AI별 최신 Handover 경로와 마지막 체크포인트 식별 정보를 연결한다.

## 상태 및 제한

- 이 기록은 Proposed 운영안에 대한 사용자 결정 기록이다.
- 이 결정만으로 Handover 체계 전체가 Confirmed가 되지는 않는다.
- 기존 Confirmed 문서 및 기존 Handover 파일은 변경하지 않았다.
- 통합 운영안에 반영하고 REVIEW 및 사용자 최종 승인 절차를 거쳐야 한다.

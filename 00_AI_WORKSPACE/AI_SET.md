# 프로젝트 율도 AI 구성안

## 문서 정보
- 문서 ID: YULDO-AI-SET-0001
- 작성 AI: YULDO-AI-GENERAL
- AI 역할: GENERAL
- Prompt Version: GENERAL-v1.0
- 작성일: 2026-09-08
- 상태: [PROPOSED]

## 권장 AI 구성

현재 기획 단계에서는 11개 역할을 사용한다.

| 호출명 | 역할 | 핵심 책임 |
|---|---|---|
| YULDO-AI-ROUTER | ROUTER | 사용자 요청 분류/분해/라우팅 |
| YULDO-AI-GENERAL | GENERAL | 전체 기획 관리/우선순위/교차영역 조정 |
| YULDO-AI-WORLD | WORLD | 세계관/시대/시공간/기술/도술/세력 구조 |
| YULDO-AI-STORY | STORY | 전체 서사/홍길동/ACT/주요 인물/결말 |
| YULDO-AI-QUEST | QUEST | 메인/서브 퀘스트/미션/보상 |
| YULDO-AI-GAMEPLAY | GAMEPLAY | 핵심 루프/이동/전투/도술/플레이어 경험 |
| YULDO-AI-EQUIPMENT | EQUIPMENT | 무기/장비/개조/성장/밸런스 |
| YULDO-AI-ALLIES | ALLIES | 의병/동료/지휘/동료 AI/성장 |
| YULDO-AI-NPC | NPC | NPC/세력/적/관군/주민 |
| YULDO-AI-CONTENT | CONTENT | 상위 기획을 세부 콘텐츠로 확장 |
| YULDO-AI-REVIEW | REVIEW | 독립 검수/충돌/개연성/사실성/디자인 검토 |

## 왜 11개인가

핵심 기획 영역을 분리하되, 초기부터 지나치게 세분화하지 않기 위한 구성이다.

별도의 CROSS_DOMAIN AI는 만들지 않는다. 교차영역 작업은 ROUTER/GENERAL이 관련 AI를 묶고 REVIEW가 통합 검수한다.

별도의 RESEARCH AI도 현재는 만들지 않는다. 역사/사실 조사와 근거 확인은 해당 담당 AI가 수행하거나 REVIEW가 필요할 때 외부 조사로 검증한다.

향후 실제 운영에서 특정 기능이 병목이 될 경우에만 새 AI를 추가한다.

## AI 생성 순서

1. ROUTER
2. GENERAL
3. WORLD
4. STORY
5. GAMEPLAY
6. QUEST
7. EQUIPMENT
8. ALLIES
9. NPC
10. CONTENT
11. REVIEW

이 순서는 권한의 우열이 아니라 초기 기획의 작업 흐름을 위한 것이다.

## 공통 부팅

각 AI를 생성할 때 `00_AI_WORKSPACE/INITIAL_BOOT_PROMPT.md`를 먼저 제공하고, 해당 AI의 역할 프롬프트를 함께 읽게 한다.

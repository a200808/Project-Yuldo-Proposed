# HANDOVER

세션을 바꿔도 작업을 이어갈 수 있도록 **AI별 인수인계 문서**를 운영한다. 모든 문서는 [PROPOSED]이며, 인수인계 문서 자체가 캐논을 확정하지 않는다.

## 목적
무료 사용 한도 등으로 세션을 자주 교체해야 하는 상황에서도 각 AI가 이전 작업을 빠르게 복구할 수 있도록 한다.

## 운영 원칙
1. 각 AI는 자기 담당 인수인계 문서를 세션 종료 시 갱신한다.
2. 새 세션은 시작할 때 자기 인수인계 문서와 관련 Confirmed/Proposed 문서를 먼저 확인한다.
3. 인수인계에는 현재 작업, 확인한 캐논, 최근 변경, 미해결 사항, 다음 작업을 남긴다.
4. Confirmed와 Proposed를 반드시 구분한다.
5. AI는 인수인계를 근거로 Confirmed를 임의 변경하거나 Proposed를 Confirmed로 승격하지 않는다.
6. 다른 AI의 제안을 덮어쓰지 않고 별도 제안/의견으로 기록한다.
7. 장기 작업이 끝나거나 큰 변경이 있으면 99_HANDOVER의 해당 AI 문서를 갱신한다.

## AI별 문서
- `ROUTER.md` — YULDO-AI-ROUTER
- `00_GENERAL.md` — YULDO-AI-GENERAL
- `WORLD.md` — YULDO-AI-WORLD
- `02_STORY.md` — YULDO-AI-STORY
- `03_QUEST.md` — YULDO-AI-QUEST
- `04_GAMEPLAY.md` — YULDO-AI-GAMEPLAY
- `05_EQUIPMENT.md` — YULDO-AI-EQUIPMENT
- `06_ALLIES.md` — YULDO-AI-ALLIES
- `NPC_FACTIONS.md` — YULDO-AI-NPC
- `CONTENT.md` — YULDO-AI-CONTENT
- `REVIEW.md` — YULDO-AI-REVIEW

`HANDOVER_TEMPLATE.md`를 복사하여 새 AI/역할이 추가될 때 동일한 형식을 사용한다.

## 세션 교체 흐름
`이전 AI 인수인계 갱신 → 새 세션 시작 → 해당 AI 인수인계 확인 → Confirmed/Proposed 재확인 → 작업 재개`

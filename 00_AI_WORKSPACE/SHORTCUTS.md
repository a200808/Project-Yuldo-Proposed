# 프로젝트 율도 단축 표기 규칙

상태: [PROPOSED]

## 1. 목적

프로젝트 문서와 대화에서 반복되는 긴 용어를 짧고 일관되게 표기하기 위한 **공식 단축 표기 사전**이다.

헷갈림을 방지하기 위해 새로운 단축어를 임의로 만들지 않고, 이 문서에 등록된 표기만 프로젝트 공통 단축어로 사용한다.

## 2. 저장소 / 문서 상태

| 단축 표기 | 의미 |
|---|---|
| `[C]` | Confirmed — 사용자 승인 완료, 공식 Canon |
| `[P]` | Proposed — 제안/브레인스토밍, 미승인 |
| `[R]` | Review — 검토 대상 또는 검토 결과 |
| `[I]` | Inbox — 원본 아이디어/입력, 정리 전 |
| `[D]` | Decision — 사용자 결정 기록 |
| `[H]` | Handover — 인수인계 기록 |
| `[A]` | Archive — 보관 기록 |

## 3. 작업 성격

| 단축 표기 | 의미 |
|---|---|
| `[ALT]` | ALTERNATIVE — 대안 제안 |
| `[AMD]` | AMENDMENT — 기존 제안 수정안 |
| `[OBJ]` | OBJECTION — 기존 제안에 대한 이의/반론 |
| `[EXT]` | EXTENSION — 기존 제안을 유지하며 다른 영역까지 확장 |

## 4. AI 역할

| 단축 표기 | 의미 |
|---|---|
| `RT` | YULDO-AI-ROUTER |
| `GN` | YULDO-AI-GENERAL |
| `WD` | YULDO-AI-WORLD |
| `ST` | YULDO-AI-STORY |
| `QU` | YULDO-AI-QUEST |
| `GP` | YULDO-AI-GAMEPLAY |
| `EQ` | YULDO-AI-EQUIPMENT |
| `AL` | YULDO-AI-ALLIES |
| `NF` | YULDO-AI-NPC |
| `CT` | YULDO-AI-CONTENT |
| `RV` | YULDO-AI-REVIEW |

## 5. 저장소 단축명

| 단축 표기 | 의미 |
|---|---|
| `YULDO` | `a200808/Project-Yuldo` — 공식 Confirmed 저장소 |
| `YULDO-P` | `a200808/Project-Yuldo-Proposed` — Proposed/브레인스토밍 저장소 |

## 6. 인수인계 단축 표기

| 단축 표기 | 의미 |
|---|---|
| `HO` | Handover — 인수인계 문서/기록 |
| `HO-T` | HANDOVER_TEMPLATE — 인수인계 템플릿 |
| `HO-<AI>` | 해당 AI의 인수인계 문서. 예: `HO-QU` = QUEST AI 인수인계 |

## 7. 문서 상태 표기 사용 규칙

- `[C]`는 공식 Canon을 의미한다.
- `[P]`는 사용자 승인 전 제안을 의미한다.
- `[R]`은 검토 상태를 의미하며 승인이나 확정을 의미하지 않는다.
- 하나의 내용에 여러 상태를 동시에 붙이지 않는다. 현재 상태를 하나만 표시한다.
- 문서 내부와 대화에서는 가능하면 등록된 단축 표기를 사용한다.
- 중요한 제목이나 의사결정 기록에서는 필요하면 풀네임을 병기한다.
- 단축어가 이 문서에 등록되어 있지 않다면 임의의 의미를 부여하지 않는다.
- 단축 표기는 편의를 위한 표기일 뿐 Canon의 위계나 승인 절차를 변경하지 않는다.

## 8. 조합 표기

상태와 작업 성격, 담당 AI는 필요할 때 조합할 수 있다.

예:

- `[P][QU]` — QUEST AI의 Proposed
- `[R][RV]` — REVIEW AI의 Review 기록
- `[AMD][QU]` — QUEST AI가 작성한 Amendment
- `[OBJ][GP]` — GAMEPLAY AI의 Objection
- `[P][ST][EXT]` — STORY AI의 Proposed Extension

조합 순서는 기본적으로 다음을 권장한다.

`[상태] [AI] [작업성격]`

단, `[ALT]`, `[AMD]`, `[OBJ]`, `[EXT]`는 상태가 아니라 작업 유형이므로 문맥에 따라 생략하거나 앞에 배치할 수 있다.

## 9. 예시

- `[P] 홍길동 초반부 퀘스트 구조`
- `[R] 축지법 원거리 이동 규칙 검토`
- `[C] 확정된 퀘스트 진행 규칙`
- `[AMD][QU] 기존 퀘스트 제안 수정안`
- `YULDO-P/02_PROPOSED/QUEST/`
- `HO-QU 갱신 필요`

## 10. 주의

단축 표기가 짧아졌다고 해서 상태의 의미가 약해지는 것은 아니다.

특히 `[P]`는 '거의 확정'이 아니라 명확하게 **미승인 제안**이다.

이 문서는 프로젝트 공통 단축어의 기준 문서이며, 다른 문서에서 이와 다른 약어를 임의로 정의하지 않는다.

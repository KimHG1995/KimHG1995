# 김형균

**Backend Engineer / AI Developer Tooling / Automation**

[English](README.en.md)

TypeScript와 NestJS를 중심으로 백엔드 시스템을 개발하고 있습니다.  
현재 AI 쪽에서는 RAG나 모델 학습보다 **Coding Agent가 실제 코드베이스를 더 잘 탐색하고 검증하도록 만드는 개발 도구**에 집중하고 있습니다.

## 주요 프로젝트

| 프로젝트 | 무엇을 해결하는지 |
| --- | --- |
| [ts-graph-tools](https://github.com/KimHG1995/ts-graph-tools) | Coding Agent가 TypeScript 파일을 하나씩 읽지 않고 symbol, caller, flow, impact를 compiler-resolved graph로 조회할 수 있게 만든 MCP 환경 |
| [agent-bench](https://github.com/KimHG1995/agent-bench) | ts-graph-tools가 실제로 도움이 되는지 Codex의 file-only 탐색과 반복 비교하는 Eval 도구. 실측에서 Graph는 도구 호출을 25% 줄였지만 토큰과 실행 시간은 오히려 증가해 개선 지점을 확인했습니다. |
| [codex-quality-setup](https://github.com/KimHG1995/codex-quality-setup) | 코드 변경 범위에 맞는 typecheck, lint, test를 선택하고 완료 조건까지 검증하는 Codex 품질 자동화 |
| [PaperTrail](https://github.com/KimHG1995/papertrail) | 비동기 렌더링, 버전 관리, 멱등성, Audit Trail을 포함한 전자문서 생성 플랫폼 |
| [LogLens](https://github.com/KimHG1995/loglens) | ClickHouse Materialized View 기반 API 트래픽, 응답시간, 에러 분석 백엔드 |
| [NetBox Cloud Inventory](https://github.com/KimHG1995/netbox-cloud-inventory) | AWS와 NAVER Cloud 자산을 공통 모델로 정규화하고 관계를 탐색하는 인프라 관리 PoC |
| [Work History](https://github.com/KimHG1995/work-history) | 실제 업무와 사이드 프로젝트의 문제, 역할, 구현, 결과를 정리한 개발 기록 |

## AI Developer Tooling

현재 AI 관련 작업은 다음 흐름에 집중합니다.

```text
코드베이스 탐색
  ↓
Code Graph / MCP로 필요한 관계 조회
  ↓
Coding Agent가 구현
  ↓
Typecheck / Lint / Test로 검증
  ↓
Agent Eval로 실제 효과 측정
```

직접 만들고 있는 영역:

- TypeScript Code Graph / MCP
- Coding Agent용 repository context
- 변경 범위 기반 자동 검증
- Agent Eval과 반복 실험
- Tool Call / Token / Latency 측정

LLM API를 붙이는 것 자체보다 **AI가 실제 개발 작업에서 어디서 도움이 되고 어디서 비용이 늘어나는지 측정 가능한 형태로 만드는 것**에 관심이 있습니다.

## Backend

**Language / Runtime**

`TypeScript` `JavaScript` `Node.js`

**Backend**

`NestJS` `Express`

**Database / Data**

`MySQL` `PostgreSQL` `Redis` `DynamoDB` `ClickHouse`

**Cloud / Infrastructure**

`AWS` `NAVER Cloud Platform` `Docker` `Nginx`

**Engineering**

`REST API` `Async Processing` `Observability` `Automation` `MCP`

## 경험

현재 공공기관 대상 교육 플랫폼의 백엔드 개발과 운영을 담당하고 있으며, 활성 사용자 150만 명 이상 규모의 서비스를 다루고 있습니다.

이전에는 에듀테크와 B2B/B2C 플랫폼에서 백엔드 개발, 관리자 시스템, 정산, 데이터 자동화, 배포와 운영 개선을 경험했습니다. 시리즈 A부터 B 투자 단계의 서비스에서 평시 약 30만 MAU, 최대 100만 MAU 규모의 운영 경험이 있습니다.

**[개발 경력과 프로젝트 기록 보기](https://kimhg1995.github.io/work-history/)**

---

백엔드 시스템을 안정적으로 운영하고, 반복되는 개발과 운영 작업을 코드와 도구로 줄이는 방법을 고민합니다.

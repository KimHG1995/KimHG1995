# 김형균

**Backend Engineer / AI Developer Tooling / Automation**

[English](README.en.md)

TypeScript와 NestJS를 중심으로 백엔드 시스템을 개발하고 있습니다.  
현재 AI 쪽에서는 RAG나 모델 학습보다 **Coding Agent를 실제 개발 흐름에 연결하고, 그 효과를 측정하는 도구**에 관심을 두고 있습니다.

## 주요 프로젝트

| 프로젝트 | 무엇을 해결하는지 |
| --- | --- |
| [ts-graph-tools](https://github.com/KimHG1995/ts-graph-tools) | 기존 `@ttsc/graph`를 target repository에 의존성으로 설치하지 않고 Codex/Claude에서 사용할 수 있도록 구성한 외부 host 및 MCP 등록 환경 |
| [agent-bench](https://github.com/KimHG1995/agent-bench) | `@ttsc/graph`를 Coding Agent에 연결했을 때 file-only 탐색보다 실제로 도움이 되는지 반복 비교하는 Eval 도구. 실측에서 도구 호출은 줄었지만 토큰과 실행 시간은 증가해 개선 지점을 확인했습니다. |
| [codex-quality-setup](https://github.com/KimHG1995/codex-quality-setup) | 코드 변경 범위에 맞는 typecheck, lint, test를 선택하고 완료 조건까지 검증하는 Codex 품질 자동화 |
| [PaperTrail](https://github.com/KimHG1995/papertrail) | 비동기 렌더링, 버전 관리, 멱등성, Audit Trail을 포함한 전자문서 생성 플랫폼 |
| [LogLens](https://github.com/KimHG1995/loglens) | ClickHouse Materialized View 기반 API 트래픽, 응답시간, 에러 분석 백엔드 |
| [NetBox Cloud Inventory](https://github.com/KimHG1995/netbox-cloud-inventory) | AWS와 NAVER Cloud 자산을 공통 모델로 정규화하고 관계를 탐색하는 인프라 관리 PoC |
| [Work History](https://github.com/KimHG1995/work-history) | 실제 업무와 사이드 프로젝트의 문제, 역할, 구현, 결과를 정리한 개발 기록 |

## AI Developer Tooling

현재는 이미 존재하는 AI/개발 도구를 실제 개발 환경에 연결하고, 그 효과를 검증하는 흐름을 만들고 있습니다.

```text
코드베이스 탐색
  ↓
MCP / Code Graph 도구 연동
  ↓
Coding Agent가 구현
  ↓
Typecheck / Lint / Test로 검증
  ↓
Agent Eval로 실제 효과 측정
```

직접 작업하고 있는 영역:

- `@ttsc/graph` 기반 MCP 호스팅/연동
- Coding Agent용 repository context 구성
- 변경 범위 기반 자동 검증
- Agent Eval과 반복 실험
- Tool Call / Token / Latency 측정

LLM API 자체를 만드는 것보다 **기존 AI 도구를 개발 워크플로에 안전하게 연결하고, 실제로 효율이 좋아졌는지 확인하는 과정**에 관심이 있습니다.

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

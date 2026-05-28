<div align="center">

# 이재한 | Backend Developer

**AI 시대, "무엇을 만들 것인가"를 아는 개발자**

📅 6개월간 7개 프로덕트 · 🧾 698 커밋 · 1인·소수 운영 · ✨ 평균 87% Conventional Commits

[![Gmail](https://img.shields.io/badge/Gmail-vivajayyy@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vivajayyy@gmail.com)

</div>

---

## About Me

AI가 코드를 작성하는 시대,  
개발자에게 더 중요해진 건 **"무엇을 왜 만들어야 하는지"** 를 아는 것이라 생각합니다.

약 10년간 **개발 → 기획 → 마케팅 → 창업 → 다시 개발**을 거치며  
비즈니스 문제를 정의하고, 요구사항을 설계하고, 직접 구현까지 해본 경험이 있습니다.

지금은 이 경험을 바탕으로 **AI를 도구이자 핵심 기술로 활용해**  
B2B SaaS · B2C 서비스 · 모바일 앱 · 실시간 자막 시스템 · AX 콘텐츠 파이프라인 등  
서로 다른 도메인의 프로덕트를 1인 또는 소수로 빠르게 만들고 배포하고 있습니다.

> **AX(AI Transformation)** 시대의 **FDE(Forward Deployed Engineer)** 처럼,  
> 고객 문제를 정의하고 실행 가능한 솔루션을 끝까지 책임지는 개발자를 지향합니다.

---

## 개발 사이클 — 정량 지표

> **"바이브 코딩이 아니라, 체계 위에서 AI를 협업자로 운영합니다."**  
> 7개 프로젝트 모두 **Claude Code + Codex CLI 조합**으로 운영합니다.  
> 직접 키보드로 코딩한 비중보다 **AI 협업 사이클을 설계·운영하는 비중이 압도적**이며,  
> 모든 프로젝트에 `CLAUDE.md` · `AGENTS.md` 운영 규칙, `TASKS.md` · `ROADMAP.md` single source of truth, 검증 하네스가 함께 있습니다.

| 프로젝트 | 기간 | 커밋 | Conventional | Claude Co-Auth ⁽¹⁾ | 비고 |
|:---|---:|---:|---:|---:|:---|
| **Rooton** | 73일 | 269 | 96.7% | 76.2% | 실제 고객사 납품 운영 |
| **AXBrief** | **6일 4시간** | 94 | **98.9%** | **84%** | Turborepo 모노레포 + 🎨 Claude 디자인 |
| Diffnote | 21일 | 102 | 70.6% | 44% | Stage 1~13 · Product Hunt 런칭 준비 · 7 PRs merged |
| MarkUI | 30일 | 126 | 73.8% | — ⁽²⁾ | Codex 중심 + 🎨 Claude 디자인 핸드오프 |
| Kidsroad | 32일 | 75 | 85.3% | 52% | AI 데이터 파이프라인 + Vercel Cron |
| Haru Ending | 23일 | 22 | 90.9% | 9% | fixture-first 하네스 + 🎨 Claude 디자인 |
| StageCaption | 7일 | 10 | **100%** | — ⁽²⁾ | 기획·아키텍처 + 🎨 Claude 디자인 |
| **합계** | ~6개월 | **698** | **~87%** | **~38%** ⁺ Codex | **사실상 100% AI 협업 운영** |

⁽¹⁾ **Claude Co-Authored 트레일러**(`Co-Authored-By: Claude <noreply@anthropic.com>`)가 붙은 커밋 비율. Claude Code는 이 트레일러를 자동으로 붙여 GitHub에서 협업자로 인식됩니다.  
⁽²⁾ 트레일러가 없는 나머지 커밋은 대부분 **Codex CLI** 기반 (Codex는 트레일러를 자동으로 붙이지 않음). 즉 표의 "—" 또는 낮은 % 는 "AI를 안 썼다"가 아니라 **"Codex 비중이 높았다"** 는 의미입니다.

**체계의 흔적**
- 7/7 프로젝트에 `CLAUDE.md` 또는 `AGENTS.md` 운영 규칙 명문화 — 자동 수행 범위, 커밋 트리거, 도메인별 검증 파이프라인 정의
- 도메인별 scope 커밋 — `feat(route)` · `fix(analytics)` · `docs(roadmap)` · `feat(db)` 등 (예: rooton 96.7%, axbrief 98.9%)
- Phase 단위 진행 + 변경 로그 — `docs(roadmap): Phase 1-A 완료 반영 + 변경 로그 기록` 같은 메타 커밋이 항상 동반
- 검증 자동화 — Diffnote (Husky + Vitest + Playwright + GitHub Actions `ai-coder.yml` + 7 PRs all merged) · MarkUI (Playwright E2E + Visual Regression) · Rooton (GitHub Actions `ci.yml`) · Haru Ending (`npm run verify`)
- 🎨 디자인도 AI 협업 — 4개 프로젝트(AXBrief · MarkUI · Haru Ending · StageCaption)의 디자인 시스템과 핸드오프 자료를 **Claude로 생성·정의**한 뒤 코드 구현

---

## Why Me?

| AI/AX 시대에 필요한 역량 | 나의 경험 |
|---------------------|----------|
| 고객 문제 정의 | 9년간 기획/PM으로 도메인 분석 및 요구사항 설계 |
| 비즈니스 이해력 | 블록체인 거래소, 음악 스트리밍, 직접 창업까지 |
| AI 협업 사이클 설계 | Claude Code + Codex CLI 조합으로 1인 풀스택 개발 사이클 운영 |
| AI를 제품 안에 녹이기 | Claude API · OpenAI Realtime API로 실제 가치 창출 |
| 디자인까지 AI로 | Claude로 디자인 시스템·핸드오프 생성 후 코드 구현 |
| 풀스택 실행력 | Python · TypeScript · Next.js · Expo · Supabase · Railway |
| 커뮤니케이션 | 기술-비기술 팀 사이 브릿지 역할 경험 |

---

## 고객 납품 — Forward Deployed 스타일

> 고객 현장의 차이를 코드 레벨에서 정리하고, 실제 납품 단계까지 끌고 간 사례입니다.

### Rooton (멀티테넌트 SaaS 납품 플랫폼)
> 고객사별 차이를 `tenants/` 와 환경변수로 분리하는 멀티테넌트 백엔드·프론트엔드

**🚧 운영 중**

> 📅 73일 · 🧾 269 commits · ✨ Conventional 96.7% · 🤖 Claude Co-Auth 76.2% (+ Codex)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js_14-000?style=flat-square&logo=next.js)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)

**🏗️ 아키텍처**
- FastAPI + SQLAlchemy + Alembic 마이그레이션 · Next.js 14 App Router
- 고객사별 `tenants/` 프로파일 + `deployments/` 배포 템플릿 — **코드 fork 없이** 차이 분리
- 고객사별 DB · Redis · Backend · Frontend 인프라 분리 + 공통 코드 1개 유지 (운영 안정성과 비용 분리 양립)
- Railway(백엔드) + Vercel(프론트) 멀티 환경

**🤝 Forward Deployed 스타일**
- 고객사별 납품 아키텍처를 **코드 컨벤션 레벨에서 명문화** (`docs/CUSTOMER_DELIVERY_ARCHITECTURE.md`)
- 도메인별 scope 커밋 운영 — `feat(route)` · `fix(analytics)` · `test(analytics)` 등 (269 커밋 중 96.7% Conventional 유지)
- Claude Code 에이전트(`backend-architect` · `frontend-developer` · `task-orchestrator`)와 Task Master 명령으로 작업 자동화
- 1인 운영 워크플로우(`main` 직접 푸시)이지만, 검증 통과 후에만 커밋·푸시하는 규칙을 `CLAUDE.md`에 명문화

🔗 [Live](https://rooton.vercel.app) · [GitHub](https://github.com/vivajayyy/rooton)

---

## AI를 핵심 기술로 활용한 프로덕트

> AI를 단순 보조 도구가 아니라 **제품의 핵심 가치**로 만든 사례입니다.

### AXBrief (AX 콘텐츠 미디어)
> AX(AI Transformation) 케이스 데이터를 자동 수집하고, AI로 고퀄리티 콘텐츠를 재생산하여 미디어 사이트로 발행하는 서비스

**🚧 MVP 개발 진행 중**

> 📅 6일 4시간 · 🧾 94 commits · ✨ Conventional 98.9% · 🤖 Claude Co-Auth 84% · 🎨 Claude 디자인 (Editorial)

![Next.js](https://img.shields.io/badge/Next.js_16-000?style=flat-square&logo=next.js)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)

**⚡ 빠른 MVP 구축 속도**
- **6일 4시간 동안 94 커밋**으로 pnpm Turborepo 모노레포(`apps/web` + `workers/collector` + `workers/generator`) + Prisma 마이그레이션 + Next.js 미디어 사이트까지 Phase 1-A 완료
- **Conventional Commits 98.9% × Claude Co-Auth 84%** — 빠르면서도 도메인별 scope·검증 파이프라인 유지

**🎨 Claude 디자인**
- Phase 3-A에서 **Claude로 'Editorial' 톤 디자인 시스템 설계** → 홈 + 기사 상세 페이지에 정식 구현
- 디자인 방향 확정·변경 로그도 ROADMAP에 명문화 (`docs(roadmap): Phase 3-A 디자인 방향 Editorial 확정 기록`)

**🎯 핵심 가치**
- 한국 기업 의사결정자·실무자에게 실질적으로 도움 되는 **AX 도입 사례·가이드** 큐레이션
- 글로벌(McKinsey · AWS · HBR) + 한국(NIPA · AI타임스 등) 다중 소스로 정부 지원사업·업종별 도입 팁·규제 가이드를 자동 발굴

**🤖 AI 파이프라인**
- RSS 실시간 감지 + 일·주 단위 배치 크롤링 병행
- AI 구조화 → AI 품질 검수 → 사람 최종 승인의 **휴먼-인-더-루프** 파이프라인
- 콘텐츠 유형별 비중(케이스 50% / 한국 특화 30% / 트렌드 20%) 자동 균형 관리

🔗 [Live](https://axbrief.vercel.app) · [GitHub](https://github.com/vivajayyy/axbrief)

---

### Kidsroad (키즈로드)
> 부모를 위한 아이 동반 축제·행사 큐레이션 서비스

**✅ 개발 완료**

> 📅 32일 · 🧾 75 commits · ✨ Conventional 85.3% · 🤖 Claude Co-Auth 52% (+ Codex)

![Next.js](https://img.shields.io/badge/Next.js_16-000?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**🤖 AI-Powered Data Pipeline**
- TourAPI(한국관광공사)에서 전국 축제·행사 데이터 자동 수집
- Claude Haiku로 블로그 분석 → 부모 체크리스트 정보(주차·유모차·수유실) 추출
- Rate Limiter로 API 비용 최적화 (50 req/min) · 지능형 재분석 정책으로 불필요한 AI 호출 최소화

**👨‍👩‍👧 Parent-Focused Filtering**
- 연령별 필터링 (0-2세 / 3-5세 / 6-9세 / 10세+)
- AI가 `is_kid_friendly` 자동 판단 — 성인 전용 행사 필터링

**🔄 Automated Data Collection**
- Vercel Cron으로 주기적 데이터 수집 자동화
- p-limit 동시성 제어(병렬 3개) · Telegram Bot 실시간 모니터링

🔗 [Live](https://kidsroad.vercel.app) · [GitHub](https://github.com/vivajayyy/kidsroad)

---

### StageCaption AI (현장 자막 OS)
> AV · LED · OBS 운영자를 위한 AI 실시간 자막 송출 OS — V1 기획 저장소

**📐 기획 · 아키텍처 설계 단계**

> 📅 7일 · 🧾 10 commits · ✨ Conventional 100% · 🤖 Codex 중심 · 🎨 Claude 디자인

![OpenAI](https://img.shields.io/badge/OpenAI_Realtime-412991?style=flat-square&logo=openai&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**🎯 포지셔닝**
- Jodio 같은 QR/PWA 통역 플랫폼과 정면 가격 경쟁하지 않고, **현장 LED · OBS · AV 운영 자막 OS** 로 차별화
- 교회·컨퍼런스 현장 파일럿을 전제로 한 PRD · 경쟁사 분석 · V1 아키텍처 · 현장 테스트 계획 수립

**🎨 Claude 디자인**
- 송출 화면(lower-third · side-panel) · 운영자 콘솔 · 모바일 QR 자막 진입 화면을 **Claude로 디자인 설계** 후 정리

**🧪 검증 우선 개발**
- OpenAI Realtime API 연동 전에 **mock caption broadcast** 부터 완성
- 모든 기능은 mock harness · 자동 테스트 · 브라우저 확인 · 현장 체크리스트 중 하나 이상의 검증 근거를 남김
- "Vibe coding은 무검증 프로토타이핑이 아니다" 라는 운영 원칙 명문화

**📋 산출물**
- PRD · 경쟁사 분석 · V1 아키텍처 · 에이전트 운영 모델 · 하네스 엔지니어링 · 현장 테스트 계획

🔗 [GitHub](https://github.com/vivajayyy/stagecaption-ai-v1-plan)

---

### Haru Ending (하루엔딩)
> 육아 후 나만의 시간을 위한 AI 자기계발 모바일 앱

**🚧 MVP 개발 진행 중**

> 📅 23일 · 🧾 22 commits · ✨ Conventional 90.9% · 🤖 Codex 중심 · 🎨 Claude 디자인 (Soft Bloom)

![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)

**🎨 Claude 디자인**
- **Claude로 'Soft Bloom' 디자인 시스템 설계** → Expo 앱 핵심 화면에 정식 적용
- `design/` 폴더에 디자인 토큰·핸드오프 자료 관리

**🤖 안전한 AI 통합**
- Anthropic API 키를 클라이언트에 두지 않고 **Supabase Edge Function**에서 secret으로 관리
- 하루 회고 · 루틴 · 집중 · 커뮤니티 흐름을 AI가 보조

**🧪 하네스 엔지니어링**
- MVP 전까지 **fixture · 순수 domain 함수 · 외부 서비스 adapter 경계** 부터 설계
- Supabase 미설정 상태에서도 부팅 가능한 구조(의도된 실패 표면화)
- `npm run verify`로 lint · typecheck · unit test 일괄 검증

**📱 운영**
- Expo Router · LAN/Tunnel 모드 분리 운영 스크립트 · 시나리오 하네스로 fixture별 핵심 화면 검증

🔗 [GitHub](https://github.com/vivajayyy/haru-ending)

---

## Harness Engineering으로 빠르게 출시한 프로덕트

> 검증 우선 운영 + 짧은 사이클로 MVP를 빠르게 출시한 사례입니다.

### Diffnote (디프노트)
> IDE의 Diff 기능을 비개발자도 쉽게 사용할 수 있는 웹 기반 문서 비교 서비스

**📌 MVP 완료 · Phase 2 고도화 진행 중**

> 📅 21일 · 🧾 102 commits · ✨ Conventional 70.6% · 🤖 Claude Co-Auth 44% (+ Codex) · 🔀 7 PRs all merged

![Next.js](https://img.shields.io/badge/Next.js_15-000?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**⚡ 빠른 출시 사이클**
- **21일 동안 102 커밋**으로 Stage 1~13 순차 진행 + **Product Hunt 런칭 준비 완료**
- Husky pre-commit + Vitest + Playwright + GitHub Actions(`ai-coder.yml`) + **7 PRs all merged** — 단일 개발자임에도 PR 워크플로우로 변경 단위 분리

**🔐 Privacy-First Architecture**
- 100% 클라이언트 사이드 처리 — 파일이 서버에 전송되지 않음
- DOMPurify를 활용한 XSS 방지

**📄 Multi-Format Support**
- TXT · PDF (pdf.js) · DOCX (mammoth.js) 파일 파싱

**⚡ Performance Optimization**
- Web Worker로 메인 스레드 블로킹 방지 · react-window 가상 스크롤링 · 동적 import 번들 최적화

**🔍 Diff Engine**
- Google diff-match-patch · Side-by-Side & Unified 뷰

🔗 [Live](https://diffnote.net) · [GitHub](https://github.com/vivajayyy/diffnote)

---

### MarkUI (팀용 라이브 피드백 SaaS)
> 라이브 제품 화면 위에서 피드백을 남기고, 그 피드백을 구조화된 작업으로 전환하는 팀 우선 SaaS

**🚧 MVP 개발 진행 중**

> 📅 30일 · 🧾 126 commits · ✨ Conventional 73.8% · 🤖 Codex CLI 중심 · 🎨 Claude 디자인 핸드오프

![Next.js](https://img.shields.io/badge/Next.js_16-000?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

**🎨 Claude 디자인 핸드오프**
- **Claude로 디자인 핸드오프 생성** → `design-handoff/` 폴더에 시안·토큰 관리 → 코드 구현
- 커밋 흔적: `feat: add shared design tokens and UI primitives`, `docs: add T-104 design system spec`, `Build install wizard from handoff`
- `AGENTS.md`에 *"Treat the design handoff as the primary visual reference"* 운영 규칙 명문화

**🧱 데이터 모델**
- `Workspace > Project > Page > Feedback` 4-tier 구조
- 스크린샷 · PPT · 메일 기반 피드백 루프를 줄이는 것이 핵심 가치

**🧪 검증 자동화**
- Vitest · Playwright E2E · Playwright Visual Regression
- Supabase SSR · Server Actions 기반 풀스택
- "사람이 방향을 잡고, 에이전트가 작은 단위로 실행한다" 운영 모델 (`AGENTS.md` 에 명문화)

🔗 [Live](https://markui-nine.vercel.app) · [GitHub](https://github.com/vivajayyy/markui)

---

## Team Project

### GameBid (게임 경매 플랫폼)
> 게임 아이템·계정·굿즈 경매 거래 플랫폼

**✅ MVP 완료 · 팀 프로젝트 (5인)**

![Java](https://img.shields.io/badge/Java_17-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**👥 팀 구성:** 디자이너 1 · 프론트엔드 2 · 백엔드 2

**담당 역할 (Backend)**
- 도메인 모델링 및 REST API 설계·구현
- 경매 로직, 입찰 처리, 종료 시간 기반 정렬
- AWS S3 이미지 업로드
- 예외 처리 구조 설계

*🔒 Organization Private Repository*

---

## Tech Stack

**Main** : Java, Spring Boot, JPA, PostgreSQL, MySQL, Python (FastAPI)

**Frontend / Mobile** : Next.js (App Router), React 19, TypeScript, Tailwind, Expo / React Native

**Data / Infra** : Supabase (Postgres · Auth · Edge Functions · RLS), Railway, Vercel (Functions · Cron · Blob), Prisma, Alembic

**AI (제품에 녹임)** : Claude API (Sonnet · Haiku), OpenAI Realtime API, Anthropic via Supabase Edge Functions

**AI 협업 도구 (개발 사이클)** : Claude Code, Codex CLI, Superpowers, Task Master, MCP

**Quality** : Vitest, Playwright (E2E · Visual), Pytest, Husky, Turborepo, GitHub Actions

---

## Career Journey

| 시기 | 역할 | 경험 |
|:---:|:---|:---|
| **2015** | 웹 개발 (PHP) | 음악 스트리밍 서비스 전체 리뉴얼 |
| **2018** | PM / 마케팅 | 블록체인 거래소, 기술 마케팅 주도 |
| **2021** | 창업 (카페) | 브랜딩부터 물류·CS까지 직접 운영 |
| **2023** | 백엔드 개발 | Java/Spring 전환, AI 활용 개발 |
| **Now** | AI 시대 풀스택 · FDE 지향 | 6개월 698 커밋 · 7개 프로덕트 · 평균 87% Conventional Commits · 사실상 100% AI 협업 운영 |

---

<div align="center">

### 🔥 Growth Mindset

**"완벽한 준비란 없다. 시작하고, 부딪히고, 성장한다."**

새로운 기술을 두려워하지 않습니다.  
AI 시대의 변화를 기회로 삼아, 매일 조금씩 더 나은 개발자가 되고 있습니다.

</div>

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

순수 개발 경력은 길지 않지만, 약 10년간 **개발 → 기획 → 마케팅 → 창업 → 다시 개발**을 거치며  
비즈니스 문제를 정의하고, 요구사항을 설계하고, 직접 구현까지 해본 경험이 있습니다.

지금은 이 경험을 바탕으로 **AI를 도구이자 핵심 기술로 활용해**  
B2B SaaS · 모바일 앱 · AX 콘텐츠 파이프라인 · 실시간 자막 시스템 등  
서로 다른 도메인의 프로덕트를 1인·소수로 빠르게 만들고 배포하고 있습니다.

> **AX(AI Transformation) · FDE(Forward Deployed Engineer) 직군은**  
> 기술 깊이만큼이나 **기획 · 설계 · 운영 능력**이 중요한 자리라고 생각합니다.  
> 코드만 깊게 파온 시니어 개발자와는 다른 결의 경쟁력으로  
> 고객 문제 정의부터 솔루션 운영까지 끝까지 책임지는 개발자를 지향합니다.

---

## 왜 AX / FDE 직군에 적합한 개발자인가

> "코드를 잘 짜는 사람" 보다 "**문제를 정의하고 운영을 책임지는 사람**"이 필요한 자리에서,  
> 다른 결의 경력이 더 큰 무기가 됩니다.

| 역량 | 흔히 있는 풀스택 개발자 | **저의 차별점** |
|---|---|---|
| 순수 코드 경력 | 5~10년+ | 짧음 (단, AI Agent 협업 사이클 운영은 시니어 수준) |
| 비즈니스 이해 | 도메인 의존 | **9년 IT 기획·마케팅 주도** + 직접 창업으로 브랜딩·물류·CS까지 |
| 요구사항 정의 | PM 의존 | 본인이 **PM** — 공공기관 프로젝트 포함 |
| AI 활용 깊이 | 도구 사용 수준 | **Skill Creator로 커스텀 스킬 직접 제작** · Agent 사이클 설계 |
| 프로젝트 운영 | 종종 약함 | Notion · Linear · GitLab 위 **AI Agent 협업 사이클 표준화** 경험 |

---

## 개발 사이클 — 정량 지표

> **"바이브 코딩이 아니라, 체계 위에서 AI를 협업자로 운영합니다."**  
> 7개 프로젝트 모두 **Claude Code + Codex CLI 조합**으로 운영.  
> 직접 키보드로 코딩한 비중보다 **AI 협업 사이클을 설계·운영하는 비중이 압도적**입니다.

| 프로젝트 | 기간 | 커밋 | Conventional | Claude Co-Auth ⁽¹⁾ | 비고 |
|:---|---:|---:|---:|---:|:---|
| **Rooton** | 73일 | 269 | 96.7% | 76.2% | 실제 고객사 납품 운영 |
| **AXBrief** | **6일 4시간** | 94 | **98.9%** | **84%** | Turborepo 모노레포 + 🎨 Claude 디자인 |
| Diffnote | 21일 | 102 | 70.6% | 44% | Product Hunt 런칭 준비 · 7 PRs merged |
| MarkUI | 30일 | 126 | 73.8% | — ⁽²⁾ | Codex 중심 + 🎨 Claude 디자인 핸드오프 |
| Kidsroad | 32일 | 75 | 85.3% | 52% | AI 데이터 파이프라인 + Vercel Cron |
| Haru Ending | 23일 | 22 | 90.9% | 9% | fixture-first 하네스 + 🎨 Claude 디자인 |
| StageCaption | 7일 | 10 | **100%** | — ⁽²⁾ | 기획·아키텍처 + 🎨 Claude 디자인 |
| **합계** | ~6개월 | **698** | **~87%** | **~38%** ⁺ Codex | **사실상 100% AI 협업 운영** |

⁽¹⁾ Claude Code는 커밋에 `Co-Authored-By: Claude` 트레일러를 자동으로 붙입니다.  
⁽²⁾ 트레일러가 없는 나머지 커밋은 대부분 **Codex CLI** 기반 — "—" 또는 낮은 %는 "AI를 안 썼다"가 아니라 **"Codex 비중이 높았다"** 는 의미입니다.

**체계의 흔적**
- 7/7 프로젝트에 `CLAUDE.md` / `AGENTS.md` 운영 규칙 명문화 — 자동 수행 범위 · 커밋 트리거 · 검증 파이프라인 정의
- 도메인별 scope 커밋 + Phase 단위 진행 + 변경 로그가 항상 동반 (`feat(route)` · `docs(roadmap): Phase 1-A 완료 반영` 등)
- 검증 자동화 — Husky · Vitest · Playwright (E2E·Visual) · GitHub Actions · `npm run verify`
- 🎨 **신기능을 출시 직후 흡수** — Claude.ai 디자인 도구를 4개 프로젝트에 즉시 도입해 1인 개발의 디자인 한계 돌파

---

## 이전 직장 프로젝트 — 공공기관 AI Agent 활용 PM

> 국내 공공 연구기관 프로젝트에서 **PM 역할로 대규모 프론트엔드 마이그레이션을 AI Agent 중심으로 진행**한 경험.  
> 단순 보조가 아닌 **개발 사이클 자체를 AI Agent 위에서 재설계**한 사례입니다.

### Vue 2 → React 전체 마이그레이션 (익명화)

**🏛️ 프로젝트 개요**
- **클라이언트** : 국내 공공 연구기관
- **나의 역할** : **PM** — 제품 방향 · 일정 · 태스크 · 팀 커뮤니케이션 총괄
- **작업 범위** : 약 **300+ Vue 컴포넌트 / 수만 줄** 규모의 레거시 프론트엔드를 React로 전체 마이그레이션
- **협업 도구** : **Notion**(문서·요구사항) · **Linear**(태스크) · **GitLab**(코드·MR·CI)

**🧭 Vue 3 검토 → React 전환 의사결정**
- 정적 분석으로 의존성 부담(특정 UI 라이브러리 70+ 파일 의존, Vue 3 미지원 패키지 다수)을 확인
- **장기 운영성 · 채용 풀 · 생태계** 관점에서 **React 전환을 PM 의사결정으로 진행**
- 단순히 "AI한테 시켰다" 가 아닌, **기술 부채와 비즈니스 트레이드오프를 분석해 방향을 잡는 PM의 본질적 일**

**🤖 AI Agent 중심 개발 사이클 (핵심 차별점)**

1. **Claude Code + Superpowers 기반 마이그레이션** — 코드 변환·컴포넌트 재작성·테스트를 Agent로 자동화
2. **Skill Creator로 커스텀 스킬 직접 제작** — 대표 사례: **GitLab 자동 리뷰 스킬**. *"AI를 쓰는 사람" 이 아니라 "AI를 자기 워크플로우에 맞게 만드는 사람"* — AX 직군의 본질
3. **PM × AI Agent 협업 사이클 표준화** — 팀원 작업 → AI Agent 자동 리뷰 → PM 승인 → 머지 흐름을 Notion·Linear·GitLab 위 single source of truth로 운영

**🏛️ 공공기관 환경에서의 의미**
- **보안 · 운영 제약**이 까다로운 공공기관 환경에서 AI Agent 중심 사이클을 실제 적용한 흔치 않은 레퍼런스
- 마이그레이션의 **대부분을 진행**했고, AI 자동 리뷰 스킬·마이그레이션 패턴·문서를 **후임이 인계받을 수 있는 형태로 정리** 후 다음 도전을 위해 이직

> *공공기관 + 대규모 마이그레이션 + PM 역할 + AI Agent 사이클 자체 설계 — 국내에서 거의 보기 어려운 조합입니다.*

---

## 고객 납품 — Forward Deployed 스타일

### Rooton (멀티테넌트 SaaS 납품 플랫폼)
> 고객사별 차이를 `tenants/` 와 환경변수로 분리하는 멀티테넌트 백엔드·프론트엔드

**🚧 운영 중** · 📅 73일 · 🧾 269 commits · ✨ Conventional 96.7% · 🤖 Claude Co-Auth 76.2%

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js_14-000?style=flat-square&logo=next.js)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)

- FastAPI + SQLAlchemy + Alembic · Next.js 14 App Router · Railway + Vercel 멀티 환경
- 고객사별 `tenants/` 프로파일 + `deployments/` 배포 템플릿 — **코드 fork 없이** 차이 분리
- 고객사별 DB · Redis · 인프라 분리 + 공통 코드 1개 유지 (운영 안정성과 비용 분리 양립)
- 납품 아키텍처를 **코드 컨벤션 레벨에서 명문화** (`docs/CUSTOMER_DELIVERY_ARCHITECTURE.md`)
- Claude Code 에이전트(`backend-architect` · `task-orchestrator`)와 Task Master로 작업 자동화

🔗 [Live](https://rooton.vercel.app) · [GitHub](https://github.com/vivajayyy/rooton)

---

## AI를 핵심 기술로 활용한 프로덕트

### AXBrief (AX 콘텐츠 미디어)
> AX(AI Transformation) 케이스를 자동 수집하고, AI로 콘텐츠를 재생산해 미디어 사이트로 발행하는 서비스

**🚧 MVP 개발 중** · 📅 6일 4시간 · 🧾 94 commits · ✨ Conventional 98.9% · 🤖 Claude Co-Auth 84% · 🎨 Claude.ai 디자인 (Editorial)

![Next.js](https://img.shields.io/badge/Next.js_16-000?style=flat-square&logo=next.js)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

- **6일 4시간 동안 94 커밋**으로 pnpm Turborepo 모노레포(`apps/web` + `workers/collector` + `workers/generator`) + Prisma + Next.js 미디어 사이트까지 Phase 1-A 완료
- **Conventional 98.9% × Claude Co-Auth 84%** — 빠르면서도 도메인별 scope·검증 파이프라인 유지
- Phase 3-A의 'Editorial' 톤 디자인 시스템을 Claude.ai 디자인 도구로 설계 → 1인 개발자임에도 전문 미디어 수준의 톤·타이포 확보
- 글로벌(McKinsey · AWS · HBR) + 한국(NIPA 등) 다중 소스 자동 수집 · RSS 실시간 + 배치 크롤링 병행
- AI 구조화 → AI 품질 검수 → 사람 최종 승인의 **휴먼-인-더-루프** 파이프라인

🔗 [Live](https://axbrief.vercel.app) · [GitHub](https://github.com/vivajayyy/axbrief)

---

### Kidsroad (키즈로드)
> 부모를 위한 아이 동반 축제·행사 큐레이션 서비스

**✅ 개발 완료** · 📅 32일 · 🧾 75 commits · ✨ Conventional 85.3% · 🤖 Claude Co-Auth 52%

![Next.js](https://img.shields.io/badge/Next.js_16-000?style=flat-square&logo=next.js)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

- **TourAPI(한국관광공사)** 전국 행사 자동 수집 → **Claude Haiku로 블로그 분석** → 부모 체크리스트(주차·유모차·수유실) 자동 추출
- Rate Limiter로 API 비용 최적화 (50 req/min) · 지능형 재분석 정책으로 불필요한 AI 호출 최소화
- AI가 `is_kid_friendly` 자동 판단 — 성인 전용 행사 필터링
- Vercel Cron 자동화 · p-limit 동시성 제어 · Telegram Bot 실시간 모니터링

🔗 [Live](https://kidsroad.vercel.app) · [GitHub](https://github.com/vivajayyy/kidsroad)

---

### StageCaption AI (현장 자막 OS)
> AV · LED · OBS 운영자를 위한 AI 실시간 자막 송출 OS — V1 기획 저장소

**📐 기획 · 아키텍처 설계** · 📅 7일 · 🧾 10 commits · ✨ Conventional 100% · 🎨 Claude.ai 디자인

![OpenAI](https://img.shields.io/badge/OpenAI_Realtime-412991?style=flat-square&logo=openai&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js)

- Jodio 같은 QR/PWA 통역 플랫폼과 다른 **현장 LED · OBS · AV 운영 자막 OS** 로 차별화
- OpenAI Realtime API 연동 전에 **mock caption broadcast** 부터 완성하는 검증 우선 개발
- 송출 화면(lower-third · side-panel) · 운영자 콘솔 · 모바일 QR 자막 진입 화면을 Claude.ai 디자인 도구로 설계
- 산출물: PRD · 경쟁사 분석 · V1 아키텍처 · 에이전트 운영 모델 · 현장 테스트 계획

🔗 [GitHub](https://github.com/vivajayyy/stagecaption-ai-v1-plan)

---

### Haru Ending (하루엔딩)
> 육아 후 나만의 시간을 위한 AI 자기계발 모바일 앱

**🚧 MVP 개발 중** · 📅 23일 · 🧾 22 commits · ✨ Conventional 90.9% · 🎨 Claude.ai 디자인 (Soft Bloom)

![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)

- Claude.ai 디자인 도구로 'Soft Bloom' 디자인 시스템 설계 → Expo 앱 핵심 화면에 적용
- **안전한 AI 통합** — Anthropic API 키를 Supabase Edge Function의 secret으로 관리 (클라이언트 노출 방지)
- **하네스 엔지니어링** — fixture · domain 함수 · adapter 경계부터 설계 · Supabase 미설정에서도 부팅 가능한 구조

🔗 [GitHub](https://github.com/vivajayyy/haru-ending)

---

## Harness Engineering으로 빠르게 출시한 프로덕트

### Diffnote (디프노트)
> IDE의 Diff 기능을 비개발자도 쉽게 쓸 수 있는 웹 기반 문서 비교 서비스

**📌 MVP 완료 · Phase 2 진행** · 📅 21일 · 🧾 102 commits · ✨ Conventional 70.6% · 🔀 7 PRs all merged

![Next.js](https://img.shields.io/badge/Next.js_15-000?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

- **21일 동안 102 커밋**으로 Stage 1~13 순차 진행 + **Product Hunt 런칭 준비 완료**
- Husky + Vitest + Playwright + GitHub Actions(`ai-coder.yml`) + **7 PRs all merged** — 단일 개발자임에도 PR 워크플로우로 변경 단위 분리
- **Privacy-First** — 100% 클라이언트 사이드 처리 (TXT · PDF · DOCX) · DOMPurify XSS 방지
- Web Worker 메인 스레드 비차단 · react-window 가상 스크롤링 · Google diff-match-patch

🔗 [Live](https://diffnote.net) · [GitHub](https://github.com/vivajayyy/diffnote)

---

### MarkUI (팀용 라이브 피드백 SaaS)
> 라이브 제품 화면 위에 피드백을 남기고, 그 피드백을 구조화된 작업으로 전환하는 팀 우선 SaaS

**🚧 MVP 개발 중** · 📅 30일 · 🧾 126 commits · ✨ Conventional 73.8% · 🤖 Codex CLI 중심 · 🎨 Claude.ai 디자인 (핸드오프)

![Next.js](https://img.shields.io/badge/Next.js_16-000?style=flat-square&logo=next.js)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

- **Claude.ai 디자인 도구로 핸드오프 자료 생성** → `design-handoff/` 폴더에 시안·토큰 관리 → 디자이너 없이 SaaS 수준의 UI 일관성 확보
- `Workspace > Project > Page > Feedback` 4-tier 데이터 모델 — 스크린샷·PPT·메일 피드백 루프를 줄임
- Vitest · Playwright E2E · Visual Regression · Supabase SSR · Server Actions
- `AGENTS.md` 에 *"사람이 방향을 잡고, 에이전트가 작은 단위로 실행한다"* 운영 모델 명문화

🔗 [Live](https://markui-nine.vercel.app) · [GitHub](https://github.com/vivajayyy/markui)

---

## Team Project

### GameBid (게임 경매 플랫폼)
**✅ MVP 완료 · 팀 프로젝트 (5인 — 디자이너 1 · FE 2 · BE 2)**

![Java](https://img.shields.io/badge/Java_17-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

게임 아이템·계정·굿즈 경매 거래 플랫폼. **Backend 담당** — 도메인 모델링 · REST API 설계·구현 · 경매·입찰 로직 · 종료 시간 기반 정렬 · AWS S3 이미지 업로드 · 예외 처리 구조 설계. *🔒 Organization Private Repository*

---

## Tech Stack

**언어 / 백엔드** : Java · Spring Boot · JPA · Python (FastAPI) · PostgreSQL · MySQL

**프론트엔드 / 모바일** : Next.js (App Router) · React 19 · TypeScript · Tailwind · Expo

**인프라 / 데이터** : Supabase (Auth · Edge Functions · RLS) · Railway · Vercel (Functions · Cron · Blob) · Prisma · Alembic

**AI (제품에 녹임)** : Claude API (Sonnet · Haiku) · OpenAI Realtime API

**AI 협업 도구** : Claude Code (+ **Skill Creator로 커스텀 스킬 제작**) · Codex CLI · Claude.ai 디자인 도구 · Superpowers · Task Master · MCP

**팀 협업** : Notion · Linear · GitLab · GitHub Actions

**Quality** : Vitest · Playwright (E2E · Visual) · Pytest · Husky · Turborepo

---

## Career Journey

| 시기 | 역할 | 경험 |
|:---:|:---|:---|
| **2015** | 웹 개발 (PHP) | 음악 스트리밍 서비스 전체 리뉴얼 |
| **2018** | PM · 마케팅 | 블록체인 거래소, 기술 마케팅 주도 |
| **2021** | 창업 (카페) | 브랜딩부터 물류·CS까지 직접 운영 |
| **2023** | 백엔드 개발 | Java/Spring 전환, AI 활용 개발 시작 |
| **이전 직장** | **PM · 공공기관 AI Agent 프로젝트** | Vue 2 → React 마이그레이션을 AI Agent 중심으로 운영 · Skill Creator로 커스텀 스킬 제작 |
| **Now** | AI 시대 풀스택 · FDE 지향 | 6개월 698 커밋 · 7개 프로덕트 · 사실상 100% AI 협업 운영 |

---

<div align="center">

**"완벽한 준비란 없다. 시작하고, 부딪히고, 성장한다."**

AX · FDE 직군이 진짜 필요로 하는 건  
**문제를 정의하고, 운영을 책임지고, 새 도구를 자기 사이클에 흡수하는 사람**이라고 믿습니다.

</div>

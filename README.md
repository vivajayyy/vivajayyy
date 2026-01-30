<div align="center">

# 이재한 | Backend Developer

**AI 시대, "무엇을 만들 것인가"를 아는 개발자**

[![Gmail](https://img.shields.io/badge/Gmail-vivajayyy@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vivajayyy@gmail.com)

</div>

---

## About Me

AI가 코드를 작성하는 시대,  
개발자에게 더 중요해진 건 **"무엇을 왜 만들어야 하는지"** 를 아는 것이라 생각합니다.

약 10년간 **개발 → 기획 → 마케팅 → 창업 → 다시 개발**을 거치며  
비즈니스 문제를 정의하고, 요구사항을 설계하고, 직접 구현까지 해본 경험이 있습니다.

지금은 이 경험을 바탕으로 **AI를 도구 삼아 더 빠르게, 더 본질에 집중하며** 개발하고 있습니다.

```
"어제보다 나은 오늘"을 만들기 위해 매일 코드를 씁니다.
```

---

## Why Me?

| AI 시대에 필요한 역량 | 나의 경험 |
|---------------------|----------|
| 요구사항 정의 능력 | 9년간 기획/PM으로 수백 건의 요구사항 분석 |
| 비즈니스 이해력 | 블록체인 거래소, 음악 스트리밍, 직접 창업까지 |
| 빠른 프로토타이핑 | AI 도구 활용해 1인 풀스택 프로젝트 완성 |
| 커뮤니케이션 | 기술-비기술 팀 사이 브릿지 역할 경험 |

---

## AI-Assisted Development

**Claude Code**를 활용해 기획부터 배포까지 개발한 프로젝트입니다.

> AI는 도구일 뿐, 방향을 정하는 건 사람입니다.  
> 기획력과 도메인 이해가 있어야 AI를 제대로 활용할 수 있다고 믿습니다.

### Diffnote (디프노트)
> IDE의 Diff 기능을 비개발자도 쉽게 사용할 수 있는 웹 기반 문서 비교 서비스

![Status](https://img.shields.io/badge/Status-Phase_2_진행중-blue?style=flat-square)
![MVP](https://img.shields.io/badge/MVP-Complete-success?style=flat-square)

![Next.js](https://img.shields.io/badge/Next.js_15-000?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white)

**🔐 Privacy-First Architecture**
- 100% 클라이언트 사이드 처리 - 파일이 서버에 전송되지 않음
- DOMPurify를 활용한 XSS 방지

**📄 Multi-Format Support**
- TXT, PDF (pdf.js), DOCX (mammoth.js) 파일 파싱
- 드래그 앤 드롭 업로드, 최대 10MB 지원

**⚡ Performance Optimization**
- Web Worker를 활용한 메인 스레드 블로킹 방지
- react-window 가상 스크롤링으로 대용량 파일 처리
- 동적 import로 번들 사이즈 최적화

**🔍 Diff Engine**
- Google diff-match-patch 알고리즘
- 줄/단어/문자 단위 비교 지원
- Side-by-Side & Unified 뷰 모드

**🧪 Testing & Quality**
- Vitest + React Testing Library (Unit/Integration)
- Playwright E2E 테스트
- Husky + lint-staged 자동화

🔗 [Live](https://diffnote.vercel.app) · [GitHub](https://github.com/vivajayyy/diffnote)

---

### Kidsroad (키즈로드)
> 부모를 위한 아이 동반 축제/행사 큐레이션 서비스

![Status](https://img.shields.io/badge/Status-Complete-success?style=flat-square)

![Next.js](https://img.shields.io/badge/Next.js_16-000?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

- PRD 작성 → DB 설계 → 구현 → 배포까지 AI와 협업
- TourAPI 연동 자동화 파이프라인
- Claude AI 기반 블로그 분석으로 데이터 보강
- Kakao OAuth 인증, 실시간 필터링

🔗 [Live](https://kidsroad.vercel.app) · [GitHub](https://github.com/vivajayyy/kidsroad)

---

## Projects

### GameBid (게임 경매 플랫폼)
> 게임 아이템/계정/굿즈 경매 거래 플랫폼

![Status](https://img.shields.io/badge/Status-MVP_Complete-success?style=flat-square)
![Team](https://img.shields.io/badge/Team-5명_(BE_담당)-purple?style=flat-square)

![Java](https://img.shields.io/badge/Java_17-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**👥 팀 구성:** 디자이너 1 · 프론트엔드 2 · 백엔드 2

**담당 역할 (Backend)**
- 도메인 모델링 및 REST API 설계/구현
- 경매 로직, 입찰 처리, 종료 시간 기반 정렬
- AWS S3 이미지 업로드
- 예외 처리 구조 설계

---

## Tech Stack

**Main** : Java, Spring Boot, JPA, PostgreSQL, MySQL

**Sub** : Next.js, React, TypeScript, Tailwind CSS, Supabase

**Tools** : Docker, Git, GitHub, Claude Code

---

## Career Journey

```
2015 ─── 웹 개발 (PHP) ─── 음악 스트리밍 서비스 전체 리뉴얼
   │
2018 ─── PM / 마케팅 ─── 블록체인 거래소, 기술 마케팅 주도  
   │
2021 ─── 창업 (카페) ─── 브랜딩부터 물류/CS까지 직접 운영
   │
2023 ─── 백엔드 개발 ─── Java/Spring 전환, AI 활용 개발
   │
 Now ─── 성장 중 ─── 매일 코드 작성, 꾸준한 학습
```

---

<div align="center">

### 🔥 Growth Mindset

**"완벽한 준비란 없다. 시작하고, 부딪히고, 성장한다."**

새로운 기술을 두려워하지 않습니다.  
AI 시대의 변화를 기회로 삼아, 매일 조금씩 더 나은 개발자가 되고 있습니다.

</div>

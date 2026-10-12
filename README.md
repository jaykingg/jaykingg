<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=36BCF7&center=true&vCenter=true&width=720&lines=Hi+there%2C+I'm+Jayking+%F0%9F%91%8B;Product+Lead+Engineer+%C2%B7+Backend;Multi-tenant+WMS+%C2%B7+5+tenants+%C2%B7+4+regions;AI+does+the+work%2C+humans+review+the+result" alt="Typing SVG" />

<p>
  <a href="https://jaykingg.github.io/jaykingg/resume/">
    <img src="https://img.shields.io/badge/Resume-D98A2B?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Web Resume" />
  </a>
  <a href="https://jaykingg.notion.site/Public-Resume-Career-ec694bdc032a4afe921dea5a225ac0e3">
    <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" alt="Notion Resume" />
  </a>
</p>

<i>"AI 가 일하는 환경을 만들고, 사람이 검토하는 단계를 설계하는 엔지니어"</i>

</div>

---

## 🙋🏻‍♂️ About Me

```yaml
name: Jayking (모준서)
role: Product Lead Engineer / Backend (6+ years)
now: 글로벌 3PL · 멀티테넌트 WMS 설계·운영 · 8인 스쿼드 배포·회고 운영 · 기획·코드 정책 정의
values:
  - 선한 영향력을 가진 사람          # Good influence
  - 해야 하는 것은 반드시 하는 사람    # Always do what I have to do
  - 보이지 않는 곳에서도 정직한 사람   # Honest even out of sight
mission: 어제보다 더 나은 삶을 만드는 기술에 기여하는 개발자
thinking:
  - AI 가 자동으로 할 수 있는 일은 환경을 만들어 맡기고, 생긴 시간은 사람의 검토와 정제에 쓴다
  - 이상을 숨기는 시스템이 아니라, 이상을 스스로 드러내는 시스템
```

---

## 🚀 Impact Highlights

> 글로벌 3PL 물류 플랫폼 · 월 1.6~2.3만 건 출고 · 5개 테넌트 · 4개 리전 · 8인 스쿼드(PM 1 · FE 2 · BE 4 · QA 1)

| | |
|---|---|
| 🤖 **AI 작업 방식** | 분석 → 구현 → 리뷰 → 문서화를 AI 가 한 흐름으로, 결과는 **사람이 diff 와 근거를 검토**한 뒤 반영 |
| 🏛️ **팀 정책 저장소** | 7개 도메인 규칙 **432건** ID 이관 · Claude Code 플러그인 배포 · 정책 판정 누락 PR 은 **CI 가 머지 차단** |
| 🧭 **프로덕트 운영** | 2024-10 PLE 지정 · 리전별 배포 일정 **74회** 운영 · 회고 **24회** 주최 · PRD 2종 · DORA 기반 팀 KPI |
| 🤝 **협업 조율** | "설명과 확정의 분리" 제안 → 고객사 채널 통합 · 인입 기준 · Slack 워크플로 제품화 · 인시던트 커뮤니케이션 12건 |
| 🟢 **서비스 가용성** | 99.6% → **99.99%** (Major 장애 월 0건) |
| ⚡ **장애 복구 MTTR** | 30분 → **1분 이내** |
| 📊 **DORA CFR** | 2025 **10.1%** → 2026 상반기 **5.4%** (잠정) |
| 🔁 **테넌트 온보딩** | 수동 SQL 14단계 → **단일 트랜잭션 API** |
| 🏅 **품질 인증** | **GS 인증 1등급** (헥사고날 아키텍처 도메인 분리) |

<sub>주요 설계: 멀티테넌시 · EDA · 헥사고날 아키텍처 · Feature Flag 엔진 · Redis Rate Limiting · 서버사이드 송장 렌더링(LMS) · 입고 v2 상태머신</sub>

---

## 🤖 AI-Native Engineering

> AI 가 자동으로 할 수 있는 일은 환경을 만들어 맡기고, 그렇게 생긴 시간을 사람의 검토와 정제에 씁니다.<br>
> 자동화의 목적은 사람을 빼는 게 아니라 사람이 검토할 시간을 만드는 것입니다.

```text
자동화 → 시간 확보 → 사람의 검토·판단 → 기준화 → AI 하네스 → 더 정교한 자동화 → 반복
```

- 🧩 **작업이 끝나면 문서가 남는 구조** - 티켓 분석 → 구현 → 리뷰 → PR → 문서 갱신을 Claude Code 스킬로 한 흐름으로 묶었습니다. 문서화 시간을 따로 잡지 않아도 도메인 문서·트러블슈팅·ADR 이 같이 갱신됩니다 (의사결정 기록 279건 · 지식 문서 1,144건 누적)
- 🔍 **사람이 검토하는 단계** - 메인 세션은 설계·검토, 구현은 서브에이전트에 위임하고 결과 diff 를 직접 읽습니다. 근거(코드 경로·commit SHA) 없는 문장은 `TODO-VERIFY` 로 표시하고, 문서와 코드가 어긋나면 린트가 잡습니다. 운영 판단은 DB 와 로그로 확인한 뒤에만 결론으로 씁니다
- 🏛️ **팀 정책 저장소 + 플러그인** - 코드를 열지 않아도 도메인 규칙에 답하는 저장소에 규칙 432건을 ID 로 옮기고, 세션 시작 hook 이 변경 파일 경로로 도메인을 추론해 규칙을 먼저 읽게 했습니다. 팀원 5명이 직접 정책 PR 12건을 올리고, 정책 판정을 건너뛴 코드 PR 은 4개 레포에서 CI 가 머지를 막습니다
- 🔀 **Jira 상태 자동 전이** - PR 열림·승인·병합·닫힘·배포 5종 이벤트로 4개 레포 티켓 상태를 전이, 코드 변경 0. 승인 시점을 KPI 종점으로 재정의
- 🚀 **팀 확산** - "AI 시대의 엔지니어링" 팀 발표, PnE 아고라 발표, AI 워크플로 사례·프롬프트 템플릿 공유. 회고 후속으로 "AI 대화는 사람이 검토" 를 팀 규칙으로 공지

<sub>"어떤 모델을 쓰느냐보다, 그 모델이 제대로 일할 환경을 어떻게 만드느냐가 더 중요한 질문이 되고 있습니다."</sub>

---

## 🧭 Product Leading · 🤝 Collaboration

- **배포 일정 운영** - 리전별 리스트업 · 시각 확정(KST/PST/HKT 병기) · 사전 공지 74회. hotfix 6단계와 "main 머지 시점 = 배포 제어" 원칙 수립
- **기획·코드 정책 정의** - 입고 고도화 PRD 661줄, 배송 요율 연동 PRD 318줄. 기획 단계에서 정해져야 할 항목을 먼저 짚어 Product 와 합의한 뒤 구현으로 넘깁니다
- **회고·KPI** - 2024-08 부터 스프린트 회고 24회 주최, 팀 성과 등급 기준 초안과 DORA Baseline 측정체계를 팀장 위임으로 작성
- **운영 요청 인입 체계** - 엔지니어 직접 소통의 위험을 정리해 "설명과 확정의 분리" 제안, 고객사 채널 통합 · 인입 형식 · 긴급 기준 · 창구 일원화를 Slack 워크플로로 제품화
- **인시던트 커뮤니케이션** - 장애가 나면 현상 → 원인 → 조치 → 재발 방지 순서로 직접 정리해 공유 (12건)
- **코드 리뷰 문화** - 리뷰 요청 117 · 답글 85, readOnly 트랜잭션 단위 · V2 객체 규칙 · DDL 리뷰 표준을 팀 공통 규칙으로

---

## 🛠️ Tech Stack

**Main**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Ktor](https://img.shields.io/badge/Ktor-087CFA?style=flat-square&logo=ktor&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)

**Data**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)

**Infra / Tools**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)

<sub>🌱 Currently focusing on **Kotlin · Kafka · DDD · Claude Code (Skills · Hooks · Plugin · MCP)** · Experience with **Webflux, MSA, BDD, JPA, Electron**</sub>

---

## 🔥 Activity

<div align="center">

<img src="https://streak-stats.demolab.com/?user=jaykingg&theme=tokyonight&hide_border=true" alt="streak" />

</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=jaykingg&style=flat-square&color=36BCF7" alt="profile views" />
</div>

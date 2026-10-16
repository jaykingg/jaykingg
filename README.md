<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=36BCF7&center=true&vCenter=true&width=720&lines=Hi+there%2C+I'm+Jayking+%F0%9F%91%8B;Product+Lead+Engineer+%C2%B7+Backend;Multi-tenant+WMS+%C2%B7+5+tenants+%C2%B7+4+regions;AI+makes+the+time%2C+humans+make+the+call" alt="Typing SVG" />

<p>
  <a href="https://jaykingg.github.io/jaykingg/resume/">
    <img src="https://img.shields.io/badge/Resume-D98A2B?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Web Resume" />
  </a>
  <a href="https://jaykingg.notion.site/Public-Resume-Career-ec694bdc032a4afe921dea5a225ac0e3">
    <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" alt="Notion Resume" />
  </a>
</p>

<i>"AI 로 시간을 만들고, 그 시간을 판단과 문제 해결에 쓰는 Product Lead Engineer"</i>

</div>

---

## 🙋🏻‍♂️ About Me

```yaml
name: Jayking (모준서)
role: Product Lead Engineer / Backend (6+ years)
now: 글로벌 3PL · 멀티테넌트 WMS 설계·운영 · 제품 관점에서 기획부터 배포까지 리딩
values:
  - 선한 영향력을 가진 사람          # Good influence
  - 해야 하는 것은 반드시 하는 사람    # Always do what I have to do
  - 보이지 않는 곳에서도 정직한 사람   # Honest even out of sight
mission: 어제보다 더 나은 삶을 만드는 기술에 기여하는 개발자
thinking:
  - 반복되는 일은 AI 환경으로 시간을 만들고, 그 시간은 검토·도메인 이해·문제 해결에 쓴다
  - 이상을 숨기는 시스템이 아니라, 이상을 스스로 드러내는 시스템
```

---

## 🚀 Impact Highlights

> 글로벌 3PL 물류 플랫폼 · 월 1.6~2.3만 건 출고 · 5개 테넌트 · 4개 리전<br>
> AI 엔지니어링 환경, 협업과 업무 프로세스, 도메인 지식 저장소와 자동화를 직접 만들어 팀이 일하는 방식을 바꿔 왔습니다.

**📦 WMS 주요 성과**

| | |
|---|---|
| 🌏 **글로벌 리전 확장** | 4개 리전 순차 오픈(WAC → JS → JP), 신규 테넌트 오픈을 수작업 없이 **반복 가능한 절차**로 전환 |
| 📥 **입고 프로세스 재구축** | 현장 운영 방식에 맞춘 신규 입고 프로세스 설계 · 구축 (의사결정 기록 46건 · 단위 테스트 446건) |
| 🚚 **배송 요율과 정산 연계** | 다중 배송사 요율 비교부터 정산까지 하나의 흐름, US 실데이터 대조 **61조합 중 차이 1건** |
| 🛡️ **서비스 안정성** | 변경 실패율 2025 **10.1%** → 2026 상반기 **5.4%**(잠정), 장애 감지와 복구 30분 → **1분 이내** |
| 🏅 **품질 인증** | **GS 인증 1등급** (헥사고날 아키텍처로 도메인과 인프라 분리) |

**⚙️ 엔지니어링 성과**

| | |
|---|---|
| 🤖 **AI 엔지니어링 환경** | 팀 단위 AI 개발 환경 구축, 도입 후 merged PR 월 **8.2 → 22.1건** |
| 🤝 **업무 프로세스 구축** | 운영 요청 인입 체계 · 배포 원칙과 hotfix 절차 · 회고와 DORA 기반 KPI 체계 정례화 |
| 📚 **지식 저장소와 자동화** | 도메인 규칙 **432건** 정책화, 지식 문서 **1,144건** · 의사결정 기록 **279건**, Jira 상태 자동 전이 |

---

## 🤖 AI 엔지니어링 환경

> 반복되는 일은 AI 가 처리할 수 있는 환경을 만들어 시간을 확보합니다.<br>
> 그렇게 생긴 시간은 결과 검토, 도메인 이해, 문제를 어떻게 풀지 고민하는 데 사용합니다.

```text
자동화 → 시간 확보 → 사람의 검토·판단 → 기준화 → AI 하네스 → 더 정교한 자동화 → 반복
```

- 🧩 **한 흐름의 작업 방식** - 티켓 분석 → 구현 → 리뷰 → PR → 문서를 Claude Code 스킬로 묶었고, 반영은 사람이 diff 와 근거를 확인한 뒤에만 합니다
- 🔍 **AI 산출물 검증** - 근거(코드 경로 · commit SHA) 없는 문장은 `TODO-VERIFY` 로 표시하고, 운영 판단은 DB 와 로그로 확인한 뒤에만 결론으로 씁니다
- 👥 **팀 환경으로 배포** - 팀원이 작업을 시작하면 해당 도메인 규칙을 AI 가 먼저 읽도록 플러그인으로 묶어, 누구나 같은 규칙과 같은 흐름으로 개발합니다
- 🚀 **팀 확산** - "AI 시대의 엔지니어링" 팀 발표, PnE 아고라 발표, AI 워크플로 사례 · 프롬프트 템플릿 공유

<sub>"어떤 모델을 쓰느냐보다, 그 모델이 제대로 일할 환경을 어떻게 만드느냐가 더 중요한 질문이 되고 있습니다."</sub>

---

## 📚 도메인 지식 저장소와 자동화

- **정책 저장소** - 코드에만 있던 도메인 규칙 432건을 ID 가 붙은 정책으로 정리해 사람과 AI 가 같은 기준으로 개발합니다. 팀원 5명이 직접 정책 PR 12건을 올렸고, 정책 반영 여부는 PR 단계에서 자동으로 확인합니다
- **작업이 끝나면 문서가 남는 구조** - 도메인 문서 · 트러블슈팅 · 의사결정 기록이 함께 갱신되어 같은 질문을 다시 조사하지 않습니다 (지식 문서 1,144건 · 의사결정 기록 279건)
- **업무 자동화** - Jira 상태는 PR 이벤트만으로 따라와 리드타임을 수동 갱신 없이 측정하고, 신규 테넌트 오픈은 단일 트랜잭션 API 로 반복 가능한 절차가 되었습니다

---

## 🤝 협업과 업무 프로세스

- **운영 요청 인입 체계** - "설명과 확정의 분리" 를 제안해 고객사 채널을 통합하고 인입 형식 · 긴급 기준 · 창구를 정해 각 직군이 역할을 명확히 수행하도록 했습니다
- **배포 일정 운영** - 리전별 리스트업 · 시각 확정 · 사전 공지 74회, hotfix 절차와 배포 원칙 수립
- **회고 · KPI** - 2024-08 부터 스프린트 회고 24회 주최, DORA 기반 팀 KPI 체계와 성과 등급 기준 초안 작성
- **장애 공유** - 장애가 나면 원인 · 조치 · 타임라인을 직접 정리해 공유합니다

---

## 🧭 제품 관점

- 현장 작업자와 셀러가 실제로 일하는 방식을 기준으로 프로세스를 다시 설계합니다
- PRD 를 쓰고, 기획 단계에서 정해야 할 항목을 먼저 합의한 뒤 구현을 진행합니다
- 문제가 발생하면 제품 · 사용자 관점에서 함께 고민하여 재정의하고 즉각 실행에 옮깁니다
- 에러 없이 잘못된 값이 쌓이는 장애가 가장 위험하다고 보고, 문제가 바로 드러나는 시스템을 먼저 만듭니다

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

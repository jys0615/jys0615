<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=wave&color=#b897ff&height=120&text=&animation=&fontColor=000000&fontSize=70" />
</div>

<div align="center">
  <h1>안녕하세요, 정윤서입니다 👋</h1>
  <h3>💻 이기종 서버를 연결하고, 병목을 데이터로 찾아 구조적으로 해결하는 백엔드 개발자 🔧</h3>
  <p>
    Spring Boot × FastAPI로 이기종 서버를 연결하고,<br/>
    성능 병목을 프로파일링으로 찾아 구조적으로 해결합니다.
  </p>
</div>

<br/>

<div align="center">
  <a href="mailto:jys0615234@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/jys0615">
    <img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white"/>
  </a>
  <a href="https://yoonsuh.com">
    <img src="https://img.shields.io/badge/Portfolio-b897ff?style=for-the-badge&logo=Safari&logoColor=white"/>
  </a>
</div>

<br/>

---

## 🛠️ Tech Stacks

**Backend**

<div align="center">
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"/>
</div>

<br/>

**AI / ML**

<div align="center">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=LangChain&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=HuggingFace&logoColor=black"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=OpenAI&logoColor=white"/>
</div>

<br/>

**Database & Infra**

<div align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=Redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=AmazonAWS&logoColor=white"/>
</div>

<br/>

---

## 🏆 수상 경력

| 연도 | 대회 | 수상 |
|------|------|------|
| 2025 | 경희대학교 제1회 세모톤 | 최우수상 |
| 2023 | 제4회 아름다운 사회복무요원 사랑나눔 공모전 | 우수상 |

<br/>

---

## 🚀 Projects

### 🤖 Agent KHU — AI 기반 캠퍼스 정보 통합 플랫폼
> MCP 아키텍처로 독립 서버를 통합한 AI 에이전트 | **2025.09 ~ 2025.12** | 졸업프로젝트 A+

- 7개 독립 MCP 서버 설계 (교실·공지·도서관·학사일정·셔틀버스 등)
- cProfile로 I/O 병목 진단 → asyncio.gather 병렬처리 + Redis 멀티레이어 캐싱 도입
- 응답시간 **16.6초 → 5.5초 (67% 단축)**, 에러율 **15% → 2%**, 캐시 히트율 **95%** 달성
- Graceful Degradation 설계 — 외부 서비스 장애 시에도 서비스 중단 없음

`FastAPI` `LangChain` `MCP` `PostgreSQL` `Redis` `Docker`

---

### 🎓 EPiC — 학번별 졸업요건 자동 진단 시스템
> 경희대 졸업요건을 LLM이 자동 분석·진단하는 AI 서비스 | **2025.03 ~ 2025.04** | 세모톤 최우수상

- FastAPI LLM 서버 + Spring Boot 관리 서버 이원화 아키텍처 설계
- JSON 명세 불일치 트러블슈팅 → API 전면 표준화로 이기종 서버 통신 안정화
- WebClient 비동기 처리 + Redis 캐싱 도입으로 **응답속도 30% 개선**
- Spring Security + JWT 기반 보안 아키텍처 구현

`FastAPI` `LangChain` `Spring Boot` `Redis` `PostgreSQL` `Docker`

---

### 🏛️ 민들레 — 동대문구 민원 자동화 플랫폼
> 4개 서버를 하나의 트랜잭션처럼 연결하는 오케스트레이션 구조 | **2025.07 ~ 2025.08**

- Next.js → Spring Boot → FastAPI → Node.js 4단계 API 오케스트레이션 설계
- 상태 플래그 기반 이벤트 구조 도입 → 서버 간 **DB 정합성 100%** 확보
- Request Chaining 최적화로 불필요한 중간 호출 제거

`Next.js` `Spring Boot` `FastAPI` `Node.js` `PostgreSQL`

---

### 🎤 InterV — LLM 기반 면접 생성 서비스
> AWS 인프라 기반 실서비스 품질의 면접 Q&A 생성 시스템 | **2025.03 ~ 2025.06** | 클라우드컴퓨팅 A+

- LangChain 프롬프트 템플릿 + BERTScore 기반 피드백 평가 파이프라인 구현
- cProfile로 모델 로딩 병목 진단 → 모델 캐싱 + 비동기 I/O + JSON 직렬화 최적화
- AWS EC2/RDS/S3/CloudFront 기반 배포 및 운영

`Spring Boot` `FastAPI` `LangChain` `AWS EC2/RDS/S3` `CloudFront`

---

### 👴 SeniorSK — 어르신 대상 키오스크 실전 학습 웹
> 사회복무 중 관찰한 문제를 직접 해결한 프로젝트 | **2023.01 ~ 2023.12** | 사랑나눔 공모전 우수상

- 튜토리얼 모드 + 실전 연습 모드 분리 설계
- 실사용자 시연 반복 → 피드백 기반 UI/UX 개선, 실수 복구 기능(되돌리기/재시작) 구현

`HTML/CSS/JS`

---

### 🧠 Open Patient-Ψ — 오픈소스 정신건강 상담 시뮬레이션
> GPT-4 기반 환자 시뮬레이션 구조를 경량 오픈소스 모델로 재현 | **2025.03 ~ 2025.07** | KCC2025 제1저자

- CBT 기반 상담 데이터셋 1,300개 직접 구축 (ChatML 포맷 정규화)
- QLoRA로 Qwen2.5 0.5B/3B 파인튜닝 — 총 **25개 하이퍼파라미터 조합** 자동 실험
- BERTScore 기반 자동 평가 파이프라인 → **GPT-4.1-nano 수준 품질 달성**

`QLoRA` `Qwen2.5` `HuggingFace` `BERTScore` `FastAPI`

<br/>

---


<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=wave&color=#b897ff&height=80&section=footer" />
</div>

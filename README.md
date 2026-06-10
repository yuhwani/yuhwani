# 안녕하세요, 김유환(yuhwani)입니다 👋

**AI·데이터 기반 서비스를 기획하고 끝까지 구현하는 개발자**입니다.
문제 정의 → 모델링 → 백엔드 → 배포·운영까지 전 과정을 직접 다루며,
특히 **AI(ML/LLM)** 와 **보안(DevSecOps·데이터 보호)** 을 함께 챙기는 개발을 지향합니다.

---

### 📌 주요 프로젝트

| 프로젝트 | 한 줄 소개 | 핵심 기술 |
|---------|-----------|----------|
| [**StockView**](https://github.com/yuhwani/StockView) | 한국·미국 주식을 ML·기술적 지표·실시간 이벤트로 분석하는 풀스택 투자 보조 웹앱 | FastAPI · React · RF/XGBoost/LSTM · Gemini · Telegram Bot |
| [**radar-guard**](https://github.com/capdiinmyear/radar-guard) | 4D mmWave 레이더 기반 환자 낙상 실시간 감지 시스템 (의료진 허브 + 보호자 PWA) | Bi-LSTM · FastAPI · Next.js · SQLCipher · Docker(ARM64) · SSE/Web Push |
| [**AI 시간표 추천**](https://github.com/gibunijjaejo/Opensource_Project) | 서강대 학생용 AI 시간표 추천 서비스 — CI/CD에 보안 자동화를 통합한 DevSecOps 파이프라인 | Next.js · FastAPI · Jenkins · Trivy/ZAP/SonarCloud/DefectDojo · Prometheus/Grafana |

#### 📈 StockView — "예측을 과대포장하지 않는" 투자 보조 서비스
- RF·XGBoost·LSTM을 같은 분할에서 비교하고, **walk-forward(시간순) 검증 + 확률 보정 + 앙상블**로 신뢰도를 관리
- FDR·네이버 증권·DART 공시·NASDAQ 등 **다중 소스 데이터 파이프라인** (소스 장애 시 백업·캐시로 무중단)
- 관심 종목 급등락·공시·뉴스를 3분 주기로 감지해 **텔레그램 실시간 알림**
- 약 9만 종목-일 백테스트로 각 근거의 실제 예측력을 측정해 공개하는 **정직한 검증**이 차별점

#### 🛏 radar-guard — 비접촉 낙상 감지, 프라이버시와 보안까지
- 카메라 없이 **mmWave 레이더 + Bi-LSTM**으로 낙상을 실시간 감지 (RunPod GPU 학습)
- 의료진용 허브 + 보호자용 PWA, **SSE·Web Push(VAPID)** 로 즉시 알림
- 환자 데이터는 **SQLCipher 암호화 DB**로 보호, Raspberry Pi(ARM64) Docker 배포까지 직접 운영

#### 🔐 AI 시간표 추천 — AI 서비스에 DevSecOps를 입히다
- Mistral OCR·Groq·Gemini를 활용한 시간표 추천 파이프라인
- Jenkins CI/CD에 **Trivy(컨테이너)·ZAP(동적)·SonarCloud(정적)·DefectDojo(취약점 관리)** 를 통합한 보안 자동화
- Prometheus·Loki·Grafana 기반 모니터링으로 운영 가시성 확보

---

### 🎯 Interests

- **AI** — 시계열·센서 데이터 모델링, LLM 활용 서비스, 모델 검증(과적합·정보 누설 방지)
- **Security** — DevSecOps 파이프라인, 데이터 암호화, 보안을 기본값으로 하는 서비스 설계

---

### 📫 Contact

- Email: cndqnr346@gmail.com
- Blog / Notion: [링크]

---

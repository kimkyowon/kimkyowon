<div align="center">

# 김교원 · Kyowon Kim

**Embedded Software Engineer**

STM32 · FreeRTOS · ARM Cortex-M · Linux

[![Blog](https://img.shields.io/badge/Tistory-why--not--working-000000?style=flat-square&logo=tistory&logoColor=white)](https://why-not-working.tistory.com)
[![Email](https://img.shields.io/badge/Email-dnjs6945@naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:dnjs6945@naver.com)

</div>

---

## About

방산·드론 전문 기업에서 병역특례로 2년 3개월간 펌웨어 엔지니어로 근무했습니다.
군용 드론 조종기 펌웨어 개발부터 B2C 제품 양산(4,000대+)까지 경험했으며,
저수준 제어와 시스템 안정성에 관심이 많고, 설계 결정의 이유를 중요하게 생각합니다.

- 🎓 한양대학교 ERICA · ICT융합학과 (2026.02 졸업) · 전공 GPA 3.8 / 4.5
- 🏢 ㈜보라스카이 F/W Engineer (2022.06 ~ 2024.08, 병역특례)
- 📝 [기술 블로그](https://why-not-working.tistory.com) — FreeRTOS, ARM Cortex-M, 프로젝트 개발기

---

## Projects

### 🚁 드론 조종기 하위 모듈 통합 관리 시스템
> STM32F401RE · SMBus · ADC · PWM · 방산 납품 · 기여도 80%

- SMBus 멀티 모듈 버스 충돌 방지 설계로 배터리 통신 안정화
- ADC 중앙값 필터로 노이즈 환경에서의 전압 측정 정확도 향상
- 온도 비례 PWM 팬 제어 · Ringbuffer 기반 실시간 프로토콜 파싱 구현
- 방위사업청 무기적합성 평가 통과

### 🎩 스마트 모자 관리 디바이스
> STM32 · Moore FSM · 히터 제어 · 양산 4,000대+

- 히터 과열 방지 FSM 설계 — 오작동 상태전이 원천 차단
- 요구사항 정의 → 펌웨어 개발 → 양산 가이드라인 작성까지 전 과정 독립 수행

### 🎯 드론 정밀 착륙 시스템 _(캡스톤 장려상)_
> YOLOv8n · Hailo-8L · Kalman Filter · STM32 · RPi5

- YOLOv8n + Hailo NPU 조합으로 27 FPS 실시간 객체 검출
- I2C + GPIO 이중 채널 통신으로 단일 경로 장애 대비
- Kalman Filter 기반 위치 예측으로 착륙 정확도 개선

### 📰 IT 뉴스 자동 팩트체킹 모니터
> Python · Claude API · Tavily · GitHub Actions · Google Sheets

- 매주 IT 키워드 뉴스를 자동 수집 후 PolitiFact 방법론 기반 6단계 신뢰도 판정
- GitHub Actions cron으로 완전 자동화, Google Sheets 대시보드에 누적
- RAG 파이프라인: Tavily 검색 → 데이터 정제 → Claude Sonnet 판정

---

## Tech Stack

| 영역 | 기술 |
|------|------|
| **Language** | C · C++ · Python |
| **MCU / Board** | STM32 · Raspberry Pi · ESP32 · Arduino |
| **RTOS / OS** | FreeRTOS · Linux |
| **Protocol** | UART · SPI · I2C · SMBus · CAN |
| **Tools** | Git · TRACE32 · Keil · STM32CubeIDE |
| **AI / Automation** | Claude API · Tavily · GitHub Actions |

---

## Education & Activities

**한양대학교 ERICA · ICT융합학과** (2018.03 ~ 2026.02)
전공 GPA 3.8 / 4.5 · 성적장학금 수혜 (학과 전체 4등)

| 기간 | 활동 |
|------|------|
| 2025.12 ~ 2026.01 | **MDS Tech** — TRACE32 입문·고급·Linux Debugging 교육 수료 |
| 2024.12 ~ 현재 | **지능형로봇사업단** — 일반인 대상 로봇 교육, 대외 행사 운영 (CO-Show · 88로봇데이), 2025.05~ 팀장 |
| 2024.04 | **한국사물인터넷협회** — STM32 + FreeRTOS + AWS IoT 연동 실습 수료 |
| 2023.12 ~ 2024.02 | **코멘토** — 리눅스 디바이스 드라이버 개발 과정 수료 |
| 2021.06 ~ 2021.08 | **Knowledge Dorm 2기** — 창업가 육성 프로그램 · 장려상 수상 |
| 2018.09 ~ 2019.02 | **소프트융합대학 학생회 집행부** — 단과대 행사 기획 및 운영 |

---

## Awards

- 🏆 ICT융합학부 캡스톤경진대회 장려상 (2025.05)
- 🏆 Knowledge Dorm 2기 성과발표회 장려상 (2021.08)
- 📊 TOEIC 720 (2025.08)

---

## Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kimkyowon&show_icons=true&theme=default&hide_border=true&title_color=34495E&icon_color=34495E" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kimkyowon&layout=compact&langs_count=6&theme=default&hide_border=true&title_color=34495E&icon_color=34495E" />
</div>

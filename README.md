<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Welcome%20to%20my%20GitHub!&fontSize=50" />
</div>

## 💡 About Me
새로운 기술을 빠르게 익히고 실제 문제에 적용하는 과정에 몰입하는 **응용 소프트웨어 개발자**입니다.
소프트웨어(프론트엔드·AI)와 하드웨어(IoT·로보틱스)를 넘나들며, **사용자 중심의 UI/UX 개선**과 **다양한 환경을 고려한 시스템 설계**에 관심이 많습니다. 혼자보다는 팀 단위의 협업을 통해 문제를 다각도로 바라보고 해결하는 것을 즐깁니다.

- 🔭 프론트엔드(React, TypeScript)를 기반으로, ROS2·임베디드(ESP32/STM32/Raspberry Pi)까지 다루며 소프트웨어와 하드웨어 양쪽에서 시스템을 설계·구현합니다.
- 🌱 KCI 등재 논문 연구 및 KISIA 보안 크루 활동을 통해, 시스템의 깊은 구조와 안전성까지 고려하는 탄탄한 개발 기본기를 다졌습니다.
- 🎯 작은 변화라도 구조를 설계하고 실행으로 옮기는 것을 중요하게 생각합니다.
- 📫 How to reach me: dongim0712@gmail.com
- 🌐 My Portfolio: https://dongim-02.github.io
- 👨‍💻 My Profile: https://sites.google.com/view/dongimhan
- 💼 LinkedIn: https://www.linkedin.com/in/dongim-han

<br/>

## 🛠️ Tech Stack

### Frontend & UI/UX
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"/>
</p>

### Embedded & Robotics
<p>
  <img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white"/>
  <img src="https://img.shields.io/badge/ESP32%2FSTM32-E7352C?style=for-the-badge&logo=espressif&logoColor=white"/>
  <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=Raspberry-Pi&logoColor=white"/>
  <img src="https://img.shields.io/badge/FreeCAD-CB333B?style=for-the-badge&logo=freecad&logoColor=white"/>
  <img src="https://img.shields.io/badge/Mitsubishi_PLC-DC0032?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/GT--Designer3-DC0032?style=for-the-badge"/>
</p>

### AI & Data
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=OpenCV&logoColor=white"/>
</p>

### Security & Systems
<p>
  <img src="https://img.shields.io/badge/System_Security-4A154B?style=for-the-badge&logo=cyberdefenders&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firmware_Fuzzing-4A154B?style=for-the-badge&logo=cyberdefenders&logoColor=white"/>
</p>

<br/>

## 🚀 Key Projects

### 🤖 Robotics & Embedded

**AutoFactory ROS2 — 자동화 팩토리 시스템** *(대한상공회의소 서울기술교육센터 / [`qkrrkdtj/autofactory-ros2`](https://github.com/qkrrkdtj/autofactory-ros2))*<br/>
ROS2 기반 자동화 팩토리 시스템 구현 프로젝트. FreeCAD로 알약 디스펜서 구조를 3D 모델링하고, 스텝 모터 정밀 제어 모듈을 구현해 공정 자동화 로직을 완성했습니다.
`ROS2` `Python` `FreeCAD` `Step Motor`

**Drive — WebSocket 기반 RC카 원격 제어 시스템** *(대한상공회의소 서울기술교육센터 / [`kdm111/team2`](https://github.com/kdm111/team2))*<br/>
웹 대시보드와 음성 인식으로 RC카를 실시간 조종하는 저지연 제어 시스템. 통신(ESP32)과 제어(STM32)를 분리한 이중화 MCU 아키텍처를 채택했고, 수신 데이터 노이즈로 인한 패킷 유실 문제를 스트리밍 파싱 방식으로 해결했습니다.
**담당:** ToF 센서 연동 및 라즈베리파이 카메라 모듈 테스트, 웹 실시간 연동 구성
`WebSocket` `C/C++` `ESP32/STM32` `UART 통신` `ToF 센서` `Raspberry Pi`

**Mini-Project — PLC 기반 자동화 설비 제어 시스템** *(대한상공회의소 서울기술교육센터)*<br/>
Mitsubishi PLC(GX-Works2)를 중심으로 서보 모터·센서·알람 지시기·HMI(GOT 터치스크린)를 통합해 자동/수동 겸용 자동화 설비 제어 시스템을 구현했습니다. BSFL, MOV/DMOV 등 래더 로직으로 공정 순차 제어와 서보 위치 티칭을 구현했습니다.
**담당:** PLC 래더 코드 작성 및 HMI(GT-Designer3) 화면 설계
`Mitsubishi GX-Works2` `PLC 래더 로직` `GT-Designer3` `Servo 제어`

**IoT 보안 알림 시스템 — 침입 감지 이메일 알림** *(백석대학교 'IoT보안프로그래밍' 교과목)*<br/>
Raspberry Pi와 PIR 센서로 침입을 감지하고 카메라로 현장을 촬영, 이미지를 Base64로 인코딩해 SMTP 서버로 즉각 경고 이메일을 전송하는 실시간 침입 감지 파이프라인.
**담당:** 아이디어 제안, 초기(변경 전) 시스템 구현, 카메라 촬영 파트 구현
`Python` `Raspberry Pi` `PIR Sensor` `SMTP` `MIMEBase/Base64`

### 🧠 AI & Data

**Virtual Try-On System — 가상 피팅 데이터 파이프라인** *(대한상공회의소 서울기술교육센터 / [`qkrrkdtj/virtual-fitting-pipeline`](https://github.com/qkrrkdtj/virtual-fitting-pipeline))*<br/>
사용자 이미지 기반 가상 의류 피팅 시스템. 이미지 리사이즈 → OpenPose(골격 인식) → SCHP(인체 파싱) → 마스크 생성으로 이어지는 10단계 프로세스를 설계하고, StableVITON 모델 학습에 적합한 데이터셋으로 자동 정제하는 백엔드 파이프라인을 구축했습니다.
**담당:** 의류 이미지 크롤링 및 데이터 전처리 파이프라인 구축
`Python` `FastAPI/React` `PyTorch` `OpenCV` `StableVITON`

### 🛡️ Security

**Co-EDR 기반 펌웨어 퍼징 시스템** *(KISIA 융합보안크루 1기 / 조장)*<br/>
다수 IoT 장치의 협력 기반 EDR 기법을 활용해 펌웨어 퍼징 효율성과 패치 검증 신뢰성을 연구. 단일 장치가 놓칠 수 있는 취약점을 교차 수집하고, 오류 이벤트를 유발한 인풋 기반으로 퍼징을 수행해 기존 대비 퍼징 효율성을 최대 41.8% 향상, 탐지 시간을 99.9% 단축했습니다.
**성과:** KISTI 원장상 수상, KCI 등재 논문 게재
`Firmware Fuzzing` `EDR 기법` `IoT Security` `KCI 논문`

<br/>

## 🏆 Awards & Honors
- **대상:** [KDT] AI융합 로봇 SW개발자 2기 (대한상공회의소 주관, 2026.07)
- **KCI 등재 논문:** 고효율 고신뢰 펌웨어의 최적화된 퍼징을 위한 이벤트 데이터 레코딩 기법 (2025.02)
- **최우수 크루상:** ICT 융합 보안크루 1기 (KISIA 주관, 2024.11)
- **KISTI 원장상:** 제7회 부채널 정보분석 경진대회 (KIISC 주관, 2024.07)
- **공모전 수상:** 창업 발명 공모전 단체상 (국제문화기술진흥원, 2024.06)

<br/>

## 🧩 Activities
- 대한상공회의소 AI융합 로봇 SW개발(2기) — 반도체SW·AI비전 과정 (2025.12 ~ 2026.07)
- 백석대학교 정보보호 동아리 HUB — 교내 보안 동아리 (2025.03 ~ 2025.12)
- 해외 일경험 — 일본 G&G 서비스 인턴십 (2025.06 ~ 2025.08)
- ICT 융합 보안크루 1기 — IoT 보안 과정 · KISIA (2023.12 ~ 2024.11)

<br/>
# 박진원 프로젝트 포트폴리오

문제 해결과 실제 구현 경험을 바탕으로 진행한 프로젝트들을 정리한 공간입니다.

---

## About Me

* **전공:** 전자공학
* **관심 분야:** 임베디드, 백엔드, AI/비전
* **기술 스택:** C++, Python, JavaScript, Node.js

---

## Projects

### AI 안면 인식 스마트 도어락 시스템 (Face Recognition AI DoorLock)

Raspberry Pi 5와 ESP32를 UART 시리얼 통신으로 연동하여 사용자를 실시간으로 식별하고 출입을 제어하는 보안 시스템입니다.

* **기술 스택:** Python, C++, Raspberry Pi 5, ESP32, YOLOv8, OpenCV
* **주요 기능:**
  * **YOLOv8 기반 실시간 안면 인식:** Custom Dataset을 학습시켜 인가된 사용자를 높은 정확도로 분류
  * **멀티 플랫폼 연동:** Raspberry Pi(비전 추론)와 ESP32(하드웨어 제어) 간 UART 통신 프로토콜 설계
  * **실시간 상태 시각화:** OLED 디스플레이를 통한 사용자 환영 메시지 및 시스템 상태 표시
  * **환경 최적화:** NoIR 카메라 특성에 따른 BGR 색상 채널 교정 및 데이터 파싱 안정화 구현

[프로젝트 보러가기](https://github.com/rootjihn/FaceDetect)

---

### YOLOv8 도로 혼잡도 분석 프로젝트

YOLOv8을 활용하여 도로 내 차량을 탐지하고, 차선별 혼잡도를 분석하여 웹 대시보드로 시각화한 프로젝트입니다.

* **기술 스택:** Python, YOLOv8, OpenCV, JavaScript
* **주요 기능:**
  * 차량 객체 탐지 및 트래킹
  * 차선별 실시간 차량 수 분석 로직 구현
  * 웹 기반 혼잡도 데이터 시각화

[프로젝트 보러가기](https://github.com/rootjihn/yolov8-traffic-dashboard)

---

### LLM·STM 연동 로켓 발사 시뮬레이션 관제 시스템

자연어 명령, 웹 대시보드, STM32 하드웨어 연동을 결합한 로켓 발사 시뮬레이션 관제 프로젝트입니다.

* **기술 스택:** HTML, CSS, JavaScript, Three.js, Chart.js, Node.js, Socket.IO, Ollama, Python, STM32
* **주요 기능:**
  * Three.js 기반의 3D 로켓 비행 시뮬레이션 구현
  * LLM(Ollama)을 통한 자연어 기반 발사 시퀀스 제어
  * STM32 보드 연동을 통한 실시간 물리 상태 데이터 모니터링

[프로젝트 보러가기](https://github.com/rootjihn/LLM-STM-rocket-launch-simulation)

---

## Contact

* **GitHub:** https://github.com/rootjihn

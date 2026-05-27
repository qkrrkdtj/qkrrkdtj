## Tech Stacks

### Languages
<p>
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
</p>

### AI & Computer Vision
<p>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white">
  <img src="https://img.shields.io/badge/Ultralytics_(YOLO)-00A3E0?style=for-the-badge&logo=ultralytics&logoColor=white">
</p>

### Embedded & Hardware
<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white">
  <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white">
</p>

### Environment & Tools
<p>
  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
</p>

<br>

## Projects

### 1. 스마트 글래스를 활용한 시각 장애인 보행 보조 어플 ([TripleK](https://github.com/2025TUKCOMCD/TripleK))
> **시각 장애인의 안전한 보행을 위해 실시간 위험 요소를 감지하고 음성으로 안내하는 안내 시스템**
- **Core Stacks**: `ESP32CAM`, `YOLOv12`, `Android Studio`, `TTS`
- **Key Features**:
  - ESP32CAM을 통해 실시간 영상 스트리밍 데이터 수집
  - YOLOv12 엔진을 활용한 고속 실시간 객체 및 위험 요소 인식 모델 구축
  - 안드로이드 어플리케이션 연동을 통해 촬영된 시각 정보를 고품질 TTS(Text-to-Speech) 음성으로 변환 및 안내

### 2. Safe Office ([safe-office](https://github.com/qkrrkdtj/safe-office))
> **다양한 MCU와 싱글보드 컴퓨터를 연동하여 안전하고 지능적인 사무실 환경을 구축하는 반응형 IoT 시스템**
- **Core Stacks**: `STM32`, `ESP8266`, `Raspberry Pi`, `IoT Sensors`
- **Key Features**:
  - STM32와 가속도/환경 센서를 활용한 실시간 상시 데이터 모니터링
  - ESP8266 서버 연동을 통한 무선 통신 인프라 및 실시간 이벤트 트리거 구현
  - Raspberry Pi 중앙 제어 시스템 허브 구축을 통한 디바이스 간 유기적 반응 제어

### 3. ROS2 YOLO PID Tracking ([ROS2_yolo_pid_tracking](https://github.com/qkrrkdtj/ROS2_yolo_pid_tracking))
> **로봇 운영체제(ROS2) 환경에서 Vision AI 알고리즘과 제어 이론을 융합한 실시간 타겟 추적 시스템**
- **Core Stacks**: `ROS2`, `YOLO`, `PID Control`, `C++ / Python`
- **Key Features**:
  - ROS2 노드(Node) 구조를 기반으로 한 카메라 영상 데이터 및 제어 명령의 실시간 퍼블리시/서브스크라이브 환경 구축
  - YOLO 모델을 통한 고정밀 타겟(Object) 인식 및 중앙 좌표 실시간 추적
  - 제어 오차를 최소화하기 위해 PID 제어 알고리즘을 적용하여 모터 액추에이터의 정밀 추적 동역학 구현

### 4. Virtual Fitting Pipeline ([virtual-fitting-pipeline](https://github.com/qkrrkdtj/virtual-fitting-pipeline))
> **기존 가상 의류 시착(VITON) 모델의 복잡한 전처리 과정을 자동화하고, 웹에서 바로 사용할 수 있도록 만든 파이프라인**
- **Core Stacks**: `Python`, `VITON Model`, `OpenCV`, `Web Framework (Flask/FastAPI 등)`
- **Key Features**:
  - 사용자가 이미지를 넣었을 때 모델 학습과 추론에 필요한 복잡한 전처리(인체 특징점 추출, 의류 이미지 정렬 등) 과정을 하나의 파이프라인으로 연결
  - 터미널 환경이 아닌 웹 브라우저를 통해 누구나 직관적으로 가상 시착 서비스를 테스트하고 이용할 수 있도록 구현

<br>

![header](https://capsule-render.vercel.app/api?type=waving&height=180&text=Dongje%20Lee&fontAlign=75&fontAlignY=40&color=gradient)

## 안녕하세요, 이동제입니다 👋

전기전자공학을 전공하며 **C언어 기반 MCU 제어와 임베디드 Linux 환경에서의 시스템 구현**을 경험했습니다.

센서 입력과 통신 데이터가 소프트웨어를 거쳐 실제 장치의 동작으로 이어지는 과정에 관심이 있습니다. Raspberry Pi·Hailo 기반 시스템 구현, 차량 통신 분석, 서보모터 기반 로봇 제작을 진행하며 하드웨어 설정과 코드 흐름, 실행 결과를 함께 확인해왔습니다.

**임베디드 소프트웨어 및 펌웨어 개발 직무**를 준비하고 있습니다.

## 대표 프로젝트

### 졸음운전 감지 및 경고 시스템
**캡스톤디자인 | 2024.09 ~ 2025.12**

Raspberry Pi 5·Hailo-8L·YOLOv8s를 활용해 운전자의 눈 상태를 탐지하고 경고하는 시스템을 개발했습니다. 카메라 입력부터 보드 추론, 센서 연동과 경고 출력까지 연결했습니다.

- 눈 상태 탐지 모델 전이학습 및 Hailo용 모델 변환·컴파일
- OS 설치, SDK·런타임 구성 및 패키지 의존성 문제 해결
- 카메라 영상의 탐지 결과 시각화 및 눈 감김 지속시간 기반 경고 기능 구현
- CO₂ 센서·부저 연동 및 보드·센서의 케이스 통합

[프로젝트 저장소](https://github.com/8ehemoth/Capstone-design)

### SOME/IP 통신 분석 및 LLM 보조 퍼징
**학부연구생 연구**

Ubuntu 환경에서 SOME/IP 서버·클라이언트 테스트 환경을 구성하고, 입력 변이에 따른 서비스 반응을 분석했습니다.

- SOME/IP 관련 오픈소스 빌드·실행 및 정상 통신 확인
- 정상·공격 트래픽 생성, PCAP 파싱·라벨링 및 데이터 전처리
- Wireshark 패킷과 실행 로그를 활용한 요청·응답 흐름 분석
- LLM 보조 퍼징 실험 및 입력에 따른 서비스 반응 비교

[관련 연구 저장소](https://github.com/8ehemoth/someip-llm-fuzzer)

### Servo2040 기반 6족 보행 로봇
**REAL-PROBLEM 메이커톤 | 2026.02 | 대상**

공개 모델링 파일과 제어 예제를 활용해 차량 하부 확인 용도의 6족 보행 로봇을 제작했습니다. 전원 구성과 펌웨어 적용, 서보 보정을 담당하며 실제 보행 동작을 확인했습니다.

- Servo2040(RP2040) 보드와 MG996R 서보모터 18개를 활용한 로봇 구성
- Ubuntu·CMake 환경에서 기존 펌웨어 빌드 및 보드 적용
- Li-Po 배터리·UBEC 전원 배선 및 납땜
- 서보별 기준 각도 캘리브레이션 및 보행 동작 조정

[제작에 참고한 모델링 자료](https://github.com/8ehemoth/hexapod)

## Tech Stack

프로젝트와 학습 과정에서 사용한 언어·도구·플랫폼입니다. 주요 사용 범위는 아래 표에 정리했습니다.

### 프로그래밍 언어
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### 도구 및 개발 환경
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![LTspice](https://img.shields.io/badge/LTspice-900028?style=for-the-badge&logo=ltspice&logoColor=white)

### 보드 및 플랫폼
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Jetson Nano](https://img.shields.io/badge/Jetson%20Nano-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

### 주요 사용 경험

| 기술 | 사용 경험 |
| --- | --- |
| **C** | ATmega128 레지스터 설정 및 GPIO·타이머·인터럽트·ADC·UART 제어 실습 |
| **C++** | Windows 소켓·GUI 기반 TCP 클라이언트·서버 구현, 등록·채팅 메시지 처리 및 스레드·동기화 실습 |
| **Python** | AI 모델 변환·추론, 차량 통신 데이터 전처리 및 퍼징 관련 코드 |
| **Linux** | Ubuntu·Raspberry Pi 개발 환경 구성, 의존성 문제 해결 및 오픈소스 빌드·실행 |
| **CMake** | 기존 오픈소스 펌웨어 빌드 및 보드 적용 |
| **Wireshark** | SOME/IP 패킷 수집 및 요청·응답 흐름 분석 |
| **STM32** | NUCLEO-F103RB·HAL 기반 UART·I²C 기초 실습 |
| **Hailo** | 모델 변환·양자화·컴파일 및 보드 추론 성능 평가 |

## 전공 실습 및 학습 기록

### ATmega128 기반 MCU 제어
**마이크로프로세서응용및실습 | 2024.03 ~ 2024.06**

ATmega128 기반 보드를 제작하고 AVR Studio에서 C언어 제어 실습을 수행했습니다. GPIO·타이머·인터럽트·ADC·UART의 동작 원리와 레지스터 설정을 학습하고, 작성한 코드의 동작을 실제 보드에서 확인했습니다.

[실습 저장소](https://github.com/8ehemoth/microprocessor-application-and-experiment)


### 고급컴퓨터프로그래밍
**C언어 기초 및 프로그래밍 실습**

C언어의 기본 문법과 프로그램 작성 방법을 학습하고 관련 과제를 수행했습니다. 수업에서 배운 개념을 코드로 작성하고 실행 결과를 확인하며, 프로그램의 동작 흐름을 이해하는 연습을 했습니다.

[학습 저장소](https://github.com/8ehemoth/Advanced-Computer-Programming)

### 자료구조및실습
**C언어 기반 자료구조 구현**

C언어 기초를 바탕으로 큐·스택·트리 등의 자료구조를 학습하고 구현 실습을 수행했습니다. 자료구조별 데이터 저장 방식과 삽입·삭제·탐색 등의 연산 과정을 코드로 확인하며, 자료구조의 동작 원리를 익혔습니다.

[학습 저장소](https://github.com/8ehemoth/Data-structure)

### STM32 기초 실습
**개인 실습 | 2026.02 ~ 2026.03**

NUCLEO-F103RB와 HAL 기반 개발 환경에서 UART·I²C 통신을 실습했습니다. 교재 예제를 참고하며 초기화 코드와 데이터 송수신 흐름을 실제 보드 동작과 연결해 확인했습니다.

## 주요 활동

### 강원대학교 ISOL 학부연구생
**2025.02 ~ 2026.08**

임베디드 AI 추론과 차량 통신 기반 연구를 수행했습니다.

- Raspberry Pi·Hailo 기반 CAN 이상 탐지 모델의 변환·양자화·컴파일 및 보드 추론
- 모델 입출력 확인과 슬라이딩 시퀀스·비동기 추론 구조의 처리 성능 평가
- SOME/IP 데이터 처리·통신 분석 및 LLM 보조 퍼징 연구

### 디지털회로실험 실습 조교
**강원대학교 전기전자공학과 | 2025.09 ~ 2025.12**

- 논리 게이트·플립플롭 실습의 회로 결선 및 동작 오류 확인 지원
- 전원공급기·오실로스코프·함수발생기·디지털 멀티미터 사용 보조
- 7-Segment와 카운터 IC를 활용한 시계 제작 실습 지원

### Python 기초 교과목 조교
**강원대학교 차세대반도체학과 | 2025.03 ~ 2025.06**

프로그래밍 실습 운영을 지원하고, 수강생의 코드 이해와 오류 해결을 도왔습니다.

### 강원대학교 무선통신 연구실 동계 인턴
**2025.01 ~ 2025.02**

Python·Linux 개발 환경과 SSH 기반 연구실 서버 활용 방법을 학습했습니다. Vitis AI·Vivado 기반 AI 가속 환경과 모델 배포·실행 흐름의 기초를 익혔습니다.

## 저장소 안내

이 GitHub에는 프로젝트 코드, 수업·개인 학습 기록, 연구와 제작에 참고한 오픈소스가 함께 있습니다.

일부 저장소에는 개발 중 사용한 실험 버전과 수업 메모가 포함되어 있습니다. 프로젝트별 구현 범위와 직접 수행한 작업, 실행 방법을 README에 정리하고 있습니다.

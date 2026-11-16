<h1 align="center">안녕하세요, 박서희입니다.</h1>

<p align="center"><strong>Embedded Software · Firmware</strong></p>

## 🎓 About Me

| 소속 | 전공·교육 |
| --- | --- |
| 광운대학교 | 전자공학과 졸업 (2025.08) |
| 대한상공회의소 서울기술교육센터 | AI 시스템반도체 SW 개발자 과정 · MCU(AVR, STM32) 펌웨어, Linux 디바이스 드라이버, FPGA 설계·검증 |

## 🛠️ Tech Stack

### Languages

![C](https://img.shields.io/badge/C-516B8B?style=flat-square&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Verilog HDL](https://img.shields.io/badge/Verilog%20HDL-B94C26?style=flat-square) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### MCU / Board

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![ATmega128A](https://img.shields.io/badge/ATmega128A-AD1F2D?style=flat-square) ![Basys3 (FPGA)](https://img.shields.io/badge/Basys3%20%28FPGA%29-5C3EA1?style=flat-square) ![Jetson Orin Nano](https://img.shields.io/badge/Jetson%20Orin%20Nano-416E16?style=flat-square&logo=nvidia&logoColor=white)

### Embedded Development

![Linux Device Driver](https://img.shields.io/badge/Linux%20Device%20Driver-343B46?style=flat-square&logo=linux&logoColor=white) ![UART](https://img.shields.io/badge/UART-17617C?style=flat-square) ![I2C](https://img.shields.io/badge/I2C-155FB0?style=flat-square) ![SPI](https://img.shields.io/badge/SPI-7338B8?style=flat-square)

### Environment & Tools

![VS Code](https://img.shields.io/badge/VS%20Code-0065A9?style=flat-square) ![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=111111) ![Vivado](https://img.shields.io/badge/Vivado-A42225?style=flat-square&logo=amd&logoColor=white) ![Git](https://img.shields.io/badge/Git-C13825?style=flat-square&logo=git&logoColor=white) ![Microchip Studio](https://img.shields.io/badge/Microchip%20Studio-AD1F2D?style=flat-square) ![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white) ![Qt](https://img.shields.io/badge/Qt-276C38?style=flat-square&logo=qt&logoColor=white)

## 💻 Projects

### Firmware

#### [STM32 레지스터 기반 DC 모터 제어](https://github.com/yckb1297/stm32f411-uart-pwm-motor-control)

- STM32F411의 GPIO·UART·타이머 레지스터를 직접 설정해 UART 명령으로 PWM 듀티를 바꾸고, 버튼 입력으로 회전 방향을 전환하거나 모터를 정지하도록 구현

#### [ATmega128A 기반 수동·자율주행 자동차](https://github.com/yckb1297/ATmega128A-SmartCar)

- Bluetooth-UART 명령을 처리하는 수동 주행과 초음파 센서 3개를 활용한 장애물 회피 자율주행을 구현

### Embedded Linux

#### [Linux 디바이스 드라이버 기반 온도 연동 팬 제어](https://github.com/yckb1297/linux-pwm-fan-driver)

- 온도 기반 자동 제어와 사용자 입력 기반 수동 제어를 지원하는 팀 프로젝트
- Jetson Orin Nano용 DC 모터 문자 디바이스 드라이버 담당

### FPGA

#### [FPGA 기반 SPI 센서 데이터 전송 시스템](https://github.com/FPGA-SPI-Master-Slave/FPGA-SPI-Master-Slave/tree/main/slave)

- 두 Basys3 보드 간 SPI 통신 프로젝트
- Slave 측 HC-SR04 센서 제어, SPI Mode 0 응답, FIFO 기반 UART 출력을 담당
- 100 MHz 시스템 클럭과 외부 SPI SCLK 사이에 요청·응답 기반 CDC를 적용

#### [FPGA 기반 전자레인지 제어 시스템](https://github.com/yckb1297/fpga-microwave)

- 전자레인지의 시간 설정, 카운트 다운, 문 개폐, 알림음을 구현하는 프로젝트
- FSM으로 대기·조리·일시정지·완료 상태를 관리

## 📬 Contact
E-mail: p.seohuii@gmail.com

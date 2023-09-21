## EasyWrite
DongYang 2023 Project _ EasyWrite

### Hardware
- Arduino Uno
- Stepper Motors
- Servo Motor
- A4988 Motor Drivers
- CNC Shield

### SoftWare
- Kotlin
- GRBL
- Python

어플 개발 계획
- 기초 UI 구성
- 기본 기능(데이터 전송, 텍스트 GCODE 변환, 등) 구현
    - 텍스트 입력 기능
    - GCODE변환 기능
    - 블루투스로 변환된 GCODE 전송 기능
- 블루투스 전송 테스트
- (추가) 음성인식 기능: 핸드폰 내장 마이크 활용
    - python 라이브러리(TextToGcode) 활용
    - 인식한 음성 텍스트로 변환
    - 음성 -> 텍스트 -> Gcode
- UI 완성

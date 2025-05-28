# 🤖 ROS2 Sensor Packages for Underwater Robots

환영합니다! 이 저장소는 수중 로봇에 탑재된 다양한 센서를 ROS2 환경에서 제어하기 위한 패키지들을 정리한 프로젝트입니다.

---

## 🌊 포함된 센서 목록

| 센서 이름     | 설명                           | 상태 |
|--------------|--------------------------------|------|
| 🧭 **DVL**     | Doppler Velocity Log          | ✅ 완료 |
| 🔊 **881A**    | Imaging Sonar (BlueView)      | ✅ 완료 |
| 🔁 **Ping360** | Scanning Sonar                | ✅ 완료 |
| 🌊 **Echo Sounder** | 수심 측정용 음향 센서      | ✅ 완료 |
| 👁️ **Oculus**  | 고해상도 이미징 소나          | ✅ 완료 |
| 🌐 **Sonoptix**| 다중빔(Multibeam) 소나         | 🔧 개발 중 |

---

## 🛠️ 개발 환경

- **OS**: Ubuntu 22.04
- **ROS 2**: Humble Hawksbill
- **빌드 시스템**: `colcon`
- **언어**: Python & C++

---

## 📂 디렉토리 구조 예시

```bash
sensor-packages-ros2/
├── DVL/
│   └── launch, config, src...
├── 881A/
├── Ping360/
├── Oculus/
├── Echo_Sounder/
├── Sonoptix/
└── README.md

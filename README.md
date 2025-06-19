# 🍅 Tomato-Artificial-Pollination-Robot-System(토마토 인공수분 자동화 시스템)

### 🤖 번거로운 토마토 인공수분 작업을 YOlOv8을 탑재한 로봇을 통해 자동화 하는 시스템
----

### 📅 개발 기간
+ 2024.01 ~ 2024.11

### 💁🏻 개발 인원
+ 본인 포함 팀원 3명
+ 지도 교수 1명

### 🌴 Environment
+ ubuntu 20.04(Jetson Nano), Window
+ Python 3.8, C, pytoch
+ Jupyter Notebook, Arduino IDE

### 🎖️ 토마토 인공수분 자동화 로봇 시스템의 목표
1. 토마토 나무 구성요소 식별
2. 1~2 화방을 대상으로 만개꽃이 2개 이상인 화방 탐색
3. 인공수분 할 화방을 자동으로 판단
4. 위와 같은 시스템을 가진 인공수분 로봇 주행

---

### 시스템 구성도
<img width="601" alt="스크린샷 2025-06-19 오후 4 00 17" src="https://github.com/user-attachments/assets/6174e396-c6f1-4e4f-8608-257a65d2258b" />


### 로봇 구현 이미지
<img width="645" alt="스크린샷 2025-06-19 오후 4 04 29" src="https://github.com/user-attachments/assets/3a357167-efa1-4f68-a3ce-03dfac196d4d" />


---
## 파일 설명

+ ⭐️⭐️⭐️⭐️⭐️Tomato_포트폴리오 -> 프로젝트 상세 설명입니다. 구성도, 설계, 문제 해결등이 나와 있습니다.
+ Tomato_Server -> 서버(노트북, 데스크탑)에서 실행하는 코드입니다.
+ Tomato_Jetson -> 젯슨나노에서 실행하는 코드입니다.
+ Arm.py -> 젯슨나노와 부착된 로봇팔을 작동하는 코드입니다.(이 코드는 제가 완전히 작성한 것이 아닌, 로봇팔에 탑재되어 있던 코드를 가져왔습니다.)
+ Cart.txt -> 카트에 탑재된 Arudino 코드입니다.

# Raspberry Pi Fire Detection System
![image](https://user-images.githubusercontent.com/63221959/164700686-37549a6a-06f1-412b-ba9e-f3afe865039e.png)

---
### Project
- 2022-1 Capston Design Project로 '라즈베리파이 기반 화재 감지 시스템'에 대한 프로젝트를 진행.
- 봄, 가을 건조한 계절때마다 매년 큰 산불 및 대형 가정 화재들이 발생하고 있다. 
- 화재는 초기발견이 매우 중요하며 화재제압의 골든타임은 5분이다.
- 가정 내에서는 사람이 집을 비운 사이 화재가 발생한다면 어느정도 화재가 발생하고 연기가 차오를때 화재경보가 감지해서 울리게된다.
- 이런 경우 화재제압에 있어서 이미 시간이 지체되며 119에서는 화재신고를 받기도 시간이 걸린다.
- 본 프로젝트는 화재를 빠르게 감지하고 이를 빠르게 신고까지 하는 시스템을 연구하고 있다.
- 또한 본 프로젝트는 화재를 빠르게 인지하지 못하는 시각장애인들에게 매우 유용한 시스템이 될 수 있다.
---
## preparation
- Raspberry Pi 4 Model B
- RPI Camera Module V2

---

## Integrated Development Environment (IDE)
#### Raspberry
- RaspiOS Full armhf-2021-05-28
- Python 3.7
- Tensorflow 1.15


#### Windows 
- Google Colab+

---

### Pip
- pip install tf_slim
- apt-get install protobuf-compiler python-pil python-lxml python-tk
- pip install -q Cython contextlib2 pillow lxml matplotlib
- pip install pycocotools

### Git
- git clone --quiet https://github.com/tensorflow/models.git

### DataSet
- individual Label project (Roboflow)

---
## System 
![first_02](https://user-images.githubusercontent.com/63221959/164699101-61dea629-7d2c-41bd-9c18-aecf783ad2af.png)
---
# To do
---
- connect database(firebase)
- TTS

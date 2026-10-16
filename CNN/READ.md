### 출력: CNN 인공지능 학습을 위한 CIFAR-10 데이터 준비 및 시각화
* <img width="1531" height="640" alt="image" src="https://github.com/user-attachments/assets/d88ec939-15dc-4ac3-80f2-4060ce58bf8d" />
* TensorFlow 2.19.0을 사용하여 CNN 인공지능 프로그램을 실행하였다.
* CIFAR-10 사진 60,000장을 불러와 학습용 50,000장과 테스트용 10,000장으로 구분하였다.
* 각 사진은 32×32픽셀의 컬러 이미지이며, 정답은 10개 종류로 구분된다.
* 학습용 사진 10장을 화면에 출력하고, 사진 아래에 고양이·자동차·개구리 등의 정답을 표시하였다.

### CNN 인공지능 모델의 신경망 구조
* <img width="979" height="490" alt="image" src="https://github.com/user-attachments/assets/0a07b48b-ccbe-4ad8-835f-4fd7c6552e64" />

* Conv2D(합성곱층)**는 32개 → 64개 → 128개의 필터를 사용하여 사진의 선, 모양 등 특징을 추출한다.
* MaxPooling2D(풀링층)**는 특징 맵의 크기를 32×32 → 16×16 → 8×8 → 4×4로 줄여 중요한 특징을 압축한다.
* Flatten(평탄화층)**은 4×4×128개의 특징을 2,048개의 숫자로 펼쳐 분류할 준비를 한다.
* Dense(완전연결층)**는 512개 → 256개의 뉴런으로 특징을 분석하고, Dropout은 과적합을 줄인다.
* 출력층(Dense 10)**은 사진을 10가지 종류로 분류하며, **Param #**은 각 층에서 학습할 가중치와 편향의 개수를 나타낸다.


### Image Style Transfer 코드
* ﻿논문: Image Style Transfer Using Convolutional Neural Networks (CVPR 2016)
* ﻿한 이미지의 ‘내용(content)’과 다른 이미지의 ‘스타일(style)’을 결합해서새로운 이미지를 만들어내는 기술을 제안
* 예시) 반 고흐의 화풍으로 그린 파리 거리의 그림
* 코드명: Style_Transfer_Tutorial의_사본.ipynb

### GAN 코드
* ﻿논문: Generative Adversarial Nets(Ian Goodfellow et al., 2014)
* ﻿가짜 이미지를 만드는 화가(생성자)와 이를 잡아내는 심사위원(판별자)이 서로 겨루며 점점 더 정교한 이미지를 만들어내는 인공지능 코드
* 코드명: GAN.ipynb
  
### Transformer 코드
* 논문명: Attention is All you needs
* 개요: Transformer 알고리즘 바탕으로 영한 번역기 모델
* 코드명: transfomer_eg.ipynb






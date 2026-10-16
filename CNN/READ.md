# 출력
<img width="1531" height="640" alt="image" src="https://github.com/user-attachments/assets/d88ec939-15dc-4ac3-80f2-4060ce58bf8d" />
* TensorFlow 2.19.0을 사용하여 CNN 인공지능 프로그램을 실행하였다.
* CIFAR-10 사진 60,000장을 불러와 학습용 50,000장과 테스트용 10,000장으로 구분하였다.
* 각 사진은 32×32픽셀의 컬러 이미지이며, 정답은 10개 종류로 구분된다.
* 학습용 사진 10장을 화면에 출력하고, 사진 아래에 고양이·자동차·개구리 등의 정답을 표시하였다.

### CIFAR-10 CNN(AlexNet 기반) 코드
* 논문: ImageNet Classification with Deep Convolutional Neural Networks(깊은 컨볼루션 신경망을 사용한 ImageNet 분류)
* 개요: 작은 이미지들(CIFAR-10)을 보고 10개의 종류 중 하나를 맞히는 모델(CNN)를 만드는 과정
* 이미지를 불러오고 → 전처리하고 → CNN 모델을 만들고 → 학습시키고 → 평가하고 → 예측까지 해보는, 딥러닝의 전형적인 전체 흐름을 알수 있다.
*  라이브러리 불러오기 → 데이터 불러오기와 전처리 → 데이터 시각화 → CNN 모델 만들기 → 모델 컴파일 → 모델 훈련 → 모델 평가 → 학습 과정 그래프 그리기
*  코드명: CIFAR-10 분류를 위한 CNN 모델.ipynb

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






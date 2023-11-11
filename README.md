# Classification_Fish species

## 🐟 Project Introduction
 1. 대회: 주어진 Dataset을 이용하여 인공지능 알고리즘 모델을 개발https://aifactory.space/task/2600/overview 
 2. 주제: 낙동강 하굿둑 물고기 영상에서 어종을 식별하고 분류하는 AI 모델 개발
 3. 팀원: 윤지영, 박주현, 이종호, 홍다경
 4. 주최 : 한국수자원공사(K-water) / 주관 : 인공지능팩토리


## 💡 Modeling


#### ResNet (Deep Residual Learning for Image Recognition) 
ResNet은 CNN Network이며 깊은 망을 더 쉽게 학습하기 위해 개발된 Network이다. 네트워크 깊이가 깊어질수록 성능이 좋아지다가 어느 시점에서 오히려 성능이 나빠지는데, 이러한 문제 해결을 위해 residual block을 도입했다. residual block은 기울기가 잘 전파될 수 있도록 하는 일종의 shortcut(skip connection)을 만들어 준다.
#### YOLOv8 (You Only Look Once) 
YOLO는 실시간 객체 인식을 위한 혁신적인 방법론이다. YOLOv8은 빠르고 정확하며 사용하기 쉽게 설계되어 다양한 객체 탐지 및 추적, 인스턴스 분할, 이미지 분류 및 포즈추정과 같은 작업이 가능하다.
YOLO 이전 버전과 비교할 때 보다 더 빠른 최첨단 성능을 제공하기 때문에 YOLOv8모델을 사용하였다.


## 📑 Dataset Component 
* train: 학습 데이터 이미지
* test: 평가 데이터 이미지
* labels: COCO format jason
* 학습 및 예측 대상 8개의 class
* 레이블 데이터 형식: COCO label형식, bbox좌표는 [x0, y0, w, h] 형식
* 44,945개의 test dataset과 104,874개의 train dataset을 이용



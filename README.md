# 객체 검출 모델 학습: 도로 주행
- [자율주행 인공지능 알고리즘 개발 챌린지](https://challenge.gcontest.co.kr/template/m/frame/info1/16335)에 개인으로 참가해 진행한 프로젝트입니다.
- Object Detection의 핵심 원리를 이해한 후, YOLO 모델 학습과 직접 촬영한 도로 주행 영상에서 객체 검출을 수행합니다.
- 가장 높은 모델 성능으로 [최우수상](https://challenge.gcontest.co.kr/template/m/frame/boardview/16335?boardSeq=1683)을 수상했습니다.

<Br>

## 배경
- 수상 실적이 필요해 참여
- 직접 모델을 개발하는 것에 흥미를 느껴 참가하게 됨

<Br>

## 주요 기능
- 도로 주행 동영상 내의 10종의 객체 [자동차, 버스, 트럭, 특수 화물차, 오토바이, 자전거, 개인형 이동 장치, 사람, 신호등, 교통 표지판] 검출 성공

<Br>

## 데이터
- 주최측에서 한국교통안전공단 ['자율주행 공개데이터셋'](https://challenge.gcontest.co.kr/template/m/frame/downloadlist/16335?q=1368) 제공
- 1920x1200 크기 도로 주행 이미지(.jpg) 10만장과 객체 10종의 위치 정보 파일(.json) 10만개
- 총 40.9GB 데이터셋
  - 학습 데이터 세트 : 80,000 images 
  - 검증 데이터 세트 : 10,000 images 
  - 테스트 데이터 세트 : 10,000 images

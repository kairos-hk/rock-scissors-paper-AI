# rock-scissors-paper-AI

Made by KDY of D.H.S. feat.LCH.T
오전 1:04 2022-11-08 최종수정 [KDY]

<정확도의 향상 방안>
1,Teachable Machine의 데이터량 증가
2,Epoch값 증가,학습량 증가
3,배경의 일치화 (Recommend = White)
4,데이터의 특징을 일치화 (동일한 배경, 각 손동작의 특이점 대두)

[Update]
기존 DATA에서 Epoch를 1000으로 하여 학습시킴 >> keras_model.h5 파일 수정됨
추가 주석 작성 및 prediction 판별식의 오류 수정 >> ai.py 파일 수정됨
사용방법 및 설명 추가 >> Read me 파일 추가

<구동방법>
1, Teachable Machine에서 Data를 Input한후 학습시킴
2, Tensorflow Keras로 추출
3, AI.py와 Keras_model.h5 파일을 동일한 폴더에 저장
4, BAT파일을 통한 라이브러리 설치 (Tensorflow , cv2는 필수로 설치해야함)
5, 사용가능한 Cam 세팅
6, 실행하고자 하는 IDE(자유) 에서 실행 ( VScode의 경우 디버깅 없이 실행을 추천)

<project.tm파일 사용법>
project.tm 파일이란 Teachable Machine에서 입력시킨 Data와 세팅값을 프로젝트로
저장시킨 것으로써, 해당 파일을 Open함으로 Teachable Machine의 세팅을 할 필요 없이 바로 학습시켜도 됨.
1, Teachable Machine 접속
2, 시작하기 >> '파일에서 기존의 프로젝트를 엽니다' 클릭 >> Project.tm 파일 선택 >> Open

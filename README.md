<img src="https://github.com/ZoneBUG/debugging-app-server/assets/97878992/909a448d-7314-442c-8cd6-332a7cdb5e86" width=100%>

# 디버깅; DEBUGGING <img src="https://github.com/ZoneBUG/debugging-app-server/assets/97878992/67ec499f-7947-4499-a65a-dff9d81b8036" align=left width=100>

> 자영업자들을 위한 맞춤형 방역 솔루션 서비스, DEBUG Your Place!
<br/>
  
## (1) Yolov5s
### 🔎 Yolov5 : 실시간 객체 인식에 적합한 모델
- 특징 1 :  탐지의 정확도가 높음 <br/>
- 특징 2 : 연산 속도가 빠름 <br/>
따라서 이동하는 해충의 실시간 탐지에 가장 적합한 모델로 yolov5를 선정하였고,  <br/>
현재 데이터셋 및 라즈베리파이 환경을 고려하여 가장 가벼운 yolov5s로 학습을 진행하였다. 

 <br/> 
 
## (2) 모델 학습 환경
#### 💧 데이터 셋 :  roboflow
#### 💧 구현 언어 :  Python
#### 💧 구현 환경 :  Google Colab

 <br/>
 
## (3) 모델 학습 과정
##### 💡 타겟 해충군 :  바퀴벌레, 그리마, 지네, 집게벌레, 노래기, 좀벌레
##### 💡 데이터 : 2000여 장의 전처리된 이미지셋
##### 💡 epoch = 100,  batch = 128

 <br/>
 
## (4) 모델 학습 결과
#### 🌱 Precision : 95% 이상의 정확도 확인
<img src="https://user-images.githubusercontent.com/86199517/206706429-7f632597-2ba1-42ba-a332-a7de1297b94c.png">
<br/>
<img width="50%" src="https://user-images.githubusercontent.com/86199517/206708294-c96fb83d-abba-4501-83db-88a9a00926f2.jpg">

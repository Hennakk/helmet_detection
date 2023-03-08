# Helmet Detection in Web Server
## 웹서버를 통한 안전모 착용 자동 감지


- Object Detection


  대표적인 컴퓨터 비전 기술로 객체의 분류와 위치를 동시에 예측
  
  기존의 classification 기술은 단일 객체만 검출이 가능
  다수의 객체의 분류와 위치를 추정하기 위해 Object Detection 기술 이용



1. Dataset

   [안전모 합성 이미지](https://github.com/Hennakk/image-processing/blob/main/result.md)

2. Tensorflow API
   - Convert XML to CVS
   - Generate TFRecode from CVS & Image
   - Custom Pre-trained model & config
   - Train model
   - Export model
   - Convert tflite model
   - Test model 
 
 3. 라즈베리파이 포팅 및 웹서버 구축
<img src="https://user-images.githubusercontent.com/98154707/222909512-0ac4bafc-ce39-4113-ab05-07ebce8425de.png" width="600" height="400"/>
<img src="https://user-images.githubusercontent.com/98154707/222909850-27e556b9-d158-4a2f-ad28-fc1e435438b3.png" width="600" height="400"/>


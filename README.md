우리 아이 옷장 [아장]
===================
기술 요소에 대한 코드 실행 과정은 제출한 시연영상을 참고해주세요~(링크: https://youtu.be/3TVrVTqvrPE)
![image](https://user-images.githubusercontent.com/81168694/205673839-162dbb55-4426-430b-9d5b-9fd8a39a57e7.png)

**2022-2 캡스톤디자인과창업프로젝트 스타트 COYD**

주제: 성장주기별 아이용 스마트 옷장 관리 서비스

# openCV - 실행 전 라이브러리 설치 코드
  pip install cvzone  
  pip install matplotlib  
  pip install imutils  
  pip install scipy  

# 사진 파일 필요 
--> 코드에 절대경로/파일명 기입 필요

**opencv objectdetection** - 객체가 있는 부분만 이미지 자르기
![image](https://user-images.githubusercontent.com/81168694/205675898-91e87e4b-ab1f-4fe8-b720-702c60c778f3.png)

**opencv** - 배경제거

![image](https://user-images.githubusercontent.com/113959581/205778779-71483e2f-e94b-43b9-beea-af7f470aa640.png)

(1) grabcut algorithm

![image](https://user-images.githubusercontent.com/113959581/205778822-22142629-9d73-4f41-9e55-4d812397e581.png)

(2) cvzone

![image](https://user-images.githubusercontent.com/113959581/205778855-edf17b7c-541d-4bf5-8e95-7b6201d736a9.png)

**opencvLen** - 객체 길이 측정 (왼쪽의 규격화된 물체 기준으로 측정)

![image](https://user-images.githubusercontent.com/113959581/205779213-be7b92f4-9fcf-4549-80aa-2ccb734fdd03.png)

![image](https://user-images.githubusercontent.com/113959581/205779227-7b44fea2-1f9e-4b41-a764-c3233bc1efae.png)



# Keras CNN model - 실행환경: Google Colaboratory
활용한 이미지 (전처리전 원본 이미지 - 예시)는 다음과 같음

![image](https://user-images.githubusercontent.com/81168694/205672593-07825063-04c2-46e6-a369-c59a98eff5f8.png)
0 - 바디슈트  
1 - 실내 우주복  
2 - 실외 우주복  
3 - 상/하의내복  

# Prototype Image
1. 회원가입 - 아이의 정보 입력  
![image](https://user-images.githubusercontent.com/81168694/205817337-02acf216-bfb6-44b8-99bf-867ef7c81ef1.png)  

2. 아이 옷 촬영 - 외곽선 검출 후 옷 스캔, 옷 사이즈 측정  
![image](https://user-images.githubusercontent.com/81168694/205817846-ec8e69fe-7eb8-43e8-af64-7a2958826ace.png)  

3. 스마트 옷장 - 카테고리별 분류 / 성장 단계별 옷 입는 기간 확인  
![image](https://user-images.githubusercontent.com/81168694/205818080-54ac39b0-5800-4d3f-a95e-541083b94398.png)  

4. 사이즈 확인 팝업 - 주기적으로 성장 기록, 맞지 않는 옷 분석  
![image](https://user-images.githubusercontent.com/81168694/205818168-0565a47a-9242-43a2-9b06-282479b8623e.png)  

5. 중고거래지원 - 구매시기, 착용시기, 착용하는 동안 아이 신체 정보 자동 기입  
![image](https://user-images.githubusercontent.com/81168694/205818843-0fbc9000-69f6-411c-a15d-ac7c78877ede.png)

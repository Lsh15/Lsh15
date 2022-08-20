## FBMS 어플 (Java)
* UI 구현
  * Figma에 제작된 20페이지 정도의 디자인을 받아 어플에 적용
  * 스플래시, 회원가입, 바코드 인식, 여러가지 대화상자 등등 구현
  *

* 기능 추가
  * String.xml을 이용하여 다국어(한국어, 영어, 일본어) 지원 및 배포
  * Zxing 라이브러리를 이용한 바코드, QR코드 인식 기능 추가
  * 인앱 업데이트 기능 추가 
  * SurfaceView를 이용한 Custom Camera 기능 추가 
  * 

* 기능 개선
  * 기존의 MPAndroidChart 라이브러리를 사용하여 제작한 그래프 대신 웹뷰로 만든 그래프를 받아와 어플에 구현 
  * multipart/form-data 방식을 이용한 명판 이미지 전송 시간 단축 (20초 -> 5초 내외)
  * 
  
* 구현한 App 화면
![image]()


<img src="https://user-images.githubusercontent.com/50148363/185748662-cfee99e9-6e75-44b7-a438-ae91731a0b69.png" width="300" height="500"/>    <img src="https://user-images.githubusercontent.com/50148363/185748728-a24d1838-7917-4bbe-b654-10faa7ebfc64.png" width="300" height="500"/>    <img src="https://user-images.githubusercontent.com/50148363/185747683-f33214ef-c4c8-467a-91a8-98e66a922a58.png" width="300" height="500"/>    <img src="https://user-images.githubusercontent.com/50148363/185748052-f49c0fef-30d4-48ea-8d0d-fb5a9eacf131.png" width="320" height="500"/>    <img src="https://user-images.githubusercontent.com/50148363/185748793-8de2fc98-282c-4480-80ed-36e511e44186.png" width="320" height="500"/>


## FBMS 알고리즘 구현 및 데이터 분석 (Python)
* 알고리즘 구현 
  * 배터리의 전압, 전류, 온도 등을 이용하여 배터리 수명예측 알고리즘 계산식을 코드로 구현  
  * 

* 데이터 분석
  *  Json파일과 Csv파일을 변환하여 데이터 전처리 작업
  *  1분 단위의 데이터들을 분석하여 일 단위, 월 단위, 연 단위 데이터 추출
  *  리눅스 Crontab을 이용한 작업 예약 스케줄러 구현
  *  

* 데이터 통신
  * Requests 라이브러리를 이용하여 서버와 데이터 통신
  * 

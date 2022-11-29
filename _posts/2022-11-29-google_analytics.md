---
layout: post
title: Google analytics
comments: true
---

나는 수업시간에 다루어지지 않은 기능인 google analytics를 추가하기로 하였다.  
google analytics는 내 블로그 접속자 수를 알 수 있게 해주는 기능이다.  

구글 애널리틱스에서 계정을 생성해야 한다.  
![측정시작](https://user-images.githubusercontent.com/118643786/204482898-5a06bc96-fdf8-4c31-bb29-b6ed5554974a.png)  

이후 화면에서 계정 이름을 작성한다.  
![계정이름](https://user-images.githubusercontent.com/118643786/204483695-ed068c19-d0ae-4cf7-be2c-d36c9a2dec72.png)  

속성 이름을 작성하고, 보고 시간대와 통화를 설정한다.  
![속성이름](https://user-images.githubusercontent.com/118643786/204483311-70633dbf-64d7-4d3e-82b1-8c9f593684be.png)  

다음 화면에서 비즈니스 정보를 입력하고 약관을 동의하면 계정이 생성된다.  
그리고 웹 스트림을 생성한다.  
![스트림생성](https://user-images.githubusercontent.com/118643786/204484262-a242aa15-160c-407a-ab79-9393efecfa4c.png)  

그리고 측정 ID를 복사하여 _config.yml파일에 다음과 같이 작성한다.  
![측정ID삽입](https://user-images.githubusercontent.com/118643786/204484855-0d2b4783-59dc-4821-b455-86d356ad0111.png)  

마지막으로 태그 안내 보기 선택 후 직접 설치하기에서 스크립트를 복사한 후 head.html파일에 다음과 같이 삽입한다.  
![태그 직접설치](https://user-images.githubusercontent.com/118643786/204485538-a073f749-49e2-42b0-a9f7-2b59881115ae.png)  

마지막으로 push하면 성공 !!  
![성공화면](https://user-images.githubusercontent.com/118643786/204485991-591250b4-60a1-4dd4-adfc-795da55b3877.png)
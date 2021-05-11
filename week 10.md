#  week 10


## 반려동물 앱 "부탁해, 집사 !" 🐕 🐈 (https://github.com/jjjaennn27/Login_Animal)
<pre> <code> [역할 분담]-가족 연동 방법구상 

   ① Recyclerview를 사용하여 가족 구성원 표시 : 이소윤,임재은,진수현
   ② 가족구성원을 입력한 후 직접 추가하는 방식 : 김민진,신정은
   ③ 입력받은 가족 구성원들을 Spinner를 사용하여 표시 : 김민진, 신정은
   ④ flutter를 사용하여 가족 로그인 연동 시도 : 김현승

</code></pre>

## Progress 관리
![image](https://user-images.githubusercontent.com/72747781/117760924-72a63880-b261-11eb-9d22-66ece4b437a1.png)

### <현재 진행 상태 / 앞으로의 진행 계획>

**가족연동**  
* 10주차까지 코드 내에서 구성원을 추가하여 Spinner를 사용하여 표시하는것 까지 진행함.
* 11주차에는 Recyclerview 를 사용하여 이를 클릭하면 그 프로필에 적힌 이름 그대로 밥,간식,산책 등등 가족연동이 필요한 곳에 자동으로 입력되게 할 것이다.


**반려동물 사진등록**
* 10주차까지 사진을 찍고 갤러리를 통해서 사진을 가지고 올 수 있게 만듦.
* 그러나, 아직 서버연결을 하지 못하였기에 11주차 이후부턴 서버연결에 집중할 것이다.

**다이어리 및 건강등록**
* 10주차까지 다이어리 및 건강등록 란에는 다이어리를 작성하며 사진을 찍고 넣을 수 있게 만들었음.
* 11주차에선 다이어리를 보다 정교하고 한눈에 보기 깔끔하게 만들예정이며, 이또한 서버연결에 집중할 예정이다.

**산책메이트 찾기**
* 10주차까지 지도검색을 통하여 근처 공원찾기까지 완료했음.
* 11주차에선 커뮤니티 형식처럼 같이 산책할 수 있는 사람을 구하도록 할 예정이다.


## 가족구성원 표시(https://github.com/leesoyuun/MyRecyclerView)

###  ※ [Recyclerview를 사용하여 가족구성원 표시] - AVD 실행 화면
<img src="https://user-images.githubusercontent.com/72747781/117760528-c2d0cb00-b260-11eb-95ef-1e963285ada0.png" height="550px"></img>


**어플 실행 및 동작**  
* 가족구성원의 이름, 나이 그리고 반려동물의 이름을 확일할 수 있음.
* 가족구성원을 클릭하면 toast 메시지로 반려동물의 이름이 나옴.

 ex. (반려동물의 이름) + 언니 = 알쏭이의 언니
 
 ## 가족 구성원 직접 추가 (https://github.com/leesoyuun/Login_Net)
 
 ### ※ [가족구성원을 직접 입력하여 추가] - AVD 실행 화면
 <img src="https://user-images.githubusercontent.com/72747781/117762433-1ee91e80-b264-11eb-95bb-3c8e22cff9d0.png" height="550px"></img>
 

**어플 실행 및 동작**  
* 가족구성원의 이름을 직접 입력하여 화면에 추가할 수 있도록 만듦.

## ArrayList로 Spinner 만들어 입력받은 구성원 표시(https://github.com/leesoyuun/Spinner)

### ※ [입력받은 구성원 선택하여 추가] - AVD 실행 화면
 <img src="https://user-images.githubusercontent.com/72747781/117763313-93708d00-b265-11eb-839b-a07b3de613c3.png" height="600px"></img>

**어플 실행 및 동작**  
* 입력받은 가족 구성원들을 Spinner로 만들어 산책 및 밥주기 등등 어떤 가족 구성원이 했는지 알아야할때 Spinner를 통하여 입력할 수 있도록함.


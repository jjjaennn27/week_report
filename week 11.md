#  week 11

## 반려동물 앱 "부탁해, 집사 !" 🐕 🐈
<pre> <code> [역할 분담] - 앱 기능에 대한 세부적인 기능 구현

   ① spinner를 이용한 반려동물 건강 체크 정보 입력 & 저장 (밥) : 김현승
   ② spinner를 이용한 반려동물 건강 체크 정보 입력 & 저장 (간식) : 김민진
   ③ spinner를 이용한 반려동물 건강 체크 정보 입력 & 저장 (산책) : 임재은
   ④ RecycleView를 이용한 산책 메이트 찾기 - 게시판 작성 구현 : 진수현
   ⑤ firebase를 이용한 팝업창을 통한 가족연동 구현 : 신정은, 이소윤
</code></pre>

## Progress 관리
![image](https://user-images.githubusercontent.com/72747781/117760924-72a63880-b261-11eb-9d22-66ece4b437a1.png)

### <현재 진행 상태 / 앞으로의 진행 계획>
- 가족연동
>10주 차에서 완벽하게 구현하지 못했던 가족연동을 11주 차에서 가족 구성원의 이름을 입력하여 추가하면 firebase 데이터베이스에 저장되게끔 성공하였다. 

- 반려동물 산책 메이트 찾기
>11주 차에선 10주 차에서 계획했던대로 커뮤니티 형식처럼 게시판을 이용하여 정보 입력 후 업로드 하면 산책 메이트 정보가 저장될 수 있게끔 하였다. 
   
- 반려동물 건강 체크 정보 입력 & 저장
>11주 차에선 반려동물 건강 체크 정보(밥, 간식, 산책)는 spinner를 이용하여 드롭다운 메뉴에 따라 선택할 수 있도록 하였다.   
>이때 당시 데이터베이스 연결을 못하였기 때문에 데이터베이스 연결을 통한 정보 저장은 아직 진행하지 못한 상황이다.

>11주 차에서 성공한 데이터베이스 정보 저장을 통하여 12주 차부터 3명이 만든 프로젝트를 하나로 합치고 데이터베이스 연결을 통하여 프로젝트를 합칠 예정이다. 

## 가족 구성원 정보 저장 (https://github.com/leesoyuun/popup)

###  ※ [firbase 데이터베이스를 통하여 가족 구성원 정보 저장] - AVD 실행 화면
![image](https://user-images.githubusercontent.com/79950103/118522086-a52ac680-b776-11eb-8b74-51e609d5df4e.png)
![image](https://user-images.githubusercontent.com/79950103/118522461-0bafe480-b777-11eb-9b25-d94f70ebfc00.png)

**어플 실행 및 동작**  
* 가족구성원 추가 화면에서 팝업 버튼을 누르게 되면 정보를 입력할 수 있는 창이 나오며 정보를 입력하고 확인을 누르면 데이터베이스에 입력한 정보가 자동으로 저장된다.
 
 ## RecycleView를 이용한 산책 메이트 찾기 (https://github.com/jinsuhyeon00/Pet_WalkingBoard)
 
 ### ※ [산첵 메이트 찾기] - AVD 실행 화면
![image](https://user-images.githubusercontent.com/79950103/118523855-84fc0700-b778-11eb-9a2e-983f71af08e3.png)

**어플 실행 및 동작**  
* 산책 메이트 찾기 화면에서 각 정보를 각각 입력하고 난 후 업로드 버튼을 누르게 되면 상단에 자신이 입력한 정보가 저장된다. 

## spinner를 이용한 반려동물 건강 정보 저장   
## 밥 : https://github.com/kkhhss9/HelloKotlin/tree/dd/abcdefg   
## 간식 : https://github.com/Kim-Min-Jin-19/Pet_Snack  
## 산책 : https://github.com/jjjaennn27/Pet_Walking

### ※ [반려동물 건강 정보 저장 - 밥] - AVD 실행 화면
![image](https://user-images.githubusercontent.com/79950103/118525207-e2448800-b779-11eb-9543-a2a10c55390c.png)
![image](https://user-images.githubusercontent.com/79950103/118525979-ba095900-b77a-11eb-9e4f-3599f3ccab18.png)
 
**어플 실행 및 동작**  
* 메인 화면에서 밥 버튼을 누르게 되면 밥 정보 입력 창이 나오고 spinner를 이용하여 각각의 정보를 입력하고 난 후 등록 버튼을 누르면 setText를 이용하여 "오늘의 밥 정보 등록 완료!" 라는 텍스트로 변경된다. 또한 권장 사료량 버튼을 클릭하면 권장 사료량에 대한 정보가 나오게 된다. 

### ※ [반려동물 건강 정보 저장 - 간식] - AVD 실행 화면
![image](https://user-images.githubusercontent.com/79950103/118527436-423c2e00-b77c-11eb-9f95-a587fe3a4742.png)
![image](https://user-images.githubusercontent.com/79950103/118527671-7879ad80-b77c-11eb-8f8d-23b01a073975.png)

**어플 실행 및 동작**  
* 메인 화면에서 간식 버튼을 누르게 되면 간식 정보 입력 창이 나오고 spinner를 이용하여 각각의 정보를 입력하고 난 후   
등록 버튼을 누르면 setText를 이용하여 "오늘의 간식 정보 등록 완료!" 라는 텍스트로 변경된다.

### ※ [반려동물 건강 정보 저장 - 산책] - AVD 실행 화면
![image](https://user-images.githubusercontent.com/79950103/118528643-87149480-b77d-11eb-8d14-b18f5085b0e2.png)
![image](https://user-images.githubusercontent.com/79950103/118528768-b3301580-b77d-11eb-91e2-ce9c4615b3c9.png)

**어플 실행 및 동작**  
* 메인 화면에서 산책 버튼을 누르게 되면 산책 정보 입력 창이 나오고 spinner를 이용하여 각각의 정보를 입력하고 난 후   
등록 버튼을 누르면 setText를 이용하여 "오늘의 산책 정보 등록 완료!" 라는 텍스트로 변경된다. 

# 산책 메이트 찾기 게시판 구현 - 진수현
(https://github.com/jinsuhyeon00/Pet_WalkingBoard/tree/s_board)
### 게시판 초기 화면, 오른쪽 + 버튼 클릭
![11](https://user-images.githubusercontent.com/79950254/119315870-418e2500-bcb1-11eb-83ff-0cf46fc0d80c.PNG)
- 입력창 팝업으로 출력
![팝업](https://user-images.githubusercontent.com/79950254/119316144-8f0a9200-bcb1-11eb-85c8-ff632fac048c.PNG)
***
### 입력 후 업로드 버튼 클릭
![22](https://user-images.githubusercontent.com/79950254/119315962-58cd1280-bcb1-11eb-9190-4fb424033af2.PNG)
- 산책 시간은 스피너를 이용하여 값 입력
- 실시간으로 파이어베이스에 저장
 
![ㅀ](https://user-images.githubusercontent.com/79950254/119316221-a9447000-bcb1-11eb-97bd-287704fa0232.PNG)
![데이터저장](https://user-images.githubusercontent.com/79950254/119316254-b95c4f80-bcb1-11eb-8867-83ab4a4f6e32.PNG)
- 각 입력값  BoardRef.push().setValue(board); 에 넣기
- listBundle.add(board); 입력된 값들 가져와 리사이클러뷰에 나타내기 위해 리스트에 저장
- adapter.notifyDataSetChanged(); 새로운 데이터 추가 및 삭제 보여줌
- listBundle.clear(); 중복으로 리사이클러뷰에 나오지 않게 기존 데이터 삭제
- 저장되었습니다 Toast 메세지 발생
***
### 왼쪽 눈 버튼 클릭
![5](https://user-images.githubusercontent.com/79950254/119309791-bd846f00-bca9-11eb-9dd1-13a6eb70322f.png)
- 게시판 목록들 보기 가능
 
![hfghfhg](https://user-images.githubusercontent.com/79950254/119317756-6aafb500-bcb3-11eb-8ad8-c468d836fa6f.PNG)

# 가족정보를 입력,저장 및 불러오기 - 이소윤, 신정은
(https://github.com/leesoyuun/popup/commit/fdca38be57d5e0295db327e9bf5364bc4e891fb1)

### 초기 화면

![image](https://user-images.githubusercontent.com/72747781/119344793-0866ac80-bcd3-11eb-909f-bb8e0a0673e6.png)

- 주요 코드
> 가족 정보 입력, 저장
>
>![image](https://user-images.githubusercontent.com/72747781/119344871-2502e480-bcd3-11eb-99c6-92ad8c648d65.png)
>
> 가족 정보 불러오기
>
>![image](https://user-images.githubusercontent.com/72747781/119344955-3ea42c00-bcd3-11eb-8d16-3da2e3d89144.png)

- 실시간으로 파이어 베이스에 가족 정보 저장

![image](https://user-images.githubusercontent.com/72747781/119345057-5ed3eb00-bcd3-11eb-9d80-7cb3baf1f29e.png)



# 산책/간식 스피너로 입력한 정보 파이어베이스에 저장 - 김민진, 임재은
(산책 - https://github.com/jjjaennn27/Pet_Walking)
(간식 - https://github.com/Kim-Min-Jin-19/Pet_Snack)


### 산책 정보 입력 실행 화면
![image](https://user-images.githubusercontent.com/79950380/119347740-e7a05600-bcd6-11eb-9e5e-3305e82c8e03.png)
1. 초기 화면
2. 스피너를 사용하여 정보 입력
3. 등록 버튼을 눌렀을 때

### 파이어베이스에 산책 정보 등록
![image](https://user-images.githubusercontent.com/79950380/119347863-128aaa00-bcd7-11eb-8d26-c699783390ec.png)

### 주요 코드
![image](https://user-images.githubusercontent.com/79950380/119348058-55e51880-bcd7-11eb-928b-99e429e67fec.png)
- 산책 정보 입력 코드

![image](https://user-images.githubusercontent.com/79950380/119348160-71502380-bcd7-11eb-930c-3c6146fe3145.png)
- 스피너 -> 텍스트로 변환 코드

![image](https://user-images.githubusercontent.com/79950380/119348098-62697100-bcd7-11eb-938b-a8c4a3605b94.png)
- 파이어베이스 연결 코드

### 간식 정보 입력 실행 화면
![image](https://user-images.githubusercontent.com/79950103/119348611-13700b80-bcd8-11eb-9c6d-8994a4f0732d.png)
1. 초기 화면
2. 스피너를 사용하여 정보 입력
3. 등록 버튼을 눌렀을 때

### 파이어베이스에 간식 정보 등록
![image](https://user-images.githubusercontent.com/79950103/119348672-27b40880-bcd8-11eb-84b7-d8f45415c38f.png)

### 주요 코드
![image](https://user-images.githubusercontent.com/79950103/119348802-50d49900-bcd8-11eb-9f32-3f9add8a6a20.png)
- 간식 정보 입력 코드

![image](https://user-images.githubusercontent.com/79950103/119348828-5af69780-bcd8-11eb-88cd-007ece5495e6.png)
- 스피너 -> 텍스트로 변환 코드

![image](https://user-images.githubusercontent.com/79950103/119348954-7d88b080-bcd8-11eb-9244-62dfe85c5340.png)
- 파이어베이스 연결 코드

# 네비게이션바로 묶기 - 김현승
(https://github.com/kkhhss9/HelloKotlin/tree/custumnavi/CustumNavi)
## 네비게이션바   
<img src="https://user-images.githubusercontent.com/70967826/119346981-dc005f80-bcd5-11eb-9735-5520c627bb3d.png" width="400px" height="600px"></img>
<img src="https://user-images.githubusercontent.com/70967826/119346995-e15daa00-bcd5-11eb-982b-8736d12e6f4a.png" width="400px" height="600px"></img>
## 눌렀을때 화면
<img src="https://user-images.githubusercontent.com/70967826/119347004-e4f13100-bcd5-11eb-9810-a6a33f67e38f.png" width="400px" height="600px"></img>
<img src="https://user-images.githubusercontent.com/70967826/119347020-e7ec2180-bcd5-11eb-9131-4feb15b29003.png" width="400px" height="600px"></img>
<img src="https://user-images.githubusercontent.com/70967826/119347042-ef132f80-bcd5-11eb-9c9e-d07349a36ed7.png" width="400px" height="600px"></img>
<img src="https://user-images.githubusercontent.com/70967826/119347057-f20e2000-bcd5-11eb-8a18-4f68dec67ee1.png" width="400px" height="600px"></img>
### 주요 코드    
<img src="https://user-images.githubusercontent.com/70967826/119347083-fb978800-bcd5-11eb-96e5-a766958c7748.png" width="400px" height="600px"></img>
<img src="https://user-images.githubusercontent.com/70967826/119347068-f5a1a700-bcd5-11eb-80e8-6d8555db5086.png" width="400px" height="600px"></img>

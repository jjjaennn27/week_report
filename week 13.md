#  week 13

## 반려동물 앱 "부탁해, 집사 !" 🐕 🐈 ( 전체 코드 https://github.com/jjjaennn27/Pet_Dairy )
<pre> <code> [역할 분담] - 앱 기능에 대한 세부적인 기능 구현

   ① 밥/간식/산책 입력 현재 날짜와 시간 파이어베이스에 저장 : 김민진, 임재은
   ② 밥/간식/산책 파이어베이스에 저장된 목록 AVD에 띄우기 (50%): 김민진, 임재은
   ③ 파이어베이스에서 스피너로 데이터 가져오기 (50%) : 김민진, 임재은
   ④ 동물등록 사진과 정보 파이어베이스 저장(80%) : 이소윤, 진수현, 신정은
   ⑤  :
   ⑥  :
   ⑦  :
  
</code></pre>


## 밥/간식/산책 입력 실시간 시간 파이어베이스 저장 : 김민진, 임재은

### 밥
![image](https://user-images.githubusercontent.com/79950380/120304424-bb09c100-c30a-11eb-9b2f-6fb372f74fe2.png)
1. 초기화면
2. NOW 버튼 클릭 -> 현재 날짜와 시간 표시
3. 등록 버튼 클릭 -> '오늘의 밥 정보 등록 완료'로 텍스트가 변하며 파이어베이스에 저장됨

### 산책
![image](https://user-images.githubusercontent.com/79950380/120305086-53a04100-c30b-11eb-86ac-21852a0faa18.png)
1. 초기화면
2. NOW 버튼 클릭 -> 현재 날짜와 시간 표시
3. 등록 버튼 클릭 -> '오늘의 산책 정보 등록 완료'로 텍스트가 변하며 파이어베이스에 저장됨

### 간식
![image](https://user-images.githubusercontent.com/79950103/120308065-a4fdff80-c30e-11eb-926c-ab28467851de.png)
1. 초기화면
2. NOW 버튼 클릭 -> 현재 날짜와 시간 표시
3. 등록 버튼 클릭 -> '오늘의 간식 정보 등록 완료'로 텍스트가 변하며 파이어베이스에 저장됨

### 주요 코드 (현재 날짜와 시간 파이어베이스에 저장)
![image](https://user-images.githubusercontent.com/79950380/120304037-5e0e0b00-c30a-11eb-9aea-d2c668086455.png)

## 밥/간식/산책 파이어베이스에 저장된 목록 AVD에 띄우기 (50%) : 김민진, 임재은
### 주요 코드 1 (getItemCount를 통해 데이터 개수 반환 - onBindViewHolder을 통해 데이터 바인딩
![image](https://user-images.githubusercontent.com/79950103/120310432-5bfb7a80-c311-11eb-88f3-45ef81e8f198.png)

### 주요 코드 2 (바인딩된 데이터가 OnCreateViewHolder를 통해 리사이클러뷰에 저장) 
![image](https://user-images.githubusercontent.com/79950103/120309919-bea04680-c310-11eb-81b0-fdaa2aafdd32.png)

## 파이어베이스에서 스피너로 데이터 가져오기 (50%) : 김민진, 임재은
### 주요 코드 (파이어베이스에서 이름 데이터 스피너로 가져오기)
![image](https://user-images.githubusercontent.com/79950380/120305555-d923f100-c30b-11eb-8632-bda24185d016.png)


## 반려동물 정보 저장 : 신정은, 이소윤, 진수현

### 이름/반려동물종/ 생일 파이어베이스 저장 : 신정은, 이소윤, 진수현
![d - 복사본](https://user-images.githubusercontent.com/79950254/120314903-b6e3a080-c316-11eb-8648-fe3dd638b8f5.PNG)

### 주요코드
![d - 복사본](https://user-images.githubusercontent.com/79950254/120315012-d7135f80-c316-11eb-9737-6bb9fc3290cd.PNG)
### 사진 파이어베이스 저장 (50%) : 신정은 ,이소윤, 진수현





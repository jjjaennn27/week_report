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
- listBundle.add(board); 리사이클러뷰에 나타내기 위해 리스트에 저장
- adapter.notifyDataSetChanged(); 새로운 데이터 추가 및 삭제 보여줌
- listBundle.clear(); 중복으로 리사이클러뷰에 나오지 않게 기존 데이터 삭제
- 저장되었습니다 Toast 메세지 발생
***
### 왼쪽 눈 버튼 클릭
![5](https://user-images.githubusercontent.com/79950254/119309791-bd846f00-bca9-11eb-9dd1-13a6eb70322f.png)
- 게시판 목록들 보기 가능


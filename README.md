# 👨‍👩‍👧‍👧 팀 프로젝트 - Muhan Intranet 사내 인트라넷

![header](https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=300&section=header&text=Muhan%20Intranet&animation=fadeIn&fontSize=90)

## 📁 프로젝트 소개
> *"쉽고 간편한, 이용자 중심의 인트라넷"*<br/>
> <br/>
> 팀원들의 재직 경험을 살려, 간편한 기능 중심의 인트라넷을 만들어 보고자 시작한 프로젝트입니다.<br/>
> 기능을 크게 마이페이지, 공지사항 게시판, 사진 게시판, 근태관리, 개인일정관리, 결재상신, 회의실 예약으로 나눌 수 있습니다. <br/>

### 🛠️ 기술 스택
- <img src="https://img.shields.io/badge/java-000000?style=for-the-badge&logo=openjdk&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  + Java 11.0.2
- <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white">&nbsp;<img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jQuery&logoColor=white">
- <img src="https://img.shields.io/badge/intellijidea-000000?style=for-the-badge&logo=intellijidea&logoColor=white">
- <img src="https://img.shields.io/badge/apachetomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white"><br>
  -  Tomcat 9.0.88

## 🏃 팀 소개
🙋‍♀️ 강경은 - **BE.** 공지사항, 근태관리 100%, 회의실 예약 70% <br/>
👩‍🦱 김민희 - **팀장 & BE.** 개인일정관리 100%, 회의실 예약 30%<br/>
👩‍🦱 구혜민 - **BE.** 로그인, 마이페이지 100%<br/>
👩‍🦱박서영 - **BE.** 사진 게시판, 메인 페이지 100% <br/>
👩‍🦱 이영규 - **BE.** 결재상신 100% <br/>

## 🖥️ 화면 구성
### 공지사항 게시판
1. 공지사항 리스트<br> <br> ![alt 공지사항 리스트](/img/board_list.png)<br>
2. 공지사항 상세 페이지(게시글 페이지) <br> <br> ![alt 공지사항 상세페이지](/img/board_post.png)<br>
3. 상세페이지의 수정, 삭제 및 댓글 목록 <br> <br> ![alt 공지사항 댓글](/img/board_post_comment.png) <br>
### 근태관리 페이지
#### 세부 기능
1. 자동 출근 시간 체크 및 퇴근 버튼 클릭 시 퇴근 시간 업데이트
2. 금주의 근무 시간 총합을 텍스트와 프로그레스 바를 활용하여 표시함.
3. 출퇴근 시간 및 하루의 업무 시간을 활용하여 출근 상태(결근, 출근, 지각, 조퇴)를 퇴근 시 시각과 함께 업데이트 <br> <br>
![alt 근태](/img/attend.png)

### 회의실 예약 페이지
#### 세부 기능
1. 검색 버튼을 클릭하면 AJAX를 활용하여, <br> 이용자가 선택한 회의실과 날짜에 해당하는 조건에 맞는 회의실 예약 가능한 시간대 테이블을 표시함(검색 기능) <br><br> ![alt 회의실 예약](/img/reservation1.png)
2. 이용자가 시간대를 선택한 후 '확인' 버튼을 클릭하면 confirm 창이 표시되고, 한 번 더 확인을 클릭하면 예약 정보가 DB 테이블에 insert 함. <br><br>![alt 회의실 예약](/img/reservation2.png)
3. 다른 이용자는 회의실 예약 정보가 등록된 시간대 테이블을 볼 수 없기 때문에, 중복 예약이 불가능함. <br><br> ![alt 회의실 예약](/img/reservation3.png)

## 기타 세부사항
[링크 사내 인트라넷 ppt] (/무한상사.pptx)

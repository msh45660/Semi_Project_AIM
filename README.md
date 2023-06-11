# Semi_Project_AIM
A.I.M (All In Movie !) - 영화 예매 사이트

- 배포 주소 : <http://itwillbs11.cafe24.com/AIM/Main.aim/>
****
## 목차
1. 프로젝트 소개
2. 사용한 기술 스택
3. 프로젝트 설계
4. 설계한 기능

**** 
### 프로젝트 소개
제작 기간 : 2022년 10월 27일 ~ 11월 29일<br>
<br>
프로젝트 목표 : 영화 사이트를 구현하여 실제 영화 사이트처럼 다양한 기능이 있는 웹사이트 제작<br>
<br>
참여인원 : 8명<br><br>
역할 : 회원가입, 고객센터 파트 구현<br><br>
<p align="left">
  <img src="https://github.com/msh45660/Semi_Project_AIM/assets/116853287/5916a0aa-7a2b-4f6e-abe6-eb34ffd9f439">
</p>

****

### 사용한 기술 스택
Java 11 / JSP / MySQL / Javascript/ Jquery <br>
HTML5 / CSS3 / AJAX / Jsoup <br>

****

### 프로젝트 설계

##### ERD 설계
<p align="left">
  <img src="https://github.com/msh45660/Semi_Project_AIM/assets/116853287/7210177f-685d-4e43-8c9c-c40d07ba16e3">
</p>

****

### 설계한 기능
A.I.M (All In Movie !) - 영화 예매 사이트 프로젝트에서 제가 구현한 기능입니다.
1. 공지사항 CRUD 기능
2. 문의 사항 작성, 문의 리스트 출력, 문의 답변 기능

## 1.공지사항 CRUD 기능
<br>  
기본적인 CRUD 기능을 공지사항 작성에 적용했습니다.

### 1-1. 공지사항 작성 - [코드확인](https://github.com/msh45660/Semi_Project_AIM/blob/master/AIM/src/main/webapp/notice/ntwrite.jsp)<br>
기본적인 공지사항을 작성 할 수 있습니다.
<br>

### 1-2. 공지사항 상세 - [코드확인](https://github.com/msh45660/Semi_Project_AIM/blob/master/AIM/src/main/webapp/notice/ntcontent.jsp)
<p align="left">
  <img src="https://github.com/msh45660/Semi_Project_AIM/assets/116853287/4a95c747-7672-48f5-bc2e-fa240c516b7d">
</p>
<br>
공지사항 상세 보기를 했을 시 관리자ID로 조건을 주어<br>
사용자는 상세내용과 목록 버튼만 출력되고 관리자는 수정,삭제 기능도 출력되도록 제어했습니다.

### 1-3. 공지사항 목록 - [코드확인](https://github.com/msh45660/Semi_Project_AIM/blob/master/AIM/src/main/webapp/notice/notice.jsp)
<p align="left">
  <img src="https://github.com/msh45660/Semi_Project_AIM/assets/116853287/000f0555-3fcb-45e2-9679-70e21e541822">
</p>
<br>
공지사항 리스트를 출력합니다.<br>
로그인 유지를 위한 세션제어를 통해 세션에서 받은 ID가 관리자 ID일 경우<br>
관리자ID로 조건을 준 공지사항 올리기 라는 버튼이 출력되도록 제어했습니다.

## 2.문의 사항 작성, 문의 리스트 출력, 문의 답변 기능 <br>

### 2-1. 문의 사항 작성 - [코드확인](https://github.com/msh45660/Semi_Project_AIM/blob/master/AIM/src/main/webapp/hp/boardhp.jsp)
<p align="left">
  <img src="https://github.com/msh45660/Semi_Project_AIM/assets/116853287/f25e934f-bf02-4ab8-a2c6-4c839fae9e0a">
</p>
<br>
문의 사항 작성을 위한 페이지 입니다.
<br>
<br>

### 2-2. 문의 리스트 출력 - [코드확인](https://github.com/msh45660/Semi_Project_AIM/blob/master/AIM/src/main/webapp/hp/myhplist.jsp)
<p align="left">
  <img src="https://github.com/msh45660/Semi_Project_AIM/assets/116853287/772f4f13-108a-4126-9137-ce3d1244c720">
</p>
<br>
문의한 내용들이 출력 됩니다.<br>
<br>
<p align="left">
  <img src="https://github.com/msh45660/Semi_Project_AIM/assets/116853287/c2483222-0b65-4600-8c60-d5e671671df6">
</p>
문의에 대한 답변이 달릴 경우 글 바로 아래에 답변 글이 생성됩니다.  
<br>

### 2-3 문의 상세 내용 - [코드확인](https://github.com/msh45660/Semi_Project_AIM/blob/master/AIM/src/main/webapp/hp/myhpcontent.jsp)
<p align="left">
  <img src="https://github.com/msh45660/Semi_Project_AIM/assets/116853287/5cda7b62-b5e6-4a15-88f9-1ae6efc283e1">
</p>
<br>
관리자 계정일 경우(좌측사진) 기존 수정,삭제 기능외에 문의 답변 기능을 통해 답변을 남길 수 있습니다.<br>
사용자의 경우 문의한 내용(우측사진)만 볼 수 있으며, 문의내용의 수정,삭제 기능을 수행할 수 있습니다.<br>


### 2-4. 문의 본인 확인 - [코드확인](https://github.com/msh45660/Semi_Project_AIM/blob/master/AIM/src/main/webapp/hp/hppwcheck.jsp)
<p align="left">
  <img src="https://github.com/msh45660/Semi_Project_AIM/assets/116853287/517443a9-47b1-4596-a992-4a8c9f26a74e">
</p>
<br>
문의 목록에서 문의 사항 클릭시 admin 또는 본인 비밀번호를 입력할 시 열람 가능합니다 <br>
문의 작성시 저장된 비밀번호와 비교하며 유효성체크를 합니다.<br>
비밀번호 작성시 알람창이 뜨며 본인확인완료 혹은 비밀번호오류의 알람창이 출력됩니다.

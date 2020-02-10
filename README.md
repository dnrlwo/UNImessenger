# UNI messenger(1차 개발물)
## 1. 개관
### 1.1. 개발 의도
Back-End에 대한 관심을 바탕으로 node.js에 대한 매력을 느끼기 위해 작업하였다. Java를 통한 IO N:N 채팅을 만들어봤지만 쓰레드의 구성의 어려움과 Blocking에 대한 처리가 새로운 방법을 추구하도록 만들었다. 더불어 NoSql의 선두주자인 mongoDB를 접목시켜 데이터의 무결성이 중요치 않은 작업에서 사용을 하였다. ~~또한 채팅방을 mac의 terminal창으로 구성하여 몰래 채팅을 할 수 있다.~~
### 1.2. 개발 정보
* 개발 인원 : 1인
* 개발 기간 : 2020.02.08 ~ 02.10 (총3일간)
#### 1.2.1. 개발 기간
| 날짜 | 진행사항 | 비고 |
|---|:---:|---:|
| 2020.02.08 | 콘셉트 결정(1차 개발물) | |
| 2020.02.09 | UI완성 |  |
| 2012.02.10 | 서버구성 및 오류 수정 |  |
#### 1.2.2. 개발 환경 및 툴
* OS : MacOS Catalina
* Language : Node.js, HTML, CSS
* DBMS : mongoDB
* Programming tool : VS code
---------------
## 2. 본론
### 2.1. 프로젝트 기능
#### 2.1.1. 로그인
<img src="/main.png" width="40%" height="30%" title="메인사진" alt=""></img>
접속 시 login을 바로 할 수 있도록 조치
#### 2.1.2. 상대방의 접속
<img src="/join.png" width="40%" height="30%" title="상대방접속사진" alt=""></img>
상대방의 접속을 띄움
#### 2.1.3. 로그인 정보를 통해 이전에 대화내역 출력
'''
<iframe width="640" height="360" src="https://youtu.be/7TgVLb3kHW4" frameborder="0" gesture="media" allowfullscreen=""></iframe>
'''
[![Watch the video]](https://youtu.be/7TgVLb3kHW4)
[![Alt text]()](https://youtu.be/7TgVLb3kHW4)
### 2.2. N차 개발물
* 채팅 읽음 표시를 만들어 로직 구성하기
* 회원정보 DB 구성하기
* 파일 전송 기능 추가하기
* 모바일 친화적 페이지 구성
----------------------
## 3. 결론
Node.js와 mongoDB에 대한 기초적인 이해. 더 나아가 node.js가 프론트에서 쓰이는 방법에 대한 공부, NoSql에서 DB를 어떻게 구성할 것인가에 대한 추가적인 공부가 필요하다.

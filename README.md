# 🍴 Res_Reserve

> 레스토랑 관리자와 예약 서비스 사용자를 위한 Android 어플리케이션

 ![java](https://img.shields.io/badge/Java-8-lightgrey)  ![Tomcat](https://img.shields.io/badge/Android-4.1.3-lightgrey) 

사용자의 레스토랑 예약, 관리자의 회원 및 예약 관리, 레스토랑 정보 제공 등

<br>

## RES 개발 과정 

[보러가기 (PDF)](https://github.com/jihojhi/Res_Android/blob/master/docs/ResApp_hj.pdf)

<br>

## 사용 예제
> #### Splash & 메인화면 
💙 메인화면 등장 전, Splash액티비티 사용한 로딩화면

<details>
 <summary>이미지 보기/숨기기</summary>
<div markdown="1">
<img width="50%" src="./pics/splash.gif"/>

</div>
</details>

<br>

> #### 레스토랑 정보 제공

💙 BottomNavigationView 를 사용한 각 정보 화면 Fragment 전환

<details>
 <summary>이미지 보기/숨기기</summary>
<div markdown="1">
<img width="50%" src="./pics/website.gif"/>

</div>
</details>

<br>

> #### Menu Tab 상세 기능

💙 GridView와 Adapter를 사용하여 많은 양의 사진 편리하게 등록, 변경 가능

💙 각 메뉴 사진 클릭 시, 메뉴명 하단에 Toast

<details>
 <summary>이미지 보기/숨기기</summary>
<div markdown="1">
<img width="50%" src="./pics/menu.gif"/>
</div>
</details>

<br>

> #### Contact 외부 앱 연결

💙 이메일과 전화번호 클릭 시, 기기 내의 외부앱으로 바로 연결

<details>
 <summary>이미지 보기/숨기기</summary>
<div markdown="1">
<img width="50%" src="./pics/contact.gif"/>

</div>
</details>

<br>

> #### 카카오 계정으로 로그인

💙 Kakao Login API적용

<details>
 <summary>이미지 보기/숨기기</summary>
<div markdown="1">
<img width="50%" src="./pics/kakao.gif"/>
</div>
</details>

<br>

> #### 회원가입

💙 기본 회원가입 양식

<details>
 <summary>이미지 보기/숨기기</summary>
<div markdown="1">
<img width="50%" src="./pics/join.gif"/>

</div>
</details>

<br>

> #### 회원가입 아이디로 로그인

💙 로그인 시, putExtra로 intent넘길 때 회원 정보 전달

💙 로그인 후, getStringExtra로 받은 회원 정보 하단에 Toast

<details>
 <summary>이미지 보기/숨기기</summary>
<div markdown="1">
<img width="50%" src="./pics/login.gif"/>

</div>
</details>

<br>

> #### 공지사항 확인

💙 반응형 공지사항 게시물 확인 나름 구현

<details>
 <summary>이미지 보기/숨기기</summary>
<div markdown="1">
<img width="50%" src="./pics/announce.gif"/>

</div>
</details>

<br>

> #### 레스토랑 예약하기

💙 예약 순서 단계별로 화면 구성

<details>
 <summary>이미지 보기/숨기기</summary>
<div markdown="1">
<img width="50%" src="./pics/reserve.gif"/>
</div>
</details>

<br>

> #### 마이페이지에서 예약 관리 및 정보 수정

💙 예약 정보나 개인 정보 수정 시, 최종 확인 기능

<details>
 <summary>이미지 보기/숨기기</summary>
<div markdown="1">
<img width="50%" src="./pics/mypage.gif"/>

</div>
</details>

<br>

> #### 관리자 로그인

💙 관리자 계정으로 로그인 후, 회원 테이블과 예약 테이블 데이터 조회 및 삭제 가능

<details>
 <summary>이미지 보기/숨기기</summary>
<div markdown="1">
<img width="50%" src="./pics/admin.gif"/>

</div>
</details>

<br>

> #### 데이터베이스 적용 확인

<details>
 <summary>이미지 보기/숨기기</summary>
<div markdown="1">
<img width="50%" src="./pics/check.gif"/>

</div>
</details>
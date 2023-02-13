# HappyHouse, 구해줘 Home
아파트 매매 정보 제공 웹 사이트, 구해줘 Home 🏡
</br>
</br>

## 💡 서비스 소개
[공공데이터포털](https://www.data.go.kr/) API와 [KAKAO Map](https://developers.kakao.com/) API 를 활용하여 아파트 매매 정보 제공과 커뮤니티 기능이 포함된 웹 서비스입니다.
</br>
</br>

## 📅 개발 기간
> 2022.05.19 ~ 2022.05.26 (1주) </br>
</br>
</br>

## 🧑🏻‍💻 개발 멤버 소개
<table>
  <tr>
    <td height="140px" align="center"><a href="https://github.com/J00HUI">
      <img src="https://avatars.githubusercontent.com/J00HUI" width="140px"/> <br><br> 이주희 <br>(Back-End) </a> <br></td>
    <td height="140px" align="center"><a href="https://github.com/sa11k">
      <img src="https://avatars.githubusercontent.com/sa11k" width="140px"/> <br><br> 송다경 <br>(Back-End) </a> <br></td>
  </tr>
  <tr>
      <td align="center">👑<br/>Vue<br/></td>
      <td align="center">REST API</td>
  </tr>
</table>
</br>


## ⚙ 프로젝트 설계
</br>
</br>

## 💎 기술 스택
버전 정보
</br>
</br>

## 🛠 시스템 아키텍쳐
</br>
</br>

## 💻 주요 기능
### 회원가입
* 일반 사용자 회원가입과 공인중개사 회원가입으로 나뉩니다. 
* 아이디 중복검사 완료 후 가입이 완료됩니다.
* 가입 시 SMS 수신 동의에 체크한 경우, 문자 알림 서비스가 제공됩니다.

| 일반 회원가입 | 공인중개사 회원가입 | 
|:-------:|:-----:|
| ![1  일반 회원가입](https://user-images.githubusercontent.com/83942393/204470426-f5d8ff74-b6f0-4ec3-9d0f-a4fcd4b15da5.gif) | ![2  공인중개사 회원가입](https://user-images.githubusercontent.com/83942393/204468550-d500b4ad-5440-4f41-932d-db2433973ef3.gif) |
</br>

### 로그인
* 회원가입 시 작성했던 아이디와 비밀번호를 통해 로그인합니다.

| | 
|:-------:|
| ![3  로그인](https://user-images.githubusercontent.com/83942393/204474225-5fdc0dd0-0504-4ad5-9c69-80b990eb8575.gif) | 
</br>

### 공인 중개사 승인
* 공인중개사 계정은 관리자 계정이 승인 시 완료됩니다.

| | 
|:-------:|
| ![4  공인중개사 승인](https://user-images.githubusercontent.com/83942393/204476370-28193b79-ac6b-494f-bce0-bf45de113faf.gif) | 
</br>

### 챗봇
* 챗봇을 통해 궁금한 점을 질문하고 답변받을 수 있습니다.

| | 
|:-------:|
| ![5  챗봇-짧](https://user-images.githubusercontent.com/83942393/204477453-672ba7b4-360c-429d-938c-ead8f2a0dadd.gif) | 
</br>

### 공지사항, 뉴스 크롤링
* 홈에서 간편하게 공지사항과 뉴스를 확인할 수 있습니다.

| | 
|:-------:|
| ![6  공지사항, 뉴스 크롤링](https://user-images.githubusercontent.com/83942393/204477580-452f7ed3-136d-44e9-9cb6-aea0aa93df67.gif)| 
</br>

### 아파트 매매 검색
* 시, 군, 동을 선택하여 해당 지역에 해당하는 아파트 매매 내역을 검색할 수 있습니다.

| | 
|:-------:|
| ![7  지도 매물 검색](https://user-images.githubusercontent.com/83942393/204477922-1787952b-d6b1-40c0-bb52-c924e8e8e08d.gif) | 
</br>

### 아파트 매매 상세 조회
* 지도에 나타난 마커 클릭 시 해당 매매의 상세 내역을 조회할 수 있습니다.
* 해당 내역에는 사진, 가격, 상세 정보, 주변 시설, 상세 설명, 조회수 가 있습니다.

| | 
|:-------:|
| ![8  매물 상세 조회](https://user-images.githubusercontent.com/83942393/204478728-e59b0e3c-996c-4db7-886a-a3bcd8a39073.gif) | 
</br>

### 관심 매물 등록
* 관심있는 매물을 찜하기 버튼을 통해 찜한 매물 리스트에 등록할 수 있습니다.

| | 
|:-------:|
| ![9  매물 찜하기](https://user-images.githubusercontent.com/83942393/204479257-960dec33-7c6f-4d4b-8c70-d8645ba0764f.gif) | 
</br>

### 관심 지역 설정
* 관심 지역 설정 시 해당 지역의 매물을 간편하게 확인할 수 있습니다.

| | 
|:-------:|
| ![10  관심지역 설정](https://user-images.githubusercontent.com/83942393/204479702-ff77fcf4-cd32-4fdb-a467-e20f32c57887.gif) | 
</br>

### 공인중개사 매물 등록
* 공인중개사 계정은 매물을 등록할 수 있습니다.
* 주소를 입력하면 지도에 표시가 되며, 상세 내역 기입 후 등록 버튼을 눌러 등록을 완료합니다.

| | 
|:-------:|
| ![11  공인중개사 매물 등록](https://user-images.githubusercontent.com/83942393/204479944-55a0784b-61e0-4939-af8a-ea9126134f31.gif) | 
</br>

### 문자 알림
* 관심지역으로 설정한 지역에 새로운 매물이 등록 시 SMS 동의 한 사용자에 한해서 문자 알림 서비스를 제공합니다.

| | 
|:-------:|
| ![12  문자 알림](https://user-images.githubusercontent.com/83942393/204480185-9fa19a82-bbbd-4c8b-bdac-42c73862af62.gif) | 
</br>





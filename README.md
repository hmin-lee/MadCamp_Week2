# 몰입캠프 2주차

### 팀원

* [이혜민](https://github.com/IamHyemin)
* [최진혁](https://github.com/cjh0507)

## 2주차 과제

### 서버와 연결된 안드로이드 어플 만들기 : HonBab

혼밥을 할 것 같은데, 주변 친구들이 다 밥약이 있는 것 같아 눈치보일 때! \
어려운 상황을 해결해주는 앱, HonBab

Facebook 로그인, 앱 안의 계정을 이용한 로그인 가능 \
완벽한 보안을 위한 숫자, 영어, 특수문자, 글자 수 제한의 비밀번호 설정

연결 서버 : http://192.249.19.242:7980

- [x] 첫번째 탭: 친구 상태를 나타내는 연락처
- [x] 두번째 탭: 친구들이 좋아하는 식당을 보여주는 갤러리
- [x] 세번째 탭: 친구들의 현재 위치를 보여주는 지도

### 기술 버전

* Android Gradle Plugin Version: 4.0.0
* Gradle Version : 6.1.1
* min SDK Version: 24(Nougat 7.0)
* target SDK Version: 30


## 설명

### 1. 연락처
#### 편하게 밥을 먹지 않은 친구를 찾아보세요 
- 보라색 하트 버튼 : 현재 혼밥 상태인 친구만을 보여주는 기능 
- 검색 : 특정한 유저 찾는 기능 
- 내 정보 : 클릭하면 현재 정보확인, 정보 업데이트 (위치 포함) 
- 친구 정보 : 클릭하면 친구 정보 확인, 전화 및 문자
- 우측 하단 버튼 : 이메일을 이용한 친구 추가


### 2. 갤러리
#### 친구가 좋아하는 음식이 무엇인지 편하게 검색해보세요 **
- 여러 맛집 정보가 나열된 card view \
- 아이템을 누르면 상세 정보 수정, 먹고 싶은 리스트에 추가 가능

### 3. 지도
#### 너무 멀리는 가기 싫다면? 친구의 위치를 확인해보세요
- 밥 먹을 친구를 찾는 사람, 아닌 사람을 색으로 구분해 편하게 친구들의 위치를 확인 가능 \
- 검색을 통해 특정 친구의 위치를 확인 가능



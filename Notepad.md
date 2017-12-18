### Kakao-clone

#### tag 1-03. 파일 생성 및 header-top 구현

#### tag 1-04. header-bottom 구현

#### tag 1-05. 네비게이션(bottom) 구현

- 네비게이션의 탭을 클릭하면 각각의 링크로 이동한다.
- 선택된 탭은 진하게 표시하기 위해서 특정 클래스를 부여한다.

#### tag 1-06. friends main영역(index.html) 구현

#### tag 1-07. chats main 영역(chats.html) 구현

#### tag 1-08. find main 영역(find.html) 구현

#### tag 1-09. more main 영역(more.html) 구현

#### tag 1-10 chat main 영역(chat.html) 구현

- chats에서 채팅 창 윈도우를 클릭하면 chat으로 이동하도록 chats.html도 수정

#### tag 1-11 profile main 영역(profile.html) 구현

- Friends의 내 프로필을 누르면 (index.html) profile.html로 이동하도록 수정
- (profile.html) X 버튼을 누르면 index 페이지로 이동
- chat.html도 < 버튼 누르면 chats.html로 이동


#### tag 2-01 CSS 준비하기

- css 폴더, style.css, reset.css, header.css 생성 후 임포트
- 모든 html 파일의 header에 top-header 클래스 부여

#### tag 2-02 top-header 레이아웃, 배경 잡기

####  tag 2-03 font-family 지정(google fonts)

- global.css 생성, open sans 적용

#### tag 2-04 바닥에 있는 navigation.css 구현

- navigation.css 생성

- 바닥에 붙이기

- header도 상단에 붙이기

- header를 상단에 붙이면 main 영역의 컨텐츠가 안보이게 되는데, 이를 해결하기

  ![](./review_imgs/problem1-alignment.jpg)

  ```
  위 정렬 문제를 해결하는 두 가지 방법은?
  ```

#### tag 2-05 search-bar 구현 

- search-bar.css 생성

#### tag 2-06

- friends.css 생성

#### tag 2-07

- chats.css 생성
- main 영역에서 채팅창 만드는 노란 원 모양 버튼 외 나머지 구현



#### tag 2-08

- chats.css 보완
- 노란색 원 모양 버튼 구현


#### tag 2-09

- find.css 생성
- header-bottom의 첫 번째 컬럼의 텍스트를 회색으로 변경



#### tag 2-10

- more.css 생성



#### tag 2-11

- profile.css 생성
- header에 top-header-trasparent 추가, 
- width, height에서 사용하는 vh 단위

#### tag 2-12

- chat.css 생성

#### tag 3-01

- (chats.css) 채팅방을 만드는 노란색 원모양 아이콘에 hover 상태 시 box-shadow transition 부여
- (search-bar.css) 서치바 보더 focus 상태에 시 노란색으로

#### tag-3-02

- (chats.css) 노란 색 원 모양 버튼이 한 바퀴 도는 transform + transition 적용
- (navigation.css) 하단 네비게이션의 4개의 아이콘에 hover 시 사이즈가 커지는 transform + transition 적용

#### tag 3-03

- (global.css) 모든 페이지 body에서 애니메이션을 적용하여 (opacity와 translateY) 서서히 아래에서 위로 나타나도록
- (friends.css/index.html) 이미지가 계속 빙글빙글 돌도록, 중간에 사이즈가 50%가 됬다가 다시 돌아오도록 애니메이션 적용

#### tag 3-04

- 모바일 사이즈가 아닐 때는 화면 크기를 줄여주세요. 출력
- bigScreen.css 생성
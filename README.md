## 🏠 머무름만으로도 여행이 되는 공간, STAWEFOLIO

![](https://velog.velcdn.com/images/sujeong_dev/post/5aa50db8-787b-43ac-8b61-f79c31a8b5a6/image.gif)

<br />

## 👏 소개

stayfolio를 모티브로한 숙박 예약 사이트

<br />

## 💡 서비스
👤 소셜(kakao) 로그인 <br />
🎵 숙소에서 감성을 더해줄 음악 추천 <br />
🏠 카테고리 별 숙소 필터링 및 키워드 검색 <br />
🛒 숙소 예약 및 예약 내역 조회 <br />

<br />

## 🚀 실행방법
```zsh
$ git clone https://github.com/sujeong-dev/39-2nd-stawefolio-frontend.git
$ git pull origin main
$ npm install
$ npm start
```

<br />

## 🔧 사용하는 기술스택
<p>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black" style="display=inline" />
<img src="https://img.shields.io/badge/Styled%20 Components-DB7093?style=flat-square&logo=StyledComponents&logoColor=white" style="display:inline-block"/>
<figure class="third"></figure>
</p>

![](https://velog.velcdn.com/images/sujeong_dev/post/7ae959d1-f530-4b7a-b1ae-92b0809d813d/image.png)

<br />

## ⭐️ 프로젝트 구조
```
.src
├── Router.js
├── components
│   ├── DayPicker
│   │   ├── CustomInput.js
│   │   └── DayPicker.js
│   ├── Footer
│   │   └── Footer.js
│   ├── Nav
│   │   ├── Nav.js
│   │   ├── WhenTo.js
│   │   └── WhereTo.js
│   └── RoomCard
│       └── RoomCard.js
├── config.js
├── images
│   └── booking
│       └── furniture.jpg
├── index.js
├── pages
│   ├── Booking
│   │   └── Booking.js
│   ├── Login
│   │   ├── Hooks
│   │   │   └── useFetch.js
│   │   ├── Login.js
│   │   ├── LoginCode.js
│   │   └── OAuth.js
│   ├── Main
│   │   ├── Main.js
│   │   └── Vibes.js
│   ├── Mypage
│   │   ├── Components
│   │   │   ├── BeforeAfter.js
│   │   │   └── Roomcard.js
│   │   └── Mypage.js
│   ├── Payment
│   │   └── Payment.js
│   └── RoomList
│       ├── DayPicker
│       │   └── CustomInput.js
│       ├── DropDown
│       │   ├── DropDown.js
│       │   ├── People.js
│       │   ├── PriceRange.js
│       │   ├── Stay.js
│       │   └── Theme.js
│       ├── Room.js
│       └── RoomList.js
└── styles
    ├── GlobalStyle.js
    └── theme.js
```

<br />


## 💡 협업 방법

[Daily Scrum](https://www.notion.so/04eef3a312024a05bb1bb7742b7afe21?pvs=4) <br />
[Weekly Sprint](https://trello.com/b/4IhZ7asL/staypolio) <br />
[GitBook](https://yhkyhk92s-organization.gitbook.io/stawefolio/) <br />
- Notion과 Trello를 사용하여 scrum, sprint 진행
- GitBook 활용하여 API 및 mockdata형식 공유

<br />

## ✨ 컨벤션

### 🏷 Naming

### 1. 파일명

- 컴포넌트의 파일명은 기본적으로 Pascal case를 사용한다. (ex. H3.js, Button.js)
- 여러 컴포넌트에서 import 하여 사용되는(utils) 파일명은 Camel case를 사용한다. (ex. useInputs.js)

### 2. 변수명

- 변수명은 기본적으로 Camel case를 사용한다. (ex. className)
- 가능한 명사를 사용한다.
- 배열과 같이 여러개의 원소를 담는 경우 복수형 명사를 사용한다.

### 3. 컴포넌트&함수명

- 컴포넌트명은 기본적으로 파일명과 동일하게한다.
- 컴포넌트 외에 함수는 변수명과 동일하게 Camel case를 사용한다.

### 4. 이미지 파일명

- 공용으로 사용하는(ex. 로고 이미지)이미지들은 ‘public/images’에 kebab-case로 작성한다.(ex. logo-image)
- 각자 컴포넌트에서 사용하는(ex. 메인페이지-사진들, 상품상세페이지-사진들)이미지들은 ‘src/images’에 컴포넌트명으로 폴더생성 후 kebab-case로 작성한다.(ex. main-image)

<br />

## ❤️ 팀원

`FrontEnd`

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/sujeong-dev"><img src="https://avatars.githubusercontent.com/u/112826154?v=4" width="100px;" alt=""/><br /><sub><b>구수정</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/Sing-DongKi"><img src="https://avatars.githubusercontent.com/u/112953746?v=4" width="100px;" alt=""/><br /><sub><b>김동기</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/Dave-ahn"><img src="https://avatars.githubusercontent.com/u/110475834?v=4" width="100px;" alt=""/><br /><sub><b>안상준</b></sub></a><br /></td>
     <tr/>
  </tbody>
</table>
- 구수정 : 숙소 리스트 페이지, 숙소 예약 페이지 <br />
- 김동기 : 메인 페이지, Navigation bar <br />
- 안상준 : 소셜로그인 페이지, 마이페이지 <br />
<br />

`BackEnd`

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/myeongseoklee"><img src="https://avatars.githubusercontent.com/u/109528794?v=4" width="100px;" alt=""/><br /><sub><b>이명석</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/exnyxxng"><img src="https://avatars.githubusercontent.com/u/107943132?v=4" width="100px;" alt=""/><br /><sub><b>이은영</b></sub></a><br /></td>
     <tr/>
  </tbody>
</table>
- 이명석 : 로그인, 숙소 리스트, 상세 API <br />
- 이은영 : 숙소 예약, 예약 내역 API <br />
<br />

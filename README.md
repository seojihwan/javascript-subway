<p align="middle" >
  <img width="200px;" src="./src/images/subway_emoji.png"/>
</p>
<h2 align="middle">level1 - 지하철 노선도 관리 SPA</h2>
<p align="middle">Browser History API를 이용해 구현하는 지하철 노선도 관리 SPA</p>
<p align="middle">
  <img src="https://img.shields.io/badge/version-1.0.0-blue?style=flat-square" alt="template version"/>
  <img src="https://img.shields.io/badge/language-html-red.svg?style=flat-square"/>
  <img src="https://img.shields.io/badge/language-css-blue.svg?style=flat-square"/>
  <img src="https://img.shields.io/badge/language-js-yellow.svg?style=flat-square"/>
  <img src="https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square"/>
</p>

# 🔥 Projects!

<p align="middle">
  <img src="./src/images/readme/subway_app_preview.png">
</p>


## 🌱 Step1
### Webpack을 통한 번들링

- [X] Webpack에서 babel을 설정한다.
- [X] 기타 플러그인 및 설정은 본인이 필요에 따라 추가한다.

### 회원가입

- [X] 유저가 회원가입 버튼을 누른다.
  - [X] 유저가 이름을 입력한다.
  - [X] 유저가 이메일을 입력한다.
  - [X] 유저가 비밀번호, 비밀번호 확인을 입력한다.
  - [X] 유저가 확인을 누른다.
  - [X] JWT(O) -> 첫 페이지 / JWT(X) -> 로그인 페이지

### 로그인

- [X] 유저가 이메일을 입력한다.
- [X] 유저가 비밀번호를 입력한다.
- [X] 유저가 확인을 입력한다.
- [X] 성공 - 로그인 버튼이 로그아웃 버튼으로 바뀐다.
- [X] 실패 - 빨간 글씨

### 로그아웃

- [X] 유저가 로그아웃 버튼을 누른다.
- [X] 성공 - 로그아웃 버튼이 로그인 버튼으로 바뀐다.

## 🎯 Step1



### 라우팅 기능

- [X] Browser History Api를 이용하여 SPA처럼 라우팅을 적용한다.

### 회원 기능

- [X] 유저는 회원 가입을 할 수 있다,
  - [X] 회원 가입시 받는 정보는 `email`, `name`, `password`이다.
- [X] 유저는 로그인 할 수 있다.
  - [X] 로그인하고 나면 로그인 버튼은 로그아웃 버튼으로 변경되어야 한다.
  - [X] 로그인한 유저만, 정보의 수정이 가능하다.
  - [X] 로그인하지 않은 유저는 정보를 읽는 것만 가능하다.
- [X] 유저는 로그아웃할 수 있다.
  - [X] 로그아웃하면 `/` 루트 페이지로 돌아온다.


## 🌱 Step2

### 역 관리 기능

유저가 지하철 역 Tab을 누른다.

**조회**

- [X] 지하철 역 리스트가 조회된다.

**생성**

- [X] 유저가 역 이름을 입력한다.
  - [X] 지하철 역은 2자 이상 20자 이하여야 한다.
  - [X] 중복된 지하철 역은 추가할 수 없다.
- [X] 유저가 확인 버튼을 누른다.
  - [X] 엔터키 또는 마우스 클릭으로 역을 추가할 수 있어야 한다.
- [X] 추가된 역이 화면에 보인다.

**수정**

- [X] 유저가 지하철 역 이름 옆 수정 버튼을 누른다.
  - [X] 지하철 역 이름 수정 모달이 뜬다.
  - [X] 수정하는 ui는 modal을 이용하여 수정한다.
  - [X] 수정 ui는 직접 구현한다.

**삭제**

- [X] 유저는 지하철 역 이름 옆 삭제 버튼을 누른다.
  - [X] 삭제 시 confirm을 이용하여 한번 더 유저가 확인할 수 있어야 한다.
  - [X] 이미 노선에 등록된 역인 경우 삭제할 수 없다.

### 노선 관리 기능

유저가 노선 관리 Tab을 누른다.

**조회**

- [X] 지하철 노선 리스트가 조회된다.

**생성**

- [X] 유저가 노선 추가 버튼을 누른다.
  - [X] 지하철 노선은 2자 이상 10자 이하여야 한다.
  - [X] 중복된 지하철 노선 이름은 추가할 수 없다.
  - [X] 색상, 상행역, 하행역, (최초 상행역과 하행역 구간의)거리, 시간을 입력한다.
- [X] 유저가 확인 버튼을 누른다.
  - [X] 엔터키 또는 마우스 클릭으로 노선을 추가할 수 있어야 한다.
- [X] 추가된 노선이 화면에 보인다.

**수정**

- [X] 유저가 지하철 노선 이름 옆 수정 버튼을 누른다.
  - [X] 지하철 노선의 이름, 상행역, 하행역, 거리, 시간, 색상을 수정할 수 있다.

**삭제**

- [X] 유저는 지하철 노선 이름 옆 삭제 버튼을 누른다.
  - [X] 삭제 시 confirm을 이용하여 한번 더 유저가 확인할 수 있어야 한다.

### 구간 관리 기능

유저가 구간 관리 Tab을 누른다.

**조회**

- [X] 지하철 구간 리스트가 조회된다.

**생성**

- [X] 유저가 구간 추가 버튼을 누른다.

  - [X] 구간 추가 모달이 뜬다.
  - [X] 상행역, 하행역이 모두 노선 안에 포함되어 있으면 추가할 수 없다.
  - [X] 역과 역 사이에 새로운 역이 추가될 수 있다.
  - [X] 노선에서 갈래길은 생길 수 없다.

- [X] 유저가 확인 버튼을 누른다.
  - [X] 엔터키 또는 마우스 클릭으로 구간을 추가할 수 있어야 한다.
- [X] 추가된 구간이 화면에 보인다.

**삭제**

- [X] 유저가 역 이름 옆에 삭제 버튼을 누른다.
  - [X] 노선에서 역이 삭제된다.

## 🎃 Step3

### 전체보기 기능

- [X] 노선의 상행 종점부터 하행 종점까지 연결된 순서대로 노선과 역 목록을 조회할 수 있다.
- [X] 조회를 위한 UI는 스스로 만든다.


<br>

## ⚙️ Before Started

#### <img alt="Tip" src="https://img.shields.io/static/v1.svg?label=&message=Tip&style=flat-square&color=673ab8"> 로컬에서 서버 띄워서 손쉽게 static resources 변경 및 확인하는 방법

로컬에서 웹서버를 띄워 html, css, js 등을 실시간으로 손쉽게 테스트해 볼 수 있습니다. 이를 위해서는 우선 npm이 설치되어 있어야 합니다. 구글에 `npm install` 이란 키워드로 각자의 운영체제에 맞게끔 npm을 설치해주세요. 이후 아래의 명령어를 통해 실시간으로 웹페이지를 테스트해볼 수 있습니다.

```
npm install -g live-server
```

실행은 아래의 커맨드로 할 수 있습니다.

```
live-server 폴더명
```

<br>

## 👏 Contributing

만약 미션 수행 중에 개선사항이 보인다면, 언제든 자유롭게 PR을 보내주세요.

<br>

## 🐞 Bug Report

버그를 발견한다면, [Issues](https://github.com/woowacourse/javascript-subway/issues)에 등록해주세요.

<br>

## 📝 License

This project is [MIT](https://github.com/woowacourse/javascript-subway/blob/main/LICENSE) licensed.

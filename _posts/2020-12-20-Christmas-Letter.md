---
title:  "[WEB] 크리스마스 카드 만들기"
excerpt: "지인들에게 보낼 크리스마스 카드 만들기 + 'SCC' 후기"
read_time: false # read_time을 출력할지 여부 1min read 같은것!
categories:
  - Study Note
tags:
  - HTML
  - CSS
  - WEB
  - 공부
  - 크리스마스
last_modified_at: 2020-12-21 23:00
date: 2020-12-20 23:35:00 
---

# Making Christmas Letter

## [스파르타코딩클럽](https://spartacodingclub.kr/) | [크리스마스: 나홀로 코딩](https://spartacodingclub.kr/online/xmas?n_c=8XRAV4KHDlGMehSwnSSy)
할 거 없는 무료한 주말에, 페이스북을 뒤적거리다가 '스파르타코딩클럽(SCC)'이라는 곳의 광고를 봤습니다.
> 크리스마스를 재정의합니다. <br><br>올해 크리스마스, 사회적 거리두기로 인해 산타와 루돌프도 집에만 있기로 했어요.<br>모두를 위해 조금씩 조심해야 하는 시기를 함께 이겨내기 위해 준비했습니다.<br>코딩으로 연하장 만들고 주변에 따뜻한 마음을 전해 보아요!

최근, HTML과 CSS를 익혔는데, 배운 지식들을 활용해보기 위해 강좌를 수강했습니다.<br>
~~사실 공짜라서...~~
<br>
### 먼저 결과물을 공유합니다.
# [🎄Christmas Letter🎅](https://oneonlee.github.io/Christmas-Letter/)

## 목차
강의 목차는 다음과 같았습니다.<br>
* [1일차](https://www.notion.so/1-da5ea1c0c29043c299ff3cbc2f3d0feb)
  * 1-1 스파르타 튜토리얼
  * 1-2 오늘 배울 것
  * 1-3 **HTML, CSS 기본 내용**
  * 1-4 Quiz_간단한 **로그인 페이지 만들어보기**
  * 1-5 **CSS 기초**
  * 1-6 **자주 쓰이는 CSS 연습하기**
  * 1-7 **폰트 입히기**
  * 1-8 숙제 설명
* [2일차](https://www.notion.so/2-83d2f3b9517b4ede89654a86b43dd1d5)
  * 2-1 크리스마스 카드 구경하기
  * 2-2 봉투 HTML 만들기
  * 2-3 (숨고르기) **웹폰트 적용하기**
  * 2-4 편지 HTML 만들기 - 르탄이
  * 2-5 편지 HTML 만들기 - 메시지
  * 2-6 **모바일 버전 처리**
  * 2-7 **간단한 Javascript 맛보기**
  * 2-8 **눈오는 효과 붙이기**
  * 2-9 히든메시지 넣어보기
  * 2-10 **공유를 위한 기초작업**
  * 2-11 배포해보기

핵심이라고 생각하는 부분들은 **볼드** 처리 했습니다.<br>

## 배운 것
* HTML과 CSS의 개념
  * HTML은 뼈대, CSS는 꾸미기!
* VSCode 꿀팁 (?)
  * VSCode에선 ctrl+K+F (맥은 cmd+K+F)로 자동정렬이 가능하다!
* 간단한 로그인 페이지 만들어보기
  * [결과물 보러가기](https://oneonlee.github.io/Christmas-Letter/login.html)
* [구글 웹폰트](https://fonts.google.com/?subset=korean) 입히기
  * 맘에 드는 폰트 선택
  * link를 복사해서 <head> ~ </head>사이에, CSS를 복사해서 <style> ~ </style> 사이에 넣는다.<br>![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F9ff2f7a1-1759-4456-b498-bf9e734acaab%2FUntitled.png?table=block&id=fa3630d4-b44b-44b8-acbb-6ec21d80b607&width=790&userId=&cache=v2)
* 카카오톡, 페이스북 등에 공유하기 위한 기초작업 - og태그 넣기
	* 아래와 같은 이미지+텍스트를 만들 수 있다.![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F0d2eb3da-9a9e-4965-a15d-4e2f45fd6118%2FUntitled.png?table=block&id=617b0d6b-526d-4393-8cd8-55d669afd011&width=860&userId=&cache=v2)
	
 ~~~JavaScript 
<meta property="og:image" content="https://www.christmastreeassociation.org/wp-content/uploads/2016/06/multiple-christmas-trees-in-one-household-800x400.jpg">
<meta property="og:title" content="길동이의 카드">
<meta property="og:description" content="2020을 추억하며">
~~~

* 하는 김에 favicon도 적용
	* 요거
	![](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fb92b561d-5a1e-4fbe-b7fa-9348e897907d%2FUntitled.png?table=block&id=01a336df-af64-4fd6-8939-f63aa1ed8df7&width=580&userId=&cache=v2)
	
~~~JavaScript
<link rel="shortcut icon" href="https://freepngimg.com/download/christmas/26196-6-christmas-stocking.png">
~~~

## 후기
그 동안 HTML과 CSS를 **배우기만** 하고 웹페이지를 처음부터 끝까지 만들어본 적이 없어서 아쉬웠는데, 작은 웹페이지를 처음으로 만들어보는 좋은 기회였습니다.

다만, 강좌에서 제시한 수강대상인 `코딩의 ㅋ도 모르는 왕초보`가 듣기에는  조금 어려울 것 같습니다.
강의 시간이 2시간으로 다소 제한적이어서, 배우는 내용 역시 제한적이었습니다.

### 마지막으로

**수료증 두둥등장 🎓**<br>
![](https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/cert/img/5fd1cedae7b11d0865a27a78_5fdd5782922b59b9f312cdd6.jpg)

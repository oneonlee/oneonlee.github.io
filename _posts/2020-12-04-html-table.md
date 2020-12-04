---
title:  "[HTML5] HTML 테이블 태그"
excerpt: "기본 태그 중 테이블 테그를 공부했습니다."
read_time: false # read_time을 출력할지 여부 1min read 같은것!
categories:
  - Study Note
tags:
  - HTML
  - WEB
  - 공부
# last_modified_at: 2020-12-02 22:32
date: 2020-12-04 22:55:00 
---

HTML의 기본 태그 중 테이블 태그를 공부했습니다.

| 태그 | 설명 |
|---|---|
| table | 표 삽입 |
| tr | 표에 행 삽입 |
| th | 표의 제목 셀 생성|
| td | 표의 일반 셀 생성 |
- 테이블 태그
<br>
| 태그 | 속성 | 설명 |
|---|---|---|
|table |border | 표의 테두리 두께 지정 |
| <r2> th, td | colspan | 셀의 너비 지정 |
||rowspan |셀의 높이 지정|
- 테이블 태그의 속성
  - th 태그와 td 태그는 colspan 속성과 rowspan 속성을 상요해 표에서 차지하는 영역을 조절 할 수 있다.
    - colspan 속성을 사용하면 영역이 가로 방향으로 늘어난다.
    - rowspan 속성을 사용하면 영역이 세로 방향으로 늘어난다.
  
---

### 예시
<table border="1">
    <thead>
        <tr>
            <th colspan="6">한국의 차</th>
        </tr>
        <tr>
            <th rowspan="6">뿌리차</th>
            <td>인삼차</td>
            <th rowspan="9">과일차</th>
            <td>수정과</td>
            <th rowspan="5">과일차</th>
            <td>뽕잎차</td>
        </tr>
        <tr>
            <td>당귀차</td>
            <td>유과차</td>
            <td>감잎차</td>
        </tr>
        <tr>
            <td>생강차</td>
            <td>구기자차</td>
            <td>솔잎차</td>
        </tr>
        <tr>
            <td>칡차</td>
            <td>대추차</td>
            <td>국화차</td>
        </tr>
        <tr>
            <td>둥글레차</td>
            <td>오미자차</td>
            <td>이슬차</td>
        </tr>
        <tr>
            <td>마차</td>
            <td>매실차</td>
            <th rowspan="4">기타</th>
            <td>두충차</td>
        </tr>
        <tr>
            <th rowspan="4">곡물차</th>
            <td>보리차</td>
            <td>모과차</td>
            <td>영지버섯차</td>
        </tr>
        <tr>
            <td>옥수수차</td>
            <td>산수유차</td>
            <td>귤강차</td>
        </tr>
        <tr>
            <td>현미차</td>
            <td>탱자차</td>
            <td>쌍화차</td>
        </tr>
    </thead>
</table>

위와 같은 표를 HTML로 나타내보자.

```html
<table border="1">
    <thead>
        <tr>
            <th colspan="6">한국의 차</th>
        </tr>
        <tr>
            <th rowspan="6">뿌리차</th>
            <td>인삼차</td>
            <th rowspan="9">과일차</th>
            <td>수정과</td>
            <th rowspan="5">과일차</th>
            <td>뽕잎차</td>
        </tr>
        <tr>
            <td>당귀차</td>
            <td>유과차</td>
            <td>감잎차</td>
        </tr>
        <tr>
            <td>생강차</td>
            <td>구기자차</td>
            <td>솔잎차</td>
        </tr>
        <tr>
            <td>칡차</td>
            <td>대추차</td>
            <td>국화차</td>
        </tr>
        <tr>
            <td>둥글레차</td>
            <td>오미자차</td>
            <td>이슬차</td>
        </tr>
        <tr>
            <td>마차</td>
            <td>매실차</td>
            <th rowspan="4">기타</th>
            <td>두충차</td>
        </tr>
        <tr>
            <th rowspan="4">곡물차</th>
            <td>보리차</td>
            <td>모과차</td>
            <td>영지버섯차</td>
        </tr>
        <tr>
            <td>옥수수차</td>
            <td>산수유차</td>
            <td>귤강차</td>
        </tr>
        <tr>
            <td>현미차</td>
            <td>탱자차</td>
            <td>쌍화차</td>
        </tr>
    </thead>
</table>
```
<br>
이렇게나 길게 코드가 나온다.   
```table border="1"```은 표의 테두리를 지정하는 속성이다.      
표의 가로줄 한 줄, 한 줄 씩 천천히 생각해보면서 구현하면 될 것 같다.
역시 1차원에서 2차원을 나타내기는 어렵다.   
실제로 응용할 일은 별로 없을 듯 하다.   

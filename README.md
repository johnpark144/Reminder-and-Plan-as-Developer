# 1) 페이스북 프로젝트

■ 페이스북 어려웠던점: (그림을 포함하자)
1. 좋아요기능을 수행하면서 모델을 자주 수정하여 시행착오를 겪고 그가운데 모델 migrate이 잘 작동되지 않아 데이터를 자주 삭제하기를 반복했던점,
2. 그리고 좋아요숫자를 입력할때 발생하는 로직들을 구현하여 실시간 입력되는 숫자와 실제 저장되는 숫자를 따로 저장하고
여러 오류속에서 하나하나 고치기를 반복했던것,
3. 로그인 구현시 가입시에 암호화된 비밀번호가 입력된 비밀번호와 계속 일치하지않아 2일동안 오류수정하려 노력함
해결 : 가입시 Jquery formdata형식으로 서버에 보내 암호화해서 발생된 오류임을 확인하여, Json형식으로바꾸는데
또 오류가 발생하여... Form태그를 사용해서 Post하니 해결..

■ 페이스북 보완할점: 
코드정리, 주석 영어문법체크, 콘솔로그 지우기

# 2) myabc 프로젝트
■ 이름을 그렇게 지은이유

■ myabc 어려웠던점: (그림을 포함하자)
1. API가 작동했다 안했다함
2. x를 누를때 Delete할건지 다시 물어보는 모달이 생성되면서 usestate가 작동되어
그 모달에서 확인누르면 항상 마지막 usestate된 id값이 입력되어 삭제됨

#########################################################################
# 3) stillsteal 프로젝트
■ 이름을 그렇게 지은이유:
여전히 싼것같은 쇼핑사이트라서

■ stillsteal 어려웠던점:
1. 장바구니 기능 구현중 Local storage를 사용하는데 새로고침 할때 마다 정보가 날라가서 혼자 해결하는데 어려웠음
2. 작은기능을 구현하기위해 큰기능보다 훨씬 더 많은 코드를 요구할떄


■ 정보:
Creater : Yeonghwan Park (John Park)
Main Tools : React(프론트), Django(백엔드, restframework)
Sub Tools : Html, CSS(Tailwind CSS), MySql
Explantion : 
Date of creation : Nov 4th ~ Nov 15th
Date of debugging : Nov 16th ~
Date of upload : 

■ 기능:
Responsive Website
Login, Logout, Signup (you can also use without login)
TokenRefresh with JWT
Navigation bar and Navigation side bar
Add to cart, subtract from cart in Realtime (Login -> Local Storage / Non-login -> Backend Server)
Search
Past-searchlist (Local Storage)
See cart in Product detail, Checkout, Cart in deferent form
Pagenation
Number of posts to display per page
Sort by category
Sort by (복잡한 옵션들 설명)
Product detail
Checkout
Image Animation and design (About Us)
Spinner Loading until Datas is found (despite no any data)

■ 사진찍기: 
장고 어드민(토큰 강조), Api, MYsql, 카테고리, 디테일, 카트


■ 동영상 찍기:

홈전체 보여주고, 홈 카테고리 하나씩 들어가보기 -> 카테고리 전체 들어가보며 페이지 개수 바꿔보기 -> 페이지 하나하나 눌러보기 -> 화살표

페이지마다 디테일 -> 뒤로가기 ->페이지 개수 바꿔서 디테일 ->뒤로가기 -> 카테고리도 들어가서 디테일 -> 뒤로가기 -> 다른 카테고리 페이지 개수 바꾸고 페이지도 바꿔서 디테일

카테고리에서 있는거 검색 -> 홈에서도 있는거 검색 -> 스피너 강조 -> 홈에서 없는거 검색 -> 홈에있는거 다시검색하여 검색어 다시올라오는거 보여줌 -> 지난검색어확인 -> 새로고침 -> 히스토리 지우기

로그인후 카트비우기 -> 홈에서 카트 -> 더해진거 보여주고 -> 카테고리에서 더카트에더함 -> 디테일에서도 카트더해지는거 보여줌 -> 카트에서 추가해보고 제거도 해봄

로그아웃후 카트 더하고 -> 확인 -> 다시로그인 다시 할떄 기존 정보 저장되있는거 보여줌 -> 어바웃어스 사진 흘러가는거 살짝보여주고 끝

반응형 홈 ->  카테고리 (지난검색어들 보여주며) ->  깔짝대보기 -> 디테일(티모바일 카드 열어놓고) -> 느리게 깔짝대보기 -> 카트 -> 깔짝대보기 -> 체크아웃 -> 깔짝대보기 -> 어바웃어스 -> 느리게 스크롤해가면서 깔짝대보기



■ 해야할것: 
- 동영상찍고 깃허브 올리기

########################################################################
# 기타
자소서쓸때 회사이름 적어 복붙이 아님을증명,
자소서 컬러나 이미지를 회사 로고와 비슷하게, 클론 아이디어 응용표시,

########################################################################
########################################################################
########################################################################

# 앞으로 계획 (구체적 계획)
- 각종게임 사이트 : 자음게임, 틱택토, 성격테스트,
- 좋은 홈페이지 포트폴리오 (장고, 리액트, mysql)
- 넷플, 아마존, 우버, 에어비엔비 클론코딩, 챗봇, 자동크롤링 사이트
- MBTI 성격테스트,
- 자주쓰는 패턴 깃허브에 모아두기
- study 디파지토리 정리 (이름, 리액트 다른거 업로드 등) 


# 봐야할 강좌들 (모아논 강좌)
- html, css, js: 
- django:
- sql :

- react, django 같이 : todoapp, 7시간강좌, notesapp

- python기본 : intermediate강좌, 중급코딩예제, 파이썬 함수책공부
- pandas : 나도코딩꺼 데이터분석, 10시간짜리, 5시간짜리

- Redux
- graphql
- aws
- ReactNative
- NextJS (13버전나오면)

- 자료구조 알고리즘
ㅡ 면접대비

# 보충공부 해야 할것 (짜투리시간 계획) -> 
- 장고 : 다대다, 일대일, form, 로그인, 가입, restful Api, authentication, authorization,
- 자바스크립트, 리액트 : 리듀스, axios, for문대신함수, 프로토타입, 호이스팅, 스코프, 클러저,
컬백, 프로미스, 어싱크어웨이트, this, new, 세션 쿠키 스토리지 저장하고 사용하기 응용

- html, css : px vh em 등 차이알기


# 구현 해봐야할 기능들 : 페이지네이션, 검색, 야간모드, 언어 바꾸기



# 지금까지한것
: 파이썬기초, 파이게임, 크롤링(BS4), 웹자동화(셀리니움,requests), 자동화(엑셀,데스크톱),
장고, html, css, 자바스크립트기초, 리액트, mysql

# 검색 
: 파이썬개발자, 소프트웨어 개발자, 프로그래머, 파이썬, (쥬니어, 엔트리), 장고개발자, 리액트개발자, 풀스택 등...

- 이메일체크, 차
(나중에 사용해서 만들것 : Framer Motion, Email, Animate.css, loader, 실시간기능, next auth, react-hook-form, styled-components,
react-lottie-player, react-simple-typewriter , GSAP (ScrollTrigger), three js)

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
# 앞으로 계획

- Gather all Before organized.ts 파일 정리

- 포폴 사이트 좋은기능들 다엮어 만들기
- 포폴들 코드 스마트폰보면서 재점검 및 쓸만했던 코드 깃허브 요약해 올리고 재 배포
- 깃허브 점검 수정, 이력서 수정
- 깃 공부하기
- 깃허브에 쓸만한거 링크 저장
- 인터뷰준비 및 코테준비 및 공부
- Meta 프론트엔드 인증서
- IBM Full Stack Software Developer
- HARVARD CS50
- jest(testing)
- Reactnative, graphql 같이 강의 듣고 깃허브 정리
- 차트라이브러리 공부

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
# 앞으로 계획 예비

- 쓸만한 API 및 라이브러리 ( RelaxJS, scrollOut, Sanity, notion Api, Gsap scroll,  threejs)

- 미용실 예약 사이트 : Calendar Date Picker, 지도

- 프로젝트와 연습한것들 Basicstudy readme에 주요 라이브러리, 구현내용 및 설명들을 요약해서 한페이지에 배열형식으로 정리해서 적어두기(라이브러리 및 툴)

- 기존에 있는 basicstudy 파일들 요약해서 사용하기 좋게 바꾸기

- 넷플, 우버, 챗봇(chatGPT),자동크롤링 사이트, mbti, 각종게임 사이트 : 자음게임, 틱택토, 성격테스트
- 지금까지 공부한거 코드패턴 사전 사이트

- 깃 자세히
- jest(testing)
- Reactnative
- 스타일컴포넌트, 머티리얼ui
- SVG 그리기
- nextjs api만들기
- Gsap (scroll)
- threejs
- blender render script
- graphql(apollo)
- aws
- node깊게 공부 + express

- 자료구조 알고리즘

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
# 보충공부 해야 할것 (짜투리시간 계획) -> 
- 장고 : 다대다, 일대일, form, 로그인, 가입, restful Api, authentication, authorization,
- 자바스크립트, 리액트, NEXTJS : 리듀스, 리덕스, Material UI, axios, React query, for문대신함수, 프로토타입, 호이스팅, 스코프, 클러저,
컬백, 프로미스, 어싱크어웨이트, this, new, JWT토큰, 여러 라이브러리

- html, css : px vh em 등 차이알기

면접 :
- JS : 클로저, this, event 버블링, 캡쳐링, 댈리게이션, async await (예외처리 까다로운점)
- 리액트 :virtual dom, 랜더링 최적화(usememo usecallback), 리렌더링 조건,
- cs 지식 : google.com 치면 무슨일이 일어나나, 

# 구현 해봐야할 기능들 : 언어 바꾸기, 뮤직플레이어

# 지금까지한것
: 파이썬기초, 파이게임, 크롤링(BS4), 웹자동화(셀리니움,requests), 자동화(엑셀,데스크톱),
장고, html, css, 자바스크립트기초, 리액트, mysql, Redux, Reactquary, Nextjs, 타입스크립트 

# 검색 
: 파이썬개발자, 소프트웨어 개발자, 프로그래머, 파이썬, (쥬니어, 엔트리), 장고개발자, 리액트개발자, 풀스택 등...



######################################################################
######################################################################
# 프로젝트

###### 1) 페이스북 프로젝트

■ 페이스북 어려웠던점: (그림을 포함하자)
1. 좋아요기능을 수행하면서 모델을 자주 수정하여 시행착오를 겪고 그가운데 모델 migrate이 잘 작동되지 않아 데이터를 자주 삭제하기를 반복했던점,
2. 그리고 좋아요숫자를 입력할때 발생하는 로직들을 구현하여 실시간 입력되는 숫자와 실제 저장되는 숫자를 따로 저장하고
여러 오류속에서 하나하나 고치기를 반복했던것,
3. 로그인 구현시 가입시에 암호화된 비밀번호가 입력된 비밀번호와 계속 일치하지않아 2일동안 오류수정하려 노력함
해결 : 가입시 Jquery formdata형식으로 서버에 보내 암호화해서 발생된 오류임을 확인하여, Json형식으로바꾸는데
또 오류가 발생하여... Form태그를 사용해서 Post하니 해결..

■ 페이스북 보완할점: 
코드정리, 주석 영어문법체크, 콘솔로그 지우기

###### 2) myabc 프로젝트
■ 이름을 그렇게 지은이유

■ myabc 어려웠던점: (그림을 포함하자)
1. API가 작동했다 안했다함
2. x를 누를때 Delete할건지 다시 물어보는 모달이 생성되면서 usestate가 작동되어
그 모달에서 확인누르면 항상 마지막 usestate된 id값이 입력되어 삭제됨


###### 3) stillsteal 프로젝트
■ 이름을 그렇게 지은이유:
여전히 싼것같은 쇼핑사이트라서

■ stillsteal 어려웠던점:
1. 장바구니 기능 구현중 Local storage를 사용하는데 새로고침 할때 마다 정보가 날라가서 혼자 해결하는데 어려웠음
2. 작은기능을 구현하기위해 큰기능보다 훨씬 더 많은 코드를 요구할떄


###### 4) mytube 프로젝트
■ 이름을 그렇게 지은이유 : 보고싶은 유튜브 영상을 나중에 볼영상에 담아두는 것을 중심으로 만든 사이트이기 때문

■ mytube 어려웠던점: (그림을 포함하자)
1. Nextjs로 만드는 첫 프로젝트 여서 시범으로 자료가 많이없는 터보팩 썼다가 버그가 가끔씩 있어서 지우기를 반복함
2. 리액트 훅이나, LINK를 사용할때마다 call is undefined에러계속 뜸, 2일정도 애먹었는데 알고보니 프로젝트 만드는 기간중
NextJS의 가장 최신버전의 오류였음, 오류 고쳐질때까지 이전버전 씀
3. 기본 웹팩을 써서 그런지 너무 느려서 딜레이될때가 많았음
4. 배포할떄 vercel을 썼는데 오류가 나서 검색했는데 검색결과가 너무 장황하게 나와서 알수 없었으나
다 조사한끝에 알아낸것은 아이콘끝에 폴더가 소문자로 시작하는데 코딩할떄 대문자로 적었었고, 기존에 코드작성할때는 대소문자 구분이 문제가 되지않았으나,
vercel은 대소문자구분 하는 것을 발견함

########################################################################


# 기타
자소서쓸때 회사이름 적어 복붙이 아님을증명,
자소서 컬러나 이미지를 회사 로고와 비슷하게, 클론 아이디어 응용표시,



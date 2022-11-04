<div width="100%" height="100%" align="center">
  
<h1 align="center">
  <p align="center">Vue.js 코딩 공작소</p>
  <a href="https://docusaurus.io">
    <img width="50%" src="cover.jpg" />
  </a>
</h1>
  
  
<b>에릭 한쳇, 벤자민 리스트원 저, 정용석 역</b></br>
길벗 · 2021년 02월 22일 발행(2쇄)</br>
[깃허브](https://github.com/githubITbook/007024)</b> 

</div>

## :bulb: 목표

- **SIMPLE 목표: 자바다운 코딩 공부**

  > 너무 과하지 않으면서 간결하게, 군더더기 없이, 딱 필요한 만큼만 있는 코드를 작성하기

</br>


## :mag: 목차

1부 Vue.js와 친해지기

1장 Vue.js 소개

  1.1 거인의 어깨 위에서

    1.1.1 모델-뷰-컨트롤러 패턴

    1.1.2 모델-뷰-뷰모델 패턴

    1.1.3 반응형 애플리케이션이란?

    1.1.4 자바스크립트 계산기

    1.1.5 Vue 계산기

    1.1.6 자바스크립트와 Vue 비교

    1.1.7 Vue는 어떻게 MVVM과 반응성을 사용할까?

    1.2 왜 Vue.js를 사용할까?

1.3 미래에 대한 생각

1.4 요약


2장 Vue 인스턴스

2.1 첫 애플리케이션

    2.1.1 Vue 인스턴스 루트

    2.1.2 애플리케이션이 잘 작동하는지 확인

    2.1.3 뷰 안에서 무언가 보여 주기

    2.1.4 Vue에서 속성 살펴보기

2.2 Vue 생명 주기

    2.2.1 생명 주기 훅 추가

    2.2.2 생명 주기 코드 탐구

    2.2.3 생명 주기 코드를 유지할까?

2.3 상품 표시

    2.3.1 상품 데이터 정의

    2.3.2 상품 화면 마크업

2.4 출력 필터 적용

    2.4.1 필터 함수 작성

    2.4.2 마크업에 필터를 추가하고 여러 값 테스트

2.5 연습 문제

2.6 요약


2부 뷰와 뷰-모델

3장 상호 작용성 추가

3.1 장바구니 데이터는 배열 추가로 시작

3.2 DOM 이벤트에 바인딩

    3.2.1 이벤트 바인딩 기초

    3.2.2 [장바구니 담기] 버튼에 이벤트 연결

3.3 [장바구니 담기] 버튼을 추가하고 개수 세기

    3.3.1 계산된 속성은 언제 사용할까?

    3.3.2 계산된 속성으로 업데이트 이벤트 살펴보기

    3.3.3 장바구니에 담긴 상품 개수 표시 및 테스트

3.4 버튼에 사용자 편의 추가

    3.4.1 재고 주시

    3.4.2 계산된 속성과 재고 작업

    3.4.3 v-show 지시자 기초

    3.4.4 v-if와 v-else를 사용해서 버튼 비활성화

    3.4.5 토글 기능이 있는 <장바구니 담기> 버튼 추가

    3.4.6 v-if를 사용해서 체크아웃 페이지 표시

    3.4.7 v-show와 v-if/v-else 비교

3.5 연습 문제

3.6 요약


4장 폼과 입력

4.1 v-model 바인딩 사용

4.2 값 바인딩 살펴보기

    4.2.1 체크 박스에 값 바인딩

    4.2.2 값 바인딩과 라디오 버튼 작업

    4.2.3 v-for 지시자 알아보기

4.3 수식어 살펴보기

    4.3.1 .number 수식어 사용

    4.3.2 입력 값 다듬기

    4.3.3 .lazy v-model 수식어

4.4 연습 문제

4.5 요약


5장 조건부, 반복, 리스트

5.1 사용 가능한 목록 메시지 표시

    5.1.1 체크 박스에 값 바인딩

    5.1.2 v-else와 v-else-if를 사용해서 메시지 더 추가

5.2 상품 반복

    5.2.1 v-for 범위를 이용한 별점 추가

    5.2.2 별점에 HTML 클래스 바인딩

    5.2.3 상품 셋팅

    5.2.4 products.json에서 상품 정보 가져오기

    5.2.5 v-for 지시자로 앱 리팩토링

5.3 레코드 정렬

5.4 연습 문제

5.5 요약


6장 컴포넌트 사용

6.1 컴포넌트란?

    6.1.1 컴포넌트 생성

    6.1.2 전역 등록

    6.1.3 지역 등록

6.2 컴포넌트의 관계

6.3 속성을 사용해서 데이터 전달

    6.3.1 리터럴 속성

    6.3.2 동적 속성

    6.3.3 속성 검증

6.4 템플릿 컴포넌트 정의

    6.4.1 인라인 템플릿 문자열 사용

    6.4.2 text/x-template 스크립트 요소

    6.4.3 단일 파일 컴포넌트

6.5 커스텀 이벤트

    6.5.1 이벤트 수신

    6.5.2 .sync를 사용해서 자식 속성 변경

6.6 연습 문제

6.7 요약


7장 고급 컴포넌트와 라우팅

7.1 슬롯 사용

7.2 지정 슬롯 살펴보기

7.3 범위 슬롯

7.4 동적 컴포넌트 앱 생성

7.5 비동기 컴포넌트 설정

7.6 Vue-CLI를 사용하여 애완용품샵 앱 변환

    7.6.1 Vue- CLI로 새로운 애플리케이션 생성

    7.6.2 라우트 설정

    7.6.3 애플리케이션에 CSS, Bootstrap, Axios 추가

    7.6.4 컴포넌트 설정

    7.6.5 Form 컴포넌트 생성

    7.6.6 Main 컴포넌트 추가

7.7 라우팅

    7.7.1 매개변수가 있는 상품 경로 추가

    7.7.2 태그와 함께 라우터 링크 설정

    7.7.3 스타일을 적용한 라우터 링크 설정

    7.7.4 수정 경로 추가

    7.7.5 리다이렉션과 와일드카드 사용

7.8 연습 문제
7.9 요약


8장 트랜지션 및 애니메이션

8.1 트랜지션 기본

8.2 애니메이션 기본

8.3 자바스크립트 훅

8.4 트랜지션 컴포넌트

8.5 애완용품샵 애플리케이션 업데이트

    8.5.1 애완용품샵 애플리케이션에 트랜지션 추가

    8.5.2 애완용품샵 애플리케이션에 애니메이션 추가

8.6 연습 문제

8.7 요약


9장 Vue 확장

9.1 믹스인과 함께 기능 재사용

    9.1.1 전역 믹스인

9.2 예제와 함께 커스텀 지시자 배우기

    9.2.1 수정자, 값, 인수를 포함한 전역 커스텀 지시자

9.3 렌더 함수와 JSX

    9.3.1 렌더 함수 예제

    9.3.2 JSX 예제

9.4 연습 문제

9.5 요약


3부 데이터 모델링, API 사용과 테스트

10장 Vuex

10.1 Vuex, 뭐가 좋을까?

10.2 Vuex 상태와 뮤테이션

10.3 게터와 액션

10.4 애완용품샵 앱과 함께 Vue-CLI에 Vuex 추가

    10.4.1 Vue- CLI에서 Vuex 설치

10.5 Vuex 헬퍼

10.6 모듈 살펴보기

10.7 연습 문제

10.8 요약


11장 서버와의 통신

11.1 서버 사이드 렌더링

11.2 Nuxt.js 소개

    11.2.1 음악 검색 앱 생성

    11.2.2 프로젝트 생성과 의존성 설치

    11.2.3 빌딩 블록 및 컴포넌트 생성

    11.2.4 기본 레이아웃 업데이트

    11.2.5 Vuex를 사용해서 저장소 추가

    11.2.6 미들웨어 사용

    11.2.7 Nuxt.js를 사용해서 경로 생성

11.3 파이어베이스와 VuexFire로 서버와 통신

    11.3.1 파이어베이스 설정

    11.3.2 파이어베이스로 애완용품샵 앱 설정

    11.3.3 인증 상태로 Vuex 업데이트

    11.3.4 인증으로 헤더 컴포넌트 업데이트

    11.3.5 파이어베이스 실시간 데이터베이스로 Main.vue 업데이트

11.4 연습 문제

11.5 요약


12장 테스트

12.1 테스트 케이스 생성

12.2 지속 통합·전달·배포

    12.2.1 지속 통합

    12.2.2 지속 전달

    12.2.3 지속 배포

12.3 테스트 종류

12.4 환경 설정

12.5 vue-test-utils로 첫 테스트 케이스 생성

12.6 테스트 컴포넌트

    12.6.1 테스트 속성

    12.6.2 텍스트 테스트

    12.6.3 CSS 클래스 테스트

    12.6.4 모의 Vuex 테스트

12.7 크롬 디버거 설정

12.8 연습 문제

12.9 요약
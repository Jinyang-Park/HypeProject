 ![로고](https://user-images.githubusercontent.com/80263801/204437496-6b6c193b-21a0-44c2-9f50-43218ca2baf7.png)


## Hype Express 소개
멋지고 쿨한 소식들을 사용자 공간에 배달하자

## Hype Express 목적
최신 패션, 음식, 여행 그리고 엔터테이먼트 등 다양한 분야의 소식을 데일리 뉴스와 유니크한 콘텐츠를 제공하는 플랫폼

## Hype Express 팀원 소개
|박진양|조영찬|김예슬|유영재|한상권
|------|------|------|------|------|
|[Github](https://github.com/Jinyang-Park)|[Github](https://github.com/chaaaniii)|[Github](https://github.com/2sel)|[Github](https://github.com/YoungJae0910)|[Github](https://github.com/Gon1782)|

## 기능 구현
* 로그인, 회원 가입 + 소셜 로그인 (구글, 깃헙) 
    - 로그인하지 않을 경우 전체 게시글 조회만 가능
    - 정규표현식을 이용한 유효성 검사
    - 이미 존재하는 이메일, 비밀번호 오류 예외처리
* 메인 
    - 네비게이션바 카테고리 클릭 시 SPA 라우팅으로 동적으로 페이지 내용을 전환
* 게시글 
    - 게시글에 작성한 날짜와 유저를 보여줌
    - Firestore 에서 제공하는 api를 이용하여 CRUD구현
    - 게시글에 댓글 작성, 수정 및 삭제 가능
    - 좋아요 버튼 구현
* 게시글 작성
    - 에디터를 사용하여 게시글 작성 구현
    - 따로 썸네일을 지정할수 있게 구현
* 마이페이지
    - 로그인시 마이페이지 생성
    - 프로필 닉네임, 사진 수정
    - 내가 쓴 게시물 조회 

## 사용스택

<div align="left">
	<img src="https://img.shields.io/badge/<svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>JavaScript</title><path d="M0 0h24v24H0V0zm22.034 18.276c-.175-1.095-.888-2.015-3.003-2.873-.736-.345-1.554-.585-1.797-1.14-.091-.33-.105-.51-.046-.705.15-.646.915-.84 1.515-.66.39.12.75.42.976.9 1.034-.676 1.034-.676 1.755-1.125-.27-.42-.404-.601-.586-.78-.63-.705-1.469-1.065-2.834-1.034l-.705.089c-.676.165-1.32.525-1.71 1.005-1.14 1.291-.811 3.541.569 4.471 1.365 1.02 3.361 1.244 3.616 2.205.24 1.17-.87 1.545-1.966 1.41-.811-.18-1.26-.586-1.755-1.336l-1.83 1.051c.21.48.45.689.81 1.109 1.74 1.756 6.09 1.666 6.871-1.004.029-.09.24-.705.074-1.65l.046.067zm-8.983-7.245h-2.248c0 1.938-.009 3.864-.009 5.805 0 1.232.063 2.363-.138 2.711-.33.689-1.18.601-1.566.48-.396-.196-.597-.466-.83-.855-.063-.105-.11-.196-.127-.196l-1.825 1.125c.305.63.75 1.172 1.324 1.517.855.51 2.004.675 3.207.405.783-.226 1.458-.691 1.811-1.411.51-.93.402-2.07.397-3.346.012-2.054 0-4.109 0-6.179l.004-.056z"/></svg>Javascript-F7DF1E?style=flat&logo=Java&logoColor=white" />
	<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" />
	<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" />
</div>


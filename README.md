# 영화 검색 · 리뷰 웹사이트 (JSP 팀 프로젝트)

2024년 7~11월, JSP/Servlet으로 만든 **영화 정보 검색과 리뷰 커뮤니티** 팀 프로젝트입니다.

## 주요 기능
| 영역 | 기능 |
|---|---|
| 회원 | 회원가입, 로그인/로그아웃, 아이디·비밀번호 찾기, 정보 수정, 마이페이지, 회원 탈퇴 |
| 영화 | 영화 목록, 카테고리별 조회, 상세 보기 |
| 리뷰 | 리뷰 작성 · 수정 · 삭제, 전체 리뷰 보기 |
| 공통 | 헤더 · 푸터 · 상단 메뉴 공통화, 로그인 체크, 다크/라이트 모드(color-modes), 글꼴 설정 |

## 구조
```
Project1/src/main/
  java/
    DAO/      회원 · 리뷰 · 상영 정보 DB 접근
    DTO/      데이터 객체
    Utils/    커넥션 풀, 페이징, 쿠키 관리, 공통 JS 함수
    SQL/      테이블 스크립트
  webapp/
    MemberSV/ 회원 화면과 처리
    BoardSV/  리뷰 게시판
    CommonSV/ 공통 레이아웃
```

## 기술
JSP, Servlet, Oracle DB, JavaScript, Bootstrap, Tomcat

## 실행 전 설정
DB 접속 정보는 저장소에 두지 않습니다. 환경변수 `DB_URL`, `DB_USER`, `DB_PASSWORD`를 설정하거나 예시값(`YOUR_DB_USER` 등)을 로컬 환경에 맞게 바꿔 주세요.

---

현재 SAP BTP 실무 포트폴리오는 [sap-btp-portfolio](https://github.com/hopepu/sap-btp-portfolio)에 정리하고 있습니다.

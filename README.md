"Spring Boot Board(SBB)" 게시판

사용한 기술 스택 : SpringBoot, IntelliJ, JAVA11, lombok, Bootstrap, thymeleaf, H2 데이터베이스 등

구현한 기술들 : 네비게이션바, 페이징, 게시물 일련번호, 답변 갯수, 스프링 시큐리티, 회원가입, 로그인/로그아웃, 글쓴이 표시
수정과 삭제, 추천, 검색 등
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
![C_3-01_2 (1)](https://github.com/Iusto/jump-to-springboot/assets/85227042/3b276b09-6408-46ac-b695-28a3600c9760)
<br>
[네비게이션 바]
브라우저의 크기가 작아지면 내비게이션 바에 있는 링크들을 작은 햄버거 메뉴 버튼으로 숨긴다. (부트스트랩의 반응형 웹 기능)
<br>
<br>
<br>
<br>
<br>
![C_3-06_2](https://github.com/Iusto/jump-to-springboot/assets/85227042/1c481b7e-185b-422c-820f-8060307fcfb0)
<br>
[엔티티] JPA
<br>
<br>
<br>
<br>
<br>
![O_3-02_6](https://github.com/Iusto/jump-to-springboot/assets/85227042/10070393-6b52-4d3a-8847-ddbc0714e71d)
<br>
[페이징] 페이징클래스 사용, 게시물 일련번호
<br>
org.springframework.data.domain.Page<br>
org.springframework.data.domain.PageRequest<br>
org.springframework.data.domain.Pageable<br>
<br>
<br>
<br>
<br>
![O_2-15_3](https://github.com/Iusto/jump-to-springboot/assets/85227042/98993ef3-2a81-4c7b-b518-700a39631e8f)
<br>
질문 등록과 답변 기능<br>
오류 발생시 입력한 내용 유지하기 (th:field 속성을 사용)<br>
제목 또는 내용에 값을 채우지 않은 상태로 질문 등록을 진행하면 다음과 같은 오류가 화면에 표시<br>
<br>
<br>
<br>
<br>
![O_3-06_3](https://github.com/Iusto/jump-to-springboot/assets/85227042/5f7d0519-ce01-444e-b807-19bcd19405a0)
![O_3-06_7](https://github.com/Iusto/jump-to-springboot/assets/85227042/29916469-7d5b-4af2-a0cb-8be33da269d6)
<br>
[회원가입/로그인/로그아웃 기능] 가입하려는 사람이 중복된 사용자일 시 오류 발생하도록 설정<br>
<br>
<br>
![C_3-07_4](https://github.com/Iusto/jump-to-springboot/assets/85227042/0747df29-c044-4463-a122-1e19aa33edb4)
![O_3-07_1](https://github.com/Iusto/jump-to-springboot/assets/85227042/4c84e712-8c63-4554-b6e8-7d5915277afd)
![O_3-07_3](https://github.com/Iusto/jump-to-springboot/assets/85227042/2fccdb75-6b85-4b15-83bd-288035a2ed37)

[로그인/로그아웃] 기본적인 기능<br>
<br>
<br>

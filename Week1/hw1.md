1주차 학습한 내용
1. 웹
- 여러 컴퓨터가 연결되어 정보를 고유하는 공간 
- 클라이언트 - 서버 패러다임 
예시 ) 우리집 컴퓨터("네이버 메인화면 데이터 주세요") <=> 네이버 컴퓨터("여기 네이버 html 코드요 ")
2. 프로토콜과 HTTP 
- 컴퓨터는 정해진 동작만 수행
- 규칙이 필요 
- 프로토콜 : 네트워크 안에서 요청과 응답을 보내는 규칙
- 자주 사용하는 HTTP Method 
GET, POST, PUT, PATCH, DELETE  
- HTTP 헤더 (통신에 대한 정보)
- HTTP 바디 (주고 받으려는 데이터)
- 요청에 대한 처리 결과는 HTTP가 정의하는 상태 코드로 나타낸다 
예시) 200, 291, 400, 404, 500
3. 프론트엔드와 백엔드
- 프론트: 화면에 채울 컨텐츠 데이터를 백엔드에 요청
- 백엔드: DB에서 가져온 컨텐츠 데이터를 프론트에게 응답 
4. API 
- 어플리케이션에서 원하는 기능을 수행하기 위헤 소통하는 구체적 방법을 정의한 것. 
- 백엔드 API : 어떤 http method, url을 사용해야 하는지 정의, 어떤 응답을 보내야 하는지 정의.

 
API 명세서
- 로그인 POST /login
- 수정 POST/users/{user_id}
- 친구 추가 POST/frineds
- 친구 삭제 DELET/friends/{friend_id}
- 할 일 생성 POST/todo 
- 할 일 체크 POST/todo/{todo_id}/check

어플리케이션 실행 에러 화면
![img](https://github.com/user-attachments/assets/d40607ab-5e76-4661-8a18-95d9cf98bc55)



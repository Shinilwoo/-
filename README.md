# 신유경의 포트폴리오  
안녕하세요. 저는 신유경입니다. 제가 지금까지 공부하고 함께 진행한 프로젝트를 소개하도록 하겠습니다.  
프로젝트의 파일은 각각의 깃허브 주소에서 확인하실 수 있습니다.  

## 📦 프로젝트 목록  

### 📝 1.[스마트 엘리베이터](https://github.com/Shinilwoo/QRapp.git)   
 엘리베이터에 프라이빗한 스마트기술 서비스를 제공하여 엘리베이터 사용자의 편리성을 높입니다. 지정 이용자의 지문데이터를 저장해서 탑승 시에 보안키 역할을 하며 외부인의 범죄예방과, 탑승과 동시에 탑승자가 원하는 층수에 도착할 때 까지 심리적인 안정감을 줄 수 있습니다. 또한 추가 방문자는 QR코드로 입장 초대코드를 받아 엘리베이터 탑승이 가능합니다.  
애완동물과 함께 탑승 시에 pet을 인식하여 엘리베이터 외부 탑승 예정자에게 pet의 탑승여부를 대기하는 동안 미리 알려주는 서비스를 제공합니다.   
💡기능  
- 설치 위치 엘리베이터 앞  
1. 아두이노 우노를 활용한 지문인식기 -> 지문저장/ 지문스캔  
2. QR코드 생성 안드로이드 스튜디오 / QR스캐너 아두이노    

- 설치 위치 열림*닫힘 버튼 박스 내  LED / 7 segment  
1. 젯슨나노에 pet인식을 학습시켜 LED에 불이 들어옴  
2. 라즈베리파이로 7segment를 활용한 각층 수  sign  

- 설치 위치 엘리베이터 안   
  보안 webcam 설치 젯슨나노   

- 서버 라즈베리파이 tcp/ip   
  지문인식, qr코드, pet 정보 등을 받아 저장 후 엘리베이터에 전달
  
🤝|조원|4명| 
⏰|개발기간|2023.03~2023.06(약 3개월)
✅|담당|안드로이드 스튜디오로 라즈베리파이 연동해서 OR코드 생성 및 아두이노 연결 qr코드 인식|  
🛠️|주요기술|Java,Android Studio,Arduino,Raspberri pi,python  아두이노uno 지문인식기, 안드로이드 스튜디오, 아두이노 QR스캐너, 아두이노 7segment, 잿슨나노, YOLOv5 web cam

### 📝 2.[오픈소스 라이브러리](https://github.com/Shinilwoo/game-test.git)  
라이브러리를 활용한 행맨게임과 리듬게임    
💡기능  
- 행맨 게임
- 리듬 게임

🤝|조원|1명|  
⏰|개발기간|2023.07~2023.08(약 2주)
✅|담당|라이센스를 확인하고 라이브러리를 사용하는것|  
🛠️|주요기술|visual studio,c

### 📝 3.[장고로 치매 노인을 위한 웹사이트](https://ddunos.github.io/CareFit/)  <sub><sup><span style=" color:gray;">(사이트로 이동)</span></sub></sup>
 “Care Fit”은 기관에서 보호사들이 노인치매환자를 대상으로 사용할 수 있는 디지털 콘텐츠 플랫폼입니다. 치매간이 테스트를 진행하고, 회원정보를 DB에 저장하여 회원의 치매레벨과 차트를 관리할 수 있습니다. 
 또한 치매라는 질병에 가장 중요한 부분인 인지능력을 활성화 하는 게임 프로그램을 추가하여 보호사들이 노인 치매예방활동 교육용으로 사용할 수 있는데 분할화면 기능으로 mobile, pc, tablet, tv monitor와 같은 다양한 화면에 호환이 가능하여, 시간과 공간의 제약 없이 편리하게 활용 할 수 있습니다.  

💡기능  
- 로그인 / 회원가입
- 검사
- 관리자의 일반사용자 정보 확인페이지
- 모션인식 게임  

🤝|조원|4명|  
⏰|개발기간|2023.09~2023.12(약 3개월)
✅|담당|치매확인을 위한 검사와 일반사용자와 관리사용자로 나눈 가입폼 및 정보 확인폼    
🛠️|주요기술|python,Django,html,css

### 📝 4.[spring boot로 행사 정보 사이트](https://github.com/Shinilwoo/KD3_B_Project.git)   
행사와 예술인의 투자정보를 모아 볼 수 있는 사이트    
💡기능  
- 로그인/회원가입
1. 아이디 찾기
2. 비밀번호 찾기
- 마이페이지
1. 개인정보 수정
2. 관계자 인증
3. 관심 목록
4. 회원탈퇴
- 메인 페이지
1. 게시물 조회순, 인기순, 최신순 등 나열
2. 행사 게시판, 투자 게시판
3. 검색
4. 헤더/푸터
- 게시판
1. 게시물 등록
2. 관심등록
3. 게시물의 상세 링크로 연결   

🤝|조원|5명|  
⏰|개발기간|2024.03~2024.4(약 1개월)
✅|담당|팀장,데이터베이스 부관리자, 게시판,관리자 페이지, 파일등록, 개인정보 수정 담당|   
🛠️|주요기술|JavaScript, HTML, CSS, AJAX, Thymeleaf Java, Spring Boot, Eclipse, MySQL , Notion, Slack, GitHub, GCP


# template_backend_node_002
REST 기능만 구현된 템플릿 입니다.

### 사전준비
- GIT 설치
- npm LTS 버전 설치
- MariaDB 설치
- Restlet 설치

### 실행방법
1. Git Bash 실행 후 git clone https://github.com/hitechinfo/template_backend_node_002.git
2. Git Bash에서 해당 폴더로 이동 후 npm install
3. (DB 설정이 되어 있지 않다면) HeidiSQL 실행 후 .sql 스크립트 실행
4. Git Bash에서 npm start
5. Restlet 실행 후 GET method로 http://localhost:3005/sample 요청
6. 200 Status와 함께 Sample 목록이 조회되면 성공!

### 개발가이드
※ 이 방법 외에도 편하신대로 하시면 됩니다.
1. 새로운 테이블을 사용할 경우 Model 정보 작성 (/api/model/sample/Sample.js 참고)

   실제 테이블명은 Model에 정의된 이름('sampleTable')에 's'가 붙은 "SAMPLE_TABLES"
2. Routing 정보 작성 (/api/interface/sample/index.js 참고)
3. Routing 후 수행할 controller 작성 (/api/interface/sample/sample.controller.js 참고)
4. Routing 사용을 위해 app.js 에 등록
5. Restlet 실행 후 api/interface 하위에 생성한 폴더명으로 호출 (GET http://localhost:3005/sample)

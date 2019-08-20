# template_backend_node_002
REST 기능만 구현된 템플릿 입니다.

### 사전준비
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

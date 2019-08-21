# template_frontend_react_002
Semantic UI를 활용한 React Template 입니다.

### 사전준비
- GIT 설치
- npm LTS 버전 설치

### 실행방법
1. Git Bash 실행 후 git clone https://github.com/hitechinfo/template_frontend_react_002.git
2. Git Bash에서 해당 폴더로 이동 후 npm install
3. Git Bash에서 npm start
4. List 메뉴의 Sample 목록 조회 기능은 [template_backend_node_002](https://github.com/hitechinfo/template_backend_node_002) 또는 [template_backend_springboot_002](https://github.com/hitechinfo/template_backend_springboot_002) 실행 필요

### 개발가이드
※ 이 방법 외에도 편하신대로 하시면 됩니다.
1. index.js에서 화면 그리는 영역 확인 (\src\index.js 참고)
- 헤더영역 수정 (src\components\block\MainHeader.js 참고)
- 푸터영역 수정 (src\components\block\MainFooter.js 참고)
- 메뉴영역 수정 (src\containers\menu\MenuContainer.js 및 src\components\menu\MainMenu.js 참고)
- "/" 으로 연결되는 메인영역 수정 (src\App.js 참고)
2. Component 또는 Container로 메인영역에 들어갈 새로운 UI 작성 (src\containers\list\ListContainer.js 및 src\components\list\SampleList.js 참고)
3. Routing 정보 등록 (src\routes\index.js 참고)

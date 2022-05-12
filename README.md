# tripper-readme

### Directory Structure
```
📂 config
 ├── 📂 fword
      ├── 📄 fword.js
      ├── 📄 fword_list.txt
 ├── 📄 baseResponseStatus.js
 ├── 📄 express.js
 ├── 📄 jwtMiddleware.js
 ├── 📄 multer.js
 ├── 📄 response.js
 ├── 📄 s3.js
 └── 📄 winston.js
📂 src
 └── 📂 app
      ├── 📂 Feed
      |    ├── 📄 feedController.js
      |    ├── 📄 feedDao.js
      |    ├── 📄 feedProvider.js
      |    ├── 📄 feedRoute.js
      |    └── 📄 feedService.js
      ├── 📂 Main
      |    ├── 📄 mainController.js
      |    ├── 📄 mainDao.js
      |    ├── 📄 mainProvider.js
      |    ├── 📄 mainRoute.js
      |    └── 📄 mainService.js 
      ├── 📂 User
           ├── 📄 userController.js
           ├── 📄 userDao.js
           ├── 📄 userProvider.js
           ├── 📄 userRoute.js
           └── 📄 userService.js
     
📄 .gitignore
📄 index.js
📄 package.json
```

### Service Architecture
![architecture](https://user-images.githubusercontent.com/72693779/168087831-0b609f35-68b3-4107-b939-63c7b3d34d84.png)


### Role
- 서버 및 DB 구축
- ERD 설계
   - [Aquerytool URL](https://aquerytool.com/aquerymain/index/?rurl=b269dfa0-8c56-4e5c-930a-797e7d246cad&)
   - Password: upe22c
- REST API 구현 + 명세서 작성
   - [API 명세서 URL](https://docs.google.com/spreadsheets/d/1-DlIcPHgdXnFslBUXaY8N4yYH3Xyw5IrjQZA8CDv9W0/edit#gid=0)
- 추가 구현
   - 검색 API 
   - 여행 게시물 수정 API
   - 댓글 관련 API Refactoring (진행중)

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

# 포트폴리오 공유 서비스 백엔드 코드

## Back-End

<div>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/mongoDB-47A248?style=flat-square&logo=mongoDB&logoColor=white"/>
</div>

<br />

### Server-Infra

<div>
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white"/>
<img src="https://img.shields.io/badge/pm2-2B037A?style=flat-square&logo=pm2&logoColor=white"/>
</div>

<br />

## 📁 프로젝트 구조

```
📦src
 ┣ 📂db
 ┃ ┣ 📂models
 ┃ ┃ ┣ 📜Award.js
 ┃ ┃ ┣ 📜Certification.js
 ┃ ┃ ┣ 📜Education.js
 ┃ ┃ ┣ 📜Like.js
 ┃ ┃ ┣ 📜Project.js
 ┃ ┃ ┗ 📜User.js
 ┃ ┣ 📂schemas
 ┃ ┃ ┣ 📜award.js
 ┃ ┃ ┣ 📜certification.js
 ┃ ┃ ┣ 📜education.js
 ┃ ┃ ┣ 📜like.js
 ┃ ┃ ┣ 📜project.js
 ┃ ┃ ┗ 📜user.js
 ┃ ┗ 📜index.js
 ┣ 📂middlewares
 ┃ ┣ 📜errorMiddleware.js
 ┃ ┗ 📜login_required.js
 ┣ 📂routers
 ┃ ┣ 📜awardRouter.js
 ┃ ┣ 📜certificationRouter.js
 ┃ ┣ 📜educationRouter.js
 ┃ ┣ 📜projectRouter.js
 ┃ ┗ 📜userRouter.js
 ┣ 📂services
 ┃ ┣ 📜awardService.js
 ┃ ┣ 📜certificationService.js
 ┃ ┣ 📜educationService.js
 ┃ ┣ 📜projectService.js
 ┃ ┗ 📜userService.js
 ┣ 📂uploads
 ┣ 📂utils
 ┃ ┣ 📜dateObjToString.js
 ┃ ┗ 📜multer.js
 ┗ 📜app.js
```

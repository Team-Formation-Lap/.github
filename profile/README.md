
# <p align = center>🏆 2025 한국공학대전 우수작품 수상 🏆<p> 

### <p align = center> &nbsp;&nbsp;&nbsp;&nbsp; <br><img width=40%, height=25%, marginTop=10, src="./IntelliView.svg"><br><br><br> &nbsp;&nbsp;&nbsp;🖥️ AI 기반 비언어 행동 분석과 이력서 기반 질문 생성을 통한 맞춤형 모의 면접 서비스 🖥️ <p> 
##### <p align = center> URL : https://expo.tukorea.ac.kr/2025/work/84 <p>
<br>


## 📌 Table of Contents
- [Demo](#-Demo)
- [System Architecture](#-System-Architecture)
- [Tech stack](#-Tech-stack)
- [ERD](#-Erd)
- [API](#-API)
- [Monitoring](#-Monitoring)
- [How to Start](#-How-to-Start)
- [Directory Structure](#-Directory-Structure)
- [Members](#-Members)

<br>

</br>


## 📹 Demo Video
### 랜딩 페이지
<img width="1512" height="858" alt="landing" src="https://github.com/user-attachments/assets/914a5ae2-abb0-40d0-9a42-f16a9504f9ad" />

### 회원가입
![signup](https://github.com/user-attachments/assets/326aceaf-3d5e-4373-80e2-34039e1a1755)

### 로그인
![signin](https://github.com/user-attachments/assets/baf2ac61-45ea-4685-97e3-cb2f3fa09ab6)

### 이력서 업로드

### 면접 진행
![채널별 차트](https://github.com/2023-Winter-Bootcamp-Team-N/2023WB-Team-N/assets/154861396/c1adf2f5-bee9-400e-8608-187d9d4a8978)

### 종합 피드백
![채널별 차트](https://github.com/2023-Winter-Bootcamp-Team-N/2023WB-Team-N/assets/154861396/c1adf2f5-bee9-400e-8608-187d9d4a8978)

### 답변 피드백
![채널별 차트](https://github.com/2023-Winter-Bootcamp-Team-N/2023WB-Team-N/assets/154861396/c1adf2f5-bee9-400e-8608-187d9d4a8978)

### 행동 피드백
![채널별 차트](https://github.com/2023-Winter-Bootcamp-Team-N/2023WB-Team-N/assets/154861396/c1adf2f5-bee9-400e-8608-187d9d4a8978)

### 마이페이지
![채널별 차트](https://github.com/2023-Winter-Bootcamp-Team-N/2023WB-Team-N/assets/154861396/c1adf2f5-bee9-400e-8608-187d9d4a8978)


## 🚨 System Architecture

<img alt="system architecture" src="https://github.com/user-attachments/assets/bd544a39-1b21-42c8-8d62-da1de315e4bc">




## 🛠 Tech stack 
<br>
<div align =center>

분야| 사용 기술|
:--------:|:------------------------------:|
**Frontend** | <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"> <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"> <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white"/> <img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white"/> <img src="https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white"> <img src="https://img.shields.io/badge/zustand-8B4513.svg?style=for-the-badge&logo=react&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
**Backend** | <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white"> <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=Amazon RDS&logoColor=white"> <img src="https://shields.io/badge/FFmpeg-%23171717.svg?logo=ffmpeg&style=for-the-badge&labelColor=171717&logoColor=5cb85c"> <img src="https://img.shields.io/badge/Uvicorn-22C3E6?style=for-the-badge&logo=uvicorn&logoColor=white"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/21/Google_Mediapipe_Logo.svg/120px-Google_Mediapipe_Logo.svg.png" width="100px"/>
**DevOps** | <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=black"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/github%20actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"> <img src="https://img.shields.io/badge/Amazon%20CloudFront-232F3E?style=for-the-badge&logo=Amazon-CloudFront&logoColor=white"> <img src="https://img.shields.io/badge/Amazon_EC2-FF9900?style=for-the-badge&logo=Amazon-EC2&logoColor=black"> <img src="https://img.shields.io/badge/certbot-0072C6?style=for-the-badge&logo=let's-encrypt&logoColor=white"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white">
**Monitoring** |   <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=black"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=black"> <img src="https://img.shields.io/badge/alertmanager-E74536?style=for-the-badge&logo=alertmanager&logoColor=black"> <img src = "https://img.shields.io/badge/cadvisor-1478FF?style=for-the-badge&logoColor=black"> <img src="https://img.shields.io/badge/flower-FF69B4?style=for-the-badge&logo=flower&logoColor=white"> 
**etc** | ![Slack](https://img.shields.io/static/v1?style=for-the-badge&message=Slack&color=4A154B&logo=Slack&logoColor=FFFFFF&label=) ![Notion](https://img.shields.io/static/v1?style=for-the-badge&message=Notion&color=000000&logo=Notion&logoColor=FFFFFF&label=) ![Figma](https://img.shields.io/static/v1?style=for-the-badge&message=Figma&color=F24E1E&logo=Figma&logoColor=FFFFFF&label=) <img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"> <img src="https://img.shields.io/badge/GitKraken-179287?style=for-the-badge&logo=GitKraken&logoColor=white"> <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white">
</div>



## 💎 ERD

<img width="1290" height="500" alt="Datebase" src="https://github.com/user-attachments/assets/39841802-99ca-4f0a-9421-a1b2953ba81c">


## 📙 API

<img width="1179" height="750" alt="api" src="https://github.com/user-attachments/assets/3a535171-a83c-4a1f-bd50-59d2e8606559" />

## 🧑‍💻 How to Start
### Backend 
```
$ git clone https://github.com/Team-Formation-Lap/Backend.git
```
### env setting in the Backend folder
* Backend/.env
```
# mysql
DATABASE_URL=
MYSQL_ROOT_PASSWORD=
MYSQL_DATABASE=

# CELERY
CELERY_BROKER_URL=

# openai
OPENAI_API_KEY=
GPT_MODEL=

```
### Run Docker
```
docker-compose up -d 
```
### Frontend
```
$ git clone https://github.com/Team-Formation-Lap/Frontend.git
```
### Install
```
yarn install
```

### Run
```
yarn dev
```
<br>




## 📚 Directory Structure

<details>
  <summary><b>Frontend</b></summary>
   <pre>
    <code>
    📦Frontend
    ┗ 📂my-project
       ┣ 📂public
       ┃  ┣ 📜favicon.ico
       ┃  ┗ 📜Interviewer.png
       ┣ 📂src
       ┃  ┣ 📂api
       ┃  ┃  ┣ 📜axiosInstance.ts
       ┃  ┃  ┣ 📜resultAPI.ts
       ┃  ┃  ┣ 📜resumeAPI.ts
       ┃  ┃  ┗ 📜signupAPI.ts
       ┃  ┣ 📂assets
       ┃  ┃  ┣ 📜book.svg
       ┃  ┃  ┣ 📜face1.png
       ┃  ┃  ┣ 📜face2.png
       ┃  ┃  ┣ 📜face3.png
       ┃  ┃  ┣ 📜face4.png
       ┃  ┃  ┣ 📜face5.png
       ┃  ┃  ┣ 📜flyingBusinessman.svg
       ┃  ┃  ┣ 📜flyingBusinesswoman.svg
       ┃  ┃  ┣ 📜InterviewerVideo.mp4
       ┃  ┃  ┣ 📜interviewVideo_song.webm
       ┃  ┃  ┣ 📜KoreanInterviewerVideo.mp4
       ┃  ┃  ┣ 📜Man.svg
       ┃  ┃  ┣ 📜Record.svg
       ┃  ┃  ┗ 📜Robot.svg
       ┃  ┣ 📂components
       ┃  ┃  ┣ 📂headers
       ┃  ┃  ┃  ┣ 📜header.tsx
       ┃  ┃  ┃  ┗ 📜InterviewHeader.tsx
       ┃  ┃  ┣ 📂modals
       ┃  ┃  ┃  ┣ 📜LoginModal.tsx
       ┃  ┃  ┃  ┣ 📜Modal.tsx
       ┃  ┃  ┃  ┣ 📜ResumeManageModal.tsx
       ┃  ┃  ┃  ┣ 📜ResumeUploadModal.tsx
       ┃  ┃  ┃  ┣ 📜ResumeUploadModal2.tsx
       ┃  ┃  ┃  ┗ 📜SignupModal.tsx
       ┃  ┃  ┣ 📂reports
       ┃  ┃  ┃  ┣ 📜BehaviorReport_design.tsx
       ┃  ┃  ┃  ┣ 📜BehaviorReport.tsx
       ┃  ┃  ┃  ┣ 📜ComprehensiveReport_design.tsx
       ┃  ┃  ┃  ┣ 📜ComprehensiveReport.tsx
       ┃  ┃  ┃  ┣ 📜QuestionReport_design.tsx
       ┃  ┃  ┃  ┣ 📜QuestionReport.tsx
       ┃  ┃  ┃  ┗ 📜RadarChart.tsx
       ┃  ┃  ┣ 📜ReplyButton.tsx
       ┃  ┃  ┣ 📜StartPageContent.tsx
       ┃  ┃  ┣ 📜VirtualInterviewer.tsx
       ┃  ┃  ┗ 📜WebcamFeed.tsx
       ┃  ┣ 📂css
       ┃  ┃  ┗ 📜modal.css
       ┃  ┣ 📂hooks
       ┃  ┃  ┣ 📜useAudioRecorder.ts
       ┃  ┃  ┣ 📜useLogin.ts
       ┃  ┃  ┣ 📜useLoginMutation.ts
       ┃  ┃  ┣ 📜useNavigation.ts
       ┃  ┃  ┣ 📜useResumeUpload.ts
       ┃  ┃  ┣ 📜useSignup.ts
       ┃  ┃  ┣ 📜useStartPage.ts
       ┃  ┃  ┣ 📜useTimer.ts
       ┃  ┃  ┣ 📜useToQAItems copy.ts
       ┃  ┃  ┣ 📜useToQAItems.ts
       ┃  ┃  ┣ 📜useUploadInterviewVideo.ts
       ┃  ┃  ┣ 📜useVideoRecorder.ts
       ┃  ┃  ┗ 📜useWebSocket.ts
       ┃  ┣ 📂pages
       ┃  ┃  ┣ 📜ArchivedReportPage.tsx
       ┃  ┃  ┣ 📜DesignPage.tsx
       ┃  ┃  ┣ 📜InterviewPage.tsx
       ┃  ┃  ┣ 📜MyPage.tsx
       ┃  ┃  ┣ 📜ReportPage.tsx
       ┃  ┃  ┗ 📜StartPage.tsx
       ┃  ┣ 📂store
       ┃  ┃  ┣ 📜authStore.ts
       ┃  ┃  ┗ 📜useInterviewStore.ts
       ┃  ┣ 📂stories
       ┃  ┃  ┣ 📜button.css
       ┃  ┃  ┣ 📜Button.stories.ts
       ┃  ┃  ┣ 📜Button.tsx
       ┃  ┃  ┣ 📜Configure.mdx
       ┃  ┃  ┣ 📜header.css
       ┃  ┃  ┣ 📜Header.stories.ts
       ┃  ┃  ┣ 📜Header.tsx
       ┃  ┃  ┣ 📜page.css
       ┃  ┃  ┣ 📜Page.stories.ts
       ┃  ┃  ┗ 📜Page.tsx
       ┃  ┣ 📂utils
       ┃  ┃  ┗ 📜constants.ts
       ┃  ┣ 📜App.css
       ┃  ┣ 📜App.tsx
       ┃  ┣ 📜index.css
       ┃  ┣ 📜main.tsx
       ┃  ┗ 📜vite-env.d.ts
       ┣ 📜eslint.config.js
       ┣ 📜index.html
       ┣ 📜package.json
       ┣ 📜postcss.config.js
       ┣ 📜README.md
       ┣ 📜tailwind.config.js
       ┣ 📜tsconfig.json
       ┗ 📜vite.config.ts
    </code>
  </pre>
</details>


<details>
  <summary><b>Backend</b></summary>
  <pre>
    <code>
      📦Backend
      ┣ 📂apps
      ┃  ┣ 📜__init__.py
      ┃  ┣ 📜asgi.py
      ┃  ┣ 📜celery.py
      ┃  ┣ 📜settings.py
      ┃  ┣ 📜urls.py
      ┃  ┗ 📜wsgi.py
      ┣ 📂interview
      ┃  ┣ 📂migrations
      ┃  ┃  ┗ 📜__init__.py
      ┃  ┣ 📜__init__.py
      ┃  ┣ 📜admin.py
      ┃  ┣ 📜apps.py
      ┃  ┣ 📜consumers.py
      ┃  ┣ 📜models.py
      ┃  ┣ 📜routing.py
      ┃  ┣ 📜serializers.py
      ┃  ┣ 📜tasks.py
      ┃  ┣ 📜tests.py
      ┃  ┣ 📜urls.py
      ┃  ┣ 📜utils.py
      ┃  ┗ 📜views.py
      ┣ 📂result
      ┃  ┣ 📂migrations
      ┃  ┃  ┗ 📜__init__.py
      ┃  ┣ 📜__init__.py
      ┃  ┣ 📜admin.py
      ┃  ┣ 📜apps.py
      ┃  ┣ 📜models.py
      ┃  ┣ 📜serializers.py
      ┃  ┣ 📜tests.py
      ┃  ┣ 📜urls.py
      ┃  ┗ 📜views.py
      ┣ 📂resume
      ┃  ┣ 📂migrations
      ┃  ┃  ┗ 📜__init__.py
      ┃  ┣ 📜__init__.py
      ┃  ┣ 📜admin.py
      ┃  ┣ 📜apps.py
      ┃  ┣ 📜models.py
      ┃  ┣ 📜serializers.py
      ┃  ┣ 📜tests.py
      ┃  ┣ 📜urls.py
      ┃  ┗ 📜views.py
      ┣ 📂user
      ┃  ┣ 📂migrations
      ┃  ┃  ┗ 📜__init__.py
      ┃  ┣ 📜__init__.py
      ┃  ┣ 📜admin.py
      ┃  ┣ 📜apps.py
      ┃  ┣ 📜authentication.py
      ┃  ┣ 📜backends.py
      ┃  ┣ 📜models.py
      ┃  ┣ 📜serializers.py
      ┃  ┣ 📜tests.py
      ┃  ┣ 📜urls.py
      ┃  ┗ 📜views.py
      ┣ 📜docker-compose.yml
      ┣ 📜Dockerfile
      ┣ 📜manage.py
      ┗ 📜requirements.txt
    </code>
  </pre>
</details>
<br>

## 👨‍👩‍👧‍👦 Members
<table width="100%" align="center" style="border-collapse: collapse; text-align: center;">
<thead>
<tr>
<th>Profiles</th>
<td width="100" align="center">

<img src="./sujin.png" width="85" height="120">
</a>
</td>
<td width="100" align="center">

<img src="./suyeon.png" width="85" height="120">

</td>
<td width="100" align="center">

<img src="./rochan.png" width="85" height="120">

</td>

</tr>
<tr>
<th>Name</th>
<td width="100" align="center">신수진</td>
<td width="100" align="center">박수연</td>
<td width="100" align="center">송새로찬</td>

</tr>
<tr>
<th>Position</th>
<td width="150" height="20" align="center">
Team Leader<br>
Frontend<br>

</td>
<td width="150" align="center">
Backend<br>

</td>
<td width="150" align="center">
Backend<br>

</td>
</tr>
</thead>
</table>





















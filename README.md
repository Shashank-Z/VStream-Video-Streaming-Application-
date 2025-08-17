# VStream-Video-Streaming-Application-
Project Title: VStream ( A Video Streaming Platform)
Project Team:
* Skarma Yangskit   (24M0857)
* Suraj Patil (24M0837)
* Shashank Zanzad (24M0780)

To start UI service:  (install node.js, npm and hls.js)
1. cd vstream-ui
2. npm install
3. npm start

To start User service: ( install mysql, django, sqlalchemy, pymysql, bcrypt)
1. create database in mysql named: vstream_user_db
2. cd vstream-user-service
3. python manage.py runserver 0.0.0.0:8000

To start video service: (install java-21, gradle-8.10.2(not necessary, we have used gradle-wrapper, but in case of any issue try install), mysql, ffmpeg)
1. create database video_db and update the url in application.properties if port is different
2. update video and thumbnail storage location if needed in AppConstant.java.
3. To run the application: ./gradlew bootRun

# JDK 17 이미지 사용
FROM openjdk:17-jdk

# JAR_FILE 변수에 값을 저장
ARG JAR_FILE=./build/libs/demo-0.0.1-SNAPSHOT.jar

# 컨테이너 실행 시 이름을 app.jar로 변경하여 컨테이너에 저장
COPY ${JAR_FILE} app.jar

# 빌드 된 이미지가 run될 때 실행할 명령어
ENTRYPOINT ["java", "-jar", "app.jar"]
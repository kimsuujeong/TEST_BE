FROM openjdk:21-jdk-slim

# 작업 디렉토리 생성
WORKDIR /app

# 빌드된 JAR 복사
COPY build/libs/*.jar app.jar

# 실행
ENTRYPOINT ["java", "-jar", "app.jar"]
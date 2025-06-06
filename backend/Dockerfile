# 使用官方 Java 运行环境
FROM openjdk:17-jdk-slim

# 添加 jar 包，名字根据你项目修改
COPY target/demo-0.0.1-SNAPSHOT.jar app.jar

# 设置容器启动后执行的命令
ENTRYPOINT ["java", "-jar", "/app.jar"]

# 可选：指定容器开放端口（Render 不强制）
EXPOSE 8081

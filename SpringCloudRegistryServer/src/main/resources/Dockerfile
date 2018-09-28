FROM java:8
RUN yum -y install java-1.7.0-openjdk-devel.x86_64 
ADD target/SpringCloudRegistryServer-0.0.1-SNAPSHOT.jar /
CMD ["java", "-jar", "SpringCloudRegistryServer-0.0.1-SNAPSHOT.jar"]
EXPOSE 8761
# discovery-eureka
docker build -t discovery-eureka .
docker stop discovery-eureka
docker rm discovery-eureka
docker run --name discovery-eureka -d -p 8761:8761 discovery-eureka java -Xms256m -Xmx256m -jar discovery-eureka.jar

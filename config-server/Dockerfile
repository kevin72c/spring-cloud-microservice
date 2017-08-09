# config-server
docker build -t config-server .
docker stop config-server
docker rm config-server
docker run --name config-server -d -p 8761:8761 config-server java -Xms256m -Xmx256m -jar config-server.jar

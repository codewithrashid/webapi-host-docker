Create dockerfile & .dockerignore file
// To login on docker hub
docker login --username =<username>  --password= <password>
// To build docker image
docker build -t rashidansari/webapi-host-docker .
//To Push the docker image on docker hub
docker push rashidansari/webapi-host-docker .

Run on local
docker run -p 8080:80 rashidansari/webapi-host-docker
http://localhost:8080/api/WeatherForecast

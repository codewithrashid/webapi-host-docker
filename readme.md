Create dockerfile & .dockerignore file <br/>
// To login on docker hub <br/>
docker login --username ="yourusername"  --password= "password" <br/>
// To build docker image <br/>
docker build -t rashidansari/webapi-host-docker . <br/>
// To Push the docker image on docker hub <br/>
docker push rashidansari/webapi-host-docker . <br/>

Run on local <br/>
docker run -p 8080:80 rashidansari/webapi-host-docker <br/>
http://localhost:8080/api/WeatherForecast 

https://projects.spring.io/spring-cloud/
```
\\ 1) Run Eureka Server
\\ 2) Start weather-service
\\ 3) start weather-app and go to http://localhost:8000/current/weather, you will that it retrieve information from weather-service
\\ 4) shutdown weather-service and you will see message unknown means that the Hystrix circuit breaker is working
\\ 5) start hystrix-dashboard and go to http://localhost:8080/hystrix/, type http://localhost:8000/hystrix.stream and click Monitor Stream
\\ 6) start turbine and go to http://localhost:8080/hystrix/, type http://localhost:3000/turbine.stream, Type Title :'Turbine' and click Monitor Stream
```
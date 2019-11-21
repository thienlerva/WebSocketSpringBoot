WebSocket using Spring Boot to send instant messages
To run localhost:/8080

https://www.javaguides.net/2019/06/spring-boot-angular-8-websocket-example-tutorial.html

Update angular 8: npm install -g @angular/cli

Inside the project we have to install tree libraries with commands:
npm install stompjs;
npm install sockjs-client
npm install jquery

npm i net -S

Follow below steps to run front-end Angular application:

git clone https://github.com/RameshMF/angular8-springboot-websocket
cd front-end/angular8-springboot-websocket
npm install
ng serve

Follow below steps to run back-end application:
1. Extract the back-end zip file
2. cd back-end/springboot-stomp-websocket
3. mvn spring-boot:run

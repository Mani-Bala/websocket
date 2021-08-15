# websocket

### A chat application with spring boot and websocket

- WebSocket is a communication protocal that makes it possible to enable two way communication between a server and client.

- WebSocket works by first establishing a regular HTTP connection with the server and then upgrading it to a bidirectional websocket connection by sending an ```Upgrade``` header

#### Initialize Application:
- Create a spring boot application by using spring boot CLI  [Official Spring Boot documentation](https://docs.spring.io/spring-boot/docs/current/reference/html/getting-started-installing-spring-boot.html#getting-started-installing-the-cli).
  > ```$ spring init --name=websocket-demo -dependencies=websocket websocket-demo```
- If we don't want to install CLI, We can use [Spring Initializer](https://start.spring.io/) web tool to generate the project.

#### WebSocket Configuration:
  - Configure the websocket endpoint and message broker.
  - @EnableWebSocketMessageBroker is used to enable our WebSocket server
  - configuring a message broker that will be used to route messages from one client to another.
  

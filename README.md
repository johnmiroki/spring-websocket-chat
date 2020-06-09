spring-websocket-chat with Maven
=====================

Forked then adapted Maven

[![Join the chat at https://gitter.im/salmar/spring-websocket-chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/salmar/spring-websocket-chat?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/salmar/spring-websocket-chat.svg?branch=master)](https://travis-ci.org/salmar/spring-websocket-chat)

Chat application using AngularJS and Spring WebSockets (STOMP over WebSockets)


![Spring WebSocket Chat](http://www.sergialmar.com/wp-content/uploads/2014/09/spring-websocket-chat-room.png "Spring WebSocket Chat")

[Video Presentation](https://www.infoq.com/presentations/spring-4-websockets/)

## Features
- Built with Spring Boot
- User login
- Chat message broadcasting and private messages (filtering profanities)
- Presence tracking sending notifications when users join / leave
- Broadcast notifications when users are typing
- WebSockets stats exposed at /stats
- WebSocket security with Spring Security
- Spring Session integration

## Running the app
 ./mvnw spring-boot:run
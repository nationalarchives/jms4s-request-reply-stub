# JMS4s Request-Reply Stub

This stub service is designed to reply to JMS messages with stubbed data and is intended for use during development and testing of frontend services that rely on the response-reply message pattern.

To start ElasticMQ in Docker run..
```
docker compose up -d
```
..from the project root directory.

To start the EchoServer use `sbt run`.
# exrabbitmq

Node JS based RabbitMQ example code

Start rabbitmq server
```bash
$> ./startRabbitMQ.sh
```
Server starts and listens on the port 5672

Start the publisher to publish some messages
```bash
$> npm publish <some message>
```

Start the consumer to consume the messages published above by publisher
```bash
$> npm consume <some message>
```

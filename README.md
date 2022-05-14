# kafka-sse-stream

Stream Kafka messages as Server Sent Events to SSE clients

![gif](https://i.imgur.com/g7rw0vB.gif)

## Examples

```
kafka-sse-stream --broker 172.10.10.5 --topics topic1
kafka-sse-stream --broker 172.10.10.5 --topics topic1 --consumergroup group1 --offset earliest
```

## Flags

```
  -b, --broker string          Kafka broker address
  -c, --consumergroup string   Kafka consumer group (default "group1")
  -h, --help                   help for kafka-sse-stream
  -o, --offset string          Kafka consumer offset (default "latest")
  -t, --topics stringArray     Kafka topics to subscribe to
```

<p align="center">
  <br>
  <img width="400" src="./awesome%20kafka.png" alt="logo of kafka-awesome repository">
  <br>
  <br>
</p>

# Awesome Kafka [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome things related to Apache Kafka.

## Contents

- [Libraries](#libraries)
  - [Kafka](#kafka)
  - [Kafka UI](#kafka-ui)
  - [Kafka Streams](#kafka-streams)
  - [Kafka Connect](#kafka-connect)
  - [REST Proxy](#rest-proxy)
  - [KSQL](#ksql)
  - [Schema Registry](#schema-registry)
  - [Other Awesome Kafka](#other-awesome-kafka)
  - [Kafkaesque](#kafkaesque)
- [Resources](#resources)
  - [Learning](#learning)
  - [Blogs](#blogs)
  - [Books](#books)

<!-- md-parser-start -->

## Libraries

### Kafka

- [topicctl](https://github.com/segmentio/topicctl) - A tool for easy, declarative management of Kafka topics. Includes the ability to "apply" topic changes from YAML as well as a repl for interactive exploration of brokers, topics, consumer groups, messages, and more.
- [sarama](https://github.com/Shopify/sarama) - Sarama is an MIT-licensed Go client library for Apache Kafka version 0.8 (and later).
- [kadeck](https://www.xeotek.com/kadeck/) - Apache Kafka Monitoring, Kafka UI and data platform for Desktop or Web.
- [conduktor](https://www.conduktor.io/)
- [mirus](https://github.com/salesforce/mirus) - Mirus is a cross data-center data replication tool for Apache Kafka.
- [kareldb](https://github.com/rayokota/kareldb) - A Relational Database Backed by Apache Kafka.
- [kcache](https://github.com/rayokota/kcache) - An In-Memory Cache Backed by Apache Kafka.
- [kafka-lag-based-assignor](https://github.com/grantneale/kafka-lag-based-assignor) - Kafka partition assignor that distributes lag evenly across a consumer group.
- [kafka-pixy](https://github.com/mailgun/kafka-pixy) - Kafka-Pixy is a dual API (gRPC and REST) proxy for Kafka with automatic consumer group control.
- [Burrow](https://github.com/linkedin/Burrow) - Kafka Consumer Lag Checking.
- [kafka-tools](https://github.com/linkedin/kafka-tools) - A collection of tools for working with Apache Kafka.
- [schema-registry-ui](https://github.com/landoop/schema-registry-ui) - Web tool for Avro Schema Registry.
- [kafkacat](https://github.com/edenhill/kafkacat) - Generic command line non-JVM Apache Kafka producer and consumer.
- [kafka-jackson](https://github.com/jcustenborder/kafka-jackson) - Kafka Serializer, Deserializer, and Serde for Jackson JSON.
- [kafkahq](https://github.com/tchiotludo/kafkahq) - Kafka GUI for topics, topics data, consumers group, schema registry, connect and more.
- [secor](https://github.com/pinterest/secor) - Secor is a service implementing Kafka log persistence.
- [reactive-kafka](https://github.com/akka/reactive-kafka) - Alpakka Kafka connector - Alpakka is a Reactive Enterprise Integration library for Java and Scala, based on Reactive Streams and Akka.
- [kafka-monitor](https://github.com/linkedin/kafka-monitor)
- [chaperone](https://github.com/uber/chaperone) - A Kafka audit system.
- [uReplicator](https://github.com/uber/uReplicator) - Improvement of Apache Kafka Mirrormaker.
- [kafka-websocket](https://github.com/b/kafka-websocket)
- [kafka-unit](https://github.com/chbatey/kafka-unit)
- [cruise-control](https://github.com/linkedin/cruise-control) - Cruise-control is the first of its kind to fully automate the dynamic workload rebalance and self-healing of a kafka cluster.
- [jocko](https://github.com/travisjeffery/jocko) - Kafka implemented in Golang with built-in coordination (No ZK dep, single binary install, Cloud Native).
- [hermes](https://github.com/allegro/hermes) - Fast and reliable message broker built on top of Kafka.
- [kt](https://github.com/fgeller/kt) - Kafka command line tool.
- [kafka-eagle](https://github.com/smartloli/kafka-eagle) - Used to monitor the consumer status of Kafka clusters, as well as offsets, metadata and other information.
- [dockerkafka](https://github.com/pinterest/doctorkafka) - DoctorKafka is a service for Kafka cluster auto healing and workload balancing.
- [kasper](https://github.com/movio/kasper) - Kasper is a lightweight library for processing Kafka topics.
- [Yelp kafka-utils](https://github.com/Yelp/kafka-utils)
- [kafka-spark-consumer](https://github.com/dibbhatt/kafka-spark-consumer)
- [kafka-streams-cep](https://github.com/fhussonnois/kafkastreams-cep) - Complex Event Processing on top of Kafka Streams.
- [spring-kafka](https://github.com/spring-projects/spring-kafka)
- [ksql-machine-learning-udf](https://github.com/kaiwaehner/ksql-machine-learning-udf)
- [kafkabeat](https://github.com/dearcode/kafkabeat) - Elasticsearch Beats for kafka.
- [sangrenel](https://github.com/jamiealquiza/sangrenel)
- [Strimzi](https://github.com/strimzi/strimzi-kafka-operator) - Operator for deploying and running Apache Kafka on Kubernetes and OpenShift.
- [Kafka Manager](https://github.com/yahoo/kafka-manager) - Web-based tool for managing a Kafka cluster.
- [Strimzi Kafka CLI](https://github.com/systemcraftsman/strimzi-kafka-cli) - A CLI for Strimzi Kafka Operator.
- [Kafka Cluster Kraft Mode - DockerCompose](https://github.com/minhhungit/kafka-kraft-cluster-docker-compose) - Workable kafka cluster with kraft mode using docker-compose.
- [Decaton](https://github.com/line/decaton) - High throughput asynchronous task processing framework

### Kafka UI

- [KafkaTrail](https://github.com/imkrishnaagrawal/KafkaTrail)
- [kafka-topics-ui](https://github.com/lensesio/kafka-topics-ui)
- [kafka-connect-ui](https://github.com/landoop/kafka-connect-ui) - Web tool for Kafka Connect.
- [Kafdrop](https://github.com/obsidiandynamics/kafdrop) - Web UI for browsing Kafka topics and consumer groups.
- [kafka-webview](https://github.com/SourceLabOrg/kafka-webview)
- [kafka-view](https://github.com/fede1024/kafka-view)
- [cruise-control-ui](https://github.com/linkedin/cruise-control-ui)
- [real-time-ui-with-kafka-streams](https://github.com/lucasjellema/real-time-ui-with-kafka-streams)
- [tsujun](https://github.com/matsumana/tsujun) - Yet another Web UI for KSQL.
- [kowl](https://github.com/cloudhut/kowl)
- [akhq](https://akhq.io)

### Kafka Streams

- [schema-registry-ui](https://github.com/lensesio/schema-registry-ui)
- [kafka-streams-consumer-offsets-to-json](https://github.com/sderosiaux/kafka-streams-consumer-offsets-to-json) - A Kafka Streams process to convert consumer_offsets to a JSON-readable topic.
- [kafka-operator](https://github.com/krallistic/kafka-operator)
- [kafkabalancer](https://github.com/CAFxX/kafkabalancer)
- [mockedstreams](https://github.com/jpzk/mockedstreams)
- [winton-kafka-streams](https://github.com/wintoncode/winton-kafka-streams) - A Python implementation of Apache Kafka Streams.

### Kafka Connect

- [Apache Camel Kafka Connect](https://camel.apache.org/camel-kafka-connector/latest/index.html) - 340+ Apache Camel components as Kafka Connect connectors.
- [kafka-connect-client](https://github.com/SourceLabOrg/kafka-connect-client) - A kafka-connect REST api client for java.
- [Confluent Connector Hub](https://www.confluent.io/product/connectors/)
- [kafka-connect-protobuf-converter](https://github.com/blueapron/kafka-connect-protobuf-converter) - Protobuf converter plugin for Kafka Connect.
- [Maxwell](https://github.com/zendesk/maxwell)
- [kafka-connect-transformers](https://github.com/Landoop/kafka-connect-transformers)
- [kafka-connect-mq-source](https://github.com/ibm-messaging/kafka-connect-mq-source)
- [kafka-connect-jenkins](https://github.com/yaravind/kafka-connect-jenkins)
- [toketi-kafka-connect-iohub](https://github.com/Azure/toketi-kafka-connect-iothub)
- [connectctl](https://github.com/90poe/connectctl) - Manage kafka connect connectors easily.
- [kafka-connect-transform-common](https://github.com/jcustenborder/kafka-connect-transform-common) - Common Transforms for Kafka Connect.
- [aiven-kafka-connect-transforms](https://github.com/aiven/aiven-kafka-connect-transforms) - A collection of Single Message Transformations (SMTs) for Kafka Connect.
- [kafka-connect-file-pulse](https://github.com/streamthoughts/kafka-connect-file-pulse) - A polyvalent, scalable and reliable, Kafka Connector that makes it easy to parse, transform and stream any file, in any format, into Apache Kafka.
- [kafka-connect-http](https://github.com/thomaskwscott/kafka-connect-http)
- [snowflake-kafka-connector](https://github.com/snowflakedb/snowflake-kafka-connector)

### REST Proxy

- [kafka-rest](https://github.com/confluentinc/kafka-rest) - Confluent REST Proxy.
- [strimzi-http-bridge](https://github.com/strimzi/strimzi-kafka-bridge) - Strimzi Kafka Bridge (AMQP & HTTP).
- [Zilla](https://github.com/aklivity/zilla) - An API gateway built for event-driven architectures and streaming that supports standard protocols such as HTTP, SSE, gRPC, MQTT and the native Kafka protocol.

### KSQL

### Schema Registry

- [apicurio-registry](https://github.com/Apicurio/apicurio-registry) - Apicurio API/schema registry (includes UI).
- [schema-registry](https://github.com/confluentinc/schema-registry) - Confluent Schema registry for Kafka.
- [ksql-jdbc-driver](https://github.com/mmolimar/ksql-jdbc-driver)
- [ballerina-schema-registry](https://github.com/ballerina-platform/module-ballerinax-confluent.cregistry) - Ballerina Confluent Schema Registry

### Other Awesome Kafka

- [ApacheKafka](https://github.com/jsroyal/ApacheKafka)
- [dharmeshkakadia/awesome-kafka](https://github.com/dharmeshkakadia/awesome-kafka)
- [infoslack/awesome-kafka](https://github.com/infoslack/awesome-kafka)
- [awesome-kafka-playground](https://github.com/anascotti/awesome-kafka-playground)
- [ballerina-avro-kafka-serializer](https://github.com/ballerina-platform/module-ballerinax-confluent.cavroserdes) - Ballerina Confluent Avro Serializer/Deserializer

### Kafkaesque

- [Pulsar](https://github.com/apache/incubator-pulsar)
- [Flink](https://flink.apache.org/)
- [Spark](https://spark.apache.org/)
- [Heron](https://github.com/apache/incubator-heron)
- [Beam](https://beam.apache.org/)
- [Arrow](https://arrow.apache.org/)
- [Samza](https://samza.apache.org/)
- [Nats](https://nats.io/)
- [Chronicle-Queue](https://github.com/OpenHFT/Chronicle-Queue)
- [CorfuDB](https://github.com/CorfuDB/CorfuDB)
- [GenStage](https://hexdocs.pm/gen_stage/GenStage.html)
- [faust](https://github.com/robinhood/faust) - Python Stream Processing.
- [redpanda](https://vectorized.io/)
- [Meteor](https://github.com/obsidiandynamics/meteor) - Lightweight, broker-less alternative to Kafka for message streaming.

## Resources

### Learning

- [Passionate Developer: Kafka Streams DSL vs processor API](https://mkuthan.github.io/blog/2017/11/02/kafka-streams-dsl-vs-processor-api/)
- [Mastering Kafka Streams](https://jaceklaskowski.gitbooks.io/mastering-kafka-streams)
- [Spark Streaming + Kafka Integration Guide](https://spark.apache.org/docs/latest/streaming-kafka-integration.html)

### Blogs

- [CodingJunkie](http://codingjunkie.net/) - Random Thoughts on Coding by Bill Bejeck.
- [Understanding Kafka with Factorio]([https://ruurtjan.com/articles/understanding-kafka-with-factorio)

### Books

- [Kafka Streams in Action](https://www.manning.com/books/kafka-streams-in-action)
- [Kafka in Action](https://www.manning.com/books/kafka-in-action)
- [Kafka the Definitive Guide](https://shop.oreilly.com/product/0636920044123.do)
- [Streaming Data Pipelines with Kafka](https://www.manning.com/books/streaming-data-pipelines-with-kafka)

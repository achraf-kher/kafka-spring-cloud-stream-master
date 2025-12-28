Activité Pratique N°3 – Event Driven Architecture avec Kafka 

Ce projet illustre la mise en place d’une architecture orientée événements (Event Driven Architecture) basée sur Apache Kafka et Spring Boot / Spring Cloud Stream.

L’application permet :

de produire des événements via une API REST,

de les publier dans Kafka,

de les traiter en temps réel avec Kafka Streams,

de produire des résultats analytiques en continu.

Le projet est basé sur le repository pédagogique suivant :
🔗 https://github.com/mohamedYoussfi/kafka-spring-cloud-stream

src/main/java
└── net.youssfi.demospringkafka
├── entities
│   └── PageEvent.java
├── processors
│   └── StreamDataAnalyticService.java
├── serializers
│   ├── CustomSerializer.java
│   └── CustomDeSerializer.java
├── service
│   ├── AppSerdes.java
│   └── PageEventService.java
├── web
│   └── PageEventController.java
└── DemoSpringKafkaApplication.java

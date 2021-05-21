# azure_hdi_jars
the 1.0 jar is trying to fix the log dependency issue
the 2.0 jar can help us create topic with partiton number  and replica factors.
usage:
java -jar   -Djava.security.auth.login.config=/usr/hdp/current/kafka-broker/config/kafka_client_jaas.conf kafka-producer-consumer-esp-2.0-SNAPSHOT.jar create myTest 4 3 10.8.0.42:9092

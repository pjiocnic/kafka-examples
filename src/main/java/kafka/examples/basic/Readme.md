__Pre-requisite for Consumer Group Demo__

Single partition serves a single consumer at a time, if that consumer is part of a group.

For 2 member of a Consumer Group to share messages received on a Topic,
each consumer should attach to a different partition of Kafka broker.

So, we need to have at least 2 partitions in our Kafka Cluster.

Instructions to have a 2-partition Kafka Cluster is provided in [Setup](https://github.com/agrawalnishant/kafka-examples#setup) section of main Readme file.

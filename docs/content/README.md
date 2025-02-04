# FeatHub

FeatHub is a stream-batch unified feature store that simplifies feature
development, deployment, monitoring, and sharing for machine learning
applications.

- [Quickstarts](quickstarts)
	- [Flink Cli Mode Quickstart](quickstarts/flink-cli-mode.md)
	- [Flink Session Mode Quickstart](quickstarts/flink-session-mode.md)
	- [Spark Client Mode Quickstart](quickstarts/spark-client-mode.md)
- [Basic Concepts](basic-concepts.md)
- [FeatHub SDK](feathub-sdk)
  - [FeatureView and Transformation](feathub-sdk/feature-view.md)
  - [Data Types and Reserved Keywords](feathub-sdk/dtypes.md)
  - [Built-in Operators and Functions](feathub-sdk/functions.md)
  - [Built-in Aggregations Functions](feathub-sdk/aggregation_functions.md)
- [Common Configurations](configurations.md)
- [Compute Engines](engines)
	- [Apache Flink](engines/flink.md)
	- [Apache Spark](engines/spark.md)
  - [Local Processor](engines/local.md)
- [Connectors](connectors)
  - [Overview](connectors/overview.md) 
  - [Formats](connectors/formats)
  - [FileSystem](connectors/filesystem.md)
  - [MySql](connectors/mysql.md)
  - [Kafka](connectors/kafka.md)
  - [Redis](connectors/redis.md)
  - [Hive](connectors/hive.md)
- [Metric Stores](metric-stores)
  - [Overview](metric-stores/overview.md)
  - [Built-in Metrics](metric-stores/metrics.md)
  - [Prometheus](metric-stores/prometheus.md)
- [Feature Registries](registries)
  - [MySQL](registries/mysql.md)
- [Deep Dive](deep-dive)
	- [Built-in Optimizations](deep-dive/optimizations.md)
- [How To](how-to)
  - [Deploy FeatHub Job on Alibaba Cloud](how-to/deploy-on-alibaba-cloud.md)

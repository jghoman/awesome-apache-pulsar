[<img src="https://github.com/jghoman/awesome-apache-pulsar/raw/master/apache-pulsar-logo.png" align="right">](https://pulsar.apache.org/)
# Awesome Apache Pulsar ![contrib badge](https://img.shields.io/github/contributors/jghoman/awesome-apache-pulsar.svg)
This is a curated list of resources about [Apache Pulsar](https://pulsar.apache.org/).  Please feel free to contribute any items that should be included. Items are generally added at the top of each section so that more fresh items are featured more prominently.

## Contents
- [Vital links](#vital-links)
- [Architecture](#architecture)
- [Comparisons with Apache Kafka](#comparisons-with-apache-kafka)
- [Testimonials](#testimonials)
- [Clients](#clients)

## Vital links
- [Source code](https://github.com/apache/pulsar/) (latest stable release [2.6.1](https://github.com/apache/airflow/tree/1.10.12))
- [Documentation](https://pulsar.apache.org/) (also the official website)
- [Twitter account](https://twitter.com/apache_pulsar?lang=en)
- [Slack workspace](https://apache-pulsar.slack.com/)

## Architecture
_n.b. these are roughly ordered by year and month of release, most recent at top_
- 2020-06: [Introduction to Apache Pulsar](https://www.baeldung.com/apache-pulsar) - Short walk-through of Pulsar's basic architecture and quickstart steps.
- 2018-10: [Understanding How Apache Pulsar Works](https://jack-vanlightly.com/blog/2018/10/2/understanding-how-apache-pulsar-works) -  [Jack Vanlightly](https://twitter.com/vanlightly) provides a thorough guide to the different arechitectural layers of Pulsar.

## Comparisons with Apache Kafka
_n.b. these are roughly ordered by year and month of release, most recent at top_
- 2020-06: [Comparing Apache Kafka and Apache Pulsar](https://blog.softwaremill.com/comparing-apache-kafka-and-apache-pulsar-3bd44e00f304) - [Jaroslaw Kijanowski](https://twitter.com/jkijanowski) provides an in-depth comparison between Pulsar and Kafka, focusing on features, community and enterprise support.

## Testimonials
_n.b. these are roughly ordered by year and month of release, most recent at top_
- 2019-10: [Why Nutanix Beam went ahead with Apache Pulsar instead of Apache Kafka?](https://medium.com/@yuvarajl/why-nutanix-beam-went-ahead-with-apache-pulsar-instead-of-apache-kafka-1415f592dbbb) - [Yuvaraj Loganathan](https://www.linkedin.com/in/yuvarajl) describes why Nutanix chose Pulsar for its Beam product.

## Clients
- Official clients supported by the Apache project:
  - [Java](https://pulsar.apache.org/docs/en/client-libraries-java)
  - [Go](https://pulsar.apache.org/docs/en/client-libraries-go)
  - [Python](https://pulsar.apache.org/docs/en/client-libraries-python)
  - [C++](https://pulsar.apache.org/docs/en/client-libraries-cpp)
  - [Node.js](https://pulsar.apache.org/docs/en/client-libraries-node)
  - [WebSockets](https://pulsar.apache.org/docs/en/client-libraries-websocket)
  - [C#](https://pulsar.apache.org/docs/en/client-libraries-dotnet)
- [pulsar-rs](https://github.com/wyyerd/pulsar-rs) ![Activity badge](https://img.shields.io/github/commit-activity/m/wyyerd/pulsar-rs) - Stand-alone Rust client that does not rely on C++ bindings.
- [pulsar-4s](https://github.com/sksamuel/pulsar4s) ![Activity badge](https://img.shields.io/github/commit-activity/m/sksamuel/pulsar4s) - Idiomatic Scala wrapper around the [official Java client](https://pulsar.apache.org/docs/en/client-libraries-java).

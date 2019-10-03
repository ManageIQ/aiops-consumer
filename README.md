# ⛔️ DEPRECATED: AI-Ops: Consumer microservice

[![Build Status](https://travis-ci.org/ManageIQ/aiops-consumer.svg?branch=master)](https://travis-ci.org/ManageIQ/aiops-consumer)
[![License](https://img.shields.io/badge/license-APACHE2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

A Consumer service that produces a recommendations JSON on an Advisor topic

## Get Started

* Learn about other services within our pipeline
  - [incoming-listener](https://github.com/ManageIQ/aiops-incoming-listener)
  - [data-collector](https://github.com/ManageIQ/aiops-data-collector)
  - [publisher](https://github.com/ManageIQ/aiops-publisher)
* Discover all AI services we're integrating with
  - [dummy-ai](https://github.com/ManageIQ/aiops-dummy-ai-service)
  - [aicoe-insights-clustering](https://github.com/RedHatInsights/aicoe-insights-clustering)
* See deployment templates in the [e2e-deploy](https://github.com/RedHatInsights/e2e-deploy) repository

## Configure

* `KAFKA_SERVER` - specify message bus server
* `KAFKA_CONSUMER_TOPIC` - topic to consume
* `KAFKA_PRODUCER_TOPIC` - topic to produce on

## License

See [LICENSE](LICENSE)

# Welcome to heartbeat 6.1.1

Ping remote services for availability and log results to Elasticsearch or send to Logstash.

## Getting Started

To get started with heartbeat, you need to set up Elasticsearch on your localhost first. After that, start heartbeat with:

     ./heartbeat -c heartbeat.yml -e

This will start the beat and send the data to your Elasticsearch instance. To load the dashboards for heartbeat into Kibana, run:

    ./heartbeat setup -e

For further steps visit the [Getting started](https://www.elastic.co/guide/en/beats/heartbeat/master/heartbeat-getting-started.html) guide.

## Documentation

Visit [Elastic.co Docs](https://www.elastic.co/guide/en/beats/heartbeat/master/index.html) for the full heartbeat documentation.

## Release notes

https://www.elastic.co/guide/en/beats/libbeat/master/release-notes-6.1.1.html

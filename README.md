# NIFI PubsubPublisher Processor

This is an [Apache NIFI](https://nifi.apache.org/) processor that
sends event message to Google Cloud Platform (GCP) PubSub topic.
The operation is quite simple, it just needs to know the name of topic, project ID and the
authentication keys if it is running outside a GCP compute instance.

This processor only sends the details of the file published on the Google cloud storage to pub-sub topic.



## Installation
* mvn pakage
* cp ./target/*.nar $NIFI_HOME/libs

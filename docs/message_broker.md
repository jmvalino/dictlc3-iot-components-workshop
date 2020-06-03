## Message Broker

When you are dealing with fleet of devices at scale, choosing the rigth message brokers is crurial for it will handle the events and data coming from diffrent devices deployed in production.

MQTT Brokers: Mosquitto, Managed - PubNub, AWS, Azure, GCP etc.

Some IoT Message Broker Providers Separate the types of message in to two: reading/ metric data and state data.

Example in AWS they have an AWS IoT "Shadow" document in Azure IoT "Twin".

![Message Broker Illustration](./assets/message_broker.png)

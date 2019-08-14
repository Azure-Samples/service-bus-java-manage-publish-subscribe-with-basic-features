---
page_type: sample
languages:
- java
products:
- azure
services: Servicebus
platforms: java
author: yaohaizh
---

## Getting Started with Servicebus - Service Bus Publish Subscribe Basic - in Java ##


  Azure Service Bus basic scenario sample.
  - Create namespace.
  - Create a topic.
  - Update topic with new size and a new ServiceBus subscription.
  - Create another ServiceBus subscription in the topic.
  - List topic
  - List ServiceBus subscriptions
  - Get default authorization rule.
  - Regenerate the keys in the authorization rule.
  - Send a message to topic using Data plan sdk for Service Bus.
  - Delete one ServiceBus subscription as part of update of topic.
  - Delete another ServiceBus subscription.
  - Delete topic
  - Delete namespace
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/service-bus-java-manage-publish-subscribe-with-basic-features.git

    cd service-bus-java-manage-publish-subscribe-with-basic-features

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Servicebus
  platforms: java
---

# Getting Started with Servicebus - Service Bus Publish Subscribe Basic - in Java #


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

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/service-bus-java-manage-publish-subscribe-with-basic-features.git

    cd service-bus-java-manage-publish-subscribe-with-basic-features

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

If you find bug in the sample, please create an issue [here](https://github.com/Azure/azure-sdk-for-java/issues).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

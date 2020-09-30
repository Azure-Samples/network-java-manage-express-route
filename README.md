---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: virtual-network
  platforms: java
---

# Getting Started with Network - Manage Express Route - in Java #


  Azure Network sample for managing express route circuits.
   - Create Express Route circuit
   - Create Express Route circuit peering. Please note: express route circuit should be provisioned by connectivity provider before this step.
   - Adding authorization to express route circuit
   - Create virtual network to be associated with virtual network gateway
   - Create virtual network gateway
   - Create virtual network gateway connection
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/network-java-manage-express-route.git

    cd network-java-manage-express-route

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
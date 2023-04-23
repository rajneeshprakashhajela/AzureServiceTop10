Security (User, Role, Policy), Monitoring, Logging, Exception Handling, Migration
1.	Azure Active Directory, AD Connect<br/>
2.	Azure API Management<br/>
3.	Azure Blob Storage<br/>
4.	Azure Event Grid (Push model)<br/>
5.	Azure Event Hub<br/>
6.	Azure Service Bus<br/>
7.	Azure Logic App<br/>
8.	Azure Function, Durable function (statefull, Stateless)<br/>
9.	Azure SQL Server <br/>
10.	Azure Cosmos DB<br/>
11.	Azure Backup, Azure Site Recovery<br/>
12.	Azure CDN<br/>
13.	Azure Data Factory<br/>
14.	Azure Virtual Machine<br/>
15.	Azure Monitor, Azure Application Insight, Log Analytics<br/>
16.	 Azure Sentinel, Security Center, Blueprint<br/>
17.	 Azure Container Registry<br/>
18.	 Azure Kubernetes Services<br/>
19.	 Azure Key Vault<br/>
20.	Azure DevOps<br/>
 





<br/><br/>


Azure Event Hubs—<br/>
A big data streaming platform and event ingestion service
This is a messaging at scale mecha<br/>nism where you process large volume of telemetry data. This cloud offering is a one-way event processing system that can take millions of events per second and can be used for analysis and storage.

EXAMPLE : Super Market – All the details related to the purchase, sent to the event hub which can be used to analyse the stock in the inventory and alert the Inventory department whenever the product goes out of stock

Event Producer, Event Receiver, Partition, Consumer Group

 
<br/>
Azure Event Grid:<br/>
Azure Event Grid is a Publisher/Subscriber model, where there is a publisher who sends a message and multiple party at the receiver ends receives these messages. This model is loosely coupled.
Event, Event Publisher, Event Subscriptions, Event Handler, Topics.

EXAMPLE – Supermarket buys similar product from multiple vendors. The place an order which is subscribed by multiple vendors. Each vendor receives a copy of the order.

 
<br/>
Azure Service Bus:<br/>
Asynchronous flow of data which is based on FirstIn-FirstOut model.
In simple terms we can compare this model with a IBM MQ i.e. a Queueing mechanism. Asynchronous flow of data which is based on FirstIn-FirstOut model. You sent a message to a queue and want this message to be processed within a specific amount of time. What if the messages is not processed either move it to dead letter queue or  perform some action to it. There is a temporary control and consistency over the data that is being processed.

EXAMPLE – Super market where the cashiers bills your item one by one


 
   <br/>
 
Azure API Management:<br/>
Azure API Management offers a scalable, multi-cloud API management platform for securing, publishing, and analyzing APIs.
Azure API Management is made up of an API gateway, a management plane, and a developer portal.
 

 
<br/>
Azure Function<br/>
Azure Functions is a serverless solution that allows you to write less code, maintain less infrastructure, and save on costs. Instead of worrying about deploying and maintaining servers, the cloud infrastructure provides all the up-to-date resources needed to keep your applications running

Azure Durable Functions is an extension of Azure Functions that lets you write stateful functions in a serverless compute environment.



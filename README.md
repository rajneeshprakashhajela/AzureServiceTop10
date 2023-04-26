Security (User, Role, Policy), Monitoring, Logging, Exception Handling, Migration <br/>
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
![image](https://user-images.githubusercontent.com/43515480/233822691-7c7d8c60-145a-47b8-a0d1-d0831cd785ce.png)

 
<br/>
Azure Event Grid:<br/>
Azure Event Grid is a Publisher/Subscriber model, where there is a publisher who sends a message and multiple party at the receiver ends receives these messages. This model is loosely coupled.
Event, Event Publisher, Event Subscriptions, Event Handler, Topics.

EXAMPLE – Supermarket buys similar product from multiple vendors. The place an order which is subscribed by multiple vendors. Each vendor receives a copy of the order.
![image](https://user-images.githubusercontent.com/43515480/233822699-78dbfcd6-42bf-45ef-a99c-d38dbc8305cd.png)

 
<br/>
Azure Service Bus:<br/>
Asynchronous flow of data which is based on FirstIn-FirstOut model.
In simple terms we can compare this model with a IBM MQ i.e. a Queueing mechanism. Asynchronous flow of data which is based on FirstIn-FirstOut model. You sent a message to a queue and want this message to be processed within a specific amount of time. What if the messages is not processed either move it to dead letter queue or  perform some action to it. There is a temporary control and consistency over the data that is being processed.

EXAMPLE – Super market where the cashiers bills your item one by one

![image](https://user-images.githubusercontent.com/43515480/233822706-dd39c17e-8724-4515-a4f1-7bcb27e0d803.png)
![image](https://user-images.githubusercontent.com/43515480/233822707-1a98dbcf-c7d3-41b2-88a3-24c27d07662a.png)

 
   <br/>
 ![image](https://user-images.githubusercontent.com/43515480/233822714-f483399d-5093-422c-ad01-c57a97a2b212.png)
Azure API Management:<br/>
Azure API Management offers a scalable, multi-cloud API management platform for securing, publishing, and analyzing APIs.
Azure API Management is made up of an API gateway, a management plane, and a developer portal.
 
![image](https://user-images.githubusercontent.com/43515480/233822724-d386ca5c-9415-4f97-8f62-fb6020718208.png)
 
<br/>
<h3>Azure Function</h3><br/>
Azure Functions is a serverless solution that allows you to write less code, maintain less infrastructure, and save on costs. Instead of worrying about deploying and maintaining servers, the cloud infrastructure provides all the up-to-date resources needed to keep your applications running <br/>

Azure Durable Functions is an extension of Azure Functions that lets you write stateful functions in a serverless compute environment. <br/>


<h3>Azure AD</h3> <br/>
<img width="567" alt="image" src="https://user-images.githubusercontent.com/43515480/233843219-f43cef11-0a50-4af5-9fb4-0cdce985d437.png">

<h3>Azure service Bus</h3> <br/>
Topic - Multiple subscriber <br/>
Queue - Queue only one consumer <br/>
![image](https://user-images.githubusercontent.com/43515480/234226268-d6d5695f-ed18-42a8-bc80-7ee94d029563.png)

<h3>Azure Cosmos DB</h3>
Globally distributed highly responsible database in cloud
![image](https://user-images.githubusercontent.com/43515480/234226393-2f7a2cda-3f56-4752-8294-0e579ba04436.png)
![image](https://user-images.githubusercontent.com/43515480/234228513-a9aaaed0-9d2c-48fb-995c-fc7a6714233e.png)

![image](https://user-images.githubusercontent.com/43515480/234228892-d1202f25-d33c-4eaf-b318-cf57d773e771.png)
![image](https://user-images.githubusercontent.com/43515480/234228906-ff375cb3-a6c5-492f-920c-07ce81c228e7.png)
![Uploading image.png…]()

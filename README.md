Migration

webapp
https://www.youtube.com/watch?v=ubFp6HW5cvo

SQL Server:
https://www.youtube.com/watch?v=MhnmG-cHrKM

Migrate via Azure Migrate <br/>
![image](https://user-images.githubusercontent.com/43515480/234507786-fca9be61-4026-47f2-ade8-29d429bfd86d.png)
![image](https://user-images.githubusercontent.com/43515480/234507913-30bbcdb0-40f2-431f-908d-f2bf97f5c22e.png)
![image](https://user-images.githubusercontent.com/43515480/234509116-f920f0c6-d52d-4583-9fa6-715beb6fe5e2.png)
![image](https://user-images.githubusercontent.com/43515480/234509638-821cf409-b46a-49a3-a09b-d97297184041.png)
![image](https://user-images.githubusercontent.com/43515480/234509746-7ce744a2-68be-4cb9-a19d-2fe57c2dbe3c.png)
![image](https://user-images.githubusercontent.com/43515480/234509878-76c65025-af93-4a28-8def-b31cfc353a42.png)
![image](https://user-images.githubusercontent.com/43515480/234509906-b9e59fc3-fc15-4d5d-a201-66106cef0370.png)
![image](https://user-images.githubusercontent.com/43515480/234510213-a9e91cf6-a255-4073-838b-c88370ac836b.png)
![image](https://user-images.githubusercontent.com/43515480/234510273-8dba12aa-5c49-42d7-9d6f-8efc7aa3e0d5.png)
![image](https://user-images.githubusercontent.com/43515480/234510674-cdceb083-da8c-41f5-861b-c157f198312a.png)
![image](https://user-images.githubusercontent.com/43515480/234511046-7522708d-adbe-4f95-8b2f-980a813a9a89.png)


<br/>
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
![image](https://user-images.githubusercontent.com/43515480/235389687-dd29c066-c87a-4493-82df-08aa104b2f38.png)

filter data  data-->(Text to column) 
![image](https://user-images.githubusercontent.com/43515480/235389913-21df0c9c-1572-4b9b-ad68-dea554c9d721.png)

![image](https://user-images.githubusercontent.com/43515480/235390025-f253af90-8aab-4da8-b95a-c17cb49b1b66.png)

key vault for Role and access policies
https://medium.com/geekculture/how-to-use-key-vault-secrets-in-azure-pipelines-658198f2eea6

![image](https://user-images.githubusercontent.com/43515480/235395500-bb0980cc-a071-446a-b162-7247504fe0d3.png)

![image](https://user-images.githubusercontent.com/43515480/235447443-76193257-1db8-46a5-8d39-866e3794eef3.png)

![image](https://user-images.githubusercontent.com/43515480/235447485-a0863717-a868-4a7b-a15e-9e74f607df02.png)
![image](https://user-images.githubusercontent.com/43515480/235447619-2baf3ff5-d333-460f-aade-24f1a438a5de.png)

NSG

![image](https://user-images.githubusercontent.com/43515480/235448733-fdafa914-9676-4504-9d36-109f58d5bdd5.png)
![image](https://user-images.githubusercontent.com/43515480/235448814-90af5417-f3b7-432a-bf46-ebde90e4ae2c.png)

<img width="532" alt="image" src="https://github.com/rajneeshprakashhajela/AzureServiceTop10/assets/43515480/44806d5e-fe71-43da-b1b1-c2b9466086af">

Logic app exception handling
Retry policies <br/>
Manage the "run after" behavior<br/>
Evaluate actions with scopes and their results<br/>
Set up Azure Monitor logs<br/>
<br/>
![image](https://github.com/rajneeshprakashhajela/AzureServiceTop10/assets/43515480/df928f91-ad83-40f9-baa3-bbd1ebc94431)

![image](https://github.com/rajneeshprakashhajela/AzureServiceTop10/assets/43515480/dc4be410-2cb2-4d5d-b5b1-a78eadb821d1)
![image](https://github.com/rajneeshprakashhajela/AzureServiceTop10/assets/43515480/93dac56b-e385-4358-b74a-fecf1b995abb)
By default, the "run after" status is set to is successful. So, the predecessor action must run successfully before the currently selected action can run.
![image](https://github.com/rajneeshprakashhajela/AzureServiceTop10/assets/43515480/58065dfd-c53e-4dc9-b28f-95486129a09f)

Logic app time out:

https://medium.com/@priyankabhakuni1/logic-apps-timeout-issue-solved-3307f45fd682


![image](https://github.com/rajneeshprakashhajela/AzureServiceTop10/assets/43515480/a339797a-aa50-4581-af54-97f708a5aee3)

https://medium.com/@jeffhollan/calling-long-running-functions-from-logic-apps-6d7ba5044701
![image](https://github.com/rajneeshprakashhajela/AzureServiceTop10/assets/43515480/2c587de4-084a-4d29-91f8-5f69c0b63ef9)


https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-exception-handling?tabs=consumption



The Webhook handles the timeout issue smoothly. I have never encountered the timeout issue again after implementing this functionality.
Webhook calls the Azure function, HTTP Trigger
HTTP Trigger has two important roles a) Send a message to a Queue b) Call Logic Apps
Ensure the message which is sent to the Queue should have the Logic App Callback URL
Once the message is sent, HTTP Trigger sends a response back to Logic Apps with a 202 (Accepted response). This should happen in the 120 seconds timeframe
The accepted response will make the Logic App go into a dehydrated state. It will no longer clock the 120 seconds timeframe


![image](https://github.com/rajneeshprakashhajela/AzureServiceTop10/assets/43515480/4abeb2a2-4cf9-43db-a59c-f0aa00de9324)

API Manangement JWT Token
https://tointegrationandbeyond.com/blogs/index.php/2020/06/13/authorization-with-azure-api-management/

secure  azure function 
https://dev.to/ib1/protecting-azure-functions-with-api-management-service-53el

https://conferenceapi.azurewebsites.net/
![image](https://user-images.githubusercontent.com/43515480/236736003-bbfa4809-7fa0-4ebc-9de3-85631a87f1f0.png)

![image](https://user-images.githubusercontent.com/43515480/236735968-e589620a-85f8-4b31-b843-2b6353322d33.png)

https://drive.google.com/drive/folders/12sFurrOhJyAqysoJAv4FClotVZXsHFUO?usp=sharing
![image](https://user-images.githubusercontent.com/43515480/236380858-15f1e7b2-dd63-44a3-bfb2-33c1c8d510db.png)

Have you worked in multi-subscription environment? What is Tenant ? (Azure lighthouse – Multiple tenant), sentinel (workbook)<br/>
What are Azure polices, give few examples? (Azure policy and Blueprint provide the  rules and structure on the subscription)<br/>
What is UDR (User defined Route) Or Route table and how to configure it in Azure? (virtual appliance)<br/>
What are private endpoints in Azure?, Public endpoint, Bastion, Firewall, Ddos Protection, ExPress Route, Site to site , ASG, NSG, compute service (VM,VMSS,ACI,AKS,App Service, Function) , azure service, Publish repository on Linux server<br/>
What do you understand by IaC? - Ansible, Terraform<br/>
What is GitFlow branching model? (Feature branch, commit changes, Create PR, Code Review, Merge branch)<br/>
What tool do you use for creating Architecture in Azure? (Miro, Draw.io, <br/>
Communication  VNET to Vnet, Subnet, VM, Subnet to Subnet, VM to VM<br/>
Azure SQL & Sql Database -LRS, GRS  (Data Migration assigstant tool), App service migration assistant tool<br/>
Azure DevOps Variable (Global Varibable then how will you change env for prod, test. (How to call  Azure secret in DevOps pipeline<br/>
 If 1 machine is full (no space in disk) and 2nd If machine  is down  then what will be first step ?<br/>
Classic editor & Yaml<br/>
Can you Write  DevOPS pipel line YAML file in notepad  for Kubernetes Deployment, Service via Terraform (Strategy & Steps). <br/>Azure DevOps Pipeline CICD Steps with Resource access. (Only selected user can execute pipeline)  . How do you  call  Variable, Azure Keyvault in pipeline.  How Azure function in CICD Pipeline ? <br/>
Difference between Azure IAAS, PAAS, SAAS.  (How Azure durable function statefull work.)<br/>
VM & VM ScaleSet , Vnet peering, Azure Policies, (Backup & Restore)<br/>
Read and write (Post and Put) , Logic app (Consumption, standard), logic app exception handling, debug issue<br/>
How  to call variable in yaml file. (global variable, local variable, dynamic varibale)<br/>
How to balance traffic (Load Balancer, Front door, application Gateway, traffic manager)<br/>
Canary, Blue Green Deployment , Helm chart, init container, SideCar<br/>
Long running job on Azure function  (time out 2 min in logic app or function then how will you handle ? <br/>
Cloud infrastructure deployment, firewall and load balancing, networking, switching, backup and disaster recovery, high <br/>availability, enterprise and cloud storage management and technologies, databases and infrastructure capacity planning<br/>
Software packaging and automated deployment experience.<br/><br/>
Do you have experience of managing kubernetes infrastructure in production environment?<br/>


![image](https://user-images.githubusercontent.com/43515480/236380874-602094a4-8d37-4c41-8533-9b124dd9fd41.png)

? Experience with using Async IOT Communication mechanisms, such as MQTT- Sparkplug.<br/>
? Experience with using scripting languages for integration with various protocols.<br/>
? Experience with API definition and design for Application Consumption.<br/>
? Experience with Data modeling and Data Storage Design.<br/>
? Experience with writing and maintaining automated testing at the unit, integration, and functional test levels.<br/>
? Experience with source control tooling such as Git and following pull requests and peer code review guidelines.<br/>
? Ability to plan, estimate, and deliver highly focused and tested features and enhancements in a 2-week agile sprint cadence and releasing.<br/>
? Has strong written skills and the ability to effective communicate technical analyses and
results to business management<br/>
? Demonstrable knowledge and skills with network programming, distributed systems, security, uthentication, and authorization in distributed systems and the web<br/>
? Familiarity with various software architectures: service oriented architecture, microservices, event driven, serverless computing<br/>
? Experience with SQL, NoSQL, and Multi-modal database systems such as MySQL,<br/>
PostgreSQL, Snowflake, and CosmosDB, etc.<br/>
? Hands-on experience with public clouds such as Microsoft Azure, Amazon Web Services, or<br/>
the Google Cloud Platform and technologies (or an equivalent) such as:<br/>
? Azure DevOps CI/CD, ? Azure Key Vault, ? Azure IOT, EventHubs, Event Grid, Azure Functions<br/>
? Experience working with DevOps technologies such as Jenkins or Chef<br/>
? Container experience using technologies such as: ? Docker,? Kubernetes,? Helm,? AKS,? OpenShift, ? Service Fabric<br/>
? Strong experience in Data Ingestion and Integration<br/>
? Deep experience with high volume distributed event data processing
? Experience with caching strategies and technologies (such as Redis) in a distributed system<br/>
? At least one additional scripting language such as Powershell, Python, Perl, R, Ruby.,? RESTful/GraphQL API Design
? Configuration Management Tool experience<br/>
![image](https://user-images.githubusercontent.com/43515480/236380881-75419412-4387-4f28-9e48-12b6ab88c27f.png)<br/>

A tenant is an Azure Active Directory (Azure AD) entity. It's the directory in which users, groups, and applications are stored. A subscription is a billing entity that you use to organize access to cloud resources.<br/><br/>

How would you design highly available and scalable architecture using azure resources load balancer, Virtual machine etc.
Region, availability set, Availability zone<br/><br/>
AKS How to decide node count or node pool size ?<br/><br/>
Git type of merge<br/>
If pipeline is deployed on prod how to revert back ?<br/>
AKS Storage Class, Persistent Volume, Persistent claim.<br/>
Classic editor and Yaml file.<br/>
Azure Table storage vs Azure CosmosDB<br/>
Azure Queue Vs Azure service bus<br/>
Event grid, event hub, Service Bus<br/>
Application Gateway vs Load Balancer<br/>
https://drive.google.com/drive/folders/12sFurrOhJyAqysoJAv4FClotVZXsHFUO?usp=sharing



![image](https://user-images.githubusercontent.com/43515480/236380892-689708ca-ece3-4a65-a420-2bf6b4ed70f5.png)

1. Microsoft Azure- PAAS - Azure VMs, Azure Storage Web Apps, Azure functions , Logic Apps, Azure Service bus<br/>
2. Azure AD and identity management <br/>
3. Azure SQL Database / COSMOS DB/MySql <br/>
4. Azure Storage : File, Blob etc.. <br/><br/>
5. DevOps Git / Azure DevOps/Jenkins <br/>
6. Dockers and Containers <br/>
7. Transformation tools and services for ex: Azure migration services 
8. Certifications/Hands on expertise on Cloud platforms Azure. Good to have: 1. Azure IAAS: Azure VMs, VNET, Gateways, Firewalls, Load balancers, Azure Front Door, Radish Cache 2. Azure Data analytics solutions: Synapse, ADF , ML and cognitive solutions .<br/>
• Hands On expereince in Azure Solutions implementating Azure VM, Storage, Web Apps, Azure functions , Logic Apps etc. and help team members to resolve technical issues <br/>
• Understand end to end requirements, perform code implementations, Code reviews, Code configurations , Deployments and update documentation LLDs. <br/>
• Source code configurations branching, merging and handling code conflicts <br/>
• Exposure to DevOps CI-CD using Azure DevOps/Bitbucket/Jenkins etc. <br/>
• Exposure \ Knowledge of transformation from on-premis to Azure hosted solutions<br/><br/>
![image](https://user-images.githubusercontent.com/43515480/236380900-6f94f504-0674-4ceb-a98e-9a946b6069fe.png)
![image](https://user-images.githubusercontent.com/43515480/236380909-f244debf-1222-4c6c-b8ff-16ed51ca6916.png)
![image](https://user-images.githubusercontent.com/43515480/236380915-4209a859-6a44-49eb-b2f3-9fb7d8bbafcd.png)
![image](https://user-images.githubusercontent.com/43515480/236380940-d3f44989-1e91-484a-9f12-2b2b95deb47d.png)
![image](https://user-images.githubusercontent.com/43515480/236380942-6c851c37-89ec-44d2-86a1-ee62ffaecf4c.png)
![image](https://user-images.githubusercontent.com/43515480/236380955-a658197e-dbce-4c5b-a669-2a6f0f0b9099.png)
![image](https://user-images.githubusercontent.com/43515480/236380968-c8c46f4a-dc07-496c-9c9d-107b1ff16357.png)
![image](https://user-images.githubusercontent.com/43515480/236380977-2ee62c25-06ca-4e5a-9786-11eb24ea3a3a.png)
![image](https://user-images.githubusercontent.com/43515480/236380982-431685a8-2aef-4809-87ef-1d42c1dcf58e.png)
![image](https://user-images.githubusercontent.com/43515480/236380996-a5378550-ae3e-44e1-8042-3c30ebb25fba.png)
![image](https://user-images.githubusercontent.com/43515480/236381004-accbc563-972e-45ac-9109-9771d670aad2.png)
![image](https://user-images.githubusercontent.com/43515480/236381014-b9ded90f-9e98-4339-ae17-04192406e31c.png)
![image](https://user-images.githubusercontent.com/43515480/236381021-3364064b-22d2-4f1b-9ae8-0996f252f78f.png)
![image](https://user-images.githubusercontent.com/43515480/236381036-a6c9b62c-cfac-4944-aed8-4d4aedd6b881.png)
![image](https://user-images.githubusercontent.com/43515480/236381044-88f51863-e7b6-4248-ac3f-950d9392d54b.png)
![image](https://user-images.githubusercontent.com/43515480/236381046-9e5080ac-d35b-4254-a9aa-995aa666fa94.png)
![image](https://user-images.githubusercontent.com/43515480/236381052-6df7c6e0-b928-49ca-a9a7-6a6f015ba475.png)
![image](https://user-images.githubusercontent.com/43515480/236381061-496c4482-3f17-4318-9f00-527ab53f159f.png)
![image](https://user-images.githubusercontent.com/43515480/236381064-95bf091d-bf5c-43b8-bc2e-d4b173d9d2e3.png)
![image](https://user-images.githubusercontent.com/43515480/236381071-6192e791-4efd-49ee-918c-d27e1a6ff9ad.png)

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
![image](https://user-images.githubusercontent.com/43515480/236381103-af3f329a-7ced-493d-a766-37f0ef93d074.png)
![image](https://user-images.githubusercontent.com/43515480/236381110-f1c1cd93-f85f-4c45-94f7-e73e38924de0.png)
![image](https://user-images.githubusercontent.com/43515480/236381116-8b0d809a-fc21-4279-9229-e485242b68d7.png)
![image](https://user-images.githubusercontent.com/43515480/236381122-0a7ae9c0-e87b-4b1d-a8d7-d68b209628c8.png)
![image](https://user-images.githubusercontent.com/43515480/236381127-272a5e77-b439-40c4-bec8-fc5e0057a8d2.png)
![image](https://user-images.githubusercontent.com/43515480/236381141-60cd37a1-bbf3-4a11-acc0-be308526fb6b.png)
![image](https://user-images.githubusercontent.com/43515480/236381146-b239fa6f-7435-466e-8c9f-e261dbfd87d9.png)
![image](https://user-images.githubusercontent.com/43515480/236381154-f8af9f92-8db3-4984-b55a-2dd77184ce14.png)
![image](https://user-images.githubusercontent.com/43515480/236381164-6c4effc4-6db0-4f3f-98b3-892d816a43f9.png)
![image](https://user-images.githubusercontent.com/43515480/236381175-c7a35ab7-aca0-4826-ae1c-64f1e4d34755.png)
![image](https://user-images.githubusercontent.com/43515480/236381202-432b6240-027f-4e55-b021-3a7857991b2d.png)
![image](https://user-images.githubusercontent.com/43515480/236381213-4026bde9-ff79-4e4a-b779-37cbe88c0ff0.png)
![image](https://user-images.githubusercontent.com/43515480/236381225-c97080a8-2e01-4295-a234-781bf96885d1.png)
![image](https://user-images.githubusercontent.com/43515480/236381230-6d1ff992-218a-4a1f-8ccf-99170c6b7e35.png)


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

![image](https://user-images.githubusercontent.com/43515480/235572969-8d51936e-0194-4879-9325-1837f2740516.png)

Multiple subscription
https://stackoverflow.com/questions/64120870/azure-devops-deployment-to-multiple-subscription

![image](https://user-images.githubusercontent.com/43515480/235573433-e917395c-33b7-4480-895f-cb93757faf1b.png)

Secure web app
https://learn.microsoft.com/en-us/azure/active-directory/develop/howto-create-service-principal-portal
![image](https://user-images.githubusercontent.com/43515480/235573864-3facb326-a792-4ead-a728-850c6c5e1ae0.png)

![image](https://user-images.githubusercontent.com/43515480/235573884-1371ac2f-f86c-4a27-b574-433e38ef5044.png)

https://learn.microsoft.com/en-us/answers/questions/661339/add-list-of-users-as-member-to-azure-ad-group-via

![image](https://user-images.githubusercontent.com/43515480/235575179-4216b2f3-017a-4bcf-b0ff-d49947a45c56.png)

Azure Policy
![image](https://user-images.githubusercontent.com/43515480/235575575-b6462550-62c3-41c3-95ff-ae0babaa130a.png)
![image](https://user-images.githubusercontent.com/43515480/235579895-2ab0169c-b181-4661-a634-bd8b796da1b4.png)
![image](https://user-images.githubusercontent.com/43515480/235580099-ca327c9d-614a-423b-b7a3-7d07f75ced44.png)

![image](https://user-images.githubusercontent.com/43515480/235580143-03e52818-ad77-4dfa-a4ba-2c7a0d385446.png)
![image](https://user-images.githubusercontent.com/43515480/235580286-499cbe4e-060b-488d-8212-813ef1a2ffba.png)

![image](https://user-images.githubusercontent.com/43515480/235580374-6d4d6b2c-ff0c-45e8-bfee-5cf3a077cfc0.png)

![image](https://user-images.githubusercontent.com/43515480/235580400-75775a22-70e1-49a6-a031-5842be7cd296.png)

![image](https://user-images.githubusercontent.com/43515480/235580461-5bad69b9-039f-48a2-a039-6b95670fa31b.png)

Azure DevOPs step by step:
https://github.com/dotnet/docs/blob/main/docs/architecture/devops-for-aspnet-developers/cicd.md

Azure Application gateway SSL offloading
SSL offloading is a process in which SSL (Secure Sockets Layer) or TLS (Transport Layer Security) encryption and decryption tasks are offloaded from a web server to a specialized device such as a load balancer, reverse proxy, or application delivery contro

https://www.youtube.com/watch?v=0OLW9R87__8

![image](https://user-images.githubusercontent.com/43515480/236263808-499beecd-7b05-48e8-97a9-9421f2710f06.png)

Application gateways, on the other hand, are designed to handle HTTP and HTTPS traffic specifically. They can perform more advanced routing and load balancing functions than a basic load balancer, such as routing traffic based on URL paths or cookie values. In addition to load balancing, application gateways can also perform functions such as SSL offloading, content caching, and web application firewall (WAF) protection.

![image](https://user-images.githubusercontent.com/43515480/236267199-0929a9fc-c317-406c-ba59-9f398a5f582b.png)
https://www.youtube.com/watch?v=8NrO8nHHPDs

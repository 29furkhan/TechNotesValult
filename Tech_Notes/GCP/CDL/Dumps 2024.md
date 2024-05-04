##### Question - 1
>`Statement: `
>`Your company uses the GCP house secure customer data. You are a data security manager and want to control which persmissions to be granted to users who handle the data. Which of the following you should do to control-permission`
>
`1. Assign roles`
`2. User access lists`
`3. User authentication roles`
`4. Assign resources`
>
>`Answer: 1. Assign roles`
>`Explanation: In order to assign permissions you should assign roles. "Cloud Identity" allows you manage and authorize "Users accounts".`
>
>`Why not others?`
>`2 Use access list: Customize access to specifics object within bucket, not managing permission.`
>`3 User authentication roles: Authentication is not valid here, becaise individual roles #1 includes authentication/ 2FA.`
>`4. Resources is not related to user permission, it is folder/ projects.`

****
##### Question - 2
>`Statement: `
>`Which of the following GCP product can be used to visialize data? (2 Answers)`
>
`1. Cloud Firestore`
`2. DataProc`
`3. DataLab`
`4. Data Studio`
>
>`Answer: 3 and 4.`
>`Tags: #DataLab, #DataStudio`
>`Explanation: #DataLab allows explore, interactive analysis, transform data, visualize using Python/ SQL. Pre-installed Jupyter notebook. #DataStudio allows charts like line, pie, bar, maps, etc.`
>
>`Why not others?`
>`1 Cloud Firestore: NoSQL document oriented database service.`
>`2 DataProc: Tool for processing and analyzing data. `
****
##### Question - 3
>`Statement: `
>`You are migrating workloads to cloud. Goal is to serve customers worldwide ASAP. According to local regulation, certain data is to be stored in specific geographical area. You need to design architecture and deployment for your workloads. What should you do?`
>
`1. Select a public cloud provider that is only active in the required geographical area. `
`2. Select a private cloud provider that globally replicates data storage for fast data access.`
`3. Select a public cloud provider that guarantees data location in the required geo area. `
`4. Select a private cloud provider that is only active in the required geo area.`
>
>`Answer: 3.`
****
##### Question - 4
>`Statement: `
>`You are an IT manager who wants to reduce the cost and labor required for manual application modernization using google cloud. You need to decide between adapting compute engine or migrate to anothos and need to explain the differences  between 2 solutions to Management. What would you explain?`
>
`1. Migrate for compute engine charges for transferring data to cloud, while anothos does not. `
`2. Migrate for anthos migrate to containers, and migrate for compute engine migrates to VM.`
`3. Migrate to compute engine needs complex deployment and setup, while anothos needs only life and shift migration.`
`4. Migrate for anthos requires manual OS upgrades, and migrate to compute engine is fully managed.`
>
>`Answer: 2`
>`Tags: #Anthose, #Compute`
>
>`Explanation: Migrate to containers is anthos, and to VMs is Computer engine.`
>
>`Why not others?`
>`1. -> Data injest is free in Google cloud so #1 stands false.`
>`3. -> Migrate to Compute engine is often lift and shift operations, while anthos migration is more complex.`
>`4. Migrate to anthos do not require manual OS upgrades and also migrate to compute engine is not fully managed solution. You get both options in VMs Managed and Unmanaged.`
****
##### Question - 5
`Tags: #VM, #Compute, #Committed Use Contract`
- `Statement`
	- `Your organization needs large amount of extra computing power in next 2 weeks. After those 2 weeks, need of additonal resouces will end. Which is a cost effective approach.`
- `Options`
	- `1. Use a committed discount to reserve a very powerful VM. `
	- `2. Purchase a very powerful physical computer.`
	- `3. Start a very powerful VM without using a committed discount.`
	- `4. Purchase multiple physical computers and scale workloads across them.`
- `Answer`
	- `#3 Start a very powerful VM without using a committed discount.`
- `Explanation`
	* `When you purchase a "committed use contract" you purchase compute engine resources at a discounted pricein return of paying for those resources for 1 year or 3 years, hence #3 is better options since we do not need it after 2 weeks. `
****
##### Question - 6
`Tags: #BigQuery`
- `Statement`
	- `Which of the following operations on BigQuery reduce the TOC for customers (3 answers)`
- `Options`
	- `1. Queries retrieve results from cache.`
	- `2. Batch loading data into BigQuery from local files.`
	- `3. Running a query on an external data source from BigQuery.`
	- `4. Deleting a table, view, individual table partitions, and UDFs.`
- `Answer`
	- `#1, #3, and #4 are correct.`
- `Explanation`
	* `Customers are not charged for queries that fetches results from cache.`
	* `They are not charged for loading data from local files/ delete the files, partitions, UDFs.`
	* `Customers are charged for the amount of data processed for running a query on external systems.`
****
##### Question - 7
`Tags: #Cost Management, #TOC`
- `Statement`
	- `Your organization need to plan it's cloud infra expenses. Which of the following your organization should do?`
- `Options`
	- `1. Review cloud resource costs frequently, as it often change based on use.`
	- `2. Review cloud resource costs annually, as part of budget meeting.`
	- `3. If your organization only uses cloud resources, infra costs are no longer part of your overall budget.`
	- `4. Invite fewer people to the meeting than you invited for on-prem planning.`
- `Answer`
	- `#1 - Review cloud resource costs frequently, as it often change based on use.`
- `Explanation`
	* `Variable nature of cloud resources and their costs, spending must be monitored and controlled on an ongoing basis.`
****

##### Question - 8
`Tags: SRE`
- `Statement`
	- `How can a software developer contribute Site reliability engineering within an organization?`
- `Options`
	- `1. By allocating problem solving tasks to operations teams.`
	- `2. By manually configuring prod systems.`
	- `3. By focusing imlementing automation.`
	- `4. By creating static solution in order to avoid failure.`
- `Answer`
	- `#3 - By focusing on automation.`
- `Explanation`
	* `SRE focus on hiring s/w engineers that avoids manual work.`
	* `SRE automates prod systems`
	* `SRE focuses on dynamic solutions.`
****

##### Question - 9
`Tags: #Security, #Security Command Center, #Compliance Report Manager`
- `Statement`
	- `The OS of some of your organizations VMs may have a security vulnerability. How can your organization most effectively identify all virtual machines that do not have the latest secutrity update?`
- `Options`
	- `1. View "Security Command Center" to identify VMs running vulnerable disk images.`
	- `2. View "Compliance Report Manager" to identify and download a recent PCI audit.`
	- `3. View "Security Command Center" to identify VMs started more than 2 weeks ago.`
	- `4. View "Compliance Report Manager" to identify and download a recent SOC 1 audit.`
- `Answer`
	- `#1 - View "Security Command Center" to identify VMs running vulnerable disk images.`
- `Explanation`
	* `Following is all SCC does.`
		* `Centralized visibility and control`
		* `Misconfigurations and vulnerabilities check.`
		* `Reports and maintain on compliance.`
		* `Detects threats targetting GCP assets.`
****


##### Question - 10
`Tags: #IoT, #IoT Core, #Traffic Director`
- `Statement`
	- `You are a manager for an energy company that is collecting the unstructured key:value data in the form of usage reports from energy meters and home appliance censors. Your IT needs to securely connect and manage its IT devices. Which of the following solutions would help you to connect and manage the IoT devices securely. `
- `Options`
	- `1. IoT core`
	- `2. Traffic director`
	- `3. IoT Hub`
	- `4. IoT portal`
- `Answer`
	- `#1 -> IOT Core`
- `Explanation`
	* `IoT Core: Fully managed, allows connect and manage IoT devices securely.`
	* `Traffic director: Load balancing across clusters.`
	* `IoT Hub and IoT portal is not a GCP product.`
****


##### Question - 11
`Tags: #BOYL, #Pay as you go`
- `Statement`
	- `You are currently managing the workloads running on "Windows server" for which your company own licenses. These workloads are only needed durint working hours, allowing you to shut down the instances during the weekend. Your windows server licneses are due renewal in a month, and you want to optimize your license cost. What should you do?`
- `Options`
	- `1. Renew your licences for an additonal period for 3 years. Negotiate a cost reduction with your current hosting provider to reduce infra cost when not in use.`
	- `2. Renew licenses for additonal period of 2 years. Negotiate cost reduction by committing to an automatic renewal of licenses at the end of 2 year period.`
	- `3. Migrate the workload to the Compute Engine with bring your own license (BOYL) model.`
	- `4. Migrate the workload to the Compute Engine with "Pay as you go" model.`
- `Answer`
	- `#3 -> Migrate the workload to the Compute Engine with bring your own license (BOYL) model.`
- `Explanation`
	* `Bringing your licenses that have specific hardware requirements require you to use BOYL model and not pay as you go.`
****


##### Question - 12
`Tags: #Data Fusion, #Cloud Composer, #DataCatalog, #DaraProc`
- `Statement`
	- `An organization wants to use  a Google cloud service for a time-restricted project with the folloing guidelines.`
		- `Developers should be free from ifra management.`
		- `Chosen service should be able to clean, prepare, blend, transform and transfer data. `
	- `Which of the following Google cloud services should organization use?`
- `Options`
	- `1. Cloud Data Fusion.`
	- `2. Cloud Composer.`
	- `3. Data Catalog.`
	- `4. DataProc.`
- `Answer`
	- `#1 -> Cloud Data Fusion`
- `Explanation`
	* `Cloud data fusion: Fully managed, helps build, and manage data pipelines supporting clean, integrate, blend, transfer, transform, etc.`
	* `Cloud Composer: Created, schedule, montior and manage workflows. Not ideal for integration of data.`
	* `Data Catalog: Fully managed, Metadata managedment tool and not integration, etc.`
	* `DataProc: Batch processing, querying, streaming.`
****


##### Question - 13
`Tags: #Zones, #Regions`
- `Statement`
	- `Your organization runs a distributed application in the compute engine VM. Your organization needs redundancy, but also needs extremely fast communication(less then 10 ms) between the parts of the application in different VMs.`
	- `Where should your org to locate these VMs?`
- `Options`
	- `1. Single zone, single region.`
	- `2. Different zones, single region.`
	- `3. Multiple regions, one zone per region to be used.`
	- `4. Multiple regions, multiple zones per region to be used.`
- `Answer`
	- `#2 -> Different zones, single region.`
- `Explanation`
	* `Multi-region arch provides higer availability. `
****


##### Question - 14
`Tags: #IaaS`
- `Statement`
	- `You are a project manager managing a client project intended to enhance customer experience in BFSI by providing smart communication solutions. As the solution is being developed for BFSI industry, your client has indicated that they prefer to have complete control of data and OS, alongwith runtimes and middlewares. Which of the following offerings would you suggest to your client?`
- `Options`
	- `1. IaaS.`
	- `2. PaaS.`
	- `3. SaaS.`
	- `4. FaaS.`
- `Answer`
	- `#1 IaaS.`
****


##### Question - 15
`Tags: #Compute`
- `Statement`
	- `An organization decides to migrate their on-prem env to cloud. They need to determine which resource components still need to be assigned ownership. `
	- `Which 2 functions does a public cloud provider own?`
- `Options`
	- `1. Hardware maintainence.`
	- `2. Infra architecture.`
	- `3. Infra deployment automation.`
	- `4. Hardware capacity management.`
	- `5. Fixing application security issues.`
- `Answer`
	- `#1 and #4. Hardware maintainence, Hardware capacity management.`
- `Explanation`
	* `When considering IaaS, at minimum cloud provider is responsible for Hardware, boot, kernel, Storage, etc.`
****


##### Question - 16
`Tags: #Disaster Recovery, #Cold, #Hot, #Live, #Warm`
- `Statement`
	- `Your client is a banking company that is designing a desaster recovery plan for it's historical compliance oriented data. Speedy access to data is not requirement of the plan.`
	- `Which of the following disaster recovery pattern would you suggest?`
- `Options`
	- `1. Cold.`
	- `2. Warm.`
	- `3. Hot.`
	- `4. Live.`
	
- `Answer`
	- `#1 -> Cold`
- `Explanation`
	* `Cold: No active resources (backup ones), timeely process to recover. Cheapest.`
	* `Warm: Partially configured and ready to use resources but not fully operational. Balance between cost and recovery time.`
	* `Hot: Fully operational and mirrors site. High cost.`
	* `Live: Continuous replication, so data and application sync. Fastest recovery and costliest. Immediate failover. `
****


##### Question - 17
`Tags: #vCPUs, #PreemptibleVMs`
- `Statement`
	- `You are a program manager within a SaaS company that offers rendering software for animation studios. Your team needs the ability to allow scenes to be scheduled at will and to be interupted at anytime to restart later. Any individual scene rendering takes less than 12 hours to complete, and there is no SLA for the completion time for all scenes. Results will be stored in a global Cloud storage bucket. The compute resources are not bound to any single geographical location. This software needs to run on Google Cloud in a const-optimized way.`
	- `What should you do?`
- `Options`
	- `1. Deploy the application on Compute Engine using preemptible instances.`
	- `2. Develop the application so it can run in an unmanaged instance group.`
	- `3. Create a reservation for minimum number of Compute Engine instances you will use.`
	- `4. Start more instances with fewer virtual centralized processing units (vCPUs) instead of fewer instances with more vCPUs.`
	
- `Answer`
	- `#1 -> Deploy the application on Compute Engine using preemptible instances.`
- `Explanation`
	* `Preemptible VMs are cost-effective instances that can be used for short-lived and non-critical workloads. Lower cost. `
****



##### Question - 18
`Tags: #CID, #Hybrid Cloud`
- `Statement`
	- `A global insurance and financial company is planning to adopt cloud services to bring down infrastructure costs. The cloud deployment model adopted must meet all relevant international data security regulations. To ensure regulation compliance, the customer data with Client Identifying Data (CID) should be stored on-premises. Data without Client Identifying Data (CID) will be stored on the public cloud. `
	- `Which of the following Cloud deployment models would you recommend?`
- `Options`
	- `1. Public cloud.`
	- `2. Private cloud.`
	- `3. Community cloud.`
	- `4. Hybrid cloud.`
	
- `Answer`
	- `#4`
- `Explanation`
	* `Hybrid has both public and on-prem services. `
	* `Private cloud is not cost effective as it is solely for single organization.`
****



##### Question - 19
`Tags: #VMs`
- `Statement`
	- `Your manager wants to restrict communication of all virtual machines with internet access; with resources in another network; or with a resource outside Compute Engine. It is expected that different teams will create new folders and projects in the near future. `
	- `How would you restrict all virtual machines from having an external IP address?`
- `Options`
	- `1. Define an organization policy at the root organization node to restrict virtual machine instances from having an external IP address`
	- `B. Define an organization policy on all existing folders to define a constraint to restrict virtual machine instances from having an external IP address`
	- `C. Define an organization policy on all existing projects to restrict virtual machine instances from having an external IP address`
	- `D. Communicate with the different teams and agree that each time a virtual machine is created, it must be configured without an external IP address`
	
- `Answer`
	- `#1 -> Define an organization policy at the root organization node to restrict virtual machine instances from having an external IP address. `
- `Explanation`
	* `Cannot say #B because more folders can be created in future and also not #C since more projects can come. We need to make a norm so #A.`
****



##### Question - 20
`Tags: #Migration`
- `Statement`
	- `A company that stores somes of it's customer credit card data on premises is migrating the data to cloud. Prior to the migration the organization wants to understand how google will store and process customer data?`
	- `Which of the following aspects of the google cloud platform should organization learn about?`
- `Options`
	- `1. Availability.`
	- `2. Security.`
	- `3. Compliance.`
	- `4. Privacy.`
	
- `Answer`
	- `#4 -> Privacy`
- `Explanation`
	* `When migrating data to cloud, organization is owner of data. Google process and transforms it but it remains private. `
****



##### Question - 21
`Tags: #Migration`
- `Statement`
	- `Your MNC has servers that are running mission critical workloads on premises around the world. You want to be able to manage the workload consistently and centrally and "stop managing infra".`
	- `What should you do?`
- `Options`
	- `1. Migrate the worloads to the public cloud.`
	- `2. Migrate to central office building.`
	- `3. Migrate the workloads to the multiple local co-location facilities.`
	- `4. Migrate the workloads to multiple private clouds.`
- `Answer`
	- `#1`
- `Explanation`
	* `Since mission critical load, we go with public clouds. `
****



##### Question - 22
`Tags: #CloudBuild`
- `Statement`
	- `Cloud build can deploy to which of these services?`
- `Options`
	- `1. Kubernetes.`
	- `2. App Engine.`
	- `3. Cloud Functions.`
	- `4. Cloud Build can deploy to all these services.`
- `Answer`
	- `#4`
- `Explanation`
	* `Cloud Build can deploy to all #1, #2, and #3.`
	* `Cloud Build: Fully managed CI/CD platform, automating process of building, tetsing, and, deploying software applications.`
****



##### Question - 23
`Tags: #IAP, #VPC`
- `Statement`
	- `Your organizations stores highly sensitive data on premises that cannot be sent over the public internet. The data must be processed both on-premises and in the cloud. `
	- `What your organization should do?`
- `Options`
	- `1. Configure Identity Access Proxy (IAP) in your google cloud VPC n/w.`
	- `2. Create a cloud VPN tunnel between Google cloud and your data center.`
	- `3. Order a partner interconnect connection with your n/w provider.`
	- `4. Enable private google access in your Google cloud VPC n/w.`
- `Answer`
	- `#3 -> Order a partner interconnect connection with your n/w provider. `
- `Explanation`
	* `Since you cannot pass the data over internet, use #C. After the service provider provisions your connection, you can start passing traffic between your n/ws by using service provider's n.w.`
****



##### Question - 24
`Tags: #SRE, #SLOS, #Cloud Logging, #Cloud Monitoring`
- `Statement`
	- `Your organization has planned to implement Site Reliability Engineering (SRE) best practices. You are tasked with configuring application-level monitoring and monitoring service-level objectives (SLOS) for applications and trigger alerts when SLOS are violated. `
	- `Which of the following products should you choose for these tasks?`
- `Options`
	- `1. Error Reporting. `
	- `2. Cloud Logging. `
	- `3. Cloud Monitoring.`
	- `4. Cloud Trace.`
- `Answer`
	- `#3 -> Cloud Monitoring. `
- `Explanation`
	* `Cloud monitoring`
		* `Collecting system metrics`
		* `Enabling best SRE practices.`
		* `Custom dashboards`
		* `Adding alerts`
****



##### Question - 25
`Tags: #CloudRun, #ContainerRegistry`
- `Statement`
	- `Your company's development team is building an application that will be deployed on Cloud Run. You are designing a CI/CD pipeline so that any new version of the application can be deployed in the fewest number of steps possible using the CI/CD pipeline you are designing.` 
	- `You need to select a storage location for the images of the application after the Cl part of your pipeline has built them. What should you do?`
- `Options`
	- `1. Create a compute engine image containing the application. `
	- `2. Store the images in Container Registry. `
	- `3. Store the images in cloud storage.`
	- `4. Create a compute engine disk containing the application.`
- `Answer`
	- `#2 -> Store the images in Container Registry `
- `Explanation`
	* `Container Registry: Allows users to store, manage, and distribute docker container images securely.`
****



##### Question - 26
`Tags:#Customer Support Plans`
- `Statement`
	- `You are a manager with an e-retail website. The company has opted for the standard support customer care plan. The number of users has surged recently, and the comopany has realized the need of responses to it's priority P1 cases in 1 hour while also maintaining control of cost.` 
	- `Which of the following support plans you should opt for?`
- `Options`
	- `1. Basic.`
	- `2. Standard.`
	- `3. Enhanced.`
	- `4. Premium.`
- `Answer`
	- `#3 -> Enhanced.`
- `Explanation`
	* `Enhance support plan includes:`
		* `1 hour response time for P1.`
		* `24/7 for P1 and P2.`
		* `Multi-channel support.`
		* `Technical experts and 3rd party technology support.`
****



##### Question - 27
`Tags:#IaaS, #PaaS, #SaaS`
- `Statement`
	- `Each of the 3 cloud service models - IaaS, PaaS, SaaS - Offers benefits between flexibility and levels of management by the cloud provider and the customer.` 
	- `Why would SaaS be right choice of service modes?`
- `Options`
	- `1. You want a balance between flexibility and levels of management by cloud provider and the customer.`
	- `2. You want to minimize the level of management by the customer.`
	- `3. You want to maximize the flexibilit to the customer.`
	- `4. You want to be able to shift your emphasis between flexibility and management by cloud provider as business change needs.`
- `Answer`
	- `#2 -> You want to minimize the level of management to the customer.`
- `Explanation`
	* `SaaS offloads all infra and application management to the SaaS vendor.`
****



##### Question - 28
`Tags:#Apigee, #API`
- `Statement`
	- `Which of the following are benefits of Apigee? (3 answers)`
- `Options`
	- `1. Ability to predict API traffic patten.`
	- `2. Ability to make backend service visible.`
	- `3. Ability to modernize legacy services via RESTful API.`
	- `4. The ability to analyze and record business metrics.`
- `Answer`
	- `#1, #3, and #4`
- `Explanation`
	* `#1, #3, and #4 them all are Aigee's benefits.`
****




##### Question - 29
`Tags: #Containers`
- `Statement`
	- `As organization increases its release velocity, the VM based application upgrades take long time to perform rolling updates due to OS boot times. You need to make application deployments faster.`
	- `What should your org do?`
- `Options`
	- `1. Migrate your VM to the cloud.`
	- `2. Convert your application to the containers.`
	- `3. Increase the resources of your VM.`
	- `4. Automate your upgrade rollouts.`
- `Answer`
	- `#2 -> Application to containers.`
- `Explanation`
	* `Specific issue is OS boot time, so taking application to container is right choice as no OS boottime problem.`
****



##### Question - 30
`Tags: #Infrastructure Security Layer`
- `Statement`
	- `Which of the following google infra security layers provides DDoS protection?`
	- `What should your org do?`
- `Options`
	- `1. Operational security.`
	- `2. Internet communications.`
	- `3. Storage Services.`
	- `4. User identity.`
- `Answer`
	- `#2 -> Internet communications.`
- `Explanation`
	* `Google has 6 infra security layers:`
		* `Operational security:`
			* `Intrusion detection, insider risk addressed.`
		* `Internet communications.`
			* `DDoS protection.`
		* `Storage Services`
			* `Encryption and deletion of data.`
		* `User Identity.`
			* `Login abuse protection.`
		* `Service Deloyment.`
		* `Hardware Infrastructure.`
****



##### Question - 31
`Tags: #Active Directory, #Authentication, #IAM, #SSO`
- `Statement`
	- `Your organization uses Active directory to authenticate users. Users' google access must be removed when their active directory account is terminated?`
	- `How should your organization to meet this requirement?`
- `Options`
	- `1. Configure 2 factor authentication in Google Domain.`
	- `2. Remove the google account from all IAM policies.`
	- `3. Configure BeyodCord and Identity aware proxy in the google domain.`
	- `4. Configure single sign-on google domain.`
- `Answer`
	- `#4 -> Single sign on.`
- `Explanation`
	* `SSO - allows user to login with single ID and password.`
****



##### Question - 32
`Tags: #Replication`
- `Statement`
	- `You are a project manager for a global company that offers high-resolution documentary film editing services. Your team of content editors in New York and London needs to collaborate on editing projects that are located in Cloud Storage buckets. The maximum time to wait for a video's availability must be within a target time of "15 minutes", with minimal loss exposure. `
	- `Which of the following storage configurations should you choose?`
- `Options`
	- `1. Single region`
	- `2. Dual region.`
	- `3. Multi-region with default replication.`
	- `4. Dual region with turbo replication.`
- `Answer`
	- `#4 -> Dual region with turbo replication.`
****



##### Question - 33
`Tags:`
- `Statement`
	- `Your company has recently aquired 3 growing startups in 3 diff countries. You want to reduce overhead in infra management and keep your costs low without sacrificing security and quality of your service to your customers?`
	- `How should you meet the requirements?`
- `Options`
	- `1. Host all your subsidiaries' services onprem together with your existing ones.`
	- `2. Host all your subsidiaries' services on cloud  together with your existing ones.`
	- `3. Build a homogeneous infra at each subsidiary, and invest in training their engineers.`
	- `4. Build a homogeneous infra at each subsidiary, and invest in hiring their engineers.`
- `Answer`
	- `#2 -> Host on cloud with existing services.`
- `Explanation`
	* `Maintainence and cost is cheaper and management is easier when both on same env.`
****



##### Question - 34
`Tags:#Migration, #Storage Transer Service`
- `Statement`
	- `A startup is planing to adopt Google cloud services. As a first step, the company plans to migrate its data to google cloud. `
	- `Which of the following should the company use to migrate over 1TB of data from a private data center to the cloud while adhering to a strict timeline of 1-2 days and accomodating available bandwidth in order to meet the project deadline?`
	- `How should you meet the requirements?`
- `Options`
	- `1. Stroage transfer service.`
	- `2. gsutil.`
	- `3. Transfer appliance.`
	- `4. Migrate for anthos and GKE.`
- `Answer`
	- `#A -> Storage transfer service`
- `Explanation`
	* `#A allows:`
		* `Data transfer from private to cloud`
		* `10 Gbps`
****



##### Question - 35
`Tags:#Storage, #Standar Storage, #Coldline Storage`
- `Statement`
	- `What is the difference between Standard and Coldline storage?`
- `Options`
	- `1. Coldline is for data where slow transer rate is acceptable.`
	- `2. Different durability guarantees.`
	- `3. Both use different APIs.`
	- `4. Coldline storage is for infrequently accessed data.`
- `Answer`
	- `#4 -> Coldline storage is for infrequently accessed data.`
- `Explanation`
	* `Difference is based on how frequently data is acce`
	* `#1 is false, #2 and #3 false too.`
****



##### Question - 36
`Tags:#Coldline, #Nearline, #Standard, #Archive`
- `Statement`
	- `A fitness application company is collecting the health data of its users is adding approximately 50 TBS of data every month. The data is expected to grow to 200+ TB every year. Users are primarily concerned with the last 30 days of data and will wait for data retrieval if data is older than 30 Days. The company decided that they will now store the infrequently accessed data older than 30 days to minimize the cost, as this data is typically accessed at max once per quarter or less. Which storage option would be best suited to store infrequently accesses data?`
- `Options`
	- `1. Standard.`
	- `2. Nearline.`
	- `3. Coldline.`
	- `4. Archive.`
- `Answer`
	- `#C -> Coldline.`
- `Explanation`
	* `Coldline -> Keep infrequently accessed data, read max once per quarter.`
	* `Standard -> Hot data. Most frequently accessed ones.`
	* `Nearline -> Keep data that can be read/ changed once per month.`
	* `Archive -> Store archive data required for legal, regulatory, and Disaster Recovery reasons.`
****



##### Question - 37
`Tags:#Cloud`
- `Statement`
	- `What would you provide near-unlimited availability of computing resources without requiring your organization to procure and provision new equipment?`
- `Options`
	- `1. Public cloud.`
	- `2. Containers.`
	- `3. Private cloud.`
	- `4. Microservices.`
- `Answer`
	- `#A -> Public cloud.`
****



##### Question - 38
`Tags:#Private, #Public, #Hybrid, #Onsite datacenter`
- `Statement`
	- `Which of the following defines a private cloud?`
- `Options`
	- `1. Collection of resources not shared with general public.`
	- `2. Collection of virtual on-demand services offered to public.`
	- `3. Collection of services shared between private and cloud users.`
	- `4. Colleciton of resources that are isolated on premises for use by an organization.`
- `Answer`
	- `#A -> Not shared with general public.`
- `Explanation`
	* `#1 -> Private cloud.`
	* `#2 -> Public cloud.`
	* `#3 -> Hybrid cloud.`
	* `#4 -> Onsite datacenter.`
****




##### Question - 39
`Tags:#Cloud Functions`
- `Statement`
	- `You are a program manager for a team of developers who are building an event-driven application to allow users to follow one another's activities in the app. Each time a user adds himself as a follower of another user, a write occurs in the real-time database.`
	- `The developers will develop a lightweight piece of code that can respond to database writes and generate a notification to let the appropriate users know that they have gained new followers. The code should integrate with other cloud services such as Pub/Sub, Firebase, and Cloud APIs to streamline the orchestration process. The application requires a platform that automatically manages underlying infrastructure and scales to zero when there is no activity.`
	- `Which primary compute resource should your developers select, given these requirements ?`
- `Options`
	- `A. Google Kubernetes Engine`
	- `B. Cloud Functions`
	- `C. App Engine flexible environment` 
	- `D. Compute Engine`
- `Answer`
	- `#B -> Cloud Functions.`
- `Explanation`
	* `Cloud Functions: `
		* `Serverless compute service`
		* `Event-driven`
		* `Designed to execute short-lived functions in response to various events, such as database writes, file uploads, HTTP requests, and Pub/Sub messages.`
****
##### Question - 40
`Tags:#Costing`
- `Statement`
	- `To optimize the company's Google Cloud spend, the management committe team wants an at a glance waterfall overview of their monthly costs and savings. Which of the following should you use to provide this information to the management team?`
- `Options`
	- `A. Cost breakdown reports.`
	- `B. Budget notifications.`
	- `C. Cost table reports.` 
	- `D. Priciing table reports.`
- `Answer`
	- `#A -> Cost breakdown reports.`
- `Explanation`
	* `Cost breakdown reports: `
		* `#A -> At a glance waterfall overview of monthly costs and savings.`
		* `#B -> Realtime status report, not to gain insights of montly costs.`
		* `#C -> access and analyze invoice and statements, not an optimal method for costing.`
		* `#D -> access SKUs prices for Google's cloud services, not good to give high overview of costs.`
****
##### Question - 41
`Tags: #BigTable`
- `Statement`
	- `Your organization is developing an application that will capture a large amount of data from millions of different sensor devices spread all around the world. Your organization needs a database that is suitable for wordlwide, highspeed data storage of a large amount of unstructured data.`
	- `Which google cloud product should your organization choose?`
- `Options`
	- `A. Firestore`
	- `B. Cloud Data Fusion.`
	- `C. Cloud SQL.` 
	- `D. Cloud BigTable.`
- `Answer`
	- `#D -> BigTable.`
- `Explanation`
	* `BigTable: `
		* `Fully managed, highly scalable.`
		* `High performance, NoSQL DB service designed for large scale applications that require low-latency and high throughput data storage.`
****
##### Question - 42
`Tags: #Storage Services`
- `Statement`
	- `Your client is a global packaging and printing company. They want to migrate to fully managed Google cloud storage solution with the following capacities.`
		- `Web content management`.
		- `File Sharing.`
		- `Media processing and rendering.`
		- `Data Analysis.`
	- `Which solution should the company use?`
- `Options`
	- `A. Archive Storage.`
	- `B. Filestore.`
	- `C. Persisten Disk.` 
	- `D. Local SSD.`
- `Answer`
	- `#B -> Filestore.`
- `Explanation`
	* `Filestore: `
		* `Fully managed, web content management, file sharing, rendering, and processing media.`
		* `Enables application migration to cloud without rewrite or re-architecht.`
****
##### Question - 43
`Tags: #DataFlow`
- `Statement`
	- `Your organization needs to build streaming data pipelines. You don't want to manage the individual servers that do the data processing in the pipelines. Instead you want a managed service that will automatically scale with amount of data to be processed.`
	- `Which google cloud product or feature should your organization choose?`
- `Options`
	- `A. Pub/ Sub.`
	- `B. DataFlow.`
	- `C. Data Catalog.` 
	- `D. Dataprep by Trif.`
- `Answer`
	- `#B -> DataFlow.`
- `Explanation`
	* `DataFlow: `
		* `Fully managed, build and run streaming pipelines.`
		* `Auto-scaling, meeting demands of data.`
****
##### Question - 44
`Tags: #Modernization, #Transformation`
- `Statement`
	- `Which of the following occurs when an organization adapts cloud technology to create and define new ways of communicating and collaborating for its customers, employees, and stakeholders.`
- `Options`
	- `A. Reduced need of security.`
	- `B. The burning platform effect.`
	- `C. Virualization of all business operations.` 
	- `D. Oganizational transformation.`
- `Answer`
	- `#D -> Organization transformation.`
****
##### Question - 45
`Tags: #Cloud Code, #Cloud Build, #CDM, #Cloud Scheduler.` 
- `Statement`
	- `Your organization is running an application in google cloud. Currently, software builds, tests, and regular deployments are done manually, but you want to reduce work for team. Your organization wants to use Google cloud managed solutions to automate your build, testing, and deployment process.`
	- `What google cloud product to be used?`
- `Options`
	- `A. Cloud Scheduler`
	- `B. Cloud Code`
	- `C. Cloud Build`
	- `D. Cloud Deployment Manager`
- `Answer`
	- `#C.`
- `Explanation`
	- `#A -> Automate execution of tasks.`
	- `#B -> An IDE plugin that enables develop, test, deploy cloud native apps from their favorite IDE.`
	- `#C ->Autmate and manage build, test, and deployment process.`
	- `#D -> IaaS enables you to create, manage, and update cloud resources.`
****
##### Question - 46
`Tags: ` 
- `Statement`
	- `Which of the following is a major cost benefit of adapting cloud native arch?`
- `Options`
	- `A. Managed services with high operational services. `
	- `B. Managed open source or open source compatible services.`
	- `C. CI/ CD.`
	- `D. Monitoring and automated recovery.`
- `Answer`
	- `#A -> Managed services with high operational services.`
- `Explanation`
	- `Managed services results in high operational savings, customer no longer responsible.`
****

##### Question - 47
`Tags: #Security Command Center` 
- `Statement`
	- `Which google cloud product can report on and maintain compliance on your entire Google Cloud organization to cover multiple projects?`
- `Options`
	- `A. Cloud Logging. `
	- `B. IAM.`
	- `C. Google Cloud Error.`
	- `D. Security Command Center.`
- `Answer`
	- `#D -> Security command center.`
- `Explanation`
	- `Security command center:`
		- `Security and risk management platofo`
		- `Centralized visibility and control.`
		- `Discover misconfig and vulnerabilities.`
		- `Report on compliance and maintainence.`
		- `Detect threat.`
****

##### Question - 48
`Tags: #Resource Manager` 
- `Statement`
	- `Organization using google cloud wants to hierarchically organize and group resources, as well as manage access control and configuration settings for container resources.`
	- `Which google product or service should the organization use?`
- `Options`
	- `A. Eventarc.`
	- `B. Artifact Registry.`
	- `C. Container Registry.`
	- `D. Resource Manager API.`
- `Answer`
	- `#D -> Resource Manager API.`
- `Explanation`
	- `#D allows programmatic management of container resources.`
****
##### Question - 49
`Tags: #VPN, #CDN, #Cloud Interconnect, #Direct Peering.` 
- `Statement`
	- `Your organization needs to establish private n/w connectivity between its on-prem nw and its workloads in google cloud. You need to be able to connect to set up the connection as soon as possible.`
	- `Which google cloud product or feature should you use?`
- `Options`
	- `A. Cloud Interconnect.`
	- `B. Direct Peering.`
	- `C. Cloud VPN.`
	- `D. Cloud CDN.`
- `Answer`
	- `#C -> #Cloud VPN.`
- `Explanation`
	- `Why not #A? It needs a physically dedicated connection.`
	- `#A -> Dedicated, high-speed connectivity between your on-premises network and Google Cloud Platform.`
	- `#B -> Direct, low-latency connections between your network and Google's edge network.`
	- `#C -> Connects your on-premises network to Google Cloud Platform over the public internet.`
	- `#D -> A content delivery network service that caches content at Google's globally distributed edge locations`
****
##### Question - 50
`Tags: #Cloud Data Loss Prevention` 
- `Statement`
	- `A credit card company has moved its applications to Google cloud. Its customer data is stored across Cloud storage, Datastore, and BigQuery and is used by applications and employees across the firm. `
	- `Which Google cloud solution should you use for the detection  and classification of the stored sensitive data?`
- `Options`
	- `A. Cloud Armer.`
	- `B. Cloud Data Loss Prevention.`
	- `C. Risk Manager.`
	- `D. Security Command Center.`
- `Answer`
	- `#B -> #Cloud VPN.`
****
##### Question - 51
`Tags: #GKE, #Firebase, #App Engine` 
- `Statement`
	- `Your organization is developing a mobile application and wants to select fully featured cloud based compute platform for it.`
	- `Which GCP product to use?`
- `Options`
	- `A. Google Kubernetes Engine.`
	- `B. Firebase.`
	- `C. Cloud functions.`
	- `D. App Engine.`
- `Answer`
	- `#B -> Firebase.`
- `Explanation`
	- `It is a google's mobile development platform.`
****

##### Question - 52
`Tags: #Cloud SQL, Cloud Spanner, Firestore.`
- `Statement`
	- `Your organization is developing a global multi-player game and requires a database that can consistently capture player statistics. The most critical requirement of the database is that it can serve information for game leaderboards and return consistent rankings at any given time across game players all over the world. The game is rapidly developing a following with almost unlimited growth in the number of players. `
	- `Which Google Cloud product should the organization choose.`
- `Options`
	- `A. Firestore.`
	- `B. Cloud Spanner.`
	- `C. Cloud SQL.`
	- `D. Bare metal.`
- `Answer`
	- `#B -> Cloud Spanner.`
- `Explanation`
	- `#A -> Scalable NoSQL DB realtime data sync.`
	- `#B -> RDBMS provides strong consistency and and high availability (99.99%).`
****

##### Question - 53
`Tags: #AppEngine, #GKE`
- `Statement`
	- `Your company has been using a shared facility for data storage and will be migrating Google cloud. One of the internal applications uses Linux custom images that needs to be migrated. `
	- `Which google cloud product should you use to maintain custom images?`
- `Options`
	- `A. App Engine flexible env.`
	- `B. Compute Engine.`
	- `C. App Engine Standard env.`
	- `D. GKE.`
- `Answer`
	- `#B -> Compute Engine.`
- `Explanation`
	- `You can use one of the following image types. 1. Public and custom images.`
****

##### Question - 54
`Tags: #Firestore, #Cloud BigTable, #MemoryStore`
- `Statement`
	- `A news media giant with over 200 publications plans to build a scalable, secure, and serverless document database with a powerful query engine that can be added with a mobile and web apps. `
	- `Which cloud product or service should org use?`
- `Options`
	- `A. Memory Store.`
	- `B. Cloud BigTable.`
	- `C. Cloud SQL.`
	- `D. Firestore.`
- `Answer`
	- `#D -> Firestore.`
- `Explanation`
	- `#D -> NoSQL document DB and can be added in mobile/ web apps.`
	- `#A -> MemoeryStore is an in-memory data store used to build application caches.`
****

##### Question - 55
`Tags: #Firestore, #Cloud BigTable, #MemoryStore`
- `Statement`
	- `Your organization wants to migrate its data management solutions to Google cloud becuase it needs to dynamically scale up/ down and run transactional SQL queries against historical data at scale. `
	- `Which cloud product should your org use?`
- `Options`
	- `A. BigQuery.`
	- `B. Cloud BigTable.`
	- `C. Pub/ Sub.`
	- `D. Cloud Spanner.`
- `Answer`
	- `#D -> Cloud Spanner.`
- `Explanation`
	- `#D -> Fully managed, mission critical RDBMS. OLTP db with high availability and consistency.`
****

##### Question - 56
`Tags: #SharedResponsibilityModel`
- `Statement`
	- `Which of the following  are always the responsibility of customers using public cloud? (2 answers)`
- `Options`
	- `A. Web client protection.`
	- `B. Data Protection.`
	- `C. N/W Control.`
	- `D. Patch Management.`
- `Answer`
	- `#A and #B`
- `Explanation`
	- `Client`
		- `#A -> Securing access web content is customer's responsibility.`
		- `#B -> Comliance, adherence of data is customer's responsibility.`
	- `Cloud Provider`
		- `N/w control, management,is cloud provider's responsibility, sometimes shared.`
		- `Patch management is shared responsibility in IaaS and PaaS.`
****

##### Question - 57
`Tags: #VisionAPI`
- `Statement`
	- `Your organziation needs to categorize objects in a large group of static images using machine learning. Which google cloud product or service should your organization use?`
- `Options`
	- `A. BigQuery ML.`
	- `B. AutoML video intelligence.`
	- `C. Cloud Vision API.`
	- `D. AutoML tables.`
- `Answer`
	- `#C`
- `Explanation`
	- `Vision API can assign labels to images and classify them into millions of predefined categories.`
****

##### Question - 58
`Tags: #Logs`
- `Statement`
	- `A DevOPS team is responsible for maintaining and analysing system and application logs for an application running across several instances on Google Cloud Platform. `
	- `What steps should the team take to ensure the integrity of the logs generated on these instances? (2 answers)`
- `Options`
	- `A. Implement log versioning on log buckets in cloud storage.`
	- `B. Copy the logs to another project with different owner.`
	- `C. Set the logging level to only collect log output for critical messages.`
	- `D. Export all logs files to BigQuery.`
- `Answer`
	- `#A and #B`
- `Explanation`
	- `Implement versioning so avoid losing or overwriting data.`
	- `Copy to another project so 2 people have ownership.`
****

##### Question - 59
`Tags: `
- `Statement`
	- `Which google cloud product is designed to reduce the risk of handling personally identifiable information?`
- `Options`
	- `A. Cloud Storage.`
	- `B. Google Cloud Armor.`
	- `C. Cloud Data Loss Prevention.`
	- `D. Secret Manager.`
- `Answer`
	- `#C -> Cloud Data Loss Prevention`
- `Explanation`
	- `Discover, classify, and protect your most sensitive data.`
****

##### Question - 60
`Tags: #Folders, #Projects, #Labels, #Tags.`
- `Statement`
	- `Your client has multiple ongoing projects and to remove conflicts has asked you to devise a way to segregate service level resources, such as compute, storage, and n/wking resources being used by various projects.`
	- `Which of the following you should use?`
- `Options`
	- `A. Folders.`
	- `B. Projects.`
	- `C. Labels.`
	- `D. Tags.`
- `Answer`
	- `#B -> Projects`
- `Explanation`
	- `#B -> Projects consists of service level resources such as compute, storage, n/wking.`
	- `#A -> Folders are used for projects rather than resources.`
	- `#C -> Labels are used to annotate resources.`
	- `#D -> Tag is a string of characters added to a resource tags field.`
****

##### Question - 61
`Tags: #Storage Transfer Service
- `Statement`
	- `Your organization in migrating google cloud. As part of that effort, it needs to move TBs of data from on-permises file servers to cloud storage. Your organization wants the migration process to be automated and to be managed by Google. Your organization has an exisiting dedicated interconnect connection that it wants to use.`
	- `Which Google Cloud product or feature should your org use?`
- `Options`
	- `A. Storage Transfer Service.`
	- `B. Migrate for anthos.`
	- `C. BigQuery data transfer service.`
	- `D. Transfer appliance.`
- `Answer`
	- `#A -> Storage Transfer Service`
- `Explanation`
	- `#A -> Fully managed, transfers data from on-prem file servers to cloud. It can transfer TBs of data quickly using your interconnect connection.`
****

##### Question - 62
`Tags: #Cloud Interconnect
- `Statement`
	- `Your organization is looking for n/w connectivity with Google cloud between it's on-prem n/w and Google cloud. The n/w connectivity must allow encryted traffic to Google Cloud and have higher throughput.`
	- `Which of the following n/wking solutions your should use?`
- `Options`
	- `A. Cloud VPN.`
	- `B. Cloud Interconnect.`
	- `C. Cloud Router.`
	- `D. Traffic director.`
- `Answer`
	- `#B -> Cloud Interconnect`
- `Explanation`
	- `#B -> Extends your on-prem n/w to Google cloud n/w through low latency connection.`
****

##### Question - 63
`Tags: #BigQuery
- `Statement`
	- `Your organization needs to analyze the data in order to gain insights into its daily operations. You want to only pay for the data you store and queries you perform. `
	- `Which google cloud product your org should choose for its data analytics warehouse?`
- `Options`
	- `A. Cloud SQL.`
	- `B. DataProc.`
	- `C. Cloud Spanner.`
	- `D. BigQuery.`
- `Answer`
	- `#D -> BigQuery`
****

##### Question - 64
`Tags: #App Engine
- `Statement`
	- `You are managing the development of a new application. You need a solution that will meet the following requirements:`
		- `The developers should focus on writing code.`
		- `Deployments should be zero-configuration.`
		- `The developers should not manage infrastructure.` 
		- `The service should be scalable and accommodate surges in traffic without provisioning, patching, or monitoring.` `Applications should be safe from security threats.`
	- `Which Google Cloud solution should you use?`
- `Options`
	- `A. App Engine.`
	- `B. Cloud Functions.`
	- `C. Confidential VMs.`
	- `D. Eventarc.`
- `Answer`
	- `#A -> App Engine.`
- `Explanation`
	- `#A -> Fully managed, serverless, highly scalable and secure applications.`
****

##### Question - 65
`Tags: #GKE`
- `Statement`
	- `Your organization wants to run a container-based application on Google Cloud. This application is expected to increase in complexity. You have a security need for fine-grained control of traffic between the containers. You also have an operational need to exercise fine-grained control over the application's scaling policies.`
	- `What Google Cloud product or feature should your organization use?`
	- `Which Google Cloud solution should you use?`
- `Options`
	- `A. Google Kubernetes Engine Cluster.`
	- `B. App Engine.`
	- `C. Cloud Run.`
	- `D. Compute Engine virtual machines.`
- `Answer`
	- `#A -> Google Kubernetes Engine Cluster.`
- `Explanation`
	- `#A`
		- `Deploy and manage container based applications.`
		- `Fine grainer control over traffic and scaling policies.`
****

##### Question - 66
`Tags: #Cloud Run`
- `Statement`
	- `A team of cloud engineers is working on developing and deploying a containerized application that will process and serve large amout of image data in cloud storage. The data must be invocable via requests or events. `
	- `Which google cloud compute service should the team use so that there are no infra management problems?`
- `Options`
	- `A. Cloud Build.`
	- `B. Cloud Cone.`
	- `C. Cloud Run.`
	- `D. Cloud Deploy.`
- `Answer`
	- `#C -> Cloud Run.`
- `Explanation`
	- `#C -> Cloud Run`
		- `Fully managed, serverless.`
		- `Development and deployment of containerzied application.`
		- `Invocable via requests and events.`
		- `No need to manage infra since it's a managed service.`
****

##### Question - 67
`Tags: #Cloud SCC`
- `Statement`
	- `Which google cloud product or feature makes specific recommendations based on security risks and compliance violations?`
- `Options`
	- `A. Google Cloud Firewalls.`
	- `B. Security Command Center.`
	- `C. Cloud Deployment Manager.`
	- `D. Google Cloud Armer.`
- `Answer`
	- `#B -> Security Command Center.`
- `Explanation`
	- `#B -> Security Command Center`
		- `Security management and data risk assessment platform.`
		- `Gain insights into Security Risks and Compliance Violations.`
****

##### Question - 68
`Tags: #CDN`
- `Statement`
	- `Which of the following scenarios is not suitable for a CDN? (Choose 2 answers)`
- `Options`
	- `A. A website for a small construction company located in USA.`
	- `B. A global retail company with customers in Europe and the Americas.`
	- `C. A family history website with only a few visitors annually.`
	- `D. A global media website that provides news in multiple languages.`
- `Answer`
	- `#A and #C`
- `Explanation`
	- `CDNs are especially useful for large, complex websites, or mobile apps with lots of dynamic content.`
	- `A small company will most likely not need a CDN becuase its customers are geographically closer to server.`
 ********
##### Question - 69
`Tags: #Anthos`
- `Statement`
	- `Which google cloud product provides a consisten platform for multi-cloud application deployments and extends other google cloud services to your organization's environment?`
- `Options`
	- `A. GKE.`
	- `B. Virtual public cloud.`
	- `C. Compute Engine.`
	- `D. Anthos.`
- `Answer`
	- `#D`
- `Explanation`
	- `#D -> Anthos is a container platform to run modern apps anywhere at scale.`
****

##### Question - 70
`Tags: #`reCAPTCHA
- `Statement`
	- `Your company's website enables users to upload images and input text to create memes of their choice. Lately, your have observed some suspicious traffic and want to protect your website from SPAM, specifically from Bots using the website.`
	- `Which of the following should you use to protect your website from bots and ensure that it is being accessed only by human users?`
- `Options`
	- `A. reCAPTA enterprise.`
	- `B. Policy troubleshooter.`
	- `C. Web Risk.`
	- `D. Cloud Identity.`
- `Answer`
	- `#A`
- `Explanation`
	- `#A
		- `Prevents abusive activities on your sites.`
****

##### Question - 71
`Tags: #Cloud Storage`
- `Statement`
	- `Your org wants an economical solution to store data such as files, graphical images, and videos and to share them securely.`
	- `Which google cloud product or service should your org use?`
- `Options`
	- `A. Cloud SQL.`
	- `B. Cloud Spanner.`
	- `C. Cloud Storage.`
	- `D. BigQuery.`
- `Answer`
	- `#C -> Cloud Storage`
- `Explanation`
	- `#C`
		- `Scalable and Durable object storage service.`
		- `Typically used to store images, videos, backups, and logs.`
****


##### Question - 72
`Tags: #Serverless`
- `Statement`
	- `A multinational food delivery startup has moved its applications to the cloud. The head of AppDev wants to introduce a new service that analyses customer preferences based on previous orders and suggests to them what to order. `
	- `Which cloud computing model would help developers create service while freeing them of infra and management risks?`
- `Options`
	- `A. Serverless.`
	- `B. IoT.`
	- `C. High performance computing.`
	- `D. Edge computing.`
- `Answer`
	- `#A -> Serverless.`
- `Explanation`
	- `#C`
		- `Build code without managing infra.`
		- `Event driven services.`
****



##### Question - 73
`Tags: #BigQueryML`
- `Statement`
	- `Your organization wants to predict the behvior of visitors to its public website. To do that, you have decided to build an ML model. Your team has database related skills but basic ML skills, and would like to use those DB skills.`
	- `Which Google product your org should use?`
- `Options`
	- `A. BigQuery.`
	- `B. Look ML.`
	- `C. TensorFlow.`
	- `D. Cloud SQL.`
- `Answer`
	- `#A -> BigQuery ML.`
- `Explanation`
	- `#A -> BigQuery ML`
		- `Execute ML models in using standard SQL query.`
		- `Do ML using SQL skills.`
		- `No advanced ML knowledge.`
****
##### Question - 74
`Tags: #Elasticity, #Load Balancing, #Fault Tolerance`
- `Statement`
	- `Which of the following cloud concepts refers to increasing or decreasing compute resources based on demand?`
- `Options`
	- `A. Elasticity.`
	- `B. Load Balance.`
	- `C. Fault tolerance.`
	- `D. High Availability.`
- `Answer`
	- `#A -> Elasticity.`
- `Explanation`
	- `#A -> Elasticity`
		- `System's ability to provision and de-provision the resources in autmated manner.`
	* `#C -> Ability of system to work even if some component fails.`
	* `#B -> Distribute traffic across multiple servers`
****



##### Question - 75
`Tags: #Database migration service`
- `Statement`
	- `Your org is moving to the google cloud. As part of it, need to migrate applications' working DB from another cloud provider to Cloud SQL. The DB runs on the MySQL engine. The migration must cause the minimal disruption to users. Data must be secured while in transit.`
- `Options`
	- `A. BigQuery Data Transfer Service.`
	- `B. MySQL batch insert.`
	- `C. Database migration service.`
	- `D. Cloud Composer.`
- `Answer`
	- `#C -> Database migration service.`
- `Explanation`
	- `#C`
		- `Protect the data in transit.`
		- `All data is encrypted on cloud.`
****



##### Question - 76
`Tags: #Projects`
- `Statement`
	- `Your organization is developing and deploying an application on Google Cloud. Tracking your Google Cloud spending needs to stay as simple as possible.`
	* `What should you do to ensure that workloads in the development environment are fully isolated from production workloads.`
- `Options`
	- `A. Apply a unique tag to development resources.`
	- `B. Associate the development resources with their own network.`
	- `C. Associate the development resources with their own billing account.`
	- `D. Put the development resources in their own project.`
- `Answer`
	- `#D -> Put the development resources in their own project.`
- `Explanation`
	- `#D`
		- `Create separate projects for your development and production environments. Projects provide a logical isolation boundary and allow you to manage resources independently..`
****
##### Question - 77
`Tags: #Hypervisor, #Anthos, #Migration`
- `Statement`
	- `Your company is running the majority of its workloads in a co-located data center. The workloads are running on virtual machines (VMs) on top of a hypervisor and use either Linux or Windows server editions. As part of your company's transformation strategy, you need to modernize workloads as much as possible by adopting cloud-native technologies. You need to migrate the workloads into Google Cloud.`
	* `What should you do?`
- `Options`
	- `A. Export the VMs into VMDK format, and import them Compute Engine`
	- `B. Export the VMs into VMDK format, and import them into Google Cloud VMware Engine`
	- `C. Migrate the workloads using Migrate for Compute Engine` 
	- `D. Migrate the workloads using Migrate for Anthos`

- `Answer`
	- `#D -> Migrate the workloads using Migrate for Anthos.`
****



##### Question - 78
`Tags: #Hypervisor, #ComputeEngine`
- `Statement`
	- `Your organization is running all of its workload in a private cloud on top of a hypervisor. Your org has decided it wants to move to Google cloud as quick as possible. Your org wants minimal changes to the current environment, while using the maximum amout of managed services google offers.`
	* `What should your organization do?`
- `Options`
	- `A. Migrate the workloads to Google cloud VMWare Engine.`
	- `B. Migrate workloads to compute engine.`
	- `C. Migrate workloads to bare metal.`
	- `D. Migrate workload to GKE.`
- `Answer`
	- `#B -> Migrate to compute engine.`
- `Explanation`
	- `#B`
		- `Lift and shift workloads at scale.`
		- `Minimal changes and risk.`
****
##### Question - 79
`Tags: #Support`
- `Statement`
	- `Your organization is releasing its first publically available application in Google Cloud. The application is critical to your business and customers requires a 2-hour SLA.`
	* `How should your org setup support to minimise the costs?`
- `Options`
	- `A. Enroll in preminum support.`
	- `B. Enroll in enhanced support.`
	- `C. Enroll in standard support.`
	- `D. Enroll in basic support.`
- `Answer`
	- `#B -> Enhanced support`
- `Explanation`
	- `Enhanced`
		- `High level of support for critical applications.`
		- `Faster response time.`
	- `Standard - 4hr, Enhanced: 1hr, Premium: 15min`
****
##### Question - 80
`Tags: #Identity Platform`
- `Statement`
	- `Your organization offers public mobile apps and websites. You want to migrate to a Google cloud based solution for checking and maintaining yours users' usernames and passwords and controlling their access to different resources based on their identity?`
	* `Which should your org choose?`
- `Options`
	- `A. VPN tunnels.`
	- `B. Identity platforms.`
	- `C. Compute engine firewall rules.`
	- `D. Private google access.`
- `Answer`
	- `#B -> Identity platform.`
- `Explanation`
	- `Identity platform: It is a solution for managing the identities of users and devices in a centralized fashion.`
****
##### Question - 81
`Tags: #BigQuery ML`
- `Statement`
	- `Which cloud service or feature lets you build ML models using standard SQL and data in DWH?`
	* `Which should your org choose?`
- `Options`
	- `A. BigQuery ML.`
	- `B. TensorFlow.`
	- `C. AutoML tables.`
	- `D. Cloud BigTable ML.`
- `Answer`
	- `#A -> BigQuery ML.`
****
##### Question - 82
`Tags: #Sustained Use Discount`
- `Statement`
	* `Your organization runs an application on virtual machines in Google Cloud. This application processes incoming images. This activity takes hours to create a result for each image. The workload for this application normally stays at a certain baseline level, but at regular intervals it spikes to a much greater workload. Your organization needs to control the cost to run this application.?`
	* `What should your org do?`
- `Options`
	- `A. Purchase committed use discounts for the baseline load.`
	- `B. Purchase committed use discounts for the expected spike load.`
	- `C. Leverage sustained use discounts for your virtual machines.`
	- `D. Run the workload on preemptible VM instances.`
- `Answer`
	- `#C-> Leverage sustained use discounts for your virtual machines.`
- `Explanation`
	- `Sustained Use Discount: Longer you run a VM instance in any given month, the bigger discount you will get from the list price.`
****
##### Question - 83
`Tags: #GCP`
- `Statement`
	* `Your organization is planning to migrate to Google cloud. What is the best practice when intially configuring Google cloud env?`
- `Options`
	- `A. Create a project via google cloud console per department in your org.`
	- `B. Define your resource hierarchy with an org node on top.`
	- `C. Create projects based on team members's requests.`
	- `D. Make every member of your company the project owner.`
- `Answer`
	- `#B-> Define your resource hierarchy with an org node on top.`
****
##### Question - 84
`Tags: #CUD, #Discount`
- `Statement`
	* `Your organization runs many workloads in different Google Cloud projects, each linked to the same billing account. Each project's workload costs can vary from month to month, but the overall combined cost of all projects is relatively stable. Your organization needs to optimize its cost.`
	* `What should your org do?`
- `Options`
	- `A. Purchase a commitment per project for each project's usual minimum.`
	- `B. Create a billing account per project, and link each project to a different billing account.`
	- `C. Turn on committed use discount sharing, and create a commitment for the combined usage.`
	- `D. Move all workloads from all different projects into one single consolidated project.`
- `Answer`
	- `#C-> Turn on committed use discount sharing, and create a commitment for the combined usage.`
- `Explanation`
	- `Committed Use Discount (CUD):` 
		- `Allow users to commit to a specific amount of usage for a Google Cloud Platform (GCP) service.`
		- `Over a one or three-year term, in exchange for discounted pricing.`
****
##### Question - 85
`Tags: #Compliance, #Security`
- `Statement`
	* `How should a multi-nantional organization that is migrating to Google cloud consider security and privacy regulations to ensure that it is in compliance with global standards?`
- `Options`
	- `A. Comply with data security and privacy regulations in geo region.`
	- `B. Comply with regional standards for data security and privacy, as the supersede all international regulations.`
	- `C. Comply with international standards for data security and privacy, becuase they supersede all regional regulations.`
	- `D. Comply with regional data security regulations, becuase they are more complex than privacy standards.`
- `Answer`
	- `#A-> Comply with data security and privacy regulations in geo region.`
****
##### Question - 86
`Tags: #Discount`
- `Statement`
	* `Your organization wants to optimize its use of google cloud discounts on VM based workloads. You plan to use 200 CPUs constantly for next 3 years, and you forecast that spikes of up to 300 CPUs will occur approx 30% of the time. `
	* `What should you choose?`
- `Options`
	- `A. 1 year committed use discount for 200 CPUs.`
	- `B. 3 years committed use discount for 300 CPUs.`
	- `C. 3 years committed use discount for 200 CPUs.`
	- `D. Regular pay as you go pricing.`
- `Answer`
	- `#C-> 3 years committed use discount for 200 CPUs.`
- `Explanation:`
	- `Note: When committed discount option is available, no question of pay as you go model.`
****
##### Question - 87
`Tags: #n/w tier, #Cloud VPN, #Cloud NAT`
- `Statement`
	* `Your organziation needs to minimize how much it pays for data traffic from google n/w to internet. `
	* `What should you choose?`
- `Options`
	- `A. Choose the standard service n/w tier.`
	- `B. Choose the premium service n/w tier.`
	- `C. Deploy cloud VPN.`
	- `D. Deploy cloud NAT.`
- `Answer`
	- `#A-> Choose the standard service n/w tier.`
- `Explanation:`
	- `Premium tier is the default for all egress traffic and offers the highest performance, it might not be the best option when cost is a consideration. Standard tier is the more economical.`
	- `Cloud VPN and Cloud NAT are both networking services that can be used to connect your Google Cloud resources to the internet. However, they do not directly affect the cost of data traffic from the Google network to the internet.`
****
##### Question - 88
`Tags: #Artifact Registry, #Cloud Storage`
- `Statement`
	* `Your org wants to migrate from on-prem to google cloud. The on-prem env consistsof containers and VMs. Which google cloud product can help migrate  the container images and VM disks?`
- `Options`
	- `A. Compute Engine and FileStore.`
	- `B. Artifact registry and Cloud Storage.`
	- `C. DataFlow and BigQuery.`
	- `D. Pub/ Sub and Cloud Storage.`
- `Answer`
	- `#B-> Artifact registry and Cloud Storage.`
- `Explanation:`
	- `Artifact Registry can manage container image migration and Cloud Storage can store virtual disk image.`
****
##### Question - 89
`Tags: #IAM`
- `Statement`
	* `Your company security team manages access control to production systems using an LDAP directory group?`
	* `How is this access control is managed in the google cloud production project?`
- `Options`
	- `A. Assign proper role to the service account in the project's IAM policy.`
	- `B. Grant each user the roles/ IAM.serviceAccountUser role on service account that exist on Google group.`
	- `C. Assign the proper role to the google group in the project's IAM policy.`
	- `D. Create the project in a folder with the same name as the LDAP directory group.`
- `Answer`
	- `#C-> Assign the proper role to the google group in the project's IAM policy.`
- `Explanation:`
	- `Assigning roles to groups is the recommended best practice for controlling access.`
****
##### Question - 90
`Tags: #cost management`
- `Statement`
	* `Your organization wants to be sure that expenditures on cloud services are in line with the budget. `
	* `Which two google cost management features will help your org gain greater visibility into its cloud resource costs? (2 answers)`
- `Options`
	- `A. Billing dashboard.`
	- `B. Resource labels.`
	- `C. Sustained use discount.`
	- `D. Finance governance policies.`
	- `E. Payments profile.`
- `Answer`
	- `#A and #B`
- `Explanation:`
	- `Billing dashboards: `
		- `Graphical overview of your cloud spending.`
		- `Organized by project, service.`
		- `Track spending overtime, identify trends, troubleshoot spikes in cost.`
	- `Resource labels:`
		- `Allows you categorize, tag your cloud resources.`
		- `Due to tags, you can analyse on different dimensions such as project, department, environment, etc.`
****
##### Question - 91
`Tags: #DataFlow`
- `Statement`
	* `Your organization needs to process large amoutns of data from an online application that operates continuously. You do not want to be required to provision infra or create a server clusters.`
	* `What should your org to choose?`
- `Options`
	- `A. Compute Engine with BigQuery.`
	- `B. Dataproc.`
	- `C. GKE with BigTable.`
	- `D. DataFlow.`
- `Answer`
	- `#D`
- `Explanation:`
	- `DataFlow:`
		- `Fully managed` 
		- `Streaming data processing service`
		- `Handle large amounts of data from continuous sources`. 
		- `Serverless, no need to provision infra or create server cluster
****
##### Question - 92
- `Statement`
	* `Your organization needs to ensure that the google cloud resources of each of your department are segregated from one another. Each department has several environments of its own: development, testing, and production.`
	* `Which strategy should your organization choose?`
- `Options`
	- `A. Create a project per department, and create a folder per environment in each project.`
	- `B. Create a folder per department, and create a project per environment in each folder.`
	- `C. Create a cloud identity domain per department , and create  a project per env in each domain.`
	- `D. Create a cloud identity domain per environment, and create a project per department in each domain.`
- `Answer`
	- `#B`
****
##### Question - 93
`Tags: #Region,#Project,#Tag,#Label`
- `Statement`
	* `Your organization is defining the resource hierarchy for its new application in Google Cloud. You need separate development and production environments. The production environment will be deployed in Compute Engine in two regions.`
	* `Which structure should your organization choose?.`
- `Options`
	- `A. Create a single project for all environments. Use labels to segregate resources by environment.`
	- `B. Create a single project for all environments. Use tags to segregate resources by environment.`
	- `C. Create one project for the development environment and one project for the production environment.`
	- `D. Create two projects for the development environment and two projects for the production environment (one for each region).`
- `Answer`
	- `#C` 
- `Explanation:`
	- `Option A and B - single project for all environments and relying on labels or tags to segregate resources. While labels and tags can be useful for organizing and categorizing resources, they may not provide the same level of isolation and control as separate projects.`
****
##### Question - 94
`Tags: #committed use discount, #cloud billiing support`
- `Statement`
	* `Your organization to purchase a 3 year committed use discount, but accidently purchases a 1 year committed use discount instead.`
	* `What should your organization should do?`
- `Options`
	- `A. Contact your financial insititution.`
	- `B. Contact trust and safety.`
	- `C. Contact cloud billing support.`
	- `D. Contact technical support.`
- `Answer`
	- `#C` 
**** 
##### Question - 95
`Tags: #IAM, #instance group, #compute engine`
- `Statement`
	* `Your organization needs to allow a production job to have access to BigQuery dataset. The production job is running on a compute engine instance that is part of an instance group.`
	* `What should be included in the IAM policy on the BigQuery dataset?`
- `Options`
	- `A. The compute engine instance group.`
	- `B. The project that owns the compute engine instance.`
	- `C. The compute engine service account.`
	- `D. The compute engine instance.`
- `Answer`
	- `#C` 
****
##### Question - 96
`Tags: #anthos, #VM, #Compute Engine, #containers`
- `Statement`
	* `How do migrate for compute engine and migrate for anthos differ?`
- `Options`
	- `A. Unlike migrate for anthos, migrate for compute engine assumes that the migration should is VMware vSphere.`
	- `B. Migrate for compute engine charges for ingress, but migrate for anthos does not.`
	- `C. Migrate for compute engine is closed source, and migrate for anthos is open source.`
	- `D. Migrate for anthos migrates to containers, and migrate for compute engine migrates to VM.`
- `Answer`
	- `#D`
****
##### Question - 97
`Tags: #LDAP`
- `Statement`
	* `Your large and frequently changing organization's user information is stored in an on-premises LDAP database. The DB includes user passwords and group and org membership.`
	* `How should your org provision Google accounts and groups to access Google Cloud resources?`
- `Options`
	- `A. Replicate the LDAP infra on compute engine.`
	- `B. Use firebase auth REST API to create users.`
	- `C. Use google cloud directory sync to create users.`
	- `D. Use the identity platform REST API to create users.`
- `Answer`
	- `#C` 
****
##### Question - 98
`Tags: #SLO, #Cost`
- `Statement`
	* `An organization is planning its cloud expenditure.`
	* `What should the org do to control the costs?`
- `Options`
	- `A. Consider the cloud resource costs as capital expenditure in annual planning.`
	- `B. Use only cloud resources; they have no cloud infra costs.`
	- `C. Review cloud resource costs frquently because costs depend on usage.`
	- `D. Access cloud resources costs only when SLO is not met by their cloud provider.`
- `Answer`
	- `#C` 
- `Explanation`:
	- `'Cloud Infrastructure' is not only physical. the resources like Cloud VPN, Internconnects, GCE, etc are all 'cloud infrastructure' resources.`
****
##### Question - 99
`Tags: #ML`
- `Statement`
	* `An org is using a ML to make predictions. One of their datasets mistakenly includes mislabled data.`
	* `How prediction will be impacted?`
- `Options`
	- `A. Increased risk of privacy leak.`
	- `B. Increased risk of inaccuracy.`
	- `C. Decreased model compatibility.`
	- `D. Decreased model training time.`
- `Answer`
	- `#B`
****
##### Question - 100
`Tags: #Cloud Spanner`
- `Statement`
	* `A global organization is developing an application to manage payments and online bank accounts in multiple regions. Each transition must be handled consistently in their DB, and they anticipate almost unlimited growth in the amount of data stored.`
	* `Which google cloud product should be used?`
- `Options`
	- `A. Cloud SQL.`
	- `B. Cloud Spanner.`
	- `C. Cloud Storage.`
	- `D. BigQuery.`
- `Answer`
	- `#B`
****
##### Question - 101
- `Statement`
	* `An e-commerce org is reviewing their cloud data storage.`
	* `What type of raw data can they store in RDBMS without any processing?`
- `Options`
	- `A. Product inventory.`
	- `B. Product photographs.`
	- `C. Instructional videos.`
	- `D. Customer chat history.`
- `Answer`
	- `#A`
****
##### Question - 102
- `Statement`
	* `An org wants to digitize and share the large volumes of historical text and images.`
	* `Why is a public cloud a better option than an premises solution?`
- `Options`
	- `A. In-house hardware management.`
	- `B. Provides physical encryption key.`
	- `C. Cost effective at scale.`
	- `D. Optimizes captial expenditure.`
- `Answer`
	- `#C`
****
##### Question - 103
- `Statement`
	* `An org wants to develop an application that can be personalized to user preferences throughout the year.`
	* `Why should they build a cloud native application instead of modernizing their existing on-prem application?`
- `Options`
	- `A. Developers can rely on the cloud provider for all source code.`
	- `B. Developers can launch new feautures in an agile way.`
	- `C. IT managers can migrate existing application architecture without needing updates.`
	- `D. IT managers can accelerate capital expenditure planning.`
- `Answer`
	- `#B`
****
##### Question - 104
- `Statement`
	* `Which technology allows org to run multiple computer OS on a single piece of hardware?`
- `Options`
	- `A. Hypervisor.`
	- `B. Containers.`
	- `C. Serverless computing.`
	- `D. Open source.`
- `Answer`
	- `#A`
- `Explanation`
	- `Abstract underlying h/w from the host OS and apps and is the core tech behind virtualization.`
	- `Allows a physical server to operate multiple VMs as guests run alongside each other.`
	- `Each VM can run a different OS.`
****
##### Question - 105
- `Statement`
	* `An organization is making a strategic change to customer support in response to feedback. They planned to extend helpline availability hours.`
	* `Why is the organization making this change?`
- `Options`
	- `A. Users expect the professional expertise.`
	- `B. Users require personalization.`
	- `C. Users expects always on services.`
	- `D. Users require regional access.`
- `Answer`
	- `#C`
****
##### Question - 106
- `Statement`
	* `How does a large hotel chain benefit from stroring their customer reservation data in the cloud?`
- `Options`
	- `A. On-premises h/w access to transaction data.`
	- `B. Realtime data transformation at scale within on-prem DB.`
	- `C. Realtime business transaction accuracy at scale.`
	- `D. Physical h/w access during peak demand.`
- `Answer`
	- `#C`
****
##### Question - 107
- `Statement`
	* `An org wants to transform multiple types of structured and unstructured data in the cloud from various sources. The data must be readily accessible for analysis and insights.`
	* `Which cloud data storage system should the org use?`
- `Options`
	- `A. Relational DB.`
	- `B. Private data center.`
	- `C. Data field.`
	- `D. Data warehouse.`
- `Answer`
	- `#D`
- `Explanation`
	- `DWH is used for the analysis and reporting.`
****

##### Question - 108
- `Statement`
	* `An org wants to use all available data to offer predictive suggestions on their website that improve over time.`
	* `Which method should the org use?`
- `Options`
	- `A. Data automation.`
	- `B. Trends analysis.`
	- `C. ML.`
	- `D. Multiple regression.`
- `Answer`
	- `#C`
****

##### Question - 109
`Tags:#TAM` 
- `Statement`
	* `Google Enterprise support offers you __________.`
- `Options`
	- `A. More predictable rates and flexible config that role-based support.`
	- `B. Fastest response times and opportunities to work directly with a dedicated TAM contact.`
	- `C. Fastest response time.`
	- `D. Ability to work directly with the TAM contact.`
- `Answer`
	- `#B`
****

##### Question - 110
- `Statement`
	* `Which google product generates highly personalized recommendations.`
- `Options`
	- `A. Recommendations ML.`
	- `B. Recommendations OCR.`
	- `C. Recommendations AI.`
	- `D. Auto Recommendations.`
- `Answer`
	- `#C`
****

##### Question - 111
- `Statement`
	* `Which of the following statements about the GCP migration service and datastream is false?`
- `Options`
	- `A. Datastream is low latency and won't bog down your source database.`
	- `B. Database Migration Service has integrations with services such as BigQuery, Cloud Spanner, Dataflow, and Data Fusion.`
	- `C. With Database Migration Service, if you are migrating to a serverless option like Cloud SQL, then you don't have to worry about over- or under-provisioning..`
	- `D. With Database Migration Service, you can start the process with just a few clicks and then enjoy continuous data replication from source to destination.`
- `Answer`
	- `#B`
****

##### Question - 112
- `Statement`
	* `Which of the following statements about GCP tools/ service is false?`
- `Options`
	- `A. You can find the latest ISO/ IEC certificates, SOC reports, and self assessment in the container registry.`
	- `B. Container registry is tightly integrated with all google's container services.`
	- `C. The resources found in the compliance reports manager tool can be used to aid your own company's reporting and compliance efforts.`
	- `D. All of the GCP services receive independent verification for security, privacy, and compliance.`
- `Answer`
	- `#A`
****

##### Question - 113
- `Statement`
	* `Which of the following is not a level of organizational GCP support?`
- `Options`
	- `A. Ultra.`
	- `B. Basic.`
	- `C. Standard.`
	- `D. Premium.`
- `Answer`
	- `#A`
- `Explanation`:
	- `basic, standard, enhanced, premium are correct lebels.`
****


##### Question - 114
`Tags: #DataStream`
- `Statement`
	* `If you need to migrate the data in Oracle to a new type of database in GCP then, _____ might be a better choice than Database migration service.`
- `Options`
	- `A. Datastream.`
	- `B. Data Fusion.`
	- `C. Cloud Spanner.`
	- `D. DataFlow.`
- `Answer`
	- `#A`
- `Explanation`:
	- `A -> Fully managed, serverless change data capture and replication service that simplifies data movement from multiple sources to Google Cloud.`
****

##### Question - 115
`Tags: #TPU`
- `Statement`
	* `A ______ is a custom designed ASIC that is used for ML workloads.`
- `Options`
	- `A. Datastream.`
	- `B. Cloud TPU.`
	- `C. Cloud GPU.`
	- `D. Container Registry.`
- `Answer`
	- `#B`
- `Explanation`:
	- `B -> Tensor Processing Unit (TPU) is a custom designed ASIC that is used for ML workloads.`
****

##### Question - 116
`Tags: #container registry`
- `Statement`
	* `Which GCP tool offers an easy, centralized location to store and manage all your docker container images?`
- `Options`
	- `A. Compliance reports managed.`
	- `B. Container registry.`
	- `C. DB migration service.`
	- `D. Cloud TPU.`
- `Answer`
	- `#B`
- `Explanation`:
	- `B -> Centralized location to store and manage docker images.`
****

##### Question - 117
`Tags: #Translate AI`
- `Statement`
	* `Which google product is used to dynamically translate between languages?`
- `Options`
	- `A. Vision OCR.`
	- `B. Natural Language.`
	- `C. Text AI.`
	- `D. Translation.`
- `Answer`
	- `#D`
****

##### Question - 118
`Tags: #container registry`
- `Statement`
	* `Which of the following statements about GCP container registry is false?`
- `Options`
	- `A. It gives you partial control over who can access, view, or download images.`
	- `B. Allows you access your images quickly and reliably.`
	- `C. It allows you to flag outdated or compromised images and prevent them from being deployed in future.`
	- `D. It helps increase the security of your images.`
- `Answer`
	- `#A`
- `Explanation`
	- `Increase security`
	- `Complete control over who can access, view and download images.`
	- `Flag outdated and compromised images`
****

##### Question - 119
`Tags: #Cloud Spanner`
- `Statement`
	* `Your org is developing an application that will manage payments and online bank accounts located around the world. The most critical requirement for your database is that each transaction is handled consistently.`
	* `Which google cloud product should your org choose?`
- `Options`
	- `A. Cloud SQL.`
	- `B. Cloud Storage.`
	- `C. Firestore.`
	- `D. Cloud Spanner.`
- `Answer`
	- `#D`
- `Explanation`
	- `Fully managed relational DB.`
	- `Proprietary RDB designed for scale.`
****

##### Question - 120
`Tags: #Tensorflow`
- `Statement`
	* `An org is searching for an open source machine learning platform to build and deploy their own custom ML applications using TPUs.`
	* `Which google cloud product should your org choose?`
- `Options`
	- `A. TensorFlow.`
	- `B. BigQuery ML.`
	- `C. Vision API.`
	- `D. AutoML vision.`
- `Answer`
	- `#A`
- `Explanation`
	- `Free and open source s/w library for ML and AI.`
****

##### Question - 121
`Tags: #Data Security`
- `Statement`
	* `An organization operates their entire IT infra from google cloud.`
	* `What should they do to prepare the data breaches?`
- `Options`
	- `A. Reduce the reliance on multi-factor authentication.`
	- `B. Data security is google's responsibility, hence preparation is minimal.`
	- `C. Create an incident plan to mitigate impact.`
	- `D. Strenthen their data center perimeter security.`
- `Answer`
	- `#C`
- `Explanation`
	- `Data security is a shared responsibility between google and customer.`
****


##### Question - 122
`Tags: #VMs`
- `Statement`
	* `An organization wants to migrate legacy applications currently hosted in their data center to the cloud. The current architecture dictates that each applicaiton needs its own OS instead of sharing an OS.`
	* `Which infra solution should they use?`
- `Options`
	- `A. VMs.`
	- `B. Open source.`
	- `C. Serverless computing.`
	- `D. Containers.`
- `Answer`
	- `#A`
- `Explanation`
	- `VMs would be the best infra solution given the requirement.`
****


##### Question - 123
`Tags: #ML`
- `Statement`
	* `An organization is training a ML model to predict extreme weather events in their country.`
	* `How should they collect data to maximize predicton accuracy?`
- `Options`
	- `A. Collect all weather data evenly across all cities.`
	- `B. Collect all weather data primarily from at-risk cities.`
	- `C. Collect extreme weather data evenly across all cities.`
	- `D. Collect extreme weather data primarily from at-risk cities.`
- `Answer`
	- `#A`
****


##### Question - 124
`Tags: #Cloud Logging`
- `Statement`
	* `An organization needs to search the application's source code to identify a potential issue. The applicaiton is distributed across multiple containers.`
	* `Which google cloud product should the org use?`
- `Options`
	- `A. Google cloud console.`
	- `B. Cloud trace.`
	- `C. Cloud monitoring.`
	- `D. Cloud logging.`
- `Answer`
	- `#D`
- `Explanation`
	- `Cloud logging`
		- `Store, search, analyze, and monitor logs from various sources, including containers. `
****


##### Question - 125
- `Statement`
	* `An organization's web developers and operations personnel use different systems.`
	* `How will increasing communications between the teams reduce issues caused by silos?`
- `Options`
	- `A. By assigning blame for failures and establishing consequences.`
	- `B. By combining job role responsibilities to ensure that everyone has shared access.`
	- `C. By increasing the data encryption to strenthen workflows.`
	- `D. By emphasizing shared ownership of business outcomes.`
- `Answer`
	- `#D`
****


##### Question - 126
`Tags: #Migration`
- `Statement`
	* `An organization is migrating their business applications form on-prem to cloud.`
	* `How could this impact their operations and personnel costs?`
- `Options`
	- `A. Reduced on-prem infra management costs.`
	- `B. Increased on-prem hardware maintenance costs.`
	- `C. Reduced cloud software licensing costs.`
	- `D. Increased cloud hardware management costs.`
- `Answer`
	- `#A`
****


##### Question - 127
`Tags: #APIs`
- `Statement`
	* `A retail company stores their product inventory in a legacy system. Often customers find the products on the company's website and want to purchase them in-store. However when they arrive, they discover that the products are out of stock. `
	* `How could company benefit from APIs?`
- `Options`
	- `A. Create personalized product recommendations for customers.`
	- `B. To optimize their on-prem legacy system stability.`
	- `C. By manually linking each inventory system to the website on a case-by-case basis.`
	- `D. By programmatically connecting inventory system to website.`
- `Answer`
	- `#D`
- `Explanation`
	- `The issue is the website shows an item is available at the store, but when the customer gets to the store, they find out that item is out of stock. Hence #D`
****


##### Question - 128
`Tags: #APIs`
- `Statement`
	* `A hotel wants to modernize their legacy systems so that the customers can make reservations through the mobile app. `
	* `What's the benefit of using APIs to do this?`
- `Options`
	- `A. They do not have to develop the end-user application.`
	- `B. They can deprecate their legacy system.`
	- `C. They can transform their systems to the cloud-native.`
	- `D. They do not have to rewrite the legacy system.`
- `Answer`
	- `#D`
- `Explanation`
	- `D -> An API is a software intermediary that allows two applications to talk to each other. In this case, the API would allow the hotel's legacy systems to talk to the mobile app. This means that the hotel would not have to rewrite their legacy systems`
****


##### Question - 129
`Tags: #APIs`
- `Statement`
	* `An org has servers running mission critical workloads on-prem around the world. They want to modernize their infra with multi-cloud arch.`
	* `What benefit an organization could get?`
- `Options`
	- `A. Ability to disable regional n/w connectivity during cyber attacks.`
	- `B. Ability to keep backups of their data on-prem in case of failure.`
	- `C. Full management access to their regional infra.`
	- `D. Reduced likelihood of system failure during high demand events.`
- `Answer`
	- `#D`
- `Explanation`
	- `D -> As the are servers running in mission-critical workloads, so most advantageous organization benefit would be reduced system failure during high demand and peak.`
****


##### Question - 130
`Tags: #GKE`
- `Statement`
	* `An org needs to run frequent updates for their business app.`
	* `Why should the org use GKE?`
- `Options`
	- `A. Customer expectations can be adjusted without using marketing tools.`
	- `B. Seamless changes can be made without causing any application downtime.`
	- `C.GKE handles version control seamlessly and out of the box.`
	- `D. GKE is well suited for all monolithic applications.`
- `Answer`
	- `#B`
- `Explanation`
	- `B -> Seamless changes can be made without causing any application downtime. Most Voted.`
****


##### Question - 131
`Tags: #Apigee`
- `Statement`
	* `An org wants to use an Apigee to manage all their APIs.`
	* `What will apigee enable to org to do?`
- `Options`
	- `A. Increase application privacy.`
	- `B. Measure and track APIs performance.`
	- `C.Analyse application development speed.`
	- `D. Market and sell APIs.`
- `Answer`
	- `#B`
- `Explanation`
	- `B -> Apigee is an API management platform that helps organizations design, secure, deploy, monitor, and scale APIs.`
****


##### Question - 132
`Tags: #unstructured data`
- `Statement`
	* `What is an example of unstructured data that org can capture from social media?`
- `Options`
	- `A. Post comments.`
	- `B. Tagging.`
	- `C. Profile picture.`
	- `D. Location.`
- `Answer`
	- `#C`
****


##### Question - 133
`Tags: #App Engine`
- `Statement`
	* `An org rellies on online seasonal sales for the majority of their annual revenue.`
	* `Why should the org use App Engine for their customer app?`
- `Options`
	- `A. Auto adjust the physical inventory in real time.`
	- `B. Autoscales during peaks in demand.`
	- `C.Runs maintenance during seasonal sales.`
	- `D. Recommends the right products to customers.`
- `Answer`
	- `#B`
- `Explanation`
	- `B -> PaaS allows org to deploy and scale their web apps automatically.`
****


##### Question - 134
`Tags: #VPC`
- `Statement`
	* `Your org recently migrated its compute workload to google cloud. You want these workloads in the google cloud to privately and securely access your large volume of on-prem data, and you also want to minimize latency.`
	* `What should org do?`
- `Options`
	- `A. Use storage transfer service to securely make your data available to google cloud.`
	- `B. Create a VPC between your on-prem data center and your google cloud resources.`
	- `C.Peer your on-prem data center to google's edge n/w.`
	- `D. Use transfer appliance to securely make your data available to google cloud.`
- `Answer`
	- `#B`
****


##### Question - 135
`Tags: #folders`
- `Statement`
	* `Your org consists of many teams. Each team has many Google Cloud Projects. Your org wants to simplify the management of identity and access policies for these projects.`
	* `How can you group these projects to meet it's goal?`
- `Options`
	- `A. Group each team's project into a separate domain.`
	- `B. Assign labels on the VMs that are part of each team's projects.`
	- `C.Use folders to group each team's projects.`
	- `D. Group team's projects into a separate org code.`
- `Answer`
	- `#C`
- `Explanation`
	- `Org -> Folder -> Project -> Resource`
****

##### Question - 136
`Tags: #folders`
- `Statement`
	* `An org needs to categorize text-based customer reviews on their website using pre-trained ML model.`
	* `What google cloud product or service should the org use?`
- `Options`
	- `A. Cloud natural language API.`
	- `B. Dialogflow.`
	- `C.Recommendations AI.`
	- `D. TensorFlow.`
- `Answer`
	- `#A`
****

##### Question - 137
`Tags: #Requestor Pays`
- `Statement`
	* `Your team is publishing research results and needs to make large amounts of data available to other researchers within the professional community and the public at minimum cost.`
	* `How should you host the data?`
- `Options`
	- `A. Use a cloud storage bucket and enable "Requster Pays"`
	- `B. Use cloud storage bucket and provide signed URLs for the data files.`
	- `C.Use cloud storage bucket and set up a cloud interconnect connection to allow access to the data.`
	- `D. Host the data on-prem, and set up a cloud interconnection to allow access to the data.`
- `Answer`
	- `#A`
- `Explanation`
	- `Enabling Requester Pays is useful, for example, if you have a lot of data you want to make available to users, but you don't want to be charged for their access to that data.`
****

##### Question - 138
- `Statement`
	* `Your company needs to segment Google cloud resources used by each team from the others. The teams' efforts are changing frequently, and you need to reduce operational risk and maintain cost visibility.`
	* `Which approach does google recommends?`
- `Options`
	- `A. One project per team.`
	- `B. One organization per team.`
	- `C. One project that contains all of each team's resources.`
	- `D. One top-level folder per team.`
- `Answer`
	- `#D`
****

##### Question - 139
`Tags: #access`
- `Statement`
	* `Your org needs to restrict the access to a cloud storage bucket. Only employees who are based in canada should be allowed to view the contents.`
	* `What is the most effective and effiecient way to satisfy your requirement?`
- `Options`
	- `A. Deploy the cloud storage bucket to a google cloud region in canada.`
	- `B. Configure google cloud armor to allow access to the bucket only if IP is based on canada.`
	- `C.Give each canadian employee an access to the bucket.`
	- `D. Create a group consisting of all canada-based employees, and give the group access the bucket.`
- `Answer`
	- `#D`
- `Explanation`
	- `Correct answer is D. Question is tricky, but it says "based" in Canada. That is not the same as restricting access to "from Canada". An employee can for instance be based in Canada, but access the services while on business trip to Singapore..`
****

##### Question - 140
`Tags: #private google access`
- `Statement`
	* `Your organization runs all its workloads on Compute Engine virtual machine instances. Your organization has a security requirement: the virtual machines are not allowed to access the public internet. The workloads running on those virtual machines need to access BigQuery and Cloud Storage, using their publicly accessible interfaces, without violating the security requirement.`
	* `Which Google Cloud product or feature should your organization use?`
- `Options`
	- `A. Identity aware proxy.`
	- `B. Cloud NAT (network address translation).`
	- `C.VPC internal load balancers.`
	- `D. Private google access.`
- `Answer`
	- `#D`
- `Explanation`
	- `NAT is option for securing Internet connection which is not ask. VM and other components are in cloud.`
****

##### Question - 141
`Tags: #Vision API`
- `Statement`
	* `You are managing a project for a large healthcare provider with 100+ clinics and hospitals across the European Union. Your client plans to develop an OCR application to digitize overall clinical records, including X-Rays and patients' health records. As part of the solution, it is decided that:`
		* `Image files will be uploaded.
		* `Text will be extracted from the image.`
		* `The extracted text will be translated into English.`
		* `The final ready text will be stored for further use.`
	* `The client does not want any overhead and has asked you to use a Google Cloud product that can offer pre-trained machine learning models through REST APIs.`
- `Options`
	- `A. AutoML vision.`
	- `B. Vision API.`
	- `C. Cloud natural lanugage API.`
	- `D. Vertex AI Vizier.`
- `Answer`
	- `#B`
- `Explanation`
	- `Vision API offered pre-trained ML models through RFCs and REST APIs. It offers solution to extract text from images, understand emotion, and more.`
****

##### Question - 142
`Tags: #Cloud Tasks`
- `Statement`
	* `An org requires a fully managed, scalable queuing service that will help manage the execution, dispatch, and delivery of multiple distributed tasks.`
	* `Which cloud solution the org to use?`
- `Options`
	- `A. Cloud scheduler.`
	- `B. Cloud tasks.`
	- `C. Service infra.`
	- `D. Workflows.`
- `Answer`
	- `#B`
- `Explanation`
	- `Cloud tasks: Fully managed, scalable queuing service that could help manage the execution, dispatch, and delivery of multiple distributed tasks.`
****

##### Question - 143
- `Statement`
	* `How does the google cloud suggest that organizations use 3rd party identity providers to enable users access to Google Cloud with their corporate credentials?`
- `Options`
	- `A. By delegating responsibility to service accounts and groups.`
	- `B. By implementing the principle of least privilege.`
	- `C. By federating 3rd party identity providers with Google Cloud.`
	- `D. By migrating unmanaged accounts to personal accounts.`
- `Answer`
	- `#C`
****



##### Question - 144
`Tags: #Vertex AI`
- `Statement`
	* `You work for an e-commerce website and want to use a product that can predict users' purchasing behavior and suggests products based on the behavior.`
	* `Which of the following Google cloud AI solutions would you recommend?`
- `Options`
	- `A. Vertex AI Matching Engine.`
	- `B. Vertex AI.`
	- `C. Vertex Explainable AI.`
	- `D. Vertex AI workbench.`
- `Answer`
	- `#A`
- `Explanation`
	- `#A -> Finds the similar items in large datasets quickly including text, images, and audio.`
****

##### Question - 145
`Tags: #IaaS`
- `Statement`
	* `You are a CTO helping an org to modernize its IT infra by adopting google's cloud services. Which of the following is an advantage of an IaaS model that you should consider when choosing solution?`
- `Options`
	- `A. Web application security is managed by Google.`
	- `B. IT costs change from operational to capital expenditures.`
	- `C. Google assumes responsibility for server maintenance.`
	- `D. Data storage and encryption become the responsibility of the org.`
- `Answer`
	- `#C`
- `Explanation`
	- `#A -> Finds the similar items in large datasets quickly including text, images, and audio.`
****


##### Question - 146
`Tags: #Local SSDs`
- `Statement`
	* `A MNC retail corporation plans to migrate its on-prem inventory management system to Google Cloud. The current inventory management system has experienced performance issues that are result of very high IOPS.`
	* `How can org increase performance and decrease latency by moving to Google Cloud?`
- `Options`
	- `A. Use Local SSDs.`
	- `B. Use SSD disks.`
	- `C. Use standanrd persistent disks.`
	- `D. Use balanced persistent disks.`
- `Answer`
	- `#A`
- `Explanation`
	- `#A -> Local SSDs offer the highest IOPS and the lowest latency because the storage is directly attached to the virtual machine.`
****

##### Question - 147
`Tags: #PaaS`
- `Statement`
	* `You are leading a team of developers on project whose goal is to improve customer experience on credit card company's website.The solution requires custom code without the overhead of managing OS or infra.`
	* `Which of the following offering would suggest for your client?`
- `Options`
	- `A. IaaS.`
	- `B. PaaS.`
	- `C. On-prem.`
	- `D. SaaS.`
- `Answer`
	- `#B`
- `Explanation`
	- `#B -> PaaS gives you env to develop and also allows you to manage code.`

****

##### Question - 148
`Tags: #Cloud Billing Budgets`
- `Statement`
	* `You work for a ridesharing company that has recently moved to Google Cloud. Jack, the senior manager of the corporate accounting group is worried about the bill and wants to track actual Google Cloud spend against planned spend. Jack also wants to receive alerts via email when certain budget expenditures are reached.`
	* `Which of the following actions should Jack take to meet these requirements?`
- `Options`
	- `A. Create Cloud Billing Budgets, set a budget amount, and set budget alert threshold rules.`
	- `B. Use Cloud Billing Reports with Google Data Studio.`
	- `C. Use Cloud Billing data export to BigQuery functionality with Google Data Studio.`
	- `D. Create a Cloud Billing account, set a budget amount, and set budget alert threshold rules.`
- `Answer`
	- `#A`
- `Explanation`
	- `#A -> `
		- `Helps customers to monitor Google cloud charges in one place.`
		- `Tracking of actual spends vs planned spend.`

****

##### Question - 149
`Tags: #BigTable`
- `Statement`
	* `Which of the following is a use of BigTable?`
- `Options`
	- `A. SQL support for an online transaction processing system.`
	- `B. Interactive querying in an online analytical processing system.`
	- `C. Real-time data sync between users.`
	- `D. NoSQL data operations for large analytical and operational workloads.`
- `Answer`
	- `#D`
- `Explanation`
	- `#D -> `
		- `Fully managed NoSQL DB.`
		- `Designed for large scaled apps.`
		- `High throughput and and low latency.`
		- `It's a DB for large analytical and operational workloads.`

****

##### Question - 150
`Tags: #Object Lifecycle Management`
- `Statement`
	* `A wearable startup collecting the health data of its users is adding approximately 50 TBS of data every month. The data is expected to grow to 200+ TB every year.`
	* `It is observed that the users are primarily concerned with the last 30 days of data and are ready to wait for data retrieval if data is older than 30 Days.`
	* `The company has decided that they will now store infrequently accessed data that is older than 30 days to minimize the cost, as this data is typically accessed no more than once per quarter.`
	* `To minimize manual intervention when moving data older than 30 days to Coldline storage from Standard storage, what should the company do?`
- `Options`
	- `A. Configure object lifecycle management.`
	- `B. Write a code and schedule it using Cloud Scheduler..`
	- `C. Configure Cloud Scheduler to move data on required conditions.`
	- `D. Configure an Object Lifecycle Management job using Cloud Scheduler.`
- `Answer`
	- `#A`
- `Explanation`
	- `#A -> `
		- `Movement of data from one storage class to another could be automated by configuring object lifecycle management.`
		- `Object lifecycle management allows the company setup rules that transfer objects from one storage to another based on age of data.`
****


##### Question - 151
`Tags: #data security, #shared responsibility`
- `Statement`
	* `Which areas are the responsibility of the customer for SaaS, PaaS, and IaaS services? (2 answers)`
- `Options`
	- `A. Devices (Mobile and PCs)`
	- `B. Information and Data.`
	- `C. Physical n/w.`
	- `D. Physical security of data center.`
- `Answer`
	- `#A and #B`
- `Explanation`
	- `#A -> `
		- `Customer to take care od devices used to access cloud services.`
	* `#B -> `
		* `In all models, data is customer's responsibility. `
	* `#Why not C? -> In SaaS and PaaS, n/w is managed by GCP. and same goes for D, all models data center is responsibility of GCP.`

****


##### Question - 152
`Tags: #RBAC`
- `Statement`
	* `An org is developing a business-critical application using Google App Engine. Which of the following should the org expect to do? (2 answers)`
- `Options`
	- `A. Establish role based access policies.`
	- `B. Encrypt data at rest.`
	- `C. Monitor applications' security.`
	- `D. Maintain n/w security.`
- `Answer`
	- `#A and #C`
- `Explanation`
	- `#A -> `
		- `Enforce RBAC (role based access control) policies to manage user permissions to access different parts of the application making sure authorized people has access.`
	* `#C -> `
		* `Detect and respond to potential threats and vulnerabilities. `
	* `#Why not B and D? -> N/w is managed by google cloud so not D and encrypting the data is google's job.`

****

****
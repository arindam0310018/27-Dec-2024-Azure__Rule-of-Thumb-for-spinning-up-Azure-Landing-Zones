# Rule of Thumb for spinning up Azure Landing Zones:-

Greetings to my fellow Technology Advocates and Specialists.

In this Session, I will provide my understanding on __Rule of Thumb for spinning up Azure Landing Zones.__

| __#__ | __OBJECTIVES__ | 
| --------- | --------- |
| 1. | __THE WHAT:__ What is the Purpose of Rule of Thumb for spinning up Azure Landing Zones ? |
| 2. | __THE WHY:__ Why is the Rule of Thumb for spinning up Azure Landing Zones required ? |
| 3. | __THE HOW:__ How to define Rule of Thumb for spinning up Azure Landing Zones required ? |

| __THE WHAT ?__ | 
| --------- |
| __Your organisation may have branch offices or subsidiaries spread across multiple countries.__ |

| __THE WHY ?__ | 
| --------- |
| __Azure Landing Zones should be provisioned in regions closest to where the workloads are deployed, But there needs to be some guidelines/principles otherwise we would have Landing Zones in every region.__ |  

| __THE HOW ?__ | 
| --------- |
| For this Article, we considered __all Azure Data Centers in Europe__: __AZURE EUROPE REGIONS.__ |

| __#__ | __REGIONS__ | __CITY__ |
| --------- | --------- | --------- | 
|  1.   | France Central       | Paris        |
|  2.   | France South         | Marseille    |
|  3.   | Germany Central      | Frankfurt    |
|  4.   | Germany North        | Berlin       |
|  5.   | Germany Northeast    | Magdeburg    |
|  6.   | Germany West Central | Frankfurt    |
|  7.   | Greece Central       | Athens       |
|  8.   | North Europe         | Dublin       |
|  9.   | West Europe          | Amsterdam    |
|  10.  | Italy North          | Milan        |
|  11.  | Norway East          | Oslo         |
|  12.  | Norway West          | Stavanger    |
|  13.  | Poland Central       | Warsaw       |
|  14.  | Spain Central        | Madrid       |
|  15.  | Sweden Central       | Gavle        |
|  16.  | Sweden South         | Staffanstorp |
|  17.  | Switzerland North    | Zurich       |
|  18.  | Switzerland West     | Geneva       |
|  19.  | UK South             | London       |
|  20.  | UK West              | Cardiff      |

| __RULE OF THUMB:-__ |
| --------- |

| __#__ | __CRITERIA__ | __DETAILS__ | __PRIORITY OF THE CRITERIA__ | __REMARKS__ |
| --------- | --------- | --------- | --------- | --------- |
| 1. | Requirement from No. of Projects ? | - | P1 | - |
| 2. | Anticipating Potential Future Region Trends. | - | P1 | Coordinating with Internal Stakeholders if the potential future region(s) can be used to the maximum. |
| 3. | Availability Zones. | If the Region Supports Availability Zones to provide higher Availability across multiple Zones. | P1 | Not all regions have three availability zones upon launch. |
| 4. | Business Continuity and Disaster Recovery. | If the region may not have a paired region, which could impact replication and disaster recovery strategies. | P1 | - |
| 5. | Scalability. | Region may have limited capacity to scale resources. | P1 | - |
| 6. | Cost. | Review the cost model as prices of Azure Services can vary between Regions. | P1 | - |
| 7. | Data Transfer. | Data Transfer between regions incur additional costs. | P1 | Evaluate Operational Impact. Time to migrate date depends upon - a.) Network Speed; and b.) Volume of Data. |
| 8. | Performance. | Test the Latency and Network Performance from Application to meet the required performance standards. | P1 | - |
| 9. | SLA. | SLAs are adjusted until they reach full operational maturity. | P2 | This is not for all Azure Services but Few. |
| 10. | Data Residency and Compliance. | Region should meet Compliance and Regulatory of the Organisation Domain. | P2 | - |
| 11. | Sustainability. | Region operates on renewable energy Sources. | P2 | Microsoft emphasizes on sustainable data centers. |

__Hope You Enjoyed the Session!!!__

__Stay Safe | Keep Learning | Spread Knowledge__

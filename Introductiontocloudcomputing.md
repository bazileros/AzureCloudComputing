# Introduction to cloud computing

## Learning objectives

---



- [ ] Define cloud computing

- [ ] Describe the shared responsibility model

- [ ] Define cloud models, including public, private, and hybrid

- [ ] Identify appropriate use cases for each cloud model

- [ ] Describe the consumption-based model

- [ ] Compare cloud pricing models.

---



## What is cloud computing

Cloud computing is the delivery of computing services over the internet.

- Virtual machine

- storage

- Databases

-  networking

- Internet of things (ioT)

- machine learning (ML)

- Artificial intelligence (AI)



### Advantages

- Compute power - is how much processing your computer can do

- Storage- Volume of data you can use use

---



## Describe the shared responsibility model

#### -  Traditional datacenter

Start with a traditional corporate datacenter. The company is responsible for maintaining the physical space, ensuring security, and maintaining or replacing the servers if anything happens. The IT department is responsible for maintaining all the infrastructure and software needed to keep the datacenter up and running. They’re also likely to be responsible for keeping all systems patched and on the correct version.

- Therefore the shared responsibility model is where these responsibilities get shared between the cloud provider and the consumer. Physical security, power, cooling and network connectivity are the responsibility of the cloud provider.

- the consumer is responsible for the data and information stored in the cloud. (You wouldn’t want the cloud provider to be able to read your information.) The consumer is also responsible for access security, meaning you only give access to those who need it.
  
  1. Infrastructure as a service (laas)
  
  2. Patform as a service (paas)
  
  3. Software as a service (saas)

### Cloud service types -:

1. Infrastructure as a service (laas)
   
   IaaS places the most responsibility on the consumer, with the cloud provider being responsible for the basics of physical security, power, and connectivity.

2. Patform as a service (paas)
   
   SaaS places most of the responsibility with the cloud provider

3. Software as a service (saas)
   
    PaaS, being a middle ground between IaaS and SaaS, rests somewhere in the middle and evenly distributes responsibility between the cloud provider and the consumer.
   
   |           | Responsibilities retained by customers | Responsibility  varies by type | resposibility transfers to cloud provider |
   |:---------:|:--------------------------------------:|:------------------------------:|:-----------------------------------------:|
   | SaaS      | customer - (10/10)                     | shared -  (3/10)               | microsoft - (0/10)                        |
   | PaaS      | customer- (10/10)                      | shared - (7/10)                | microsoft - (0/10)                        |
   | Laas      | customer - (10/10)                     | shared - (10/10)               | microsoft - (0/10)                        |
   | On - prem | customer - (10/10)                     | shared - (10/10)               | microsoft - (10/10)                       |



## Customers (Always responsible for: )

- The information and data stored in the cloud

- Devices that are allowed to connect to your cloud (cell phones, computers and so on...)

- The accounts and identities of the people, services, and devices within your organisation.

## Cloud provider (Always responsible for: )

- The physical datacenter
- The physical network
- The physical hosts

## Service Model

- Operating systems

- Network controls

- Applications

- Identity and infrastructure

---

# Define Cloud Models

Cloud models define the deployment type of cloud resourses

their 3 main cloud models 

```textile
1. Private Model
2. Public Model
3. Hyblid model
```

#### Private Cloud

Private cloud is a cloud that is used by a single entity.

- Provides alot of control for the company or IT department

- However it is costly and has fewer benefits

- It can be hosted from your own datacenter, offset datacenter and third party that has a data center dedicated for that company

- A private cloud is like having your own special computer system that only you can use. It's different from a regular computer because it can do a lot more things and it's connected to the internet. It's like having your own playground where you can control everything and decide what games to play. But having your own playground can be more expensive and you might not get all the fun things that other kids have in a public playground. Your private playground can be in your backyard or it can be in a special place just for you.



#### Public Cloud

A public cloud is built, controlled, and maintained by a third-party cloud provider

- Anyone that wants to purchase cloud services can access and use resources.

- The general public availability is a key difference between public and private clouds.

- A public cloud is like a big playground that is owned and taken care of by someone else. This playground is open to anyone who wants to come and play. You don't need to have your own toys or equipment because everything you need is already there. It's different from having your own private playground because you can't control who else gets to play in the public playground.



#### Hybrid Cloud

Hybrid cloud uses both public and private clouds, allowing private cloud to surge and providing extra security.

- A hybrid cloud environment can be used to allow a private cloud to surge for increased, temporary demand by deploying public cloud resources

- Users can flexibly choose which services to keep in public cloud and which to deploy to their private cloud infrastructure.

- A hybrid cloud is like having two types of clouds that work together. One cloud is like a private club that only certain people can use, and the other cloud is like a public park that anyone can use. Sometimes, when the private club gets really busy, it can borrow some space from the public park to make more room for people. This way, the private club can handle more people when there are a lot of them. It's also like having two lockers, one at home and one at school. You can choose which things you want to keep in your home locker and which things you want to keep in your school locker.



### Highlights of few key comparative aspects between cloud models.

| <mark>Public cloud</mark>                                                   | <mark>Private cloud</mark>                                                      | <mark>Hybrid cloud</mark>                                                    |
| --------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| **No** <u>capital expenditures</u> to *scale up*                            | **Organizations** have *complete control* over <u>resources and security</u>    | Provides the <u>most flexibility</u>                                         |
| **Applications** can be <u>quickly provisioned and deprovisioned</u>        | **Data** is <u>not collocated</u> with other organizations’ *data*              | **Organizations** *determine* where to <u>run their applications</u>         |
| **Organizations** <u>pay only for what they use</u>                         | **Hardware** must be *purchased* for <u>startup and maintenance</u>             | **Organizations control** <u>security, compliance, or legal requirements</u> |
| **Organizations** *don’t have complete control over resources and security* | **Organizations** are *responsible* for <u>hardware maintenance and updates</u> |                                                                              |



### Multi-cloud

- multi-cloud scenario, use multiple public cloud providers, different features, migrating, manage resources and security

- In a multi-cloud scenario, you use multiple public cloud providers. Maybe you use different features from different cloud providers. Or maybe you started your cloud journey with one provider and are in the process of migrating to a different provider. Regardless, in a multi-cloud environment you deal with two (or more) public cloud providers and manage resources and security in both environments.

- In a multi-cloud scenario, it means using more than one cloud provider. It's like having different stores where you can buy things. Sometimes you might go to one store because they have a toy you like, and other times you might go to a different store because they have a different toy you want. In the same way, people use different cloud providers for different things they need. It could be because one provider has a special feature they want or because they are moving from one provider to another. When you use multiple cloud providers, you have to manage and take care of your things in both places to make sure they are safe and working well.



### Azure Arc

Azure Arc is a set of technologies that helps manage your cloud environment.

- Azure Arc is like a special tool that helps people take care of their cloud environment. A cloud environment is like a big computer that stores and runs programs and data. It can be in different places, like on the internet or in a special room in a building. Azure Arc can help manage this cloud environment, no matter where it is. It's like having a remote control that can manage your TV no matter where you are in the house. So, whether your cloud is only on Azure, in your own computer room, or even in different places at the same time, Azure Arc can help you take care of it.



### Azure VMware Solution

- If you have a special way of running computer programs called VMware, but you want to move those programs to a different kind of computer system that is shared by many people, Azure VMware Solution can help you do that. It is like moving your toys from your room to a big play area where you can share and play with other kids. It makes sure your programs work well in the new place and can grow bigger if you need more space.







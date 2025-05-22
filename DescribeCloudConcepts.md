# MS Azure Fundamentals: Describe Cloud Concepts

## What is cloud computing
Cloud computing is the delivery of computing services over the internet. Computing services include common IT infrastructure such as virtual machines, storage, databases, and networking. Cloud services also expand the traditional IT offerings to include things like Internet of Things (IoT), machine learning (ML), and artificial intelligence (AI).

Because cloud computing uses the internet to deliver these services, it doesn’t have to be constrained by physical infrastructure the same way that a traditional datacenter is. That means if you need to increase your IT infrastructure rapidly, you don’t have to wait to build a new datacenter—you can use the cloud to rapidly expand your IT footprint.

Basic cloud services:
- Compute power - how much processing your computer can do. Add and remove compute power as you need it. This saves on cost since you only pay for the resources you use. 
- Storage - volume of data you can store on a computer. With cloud computing, request more storage as you need it. 
- Network - not mentioned here but usually considered third leg in stool.

---

## Describe the shared responsibility model
- Provider responsibilities:
    - Physical security, power, cooling, and network connectivity are the responsibility of the cloud provider.
    - Physical data center, network, and hosts.
- Consumer responsibilities:
    - The consumer is responsible for the data and information stored in the cloud.
    - The consumer is also responsible for access security, meaning you only give access to those who need it.
    - Information and data stored in the cloud, devices allowed to connect to the cloud, and accounts and identities of the people, services, and devices within organization.
- It depends:
    - If you’re using a cloud SQL database, the cloud provider would be responsible for maintaining the actual database. However, you’re still responsible for the data that gets ingested into the database.
    - If you deployed a virtual machine and installed an SQL database on it, you’d be responsible for database patches and updates, as well as maintaining the data and information stored in the database.
    - The service model will determine responsibility for operating systems, network controls, applications, and identity and infrastructure.

* Image: [Shared Responsibility Model](ms_azurefundamentals/images/SharedResponsibilityModel.png)

---

## Define cloud models

*Private cloud*
A private cloud is, in some ways, the natural evolution from a corporate datacenter. It’s a cloud (delivering IT services over the internet) that’s used by a single entity. Private cloud provides much greater control for the company and its IT department. However, it also comes with greater cost and fewer of the benefits of a public cloud deployment. Finally, a private cloud may be hosted from your on site datacenter. It may also be hosted in a dedicated datacenter offsite, potentially even by a third party that has dedicated that datacenter to your company.

*Public cloud*
A public cloud is built, controlled, and maintained by a third-party cloud provider. With a public cloud, anyone that wants to purchase cloud services can access and use resources. The general public availability is a key difference between public and private clouds.

*Hybrid cloud*
A hybrid cloud is a computing environment that uses both public and private clouds in an inter-connected environment. A hybrid cloud environment can be used to allow a private cloud to surge for increased, temporary demand by deploying public cloud resources. Hybrid cloud can be used to provide an extra layer of security. For example, users can flexibly choose which services to keep in public cloud and which to deploy to their private cloud infrastructure.

*Multi-cloud*
A fourth, and increasingly likely scenario is a multi-cloud scenario. In a multi-cloud scenario, you use multiple public cloud providers. Maybe you use different features from different cloud providers. Or maybe you started your cloud journey with one provider and are in the process of migrating to a different provider. Regardless, in a multi-cloud environment you deal with two (or more) public cloud providers and manage resources and security in both environments.

*Azure Arc*
Azure Arc is a set of technologies that helps manage your cloud environment. Azure Arc can help manage your cloud environment, whether it's a public cloud solely on Azure, a private cloud in your datacenter, a hybrid configuration, or even a multi-cloud environment running on multiple cloud providers at once.

*Azure VMWare Solution*
What if you’re already established with VMware in a private cloud environment but want to migrate to a public or hybrid cloud? Azure VMware Solution lets you run your VMware workloads in Azure with seamless integration and scalability.

* Image: [Cloud Model Table](ms_azurefundamentals/images/CloudModelTable.png)

---

## Describe the consumption-based model


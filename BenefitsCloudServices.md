# MS Azure Fundamentals: Describe the Benefits of Using Cloud Services

## Benefits of high availability and scalability in the cloud

*High availability*
It’s important the resources are available when needed. High availability focuses on ensuring maximum availability, regardless of disruptions or events that may occur.

Azure is a highly available cloud environment with uptime guarantees depending on the service. These guarantees are part of the service-level agreements (SLAs).

Service Level Agreement (SLA) - formal agreement between a service provider and customer that guarantees a state level of service. Could be with a service provider and also used within an organization such as an IT department and business users. 

Azure SLA is represented as a percentage related to the service or applications availability or up time. SLA also includes down time and any credit if SLA is not met. They have up time of 99%, 99.9%, 99.95%, and 99.99%. 

- 99% available: 1.68hrs/wk, 432mins/mo (7.2hrs/mo) down time.
- 99.9% available: 10mins/wk, 43.2mins/mo down time.

* Each Azure service has it's own SLA to ensure to optimize availability to the business needs.

*Scalability*
Scalability refers to the ability to adjust resources to meet demand. If you suddenly experience peak traffic and your systems are overwhelmed, the ability to scale means you can add more resources to better handle the increased demand.

The other benefit of scalability is that you aren't overpaying for services. Because the cloud is a consumption-based model, you only pay for what you use. If demand drops off, you can reduce your resources and thereby reduce your costs.

Scaling generally comes in two varieties: vertical and horizontal. Vertical scaling is focused on increasing or decreasing the capabilities of resources. Horizontal scaling is adding or subtracting the number of resources.

1. Vertical scaling - With vertical scaling, if you were developing an app and you needed more processing power, you could vertically scale up to add more CPUs or RAM to the virtual machine. Conversely, if you realized you had over-specified the needs, you could vertically scale down by lowering the CPU or RAM specifications.

2. Horizontal scaling - With horizontal scaling, if you suddenly experienced a steep jump in demand, your deployed resources could be scaled out (either automatically or manually). For example, you could add additional virtual machines or containers, scaling out. In the same manner, if there was a significant drop in demand, deployed resources could be scaled in (either automatically or manually), scaling in.

---

## Benefits of reliability and predictability in the cloud

*Reliability*
Reliability is the ability of a system to recover from failures and continue to function. It's also one of the pillars of the Microsoft Azure Well-Architected Framework. The cloud, by virtue of its decentralized design, naturally supports a reliable and resilient infrastructure.

*Predictability*
Predictability can be focused on performance predictability or cost predictability. Both performance and cost predictability are heavily influenced by the Microsoft Azure Well-Architected Framework.

Performance predictability focuses on predicting the resources needed to deliver a positive experience for your customers. Autoscaling, load balancing, and high availability are just some of the cloud concepts that support performance predictability.

Cost predictability is focused on predicting or forecasting the cost of the cloud spend. With the cloud, you can track your resource use in real time, monitor resources to ensure that you’re using them in the most efficient way, and apply data analytics to find patterns and trends that help better plan resource deployments.

You can even use tools like the Total Cost of Ownership (TCO) or Pricing Calculator to get an estimate of potential cloud spend.

---

## Benefits of security and governance in the cloud

*Security*
On the security side, you can find a cloud solution that matches your security needs. If you want maximum control of security, infrastructure as a service provides you with physical resources but lets you manage the operating systems and installed software, including patches and maintenance. If you want patches and maintenance taken care of automatically, platform as a service or software as a service deployments may be the best cloud strategies for you.

And because the cloud is intended as an over-the-internet delivery of IT resources, cloud providers are typically well suited to handle things like distributed denial of service (DDoS) attacks, making your network more robust and secure.

*Governance*
Whether you’re deploying infrastructure as a service or software as a service, cloud features support governance and compliance. Things like set templates help ensure that all your deployed resources meet corporate standards and government regulatory requirements. Plus, you can update all your deployed resources to new standards as standards change. Cloud-based auditing helps flag any resource that’s out of compliance with your corporate standards and provides mitigation strategies. Depending on your operating model, software patches and updates may also automatically be applied, which helps with both governance and security.

---

## Benefits of manageability in the cloud

*Management of the cloud* speaks to managing your cloud resources. In the cloud, you can: automatically scale resource deployment based on need, deploy resources based on a preconfigured template, removing the need for manual configuration, monitor the health of resources and automatically replace failing resources, receive automatic alerts based on configured metrics, so you’re aware of performance in real time.

*Management in the cloud* speaks to how you’re able to manage your cloud environment and resources. You can manage these: through a web portal, using a command line interface, using APIs, and using PowerShell.

---

## Knowledge check

1. Which type of scaling involves adding or removing resources (such as virtual machines or containers) to meet demand? Horizontal scaling
2. What is characterized as the ability of a system to recover from failures and continue to function? Reliability

---

## Additional resources

TODO: Complete this training
[Build great solutions with the MS Azure Well-Architected Framework](https://learn.microsoft.com/en-us/training/paths/azure-well-architected-framework/)
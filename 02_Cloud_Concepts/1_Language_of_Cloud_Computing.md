# The Language of Cloud Computing

Terms to Know:

### High Availability

In a traditional on-premise deployed application you have to manage your own hardware, you have physical access to your hardware and apps, and you can't just ad servers easily if one breaks or you get more traffic than your server can handle.

In a cloud deployed application you don't own the hardware, you can add more servers with the click of a button, and if the hardware fails you can replace it instantly. High Availability in the cloud depends on the number of virtual machines set up to cover each other in case one dies. This is done with a cluster which is an identical grouping of virtual machines.

High Availability does not mean "Infinite Availability".

### Reliability

High Availability does not mean your system is reliable. Reliability is about the fault tolerance and disaster recovery abilities of your system. The ability of a system to recover from failures and continue to function is called Resilience. 

To make ours systems more reliable, it is a good practice to Deploy to Multiple Locations. This gives you Global-scale Computing as well sa protects you from regional failures. 

It is also good practice to avoid creating a single point fo failure in your systems. To avoid this problem it is good to have resources in multiple locations. If one computer goes down, others can pick up the load.

### Scalability

In cloud computing Scalability is the process of adding more resources as needed. This is important because it's hard to predict when the most users will use the system. 

Since Azure has a perceivably unlimited number of servers, Azure will always be able to add more servers or increase the memory of CPU of existing resources to fulfill any needs your app may have. This is adding more resources to your pool of resources.

When we add more VMs or containers to handle larger loads, this is called Horizontal Scaling or Scaling Out. When we increase the power of our existing resources (CPU/RAM) this is called Vertical Scaling or Scaling Up. In typical cloud computing environments we usually prefer Horizontal Scaling.

### Security

Full control of teh security of your cloud environment. Patches, maintenance, network controls, and more. 

### Predictability

It is important for us to be able to predict the performance and cost of our systems. 

**Performance**: We want to deliver a consistent experience for our customers regardless of traffic. We use autoscaling, and load balancing, and high availability to provide a consistent customer experience.

**Costs**: We want to avoid any unexpected surprise charges. We also want to track and forecast resource usage (costs) in real time. Analytics can provide patterns and trends to optimize usage.

### Governance

The ability or capability to establish corporate standards for our different Azure deployed environments including restrictions on deployed resources when necessary. This allows us to create standardized environments that uphold to a corporate standard, and we can audit our existing resources.

### Manageability

We want the ability to mange the cloud using tools like Autoscaling, Monitoring, and Template-based Deployments.

We also want management in the cloud using the Azure Portal, CLI, and APIs.

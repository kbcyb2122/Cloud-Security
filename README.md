# Cloud-Security

The attached PDF shows a secure Azure Cloud configuration. While this architecture is secure enough, we can and should further harden setups by:
Locking the root account and limiting sudo access of the admin account on the jump box.
Implementing log monitoring on the jump box.
Implementing two-factor authentication for SSH login to the jump box.
Implementing a host firewall (UFW or IPtables) on the jump box.
Limiting jump box network access with a virtual private network (VPN).
Limiting the number of machines that our jump box can access

The fact that cloud networks are virtualized and defined by software gives them numerous security benefits:

- **Ground-up security**: From a security perspective, the cloud presents an opportunity to build a secure system from the beginning, as opposed to trying to implement new security measures on old systems.

- **Easy configuration**: Instead of having to learn the many different tools that will be included on a network, an administrator can use the cloud service provider's website portal or command line to create all their needed items.

- **Quick turnaround**: Compromised and insecure machines can be discarded and replaced quickly, at no additional cost to the organization.

- **Personalized networks from cloud providers:** Software and configuration-as-code allows cloud providers to deploy the specific network that engineers need for their circumstances. Security specialists can define the secure network they need, and the cloud provider can create and test the deployments, making the networks more dependable.

- **High availability and fault tolerance**: Without their own physical data centers, engineers can focus on deploying their machines in multiple places, and the provider can maintain the data center. This way, cloud networks are more robust against power outages, DoS attacks and other threats, as long as they are configured correctly.

- **Easy implementation**: Security controls can be implemented more easily, because they require only modifications to software-defined networking patterns. No complicated rearrangements of physical wiring are necessary.

- **Affordability**: Organizations can use powerful machines that they would not be able to afford if they had to purchase and maintain them themselves. For example, GPU processing units, which are very expensive to buy and very expensive to lose to an attacker.

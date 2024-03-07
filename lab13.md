# Author: Rebecca Childs
## Reading Notes:
### Lab 13

### How has virtualization evolved beyond desktops and servers?
This technology abstracts the network layer from physical hardware, enabling flexible and dynamic network provisioning. It allows creation of virtual networks, independent of the underlying physical infrastructure, offering features like:
Software-Defined Networking (SDN): Decouples network control from forwarding, allowing for centralized management and programmability of network behavior.
Network Function Virtualization (NFV): Replaces dedicated network hardware appliances with software running on virtual machines, increasing agility and cost efficiency.
Storage Virtualization: This technology abstracts physical storage resources, creating a pool of storage that can be dynamically allocated to applications and users.
### In the context of the Amazon IaaS Cloud Service Model, what does EC2 stand for?
EC2 stands for Elastic Compute Cloud.
It's a service that allows users to rent virtual computers, also known as instances, on which they can run their own applications. These virtual machines are scalable and can be easily provisioned and deprovisioned as needed, offering a pay-as-you-go model for compute resources.
### What types of storage does EC2 use, and how is EC2 web traffic managed?
Amazon Elastic Block Store (EBS): This provides persistent block-level storage volumes that attach to EC2 instances. EBS volumes are ideal for storing data that needs to survive instance restarts or terminations, such as databases or applications relying on specific configurations.
Amazon Simple Storage Service (S3): This offers object-level storage designed for scalability, durability, and cost-effectiveness. It's suitable for storing large amounts of unstructured data like backups, logs, or static website content.
Instance Store Volume: This provides temporary block-level storage directly attached to the EC2 instance. It's suitable for storing temporary data that doesn't need to persist beyond the instance's lifecycle, like temporary files or cache data.
Ephemeral Storage: This is temporary storage local to the instance itself. It's the least persistent option and suitable only for storing data that needs to be available during the instance's uptime, like temporary configurations or logs.
EC2 doesn't directly manage web traffic. However, it integrates with various services for load balancing and traffic distribution:

Application Load Balancer (ALB): This distributes incoming traffic across multiple healthy EC2 instances in your application, ensuring high availability and scalability. It's ideal for modern web applications and APIs.
Network Load Balancer (NLB): This distributes incoming traffic at the network layer, handling protocols like TCP and UDP. It's suitable for highly scalable applications requiring low latency and high throughput.
Classic Load Balancer: This is an older option offering basic load balancing functionality. While still supported, it's generally recommended to use ALB or NLB for new applications.
### What are the benefits of service-oriented architecture for customers of EC2 virtualized services?
Increased Agility and Scalability, Faster development and deployment, Improved Maintainability and Reusability, Service reuse, Enhanced Integration and Flexibility, Standardized interfaces, and Platform independence. 
### Analyze how cloud virtualization can promote equitable access to technology resources across diverse populations. How can this technology bridge cultural gaps and empower underserved communities?
Software as a Service (SaaS): Cloud platforms offer a wide range of software applications accessible through a web browser. This eliminates the need for individual software installations or compatibility concerns, making it easier for people with limited technical expertise to access essential tools and resources. Educational institutions and community centers can leverage SaaS solutions for learning management systems, communication tools, or productivity software, fostering greater participation in the digital world.
Ubiquitous access: Cloud-based resources can be accessed from any device with an internet connection, regardless of its specifications or operating system. This empowers individuals with limited access to high-end devices to still leverage powerful computing resources, promoting digital inclusion across diverse populations. Students can access learning materials and tools from any internet-connected device, overcoming limitations of personal computers or outdated hardware.
Localization and Language Support: Cloud platforms often offer localization features and language support, making technology more accessible to non-native speakers. This can be crucial for bridging the digital divide in multilingual communities, ensuring essential information and resources are available in preferred languages. Educational materials and government services can be translated and delivered through the cloud, promoting greater understanding and participation.
Cloud-based collaboration tools: Cloud platforms offer a variety of collaboration tools like document sharing, video conferencing, and project management software. This empowers geographically dispersed communities to work together on projects, share knowledge, and participate in online learning opportunities. This can be instrumental for fostering innovation and knowledge sharing within underserved communities, allowing them to connect with experts and resources beyond their immediate physical location.
## Things I want to learn more about:
N/A
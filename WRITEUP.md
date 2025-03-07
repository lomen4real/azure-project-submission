# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 



## My Analysis: Azure VM vs Azure App Service

### Azure Virtual Machines (VMs)

**Pros**:
- Full Control: Complete control over the OS, software, and configurations.
- Customizability: Ideal for specific configurations or unsupported software.
- Isolation: Dedicated environment for security and performance.

**Cons**:
- Management Overhead: Requires OS updates, security patches, and maintenance.
- Complexity: More complex to set up and manage.
- Cost: Can be more expensive, especially when idle.

### Azure App Service

**Pros**:
- Managed Service: Azure handles infrastructure, scaling, patching, and maintenance.
- Ease of Use: Simplifies deployment and management.
- Scalability: Built-in scaling features.
- Cost-Effective: More cost-effective for variable usage patterns.

**Cons**:
- Limited Control: Less control over the underlying infrastructure.
- Compatibility: May not support all required software or configurations.

### My choice:

For this project, I will be using **Azure App Service** due to its ease of use, managed infrastructure, and scalability. It allows for a more streamlined deployment process and reduces the management overhead, enabling us to focus on developing and deploying the application.


### Application Changes Based on Deployment Decision
Application Requirements and Infrastructure Control: Choosing to deploy the application on a Virtual Machine (VM) would provide more control over the infrastructure, allowing for custom configurations and installations that might be necessary for specific application requirements. This could include custom software, specific versions of dependencies, or advanced networking configurations. However, this approach requires more management and maintenance of the underlying infrastructure.

On the other hand, deploying the application using Azure App Service offers a more managed environment with built-in scaling, monitoring, and security features. This reduces the operational overhead and allows the development team to focus more on the application code rather than infrastructure management. However, it might have limitations in terms of custom configurations compared to a VM.

## Other Needs and Changes:

Scalability: If the application is expected to handle variable traffic loads, Azure App Service provides easier scaling options compared to a VM.
Maintenance: Using Azure App Service reduces the need for manual updates and maintenance of the server, which can be beneficial for smaller teams or projects with limited operational resources.
Compliance and Security: If the application has specific compliance or security requirements, deploying on a VM might offer more flexibility to implement custom security measures.
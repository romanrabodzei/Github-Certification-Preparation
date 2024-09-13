# GitHub Administration

**This certification validates your expertise in administering GitHub Enterprise.**
<p>
Candidates for this exam should have experience administering GitHub Enterprise, understand how GitHub is deployed, distributed, and licensed and how to provide support for GitHub Enterprise users. This exam measures your ability to accomplish the following technical tasks: manage user identities and GitHub authentication; manage access and permissions based on membership; enable secure software development and ensure compliance; and manage GitHub Actions and GitHub Packages.
</p>

> [!IMPORTANT]
> **These are NOT real questions from the exam, but quite close enough to what you can get. The goal is to help you to be prepared and obtain the certification.**

## Skills measured

- Support GitHub Enterprise for users and key stakeholders (15% of the exam)
- Manage user identities and GitHub authentication (20% of the exam)
- Describe how GitHub is deployed, distributed, and licensed (5% of the exam)
- Manage access and permissions based on membership (20% of the exam)
- Enable secure software development and ensure compliance (15% of the exam)
- Manage GitHub Actions (20% of the exam)
- Manage GitHub Packages (5% of the exam)

## Questions

As the IT manager preparing to integrate your organization's GitHub Enterprise Cloud with a System for Cross-domain Identity Management (SCIM) API, you are evaluating which Identity Providers (IdPs) are supported. Which three IdPs are officially supported by GitHub Enterprise Cloud for SCIM API integration with organizations?
<details><summary>Show the answer</summary><p>

- **Microsoft Entra ID**
> Microsoft Entra ID (formerly Azure Active Directory) supports SCIM API integration with GitHub Enterprise Cloud, allowing organizations to manage GitHub user accounts and team memberships directly through Microsoft's identity service
- **Okta**
> Okta is supported for SCIM API integration with GitHub Enterprise Cloud, enabling automated user and team provisioning and de-provisioning, facilitating efficient identity management across the organization
- **OneLogin**
> OneLogin is another IdP that supports SCIM API for GitHub Enterprise Cloud, offering similar benefits as Okta in terms of streamlining user account management directly from the identity provider's platform
</details>

---
You are tasked with improving the security and management of your company's GitHub Enterprise Cloud, you are exploring options for user management. What is the primary function of Enterprise Managed Users in GitHub?
<details><summary>Show the answer</summary><p>

- **To centrally manage identity and access of enterprise members on GitHub from an identity provider (IdP)**
> The primary function of Enterprise Managed Users in GitHub is to allow enterprises to centrally manage the identity and access of their members on GitHub directly from an identity provider (IdP). This feature facilitates the administration of user accounts, ensuring that access control and identity management are streamlined and secure, aligned with the company's IT policies
</details>

---
As a software development team leader, you're considering integrating apps and actions from the GitHub Marketplace into your projects. What are the benefits and risks associated with using these marketplace resources?
<details><summary>Show the answer</summary><p>

- **Benefits include automation of workflows and enhanced functionality; risks include potential security vulnerabilities and dependency on third-party services**
> Using apps and actions from the GitHub Marketplace can significantly automate workflows and enhance the functionality of projects, making development processes more efficient. However, these integrations also come with risks such as potential security vulnerabilities within the third-party services and a reliance on these services that might impact project continuity if they become unavailable
</details>

---
Which Docker command is used to publish a container image to GitHub Packages?
<details><summary>Show the answer</summary><p>

- **docker push ghcr.io/OWNER/IMAGE_NAME:TAG**
> The docker push command is used to upload a container image to a Docker registry. In the context of GitHub Packages, specifying ghcr.io/OWNER/IMAGE_NAME:TAG as the target allows you to push the image to the GitHub Container Registry under the specified owner's account, image name, and tag. This command is essential for developers looking to distribute their Docker images through GitHub Packages
</details>

---
How are GitHub Actions minutes consumed for jobs running on different operating systems?
<details><summary>Show the answer</summary><p>

- **Jobs on Windows and macOS consume minutes at 2 and 10 times the rate of jobs on Linux runners, respectively**
> In GitHub Actions, job execution times are billed differently based on the operating system of the runners. Jobs run on Windows and macOS consume minutes at higher rates compared to Linux runners, reflecting the cost associated with these platforms. Specifically, Windows runners consume minutes at twice the rate, and macOS runners consume minutes at ten times the rate of Linux runners. This is designed to account for the higher operational costs of Windows and macOS environments
</details>

---
What are the steps to utilize the Azure Pipelines GitHub App from the GitHub Marketplace for deploying your code?
<details><summary>Show the answer</summary><p>

- **Search for "Azure Pipelines" in the GitHub Marketplace, select the app, click "Install", and then follow the setup instructions to configure your deployment**
> To use Azure Pipelines for deploying your code, the first step is to find the app in the GitHub Marketplace. By searching for "Azure Pipelines", you can easily locate the app. After selecting it, you click on the "Install" button and proceed to configure your deployment by following the setup instructions provided. This process integrates Azure Pipelines with your GitHub repository, enabling continuous integration and deployment capabilities directly from your GitHub workflow.
</details>

---
You're exploring the differences between enabling SAML Single Sign-On (SSO) for a single organization versus for all organizations within an enterprise account. What is a key difference between these two approaches?
<details><summary>Show the answer</summary><p>

- **SAML SSO for a single organization allows for different Identity Providers (IdPs) for each organization, whereas enabling it for all organizations mandates a single IdP for the entire enterprise**
> Enabling SAML SSO for a single organization within GitHub Enterprise Cloud allows for flexibility in authentication methods, meaning each organization can integrate with its own Identity Provider (IdP). However, when SAML SSO is enabled for all organizations in an enterprise account, a single IdP must be used across the entire enterprise. This ensures a unified authentication strategy but reduces the flexibility for individual organizations
</details>

---
How can a self-hosted runner be integrated into a specific GitHub repository?
<details><summary>Show the answer</summary><p>

- **Access the repository settings, navigate to Actions then Runners, and follow the setup instructions to download, configure, and initiate the self-hosted runner software**
> Adding a self-hosted runner to a GitHub repository involves navigating to the repository’s settings, selecting the Actions tab, then choosing Runners. This section provides detailed instructions for downloading the self-hosted runner application, configuring it for the specific repository, and starting the runner service. This process ensures the runner is properly set up to execute workflows associated with the repository
</details>

---
What is the purpose of enterprise policies within GitHub Enterprise Cloud?
<details><summary>Show the answer</summary><p>

- **Enterprise policies establish uniform guidelines across all organizations within an enterprise, ensuring consistent governance and eliminating individual organization policy variations**
> Enterprise policies in GitHub Enterprise Cloud are designed to enforce uniform policies across all organizations within an enterprise. This ensures that governance and policy enforcement are consistent, providing centralized control over key aspects like repository management, security settings, and more, without allowing individual organizations to deviate with their own policies
</details>

---
Which package managers and formats does GitHub Packages support?
<details><summary>Show the answer</summary><p>

- **NuGet for .NET**
- **Maven for Java**
- **npm for JavaScript**
- **RubyGems for Ruby**
</details>

---
As an IT administrator implementing GitHub for your company's development processes, you're integrating GitHub Enterprise Cloud with your identity management. How are user accounts provisioned with Enterprise Managed Users?
<details><summary>Show the answer</summary><p>

- **User accounts are provisioned by the enterprise's IdP, with access provided to GitHub Enterprise Cloud**
> With Enterprise Managed Users, user accounts are provisioned directly by the enterprise's Identity Provider (IdP). This integration allows for seamless access management and provisioning, aligning GitHub access with the organization's existing identity management practices. It simplifies the administration of GitHub user accounts within the enterprise context
</details>

---
What are the security concerns associated with using self-hosted runners for public repositories?
<details><summary>Show the answer</summary><p>

- **Storing harmful data persistently**
> Malicious workflows could result in the persistence of dangerous data on the host machine, such as malware or tools for further exploitation, which could be used in subsequent attacks or to compromise the system
- **Disclosure of the network environment**
> The network environment could be exposed to unauthorized users through self-hosted runners, revealing sensitive information like IP addresses, network topology, or other resources accessible within the network
- **Execution of malicious programs on the host machine**
> Allowing self-hosted runners on public repositories can lead to the execution of malicious programs on the host machine, as untrusted code could be run as part of a workflow, posing a significant security risk
- **Breaching the runner's sandbox environment**
> Attackers could potentially escape the runner's sandbox environment, gaining unauthorized access to the host machine. This escape could lead to a broad range of malicious activities, including accessing sensitive data or affecting other processes
</details>

---
As the administrator of a GitHub Organization, you aim to ensure that all users authenticate using the company's identity provider. Which option should you implement to integrate corporate authentication?
<details><summary>Show the answer</summary><p>

- **Setup SAML SSO**
> "Setup SAML SSO" is the correct answer. By setting up SAML Single Sign-On (SSO), you can integrate GitHub with the corporate identity provider, allowing users to authenticate with their corporate credentials. This ensures a secure and centralized method of user authentication in line with corporate identity management policies
</details>

---
As a DevOps engineer tasked with setting up a collaborative environment for your company's software development projects, you're considering GitHub solutions. What is GitHub Enterprise Server primarily designed for?
<details><summary>Show the answer</summary><p>

- **A self-hosted platform for software development within your enterprise**
> GitHub Enterprise Server is designed as a self-hosted platform that allows enterprises to host their software development projects on their own infrastructure. This setup provides companies with control over their development environment while leveraging GitHub's tools and features for collaboration, version control, and project management within the confines of their enterprise security and compliance requirements
</details>

---
Is it possible to create nested teams within a GitHub organization, and how are they typically used?
<details><summary>Show the answer</summary><p>

- **Yes, nested teams are supported and commonly used to mirror an organization's internal structure**
> GitHub supports the creation of nested teams within organizations, allowing for a hierarchical structure that can closely reflect the internal organization of a company or enterprise. This feature enables more granular management of permissions, notifications, and code review assignments, facilitating efficient collaboration and access control across different levels of the organization
</details>

---
As an IT manager implementing GitHub Enterprise Cloud with Enterprise Managed Users, you need to understand how usernames and profile information are managed. Which statement accurately reflects this process?
<details><summary>Show the answer</summary><p>

- **Usernames and profile information are set through the enterprise's IdP and cannot be changed by the users**
> In the context of Enterprise Managed Users, usernames and profile information are indeed set through the enterprise's Identity Provider (IdP) and are not subject to change by the users. This policy ensures that user identities are consistent with the enterprise's directory services and adhere to its identity management protocols
</details>

---
Who is authorized to manage billing information within a GitHub organization?
<details><summary>Show the answer</summary><p>

- **Owner and Billing Manager**
</details>

---
In your role as an organization owner, you need to promote a team member to a higher role within your GitHub organization. How can you accomplish this task?
<details><summary>Show the answer</summary><p>

- **By navigating to the organization's settings, selecting Members, and then adjusting the member's role from the list**
> Organization owners can change the role of a member by accessing the organization's settings, choosing "Members," and then adjusting the roles accordingly. This method provides a direct and manageable way to handle role assignments within an organization
</details>

---
You're evaluating the scope of GitHub Support to address various issues. Which of the following issues can GitHub Support help resolve?
<details><summary>Show the answer</summary><p>

- **Assistance with GitHub account and billing queries**
- **Installing and using Advanced Security**
- **Installing and using GitHub Enterprise Server**
- **Identifying and verifying the causes of suspected errors**
</details>

---
What are the default permissions of a member in a GitHub organization?
<details><summary>Show the answer</summary><p>

- **Members can create private repositories (subject to the organization's policy) and participate in projects within the organization to which they are granted access**
> By default, members of a GitHub organization can create private repositories (if allowed by the organization's policies) and can participate in any project within the organization they have been given access to. This level of permission facilitates collaboration while allowing the organization to maintain control over repository creation and access
</details>

---
Which GitHub plan includes the feature to use secret scanning in private repositories?
<details><summary>Show the answer</summary><p>

- **Any GitHub Enterprise plan with a GHAS license**
> Secret scanning in private repositories is a feature included in any GitHub Enterprise plan that has a GitHub Advanced Security (GHAS) license. This feature helps organizations protect their code by automatically scanning repositories for known types of secrets, ensuring that sensitive information like passwords, tokens, and keys are not accidentally exposed
</details>

---
As a project manager overseeing your development team's use of GitHub Enterprise, you're addressing the needs of managed users who wish to contribute to projects outside of the enterprise. What must these users do to participate in external projects?
<details><summary>Show the answer</summary><p>

- **Managed users are not allowed to contribute to public resources, and they need a separate personal account for this purpose**
> Managed users within an enterprise environment are restricted from contributing to resources outside of their enterprise on GitHub to maintain security and compliance. As such, they need a separate personal account to participate in public projects or contribute to resources outside the enterprise. This policy ensures that enterprise controls and security policies are not circumvented
</details>

---
As an administrator tasked with overseeing your organization's use of GitHub Advanced Security, you're evaluating the different levels of support available to assist with its installation and usage. Which is the minimum level of support that provides help specifically for Advanced Security?
<details><summary>Show the answer</summary><p>

- **GitHub Enterprise Support**
> GitHub Enterprise Support is the correct answer. This level of support is designed for organizations utilizing GitHub Enterprise and includes assistance for installing and using Advanced Security features, ensuring that enterprises have the guidance and support needed for their security initiatives
</details>

---
As a project manager exploring collaborative platforms for your development team, you're evaluating GitHub for managing your projects. What is the primary purpose of creating a GitHub organization?
<details><summary>Show the answer</summary><p>

- **To allow businesses and open-source projects to collaborate across many projects at once with advanced security and administrative features**
> GitHub organizations are designed to support collaboration among team members on multiple projects, providing a structured environment with advanced security and administrative features. This setup is ideal for businesses and open-source projects looking for an efficient way to manage permissions, enforce policies, and streamline project management across their repositories
</details>

---
How is authentication to GitHub Packages typically performed?
<details><summary>Show the answer</summary><p>

- **By using a Personal Access Token (PAT) with the necessary scope**
> Authenticating to GitHub Packages requires a Personal Access Token (PAT) with the appropriate scope. This method ensures secure access and the ability to publish, install, and manage packages within GitHub. The PAT must be configured with the right permissions to interact with GitHub Packages, providing a secure way to authenticate and authorize package operations
</details>

---
How can a GitHub organization simplify access management and enhance collaboration among its members?
<details><summary>Show the answer</summary><p>

- **By creating nested teams that reflect the organization's structure, with cascading access permissions and mentions**
> Creating nested teams within a GitHub organization allows for a hierarchical structure that mirrors the organization itself. This approach simplifies access management by enabling cascading permissions, where access rights and mentions can be efficiently managed across different levels of the organization, thus enhancing collaboration among members
</details>

---
How can an organization admin set default permissions for new members in a GitHub organization?
<details><summary>Show the answer</summary><p>

- **In the organization's settings, under the Access section, choose Member privileges, then select a permissions level under Base permissions and confirm the change**
> An organization admin can set default permissions for new members by navigating to the organization's settings, selecting the Access section, then Member privileges, and finally choosing a permissions level under Base permissions. This process allows for the configuration of a default permission level that applies to all new members, ensuring consistent access rights across the organization
</details>

---
How can an organization improve the security of their GitHub Actions workflows?
<details><summary>Show the answer</summary><p>

- **By adopting practices like secure handling of secrets and regularly reviewing audit logs for anomalies**
> (Secure handling of secrets ensures that sensitive information is protected during the execution of GitHub Actions workflows. Regularly reviewing audit logs helps identify and investigate anomalous activities that could indicate security issues or breaches, making this approach effective for enhancing the security of GitHub Actions workflows
</details>

---
Is it possible to upload container images to GitHub Packages?
<details><summary>Show the answer</summary><p>

- **Yes, GitHub Packages supports the hosting of container images**
> GitHub Packages allows users to upload, store, and manage container images alongside their code and CI/CD workflows. This service supports Docker images and provides a seamless way to integrate container management into the GitHub ecosystem. By leveraging GitHub Packages, developers can easily publish and share container images within their projects or with others, enhancing collaboration and distribution of software
</details>

---
You decide to utilize a GitHub feature that visualizes a repository's ecosystem of packages. What is this feature called that displays both the dependencies of the project and the projects dependent upon it?
<details><summary>Show the answer</summary><p>

- **GitHub dependency graph**
> The GitHub dependency graph is the correct answer. It provides a visual representation of a repository's dependencies (the packages and repositories that the repository depends on) and its dependents (the packages and repositories that depend on the repository). This feature helps developers understand and manage the relationships within their project's software supply chain)
</details>

---
Which type of runners should be utilized for GitHub Actions when an IP allow list is active for your enterprise?
<details><summary>Show the answer</summary><p>

- **Self-hosted runners or specific GitHub-hosted runners with defined static IP ranges**
> When an IP allow list is enabled for an enterprise, it's essential to use runners that comply with the IP restrictions imposed by the allow list. Self-hosted runners, which can be configured within an allowed IP range, or GitHub-hosted runners that offer static IP addresses, ensure that GitHub Actions workflows can operate within the security parameters set by the enterprise. This approach maintains the integrity of the enterprise's network security by only permitting actions from known, allowed IP addresses
</details>

---
How can you ensure communication between your self-hosted or specific GitHub-hosted runners and GitHub when an IP allow list is active?
<details><summary>Show the answer</summary><p>

- **Include your runners' IP addresses or ranges in the enterprise's IP allow list settings**
> To ensure that self-hosted or designated larger GitHub-hosted runners can communicate with GitHub when an IP allow list is in use, you need to add the IP addresses or IP address ranges of those runners to the IP allow list configured for your enterprise. This action allows these specific runners to be recognized and authorized to interact with GitHub's servers, ensuring that your workflows and actions can run smoothly without being blocked by the IP restrictions in place
</details>

---
Where can GitHub Enterprise Server be deployed?
<details><summary>Show the answer</summary><p>

- **On-premises data center or to a public cloud service (e.g., AWS, GCP, Azure)**
</details>

---
What is the primary purpose of the audit log for organization admins within a GitHub organization?
<details><summary>Show the answer</summary><p>

- **The audit log enables organization admins to track and review actions performed by members, providing critical insights for security and compliance monitoring**
> The audit log is a comprehensive tool that records various activities within the organization, such as user actions, team changes, and repository settings adjustments. It helps organization admins to monitor security, track changes, and ensure compliance by providing detailed information about who performed an action, what the action was, and when it was done
</details>

---
As a systems administrator tasked with enhancing your company's development infrastructure, you're considering implementing GitHub Enterprise Server. Which of the following is a key feature of GitHub Enterprise Server?
<details><summary>Show the answer</summary><p>

- **Runs on your infrastructure and governed by access and security controls you define**
> A defining feature of GitHub Enterprise Server is its ability to run on your own infrastructure, offering you full control over access and security measures according to your organization's policies. This self-hosted solution enables enterprises to manage their development environment closely, ensuring that their projects are secure and compliant with internal standards
</details>

---
Who is authorized to edit a team within a GitHub organization?
<details><summary>Show the answer</summary><p>

- **Team maintainers or organization admins**
> Within a GitHub organization, the ability to edit a team, including changing its settings or membership, is restricted to team maintainers and organization admins. This ensures that only individuals with the necessary permissions can make significant changes to a team's configuration, maintaining the integrity and structure of the organization's collaborative environment
</details>

---
Which GitHub Support level provides SLA and written support in English 24/7?
<details><summary>Show the answer</summary><p>

- **GitHub Premium Support**
> GitHub Premium Support is designed for organizations that require around-the-clock assistance with guaranteed response times, as defined by a Service Level Agreement (SLA). This level of support provides written support in English 24/7, catering to the needs of businesses with critical operations that depend on GitHub
</details>

---
As an administrator setting up a new project in your GitHub organization, you're considering involving external experts as collaborators. How does the role of an outside collaborator differ from that of a member within your organization?
<details><summary>Show the answer</summary><p>

- **Outside collaborators are assigned access on a repository-by-repository basis, while members may have broader permissions within the organization depending on their role**
> Outside collaborators in a GitHub organization are given access to specific repositories on an individual basis, which is ideal for working with people outside your organization on particular projects without granting them broader permissions that members might have. This allows for flexible and secure collaboration
</details>

---
What is the main difference between visible and secret teams in a GitHub organization?
<details><summary>Show the answer</summary><p>

- **Visible teams are open to all organization members, while secret teams are private, only seen by team members and owners**
> The primary distinction lies in visibility and mentionability; visible teams are accessible to all members of the organization for viewing and mentioning, whereas secret teams offer a layer of privacy, visible only to their members and the organization's owners, ideal for sensitive or confidential work
</details>

---
What are the implications of deploying within a single organization compared to multiple organizations on platforms like GitHub?
<details><summary>Show the answer</summary><p>

- **Multiple organizations increase operational flexibility but come with higher complexity and potential cost**
> Creating multiple organizations can cater to the specific needs of different projects or teams, offering tailored access controls and the ability to manage resources and permissions more precisely. This approach enhances operational flexibility but also introduces additional complexity in terms of management and oversight. Furthermore, depending on the platform's pricing structure, managing multiple organizations could result in higher costs
- A single organization simplifies administrative overhead but may not provide sufficient project isolation
> Using a single organization can streamline the management process by centralizing teams, permissions, and repositories, thus reducing the administrative burden. However, it might not adequately segregate different projects or teams, especially if they have distinct operational requirements or need to be isolated for security or organizational reasons
</details>

---
What is the primary purpose of enterprise accounts in GitHub Enterprise Cloud?
<details><summary>Show the answer</summary><p>

- **To provide administrators with a single point of visibility and management across multiple organizations**
> Enterprise accounts in GitHub Enterprise Cloud are designed to give administrators a unified view and control over multiple organizations within the enterprise. This facilitates easier management of policies, security, and compliance across all organizations under the enterprise account
</details>

---
What is the default spending limit for GitHub Actions on monthly-billed accounts?
<details><summary>Show the answer</summary><p>

- **The default spending limit is $0, preventing additional usage beyond the included amounts**
> The default spending limit for GitHub Actions on monthly-billed accounts is set to $0. This limit is in place to prevent any additional charges beyond the free tier unless the account owner decides to increase the limit manually. It serves as a control mechanism to avoid unexpected charges
</details>

---
As an administrator, how do you ensure a user has the least privilege necessary for accessing a particular repository in your GitHub organization?
<details><summary>Show the answer</summary><p>

- **Grant the user 'Read' access as an outside collaborator to the specific repository, allowing them to clone the repository without the capability to push changes**
> Adding a user as an outside collaborator with 'Read' access to a specific repository is the most straightforward way to grant the necessary permissions for accessing the repository without overprivileging. This allows the user to view and clone the repository, aligning with the principle of least privilege
</details>

---
You're interested in enhancing your GitHub repositories with additional functionalities by installing a new GitHub App from the GitHub Marketplace. What are the correct steps to follow for installing a GitHub App for your organization?
<details><summary>Show the answer</summary><p>

- **Browse GitHub Marketplace, select the app, choose a plan, select the organization, and then review and install the app**
> The proper process involves browsing the GitHub Marketplace to find the desired app, selecting a suitable plan for your needs, choosing the organization where the app will be installed, and finally reviewing the permissions and installation settings before confirming the installation. This streamlined process ensures that the app is correctly configured and associated with your organization
</details>

---
As a network engineer tasked with managing the GitHub Enterprise Server for your organization, you're exploring various administration options. How can GitHub Enterprise Server's administration be handled?
<details><summary>Show the answer</summary><p>

- **Via browser, administrative SSH access, and REST or GraphQL APIs**
> GitHub Enterprise Server offers a flexible administration approach that can be handled via a web browser for UI-based management, administrative SSH access for command-line operations, and REST or GraphQL APIs for automated or programmable interactions. This multifaceted approach allows administrators to choose the method that best fits their operational needs and preferences, providing the ability to manage configurations, user access, and other server settings effectively
</details>

---
As a GitHub Enterprise Server administrator, you are required to generate a support bundle for troubleshooting purposes. Which of the following steps correctly outline the procedure for doing so?
<details><summary>Show the answer</summary><p>

- **Generate and download a support bundle directly to your local machine via SSH using the ghe-support-bundle -o > support-bundle.tgz CLI command**
> Using the ghe-support-bundle command via SSH is a valid and efficient way to generate a support bundle from the server. This command allows administrators to specify options and directly download the bundle to their local machine for analysis or to share with GitHub support
- **Navigate to your GitHub Enterprise Server instance, select the Site admin page, then Management Console. Choose Support in the top navigation bar and click "Download support bundle."**
> This method is a direct way to generate and download a support bundle from the GitHub Enterprise Server's web interface. It is designed for administrators to easily access diagnostic information without needing command-line access
</details>

---
In a GitHub organization, which role possesses the highest level of access?
<details><summary>Show the answer</summary><p>

- **Owner**
</details>

---
Which features are exclusively provided by GitHub Enterprise Cloud compared to the GitHub Free plan?
<details><summary>Show the answer</summary><p>

- **Ability to restrict email notifications to verified domains**
> The capability to restrict email notifications to verified domains enhances security and communication management within organizations, a feature beyond the scope of the GitHub Free plan
- **Privately published GitHub Pages sites**
> The ability to publish GitHub Pages sites privately is an advanced feature that caters to the needs of enterprises requiring privacy for their project documentation or sites, not offered in the free plan
- **SAML authentication**
> SAML authentication is an enterprise-grade feature that allows organizations to integrate GitHub with their identity providers for single sign-on, not available in the GitHub Free plan
- **Additional GitHub Actions minutes**
> GitHub Enterprise Cloud provides additional GitHub Actions minutes beyond what is available in the GitHub Free plan, supporting more extensive automation and CI/CD workflows
</details>

---
How can an enterprise monitor its GitHub Actions usage?
<details><summary>Show the answer</summary><p>

- **By utilizing webhooks for workflow jobs and runs, and incorporating a data archiving strategy**
> Organizations can track GitHub Actions usage efficiently by setting up webhooks to receive real-time information on workflow jobs and runs. Pairing this data collection with a data archiving system enables comprehensive analysis and reporting on usage metrics. This method provides accurate, detailed insights into how GitHub Actions are utilized within the company, helping to optimize resources and understand workflow efficiency
</details>

---
What is a key advantage of having an enterprise account on GitHub Enterprise Cloud for an organization?
<details><summary>Show the answer</summary><p>

- **It allows owners to centrally manage policy and billing for multiple organizations**
> One of the primary advantages of having an enterprise account on GitHub Enterprise Cloud is that it enables owners to centrally manage policies and billing across multiple organizations within the enterprise. This central management simplifies administrative tasks and ensures cohesive policy enforcement and financial oversight
</details>

---
In your role as a GitHub organization administrator, you're outlining responsibilities for new team roles. What is the primary responsibility of a billing manager in a GitHub organization?
<details><summary>Show the answer</summary><p>

- **Managing billing settings for the organization, including updating payment methods and reviewing invoices**
> The primary responsibility of a billing manager in a GitHub organization is to manage the billing settings, which includes tasks such as updating payment methods and reviewing invoices. This role is crucial for ensuring that the organization's financial account with GitHub is in good standing and accurately reflects the services used
</details>

---
In which formats can GitHub audit logs be exported?
<details><summary>Show the answer</summary><p>

- **JSON and CSV**
</details>

---
In a software development company's GitHub organization, what is the primary responsibility of a Security Manager?
<details><summary>Show the answer</summary><p>

- **They oversee security alerts and configure code security settings across the organization, with read access to all repositories**
> A Security Manager's main role is to monitor security alerts and manage code security settings to ensure the organization's code is protected. This includes having read access to all repositories to oversee security without making direct changes to the code
</details>

---
As a GitHub Enterprise administrator tasked with enhancing the security of your organization's GitHub account, you're planning to enable and enforce SAML Single Sign-On (SSO). What are the correct steps to accomplish this for a single organization?
<details><summary>Show the answer</summary><p>

- **Access Organization Settings, click Security, enable SAML SSO, add IdP URL, test the configuration, and opt to enforce SAML SSO upon successful testing**
> This option outlines the correct process for enabling and enforcing SAML SSO in a GitHub Enterprise organization. The steps include accessing the organization settings, navigating to the security section, enabling SAML SSO, adding the Identity Provider (IdP) URL, testing the configuration to ensure it works correctly, and finally enforcing SAML SSO after successful testing
</details>

---
As a system administrator responsible for your organization's GitHub Enterprise Server, you're tasked with implementing best practices to prevent data loss. What does GitHub recommend for this purpose?
<details><summary>Show the answer</summary><p>

- **Establishing a plan for disaster recovery and configuring backups**
> GitHub recommends establishing a comprehensive plan for disaster recovery and configuring regular backups for GitHub Enterprise Server. This approach ensures that data is safeguarded against loss due to system failures, human errors, or other unforeseen issues, providing a reliable means to restore the server and its data to a known good state in case of disaster
</details>

---
Which is the main restriction of Enterprise Managed User accounts in GitHub Enterprise Cloud?
<details><summary>Show the answer</summary><p>

- **They cannot interact with public repositories outside their enterprise**
> The main restriction of Enterprise Managed User accounts in GitHub Enterprise Cloud is that they cannot interact with public repositories outside their enterprise. This limitation is designed to ensure that enterprise policies and security measures are adhered to, by controlling the scope of user activities within the confines of the enterprise's GitHub environment
</details>

---
What is the main difference between GitHub Enterprise Cloud and GitHub Enterprise Server in terms of hosting?
<details><summary>Show the answer</summary><p>

- **GitHub Enterprise Cloud is hosted by GitHub, while GitHub Enterprise Server is hosted on your own servers**
> The primary distinction between GitHub Enterprise Cloud and GitHub Enterprise Server lies in their hosting models. GitHub Enterprise Cloud is a cloud-hosted solution managed by GitHub, providing scalability and ease of access without the need for internal infrastructure, whereas GitHub Enterprise Server is an on-premises solution that allows organizations to host their own instance of GitHub, giving them control over their data and integration with internal tools
</details>

---
How should workflows be configured with runners to meet specific workload requirements efficiently?
<details><summary>Show the answer</summary><p>

- **Opt for self-hosted runners for tailored environments or GitHub-hosted runners for automated updates and isolated environments**
> Selecting the appropriate type of runner depends on the specific needs of your workflow. Self-hosted runners are ideal for customized environments where specific software or hardware configurations are necessary that GitHub-hosted runners cannot provide. On the other hand, GitHub-hosted runners offer the advantage of automatic updates and clean, isolated instances for each job, ensuring a consistent and secure environment
</details>

---
You are tasked with generating and sharing diagnostic files to support troubleshooting efforts. Which of the following methods are correct for accomplishing this?
<details><summary>Show the answer</summary><p>

- **Create a diagnostic file from the Management Console by navigating to the Support tab and clicking "Download diagnostics info."**
> Creating a diagnostic file directly from the Management Console is another correct method. This approach allows administrators to easily download diagnostic information via the web interface, simplifying the process of sharing this data with GitHub support
- **Use the ghe-diagnostics command-line utility to retrieve the diagnostics for your instance**
> The ghe-diagnostics command-line utility is a valid method for retrieving diagnostic information from your GitHub Enterprise Server instance. It provides a straightforward way to collect necessary data for troubleshooting
</details>

---
As a security administrator setting up GitHub Enterprise Cloud for your organization, you're configuring user access through managed user accounts. What is required for a user to authenticate with these accounts?
<details><summary>Show the answer</summary><p>

- **Users must authenticate on the enterprise's IdP to access resources on GitHub.com**
> For managed user accounts in GitHub Enterprise Cloud, users authenticate using the enterprise's Identity Provider (IdP). This setup ensures that access to GitHub.com resources is secure and managed centrally, aligning with the enterprise's overall security policies and allowing for single sign-on capabilities
</details>

---
What authentication method is necessary for downloading or publishing to GitHub Packages within GitHub Actions workflows or other CI/CD platforms?
<details><summary>Show the answer</summary><p>

- **Utilize the GITHUB_TOKEN for publishing packages linked to the workflow's repository and a Personal Access Token (PAT) for installing packages from private repositories**
> For workflows, such as those in GitHub Actions, the GITHUB_TOKEN is used to authenticate for publishing packages that are associated with the repository triggering the workflow. This provides a seamless integration for CI/CD pipelines to publish new package versions automatically. For installing or accessing packages from private repositories, a Personal Access Token (PAT) with the appropriate permissions is required. This ensures secure access to private packages while maintaining the automation of the CI/CD pipeline
</details>

---
What role do teams play within a GitHub organization?
<details><summary>Show the answer</summary><p>

- **Teams manage repository access, handle notifications, and allow hierarchical organization with nested teams**
> In GitHub organizations, teams are key for managing permissions and notifications efficiently, enabling administrators to assign access levels, utilize mentions for targeted notifications, and organize teams into a hierarchical structure that mirrors the organizational setup
</details>

---
In a GitHub organization, which role is responsible for managing access to the organization's resources?
<details><summary>Show the answer</summary><p>

- **Organization owner**
> The organization owner has full administrative access to the organization, including the authority to manage access to the organization's resources, settings, and member roles. This role is crucial for ensuring that the right individuals have the appropriate level of access to the organization's projects and resources
</details>

---
You are a software developer looking to optimize CI/CD workflows for your open-source project hosted on GitHub. You're considering the cost implications of using GitHub Actions. How does GitHub bill for GitHub Actions usage in public repositories?
<details><summary>Show the answer</summary><p>

- **GitHub Actions usage is free for public repositories**
> GitHub Actions is free for public repositories, encouraging open-source collaboration and continuous integration/continuous deployment (CI/CD) practices without additional cost. This policy supports the open-source community by providing essential automation tools at no charge, facilitating development, testing, and deployment processes
</details>

---
How can an organization admin effectively search for webhook modification events in the audit log?
<details><summary>Show the answer</summary><p>

- **By using the operation qualifier, such as operation:modify, to locate events where a resource like a webhook was altered**
> Organization admins can use specific qualifiers like operation:modify in their search queries within the audit log to pinpoint events where an existing resource, such as a webhook, has been modified. This method allows for precise and efficient searches related to specific actions on resources
</details>

---
What information is accessible on a GitHub organization's team page?
<details><summary>Show the answer</summary><p>

- **Team members, child teams, the team's repositories, and settings for updating the team's description and profile picture**
> A team's page within a GitHub organization includes details about its members, any child teams, the repositories they have access to, and settings that allow for the modification of the team's description and profile picture. This provides a comprehensive overview of the team's structure and resources within the organization
</details>

---
Which of the following are true about the benefits and drawbacks of creating a new organization on GitHub?
<details><summary>Show the answer</summary><p>

- **Benefit: Enables structured permission management across multiple projects**
> Creating a new organization allows for structured permission management, making it easier to control access across different projects and repositories
- **Benefit: Facilitates collaboration by organizing teams around specific projects or initiatives**
> Organizations help facilitate collaboration by enabling the creation of teams that can focus on specific projects or areas, improving efficiency and teamwork
- **Drawback: Increases administrative overhead with more entities to manage**
> While organizations offer many collaboration and management benefits, they also introduce additional administrative responsibilities, including managing members, teams, and permissions
</details>

---
How can an organization create and configure a self-hosted runner group on GitHub?
<details><summary>Show the answer</summary><p>

- **Access the organization's settings, choose Actions, select Runner groups, then create a new group and define the repository access policy**
> The process for creating a self-hosted runner group within an organization on GitHub involves navigating to the organization's settings, selecting the Actions tab, and then the Runner groups option. From there, the organization can create a new runner group and assign specific repository access policies to it. This allows for precise control over which repositories can use the runners within the group, enhancing security and efficiency in workflow management
</details>

---
What are the effects and potential abuse vectors of enabling self-hosted runners on public repositories?
<details><summary>Show the answer</summary><p>

- **Unauthorized access to the runner if not securely configured**
> One of the risks of self-hosted runners, especially when used with public repositories, is the potential for unauthorized access if the runner is not securely configured, leading to security vulnerabilities
- **Exposure of sensitive environment variables or secrets**
> If not properly managed, self-hosted runners might expose sensitive information, such as environment variables or secrets, especially when used in conjunction with public repositories
- **Consumption of server resources by malicious workflows**
> Malicious workflows can consume server resources on self-hosted runners, leading to potential denial of service attacks or increased costs for the host
</details>

---
Within a GitHub organization's team, what positions can a team member occupy?
<details><summary>Show the answer</summary><p>

- **Team maintainer, Team member**
> In GitHub teams, individuals can hold the roles of "Team maintainer" and "Team member." Team maintainers have permissions to manage team settings, including adding or removing team members, while team members are part of the team with access to team repositories based on the permissions granted to the team
</details>

---
What factors should be considered when analyzing the consumption of metered products like GitHub Actions minutes or storage for GitHub Packages?
<details><summary>Show the answer</summary><p>

- **The type of workflows triggering GitHub Actions and their frequency**
> The consumption of GitHub Actions minutes is significantly influenced by the type and frequency of workflows executed. More complex or frequent workflows will consume more minutes
- **The size and number of packages stored in GitHub Packages**
> For GitHub Packages, the total storage consumed is directly related to the size and number of packages hosted. Larger or more numerous packages will result in higher storage usage
- **The pricing plan selected by the organization**
> The organization's selected pricing plan can impact how consumption is billed or metered, with different plans offering varying amounts of included minutes or storage, affecting overall costs
</details>

---
How does the SCIM protocol facilitate identity management in GitHub?
<details><summary>Show the answer</summary><p>

- **By automating user and team synchronization between GitHub and identity providers**
> The SCIM protocol supports automated user and team synchronization, enabling organizations to manage GitHub users and teams efficiently through their identity provider. This automation helps in keeping user data consistent across platforms
</details>

---
What is the purpose of Teams within a GitHub organization?
<details><summary>Show the answer</summary><p>

- **To group organization members who share common responsibilities, enabling simplified repository access management and collaboration**
> Teams within a GitHub organization are designed to group members based on their roles or project involvement, facilitating easier management of repository permissions, enhancing collaboration, and streamlining communication among team members
</details>

---
What makes webhooks a preferable choice over audit logs or API polling for tracking events in GitHub organizations?
<details><summary>Show the answer</summary><p>

- **Webhooks deliver instant notifications for specific events, reducing the need for frequent audit log checks or API polling**
> Webhooks are designed to provide real-time event notifications, making them highly efficient for scenarios where immediate updates are essential. This feature eliminates the inefficiencies associated with regularly searching through audit logs or continuously polling the API to detect changes or events
</details>

---
How is pricing for GitHub Actions determined for public repositories?
<details><summary>Show the answer</summary><p>

- **GitHub Actions usage is free for public repositories**
> GitHub Actions provides unlimited minutes for public repositories, making it free to use for open-source projects. This encourages the development and CI/CD automation of open-source software without incurring additional costs
</details>

---
As an IT administrator configuring user access for your organization's GitHub Enterprise Cloud, you're exploring how to automate user account management. What does SCIM stand for and how is it utilized in the context of GitHub?
<details><summary>Show the answer</summary><p>

- **SCIM is a protocol for automating identity provisioning and management, integrating with Identity Providers to manage memberships in GitHub Enterprise Cloud**
> SCIM, or System for Cross-domain Identity Management, is indeed a protocol designed for automating the management and provisioning of user identities. In GitHub, it enables seamless integration with external Identity Providers (IdPs) to efficiently manage organization memberships and user accounts in GitHub Enterprise Cloud, demonstrating its role in streamlining administrative tasks and enhancing security
</details>

---
What is the primary rate limit for authenticated personal users making REST API requests to GitHub API?
<details><summary>Show the answer</summary><p>

- **5,000 requests per hour**
> Authenticated personal users can make up to 5,000 requests per hour to the GitHub API, which allows for efficient interaction with GitHub's resources and services
</details>

---
What strategy should be employed for managing and leveraging reusable components in GitHub Actions?
<details><summary>Show the answer</summary><p>

- **Utilize a central repository for shared actions and workflows, adopt consistent naming conventions, and plan for regular updates and maintenance**
> Employing a central repository for storing shared GitHub Actions and workflows, along with consistent naming conventions, facilitates easy discovery and use of these components. Regular updates and maintenance ensure that the reusable components remain effective and secure over time
</details>

---
Before employing git filter-repo or BFG Repo-Cleaner to remove sensitive data from your repository, which preliminary action is recommended?
<details><summary>Show the answer</summary><p>

- **Merge or close all open pull requests**
> Merging or closing all open pull requests is recommended before running git filter-repo or BFG Repo-Cleaner to ensure that the cleanup process does not interfere with or disrupt the ongoing work. This step helps maintain the integrity and continuity of the project development
</details>

---
What is a primary effect of configuring IP allow lists for GitHub-hosted runners?
<details><summary>Show the answer</summary><p>

- **It restricts which IP addresses can interact with GitHub-hosted runners, enhancing security**
> Configuring IP allow lists for GitHub-hosted runners is a security measure that restricts runner access to only those IP addresses specified in the allow list. This helps protect your workflows and resources from unauthorized access
</details>

---
How can GitHub APIs extend the capabilities of administrators beyond the user interface?
<details><summary>Show the answer</summary><p>

- **By allowing the automation of tasks such as querying the audit log and integrating with external tools**
> GitHub APIs can significantly extend the capabilities of administrators beyond what is available through the GitHub user interface. They allow for the automation of various tasks, including querying the audit log, managing organization and repository settings, and integrating GitHub data with external tools and systems. This flexibility enables administrators to tailor GitHub's functionality to better suit the enterprise's specific needs and workflows
</details>

---
What management option is exclusive to GitHub Enterprise Cloud for handling user accounts?
<details><summary>Show the answer</summary><p>

- **Using Enterprise Managed Users to create and manage user accounts through your Identity Provider (IdP)**
> GitHub Enterprise Cloud offers the exclusive feature of Enterprise Managed Users, allowing administrators to centrally manage user accounts and authentication through their Identity Provider (IdP). This integration simplifies user account lifecycle management, aligning with enterprise security and compliance standards
</details>

---
What is recommended for enhancing code collaboration within developer workflows?
<details><summary>Show the answer</summary><p>

- **Implementing a fork-and-pull model for external contributors and a branching model for internal collaboration**
> Utilizing a fork-and-pull model for external contributors alongside a branching model for internal team collaboration strikes a balance between maintaining code quality and encouraging contributions. This approach allows for rigorous code review and integration testing while accommodating contributions from a broader community
</details>

---
How can you authenticate to GitHub Packages to publish a package?
<details><summary>Show the answer</summary><p>

- **By embedding a Personal Access Token (PAT) with the appropriate permissions in your configuration**
> To publish a package to GitHub Packages, you must authenticate using a Personal Access Token (PAT) with the appropriate permissions. This ensures secure access control and package management within GitHub
</details>

---
After the removal of sensitive data from a repository's history and its subsequent push to GitHub, which action is essential to completely remove the data from GitHub?
<details><summary>Show the answer</summary><p>

- **Contact GitHub Support to remove cached views and references**
> After sensitive data has been removed from a repository's history and pushed to GitHub, it's necessary to contact GitHub Support to remove cached views and references. This step ensures that the sensitive data is fully removed from GitHub's systems, including any cached copies that might still be accessible
</details>

---
Which of the following are valid authentication methods available in GitHub?
<details><summary>Show the answer</summary><p>

- **Personal access token (PAT)**
- **SAML SSO for enterprise accounts**
- **OAuth tokens for third-party app integrations**
</details>

---
Under which circumstance is GitHub Packages NOT the appropriate tool to use?
<details><summary>Show the answer</summary><p>

- **When desiring to share code between methods within your application**
> GitHub Packages is designed for hosting and distributing software packages and container images across teams and projects. It is not suited for internal code sharing within the application, such as sharing code between methods. This type of code organization and reuse within an application is typically managed through the application's architecture and codebase itself, not through a package management system
</details>

---
Which role within a team allows a member to manage team settings and repository access?
<details><summary>Show the answer</summary><p>

- **Maintainer**
> The Maintainer role within a GitHub team is endowed with permissions to manage the team's settings, including modifying team membership and managing the team's access to repositories. This role is crucial for the administration and coordination of team activities within an organization
</details>

---
How can GitHub Actions workflows utilize GitHub Packages for CI/CD processes?
<details><summary>Show the answer</summary><p>

- **By using the GITHUB_TOKEN for authentication to publish or install packages**
> GitHub Actions workflows can interact seamlessly with GitHub Packages by using the GITHUB_TOKEN for authentication. This token simplifies the process of publishing to or installing packages from GitHub Packages, making it an integral part of automating CI/CD pipelines
</details>

---
In a software development organization on GitHub, what are the specific responsibilities of a GitHub App manager?
<details><summary>Show the answer</summary><p>

- **GitHub App managers can adjust the settings for GitHub App registrations owned by the organization but cannot install or uninstall GitHub Apps**
> GitHub App managers are tasked with managing the settings of GitHub App registrations that the organization owns. This role specifically includes adjusting configurations but does not extend to installing or uninstalling GitHub Apps, ensuring a level of control and security over the applications utilized within the organization
</details>

---
What are the key differences between GitHub Packages and releases?
<details><summary>Show the answer</summary><p>

- **Releases are used for distributing final versions of software, often with binary files and executables**
> Releases allow developers to distribute software versions to end-users, including binary files, source code, and other assets, making it suitable for delivering finished products
- **GitHub Packages requires external CI/CD integration for any operation**
> Releases are associated with Git tags, which mark specific points in a repository's history, making them ideal for versioning software and tracking changes over time
- **GitHub Packages is optimized for package management, offering features like versioning and dependencies**
> GitHub Packages is designed for managing development packages, supporting version control and dependencies to streamline development workflows
</details>

---
What action is required from GitHub Support rather than being solvable by an administrator?
<details><summary>Show the answer</summary><p>

- **Restoring a deleted repository**
> Restoring a deleted repository is a task that typically requires intervention from GitHub Support, as it may involve data that is not directly accessible to organization administrators after deletion
</details>

---
When writing scripts to manage multiple GitHub organizations and handle different access rights, what is a key consideration to ensure maintainability?
<details><summary>Show the answer</summary><p>

- **Utilizing the GitHub API with a Personal Access Token (PAT) that has the appropriate scopes across all organizations**
> To ensure maintainability and security when managing multiple organizations, it's crucial to use the GitHub API with a Personal Access Token (PAT) that has been granted the necessary scopes. This approach allows for scalable and flexible script execution across different organizations while adhering to best practices for authentication and authorization
</details>

---
What is the primary purpose of SCIM and team synchronization in GitHub?
<details><summary>Show the answer</summary><p>

- **To automate identity provisioning and connect GitHub teams with IdP groups for efficient membership management**
> SCIM (System for Cross-domain Identity Management) automates the provisioning and management of user identities across systems, including creating and updating users and their access rights. Team synchronization in GitHub leverages this alongside SAML single sign-on to efficiently manage GitHub team memberships by linking them with groups in an Identity Provider (IdP), streamlining access control and membership updates
</details>

---
Which GitHub solution is hosted by GitHub and offers a cloud-based enterprise environment?
<details><summary>Show the answer</summary><p>

- **GitHub Enterprise Cloud (GHEC)**
> GitHub Enterprise Cloud (GHEC) is the cloud-based solution offered by GitHub for enterprises, providing a hosted environment that includes all of GitHub's features and functionalities, without the need for self-hosting or managing servers
</details>

---
What distinguishes GitHub AE from other GitHub enterprise offerings?
<details><summary>Show the answer</summary><p>

- **GitHub AE is specifically designed for the highest levels of security and compliance, catering to government and highly regulated industries**
> GitHub AE, or GitHub Advanced Enterprise, is tailored for organizations with stringent security, compliance, and policy requirements, such as government agencies or industries subject to heavy regulation, offering a cloud-hosted environment with additional controls and features
</details>

---
What's the difference between GitHub Apps and OAuth apps?
<details><summary>Show the answer</summary><p>

- **GitHub Apps offer granular permissions to specific repositories, while OAuth Apps request access to user data across all repositories**
> GitHub Apps provide fine-grained permissions tailored to specific repositories, enabling administrators to control access more precisely. In contrast, OAuth Apps typically request broader access to user data across all repositories
</details>

---
Which of the following is a supported SCIM provider for integrating with GitHub?
<details><summary>Show the answer</summary><p>

- **Azure**
</details>

---
Who is authorized to set up IP allow lists for a company on GitHub?
<details><summary>Show the answer</summary><p>

- **Enterprise owners**
> Enterprise owners have the highest level of administrative rights within GitHub Enterprise, which includes the ability to configure IP allow lists. This setting is crucial for enhancing security by restricting access to the enterprise's resources on GitHub to specified IP addresses. Enterprise owners can enforce these restrictions to protect sensitive data and comply with organizational security policies
</details>

---
How can GitHub Actions be effectively reused across multiple workflows within an enterprise?
<details><summary>Show the answer</summary><p>

- **By creating reusable workflows and actions stored in a dedicated repository and referencing them in other workflows**
> Storing reusable GitHub Actions and workflows in a dedicated repository allows them to be easily referenced and used in multiple other workflows across the enterprise. This approach promotes efficiency and consistency while enabling centralized updates and maintenance
</details>

---
In your organization on GitHub, you need a role for new contributors who should help manage project issues and pull requests without the ability to modify code directly. Which repository role should you assign to these contributors?
<details><summary>Show the answer</summary><p>

- **Triage**
> The "Triage" role is specifically designed for contributors who need to proactively manage issues and pull requests without having direct write access to the repository. This role allows them to label, close, or assign issues and pull requests, making it the perfect choice for contributors focused on project management tasks without the risk of altering the codebase
</details>

---
What is a critical first step in developing an enterprise's CI/CD strategy?
<details><summary>Show the answer</summary><p>

- **Identifying the software development lifecycle and integration points for automation**
> The critical first step in developing an enterprise's CI/CD strategy involves understanding the existing software development lifecycle (SDLC) and identifying where automation through CI/CD can be most beneficial. This ensures that the CI/CD strategy is tailored to the enterprise's specific needs and integrates seamlessly with current processes
</details>

---
How are GitHub Actions typically consumed compared to GitHub Apps?
<details><summary>Show the answer</summary><p>

- **GitHub Actions are used within workflows in repositories, while GitHub Apps are installed at the organization or repository level**
> GitHub Actions are components used within CI/CD workflows that are defined in a repository to automate software development practices. GitHub Apps, conversely, are installed at the organization or repository level to extend GitHub functionalities, providing services like monitoring, security, and continuous integration across multiple repositories
</details>

---
What is a key difference between GitHub-hosted and self-hosted runners?
<details><summary>Show the answer</summary><p>

- **GitHub-hosted runners are automatically scaled and maintained by GitHub, while self-hosted runners are managed and hosted by the user**
> The main difference between GitHub-hosted and self-hosted runners is who manages them. GitHub-hosted runners are provided and scaled by GitHub, offering a maintenance-free option for running workflows. Self-hosted runners, on the other hand, give users control over the hosting environment but require the user to manage and maintain the runners
</details>

---
How can organization admins access the audit log for actions performed within their GitHub organization?
<details><summary>Show the answer</summary><p>

- **Navigate to the organization's settings by selecting the profile photo, choosing "Your organizations," selecting the desired organization, going to "Settings," finding "Audit log," and using the "Export" dropdown to export the log in either JSON or CSV format**
> This is the proper method for organization admins to access and export the audit log within GitHub, providing a direct way to review actions performed within the organization
</details>

---
How do you change which repositories can access a specific runner group in an organization?
<details><summary>Show the answer</summary><p>

- **In the organization's settings, go to Actions, click on Runner groups, select a group, and then adjust the repository access settings**
> The process for changing which repositories can access a specific runner group in an organization involves navigating to the organization's settings on GitHub, selecting Actions, then Runner groups. From there, choosing a specific runner group allows you to modify its repository access settings. This interface provides a straightforward way to control which repositories are permitted to use the runners in a given group, ensuring that access is restricted based on the organization’s requirements and security policies
</details>

---
When recommending tooling and workflows to teams within an enterprise, what considerations should be taken into account?
<details><summary>Show the answer</summary><p>

- **The current technology stack and development practices of the team**
> Understanding the team's current technology stack and development practices is crucial to recommend tooling and workflows that will be compatible and enhance productivity rather than disrupt existing processes
- **Integration capabilities with existing tools and systems**
> Tools that can integrate seamlessly with the team's existing tools and systems minimize the learning curve and disruption, facilitating a smoother transition and better adoption rates among team members
- **The scalability of the tools to meet future growth**
> The scalability of tools is an essential consideration to ensure that the recommended solutions can accommodate future growth and development needs without requiring frequent tool changes or upgrades
</details>

---
What are the advantages of using nested teams within a GitHub organization's structure?
<details><summary>Show the answer</summary><p>

- **Nested teams allow for hierarchical organization, inheriting permissions from parent teams, easing permission management, and facilitating communication**
> Nested teams mirror the organizational hierarchy, automatically inheriting access permissions from their parent teams. This setup simplifies the management of permissions and improves communication within different layers of the organization, making it easier to maintain a clear and efficient organizational structure
</details>

---
Can organization administrators adjust IP allow list settings that are inherited from their enterprise's master allow list?
<details><summary>Show the answer</summary><p>

- **No, they cannot alter settings inherited from the enterprise's allow list**
> Organization administrators do not have the capability to manage or alter IP allow list entries that are inherited from the enterprise account's allow list. These settings are controlled at the enterprise level to ensure a uniform security posture across all organizations within the enterprise. This limitation helps maintain the integrity of the enterprise's security policies and prevents unauthorized access modifications
</details>

---
How does integrating team synchronization with Microsoft Entra ID benefit GitHub Enterprise Cloud organizations?
<details><summary>Show the answer</summary><p>

- **By automatically updating GitHub team memberships to reflect changes in the IdP group, eliminating the need for manual management**
> Team synchronization with Microsoft Entra ID (previously Azure AD) allows GitHub Enterprise Cloud organizations to automatically sync team memberships with identity provider (IdP) groups. This feature reduces administrative overhead by reflecting membership changes made in the IdP directly in GitHub, thereby eliminating the need for manual updates or custom scripts
</details>

---
How can administrators generate support bundles and diagnostics in GitHub Enterprise Server?
<details><summary>Show the answer</summary><p>

- **Through the site admin dashboard, by navigating to the 'Support' section and selecting 'Generate support bundle'**
> In GitHub Enterprise Server, administrators can generate support bundles and diagnostics directly through the site admin dashboard under the 'Support' section, providing a comprehensive package of logs and system information useful for troubleshooting
</details>

---
What best describes GitHub Enterprise Policies?
<details><summary>Show the answer</summary><p>

- **Settings managed by organization owners to control aspects like repository management, team access, and security features within their GitHub organization**
> GitHub Enterprise Policies refer to the various settings and controls that organization owners can manage to ensure their GitHub organization operates securely and efficiently. These policies can cover a wide range of aspects, from repository management and team access to implementing security features, providing a structured way to govern how the organization uses GitHub
</details>

---
What functionality does team synchronization via SCIM provide?
<details><summary>Show the answer</summary><p>

- **It automatically updates GitHub team memberships based on changes in the identity provider**
> Team synchronization via SCIM automates the process of updating GitHub team memberships whenever there are changes in the identity provider, such as adding or removing users. This ensures that team information remains consistent and up-to-date across systems
</details>

---
Which methods can be used to authenticate against GitHub?
<details><summary>Show the answer</summary><p>

- **Using a username and password**
- **Implementing deploy keys for specific repositories**
> Deploy keys offer a secure authentication method for individual repositories. They are SSH keys that grant access to a single repo, making them ideal for automation and services that need to pull or clone repository code
- **Utilizing a Personal Access Token (PAT)**
- **Generating and using SSH keys**
</details>

---
Which standards are recommended for developer workflows?
<details><summary>Show the answer</summary><p>

- **Implementing branch protection rules**
> Branch protection rules are essential for safeguarding the integrity of the codebase, ensuring that changes meet quality standards before being merged. They enforce policies like mandatory code reviews and passing status checks
- **Designating code owners for critical parts of the codebase**
> Designating code owners helps ensure that changes to critical parts of the codebase are reviewed by individuals with the appropriate expertise, improving code quality and maintainability
</details>

---
How can access to reusable GitHub Actions be controlled within an enterprise?
<details><summary>Show the answer</summary><p>

- **By configuring repository visibility and access permissions, and using GitHub's built-in features to restrict the use of actions to authorized personnel**
> The visibility of repositories storing reusable actions and the permissions set on these repositories can be managed within GitHub to control who has access to these actions. GitHub also offers features that allow organizations to restrict which actions their members can use, ensuring that only authorized personnel can use specific actions
</details>

---
What are the benefits and risks of using apps and actions from the GitHub Marketplace?
<details><summary>Show the answer</summary><p>

- **Benefits include automation of workflows, enhanced security scanning, and integration with external tools**
> Apps and Actions from the GitHub Marketplace can significantly automate and streamline workflows, offer additional security scanning capabilities, and facilitate integration with external tools and services, enhancing the development process
- **Risks include potential security vulnerabilities from third-party code and dependence on external maintenance**
> A potential risk of using third-party apps and actions is introducing security vulnerabilities into your projects, as well as the possibility of becoming dependent on external developers for updates and maintenance
- **Benefits include unrestricted access to all repository data without authentication**
> Utilizing pre-built solutions from the GitHub Marketplace can lead to increased productivity by reducing the need to develop custom tools and allowing teams to focus on their core development tasks
</details>

---
Within a GitHub organization, various roles can be assigned to members to control their access to repositories. Which of the following are valid repository roles?
<details><summary>Show the answer</summary><p>

- **Read**
- **Triage**
- **Maintain**
- **Write**
- **Admin**
</details>

---
As an organization on GitHub plans to utilize self-hosted runners for its Actions workflows, what steps must be taken to integrate these runners?
<details><summary>Show the answer</summary><p>

- Obtain organization owner permissions, go to the organization's settings, choose Actions, then Runners, and adhere to the provided instructions to set up the self-hosted runner
> To add a self-hosted runner to an organization, one must have organization owner access. The process involves navigating to the organization's settings, selecting the Actions tab, then the Runners section, and following the setup instructions. This sequence ensures that the self-hosted runner is correctly configured to execute Actions workflows within the organization, providing a secure and customized execution environment for the organization's specific needs
</details>

---
Which of the following types of access tokens are supported by GitHub?
<details><summary>Show the answer</summary><p>

- Personal Access Token (PAT)
> GitHub supports Personal Access Tokens (PATs) for users to access GitHub through the API securely
- Installation Access Token for a GitHub App
> Installation Access Tokens are used by GitHub Apps to interact with the GitHub API on behalf of a specific installation on an account or repository
- User Access Token for a GitHub App
> User Access Tokens for GitHub Apps enable the app to act on behalf of a user, offering a more granular permission model than PATs
</details>

---
What practice is effective in preventing the accidental commit of sensitive data or files to a git repository?
<details><summary>Show the answer</summary><p>

- Using a visual program like GitHub Desktop to review commits before finalizing them
> Utilizing a visual program like GitHub Desktop allows developers to carefully review each commit, including the changes being made. This review process helps in identifying and removing any sensitive data or files that should not be committed, thereby preventing accidental exposure
</details>

---
Where can administrators find statistics on license usage for their organization on GitHub?
<details><summary>Show the answer</summary><p>

- In the organization's settings under the "Billing" section
> Administrators can find comprehensive statistics on license usage for their organization directly within GitHub by navigating to the organization's settings and then to the "Billing" section. This area provides detailed information on usage and costs associated with the organization's GitHub account
</details>

---
How can an organization owner view license usage statistics for their GitHub Enterprise Server?
<details><summary>Show the answer</summary><p>

- By navigating to the Site admin dashboard to view the license usage under Enterprise account settings
> Organization owners can view statistics on license usage for their GitHub Enterprise Server by navigating to the Site admin dashboard. This section provides insights into the current license usage, including the number of active users, which is crucial for managing licenses effectively within an enterprise environment
</details>

---
When needing to purge sensitive data from a project's history in Git, which tools are recommended for the task?
<details><summary>Show the answer</summary><p>

- git filter-repo and BFG Repo-Cleaner
> git filter-repo and BFG Repo-Cleaner are specialized tools designed for cleaning up sensitive data from a Git repository's history. These tools allow developers to remove unwanted data efficiently, ensuring that sensitive information does not remain in the project history
</details>

---
How can an administrator give a user the minimum required permissions for accessing a specific repository within an organization?
<details><summary>Show the answer</summary><p>

- By adding the user as an outside collaborator to the repository with the appropriate role
> To grant a user minimum required permissions for a specific repository, an administrator can add the user as an outside collaborator to that repository and assign them the role that best fits their needs, such as read, write, or maintain
</details>

---
What is the primary distinction between a GitHub App and a GitHub Action in terms of permissions?
<details><summary>Show the answer</summary><p>

- GitHub Apps have more granular permission settings, whereas Actions run with permissions tied to the GITHUB_TOKEN
> GitHub Apps are designed to interact with GitHub's API more securely and flexibly, offering granular permission settings that can be tailored to specific needs. In contrast, GitHub Actions operate with a more limited scope of permissions determined by the GITHUB_TOKEN, which provides a predefined set of permissions to interact with the GitHub API during workflow execution
</details>

---
How is access to self-hosted runners organized within an organization on GitHub through the use of runner groups?
<details><summary>Show the answer</summary><p>

- By establishing runner groups to organize runners and setting access rules for organization repositories
> Runner groups in GitHub are designed to manage access to self-hosted runners efficiently within an organization. By creating runner groups, an organization can categorize its runners into sets and then define access policies that determine which repositories within the organization can use these runners. This system allows for flexible, scalable, and secure management of runner access across multiple projects, ensuring that only authorized repositories can trigger workflows on specific runners
</details>

---
What is a primary goal of the tooling ecosystem in an enterprise setting?
<details><summary>Show the answer</summary><p>

- To integrate various software development tools to enhance collaboration, automate workflows, and improve productivity across teams
> The primary goal of establishing a tooling ecosystem within an enterprise is to create a cohesive environment where various tools work together seamlessly. This integration supports collaboration among teams, automates repetitive tasks, and overall enhances the productivity and efficiency of the software development process
</details>

---
How can GitHub APIs enhance the administrative capabilities beyond the user interface?
<details><summary>Show the answer</summary><p>

- By allowing administrators to programmatically query the audit log and automate repository management tasks
> GitHub APIs extend administrative capabilities by providing programmable access to a wide range of GitHub functionalities, including querying the audit log for monitoring activities within the organization and automating tasks like repository creation, user management, and more, which enhances efficiency and control
</details>

---
How can developers authenticate to GitHub Packages to publish or install packages?
<details><summary>Show the answer</summary><p>

- Utilizing a Personal Access Token (PAT) with the required scopes
> To authenticate to GitHub Packages for publishing or installing packages, developers need to use a Personal Access Token (PAT) with the required scopes. This method ensures secure access and operation within GitHub Packages, allowing for controlled distribution and consumption of packages
</details>

---
How can you ensure that users only utilize Actions created by GitHub or verified creators in their workflows?
<details><summary>Show the answer</summary><p>

- By configuring Policies to allow only actions created by GitHub or verified creators
> Administrators can configure Policies within GitHub to specifically allow actions created by GitHub or verified creators. This is achieved through the "Allow select actions" menu in the Actions policy settings, enabling organizations to limit the actions users can employ to those deemed secure and reputable, thus ensuring compliance with organizational standards and security policies
</details>

---
Can an enterprise account on GitHub contain multiple organizations?
<details><summary>Show the answer</summary><p>

- Yes
> An enterprise account on GitHub is designed to contain multiple organizations, allowing for centralized management of policies, billing, and security settings across all the organizations within the enterprise. This structure supports scalability and simplifies administration for large companies or groups with diverse teams and projects
</details>

---
How can encrypted secrets be accessed within GitHub Actions workflows?
<details><summary>Show the answer</summary><p>

- Using the ${{ secrets.NAME }} syntax
> Encrypted secrets are accessed within GitHub Actions workflows by using the ${{ secrets.NAME }} syntax, where NAME is the name of the secret. This ensures that secrets are securely injected into the workflow runs
</details>

---
What is a recommended standard for developer workflows regarding code collaboration?
<details><summary>Show the answer</summary><p>

- Implementing a fork-and-pull model for external contributors alongside a branching model for internal collaboration
> Combining a fork-and-pull model for external contributors with a branching model for internal team members is a best practice that balances open collaboration with control over the main codebase. It allows for community contributions while maintaining code quality and review processes for internal development
</details>

---
Where can you find the dependency graph listing all the packages your repository depends on within your GitHub repository?
<details><summary>Show the answer</summary><p>

- In the Insights tab and then the Dependency graph section
> The dependency graph is a feature that provides a visual representation of the packages and other repositories that your project depends on. You can find it by navigating to the Insights tab of your repository and selecting the Dependency graph section. This tool is invaluable for understanding your project's dependencies and for identifying potential security vulnerabilities
</details>

---
What are the consequences of a user's membership in a GitHub organization or instance?
<details><summary>Show the answer</summary><p>

- The user gains access to private repositories within the organization based on their assigned permissions
> Being a member of a GitHub organization allows a user access to the organization's private repositories to the extent permitted by their role and permissions within the organization. This facilitates collaboration and contribution to projects securely
- Membership in an organization subjects the user to the organization's security policies, such as enforced two-factor authentication (2FA)
> When a user becomes a member of an organization, they must adhere to the security policies set by the organization, which may include requirements like two-factor authentication (2FA) to enhance security
</details>

---
Which tools can be used to tamper with Git history and erase sensitive data?
<details><summary>Show the answer</summary><p>

- git filter-repo and BFG Repo-Cleaner
> Both git filter-repo and BFG Repo-Cleaner are powerful tools used to rewrite Git history and remove sensitive data from repositories. They are commonly used when sensitive information, such as passwords or confidential files, needs to be permanently removed from the repository history
</details>

---
How can an administrator find and install the Azure Pipelines GitHub App from the GitHub Marketplace?
<details><summary>Show the answer</summary><p>

- By searching for "Azure Pipelines" in the GitHub Marketplace and following the installation instructions for their repository or organization
> The GitHub Marketplace is a central location where users can discover and install apps like Azure Pipelines directly within their GitHub environment. By searching for the app and following the provided installation instructions, administrators can easily integrate Azure Pipelines into their workflows
</details>

---
What is the simplest way to prevent the creation of public repositories within a GitHub organization?
<details><summary>Show the answer</summary><p>

- At the organization level, in "Member Privileges" settings, disallow the creation of public repositories
> The most straightforward method to prevent the creation of public repositories within a GitHub organization is to adjust the settings in the "Member Privileges" section of the organization's settings. Administrators can specifically disallow the creation of public repositories, ensuring all new repositories created by members are private by default. This setting provides a proactive approach to maintaining repository privacy at the organizational level
</details>

---
How can GitHub Apps react to specific events, and what are some examples of these events?
<details><summary>Show the answer</summary><p>

- GitHub Apps subscribe to events through webhooks, which notify the app of specific actions like pull request openings or issue creations
> GitHub Apps indeed react to specific events by subscribing to them through webhooks. These events include actions like pull request openings, issue creations, push events, etc
</details>

---
How does GitHub manage identity and authorization for users within organizations?
<details><summary>Show the answer</summary><p>

- GitHub uses a combination of SAML SSO for identity management and fine-grained access controls for authorization within organizations
> For enterprise-level identity management, GitHub supports SAML Single Sign-On (SSO), allowing organizations to integrate with identity providers for secure authentication. Once authenticated, GitHub provides detailed access controls, enabling organizations to define specific permissions for users, such as read, write, or admin access to repositories, effectively managing authorization within the platform
</details>

---
GitHub Actions workflow runs specifically on a self-hosted agent that operates on Linux with an ARM architecture?
<details><summary>Show the answer</summary><p>

- By using runs-on: [self-hosted, linux, ARM]
> To target a workflow to run on a specific self-hosted runner that is using Linux with an ARM architecture, you should specify runs-on: [self-hosted, linux, ARM] in your workflow file. This combination of labels ensures that the job runs only on self-hosted runners that match all three specified criteria: being self-hosted, running Linux, and using the ARM architecture
</details>

---
What is a fundamental difference between a GitHub App and a GitHub Action?
<details><summary>Show the answer</summary><p>

- GitHub Apps are third-party applications that extend GitHub functionalities, while Actions are used to automate workflows within the GitHub environment
> GitHub Apps provide a way to integrate third-party services and extend GitHub functionalities, offering granular permissions for accessing specific GitHub data. GitHub Actions automate workflows directly within GitHub, enabling continuous integration and continuous deployment (CI/CD) processes without requiring external tools
</details>

---
What is the scope of encrypted secrets at the organization level in GitHub Actions?
<details><summary>Show the answer</summary><p>

- Available to multiple repositories within the organization
> Encrypted secrets at the organization level are designed to be available across multiple repositories within the organization, allowing for easier management of secrets that are common to several projects
</details>

---
How does Team sync through Active Directory (AD) function for GitHub organizations?
<details><summary>Show the answer</summary><p>

- It automatically synchronizes GitHub team memberships with user groups in Active Directory, reflecting changes in team composition directly from AD
> Team sync through Active Directory (AD) allows for the automatic synchronization of GitHub team memberships with user groups defined in AD. This means that when changes are made to user groups in AD, such as adding or removing members, these changes are automatically reflected in the corresponding GitHub teams, streamlining team management and ensuring consistency across platforms
</details>

---
How can GitHub Actions workflows authenticate to GitHub Packages for publishing or consuming packages?
<details><summary>Show the answer</summary><p>

- By utilizing the GITHUB_TOKEN provided by GitHub Actions for secure authentication
> GitHub Actions workflows can securely authenticate to GitHub Packages using the GITHUB_TOKEN that is automatically provided by GitHub Actions. This token is scoped to the current repository, allowing workflows to publish or consume packages without needing to manually manage authentication tokens
</details>

---
What is a deploy key in the context of GitHub?
<details><summary>Show the answer</summary><p>

- An SSH key that grants access to a single repository on GitHub, used to deploy projects to a server
> A deploy key is an SSH key specifically used for deploying projects from a GitHub repository to a server. It grants access solely to a single repository. The public part of this key is attached directly to the repository on GitHub, ensuring secure communication between the repository and the server where the private key is stored. This setup is ideal for automation and CI/CD processes where repository-specific access is required without granting broader permissions associated with a personal account
</details>

---
What are the two roles available at the team level within a GitHub organization?
<details><summary>Show the answer</summary><p>

- Maintainer
- Member
</details>

---
On GitHub Enterprise Server, how can an administrator generate a support bundle to provide to GitHub Support?
<details><summary>Show the answer</summary><p>

- By executing ssh -p 122 admin@hostname -- 'ghe-support-bundle -o' > support-bundle.tgz on the server
> The provided SSH command line is the appropriate method to generate a support bundle on GitHub Enterprise Server. This process collects vital system and application logs into a .tgz file, which can then be shared with GitHub Support for troubleshooting purposes. The command ensures that all necessary information is compiled efficiently and securely
</details>

---
How can you use 3rd party vaults to manage secrets for GitHub Actions?
<details><summary>Show the answer</summary><p>

- Secrets are stored in the third-party vault, and a decryption step within the workflow accesses them, using a key stored as a GitHub Actions secret
> Utilizing third-party vaults for managing secrets in GitHub Actions involves securely storing the secrets outside of GitHub and accessing them during the workflow execution. A common method is to store a decryption key or access token as a secret within GitHub Actions. This key is then used in a step within the workflow to authenticate and decrypt or directly access the secrets stored in the third-party vault. This approach ensures that sensitive information is securely managed while still being accessible to the workflow when needed
</details>

---
Does GitHub Enterprise Server include the GitHub Packages feature?
<details><summary>Show the answer</summary><p>

- Yes
> GitHub Enterprise Server includes the GitHub Packages feature, allowing users to host, manage, and share packages alongside their source code. This integration facilitates efficient package management within the same platform used for version control and CI/CD processes
</details>

---
When setting up a workflow template, which two files are essential for its creation?
<details><summary>Show the answer</summary><p>

- A JSON properties file with a ".properties.json" extension (e.g., my-workflow.properties.json)
> is necessary for defining workflow properties, such as descriptions, inputs, and outputs, in a structured format. This file helps in categorizing and providing metadata for the workflow template, making it easier to understand and use
- A YAML file named after the workflow (e.g., my-workflow.yml)
> A YAML file (e.g., my-workflow.yml) is crucial for defining the steps, jobs, and events that trigger the workflow. This file outlines the workflow's operations and is mandatory for the workflow to be recognized and executed by the system
</details>

---
Where can organization administrators find statistics of license usage for their organization on GitHub?
<details><summary>Show the answer</summary><p>

- In the organization's settings under the "Billing" section
> Organization administrators can find statistics on license usage, including details on seats used and available, directly within their organization's settings under the "Billing" section. This information helps in managing subscriptions and understanding the organization's utilization of GitHub resources
</details>

---
How can an administrator generate support bundles and diagnostics for GitHub Enterprise Server?
<details><summary>Show the answer</summary><p>

- Through the site admin dashboard, by navigating to the 'Support' section and selecting 'Generate support bundle'
> Administrators of GitHub Enterprise Server can generate support bundles and diagnostics directly through the site admin dashboard. This feature allows them to collect relevant data and logs, facilitating the troubleshooting process or when contacting GitHub Support for assistance
</details>

---
What types of issues does GitHub Support cover?
<details><summary>Show the answer</summary><p>

- Account, Security, and Abuse issues
> GitHub Support provides assistance for a range of issues, specifically focusing on Account, Security, and Abuse concerns. This includes helping users secure their accounts, addressing potential security vulnerabilities, and managing abuse reports to maintain a safe and supportive community
</details>

---
Which role should you assign to a contributor who needs full control over a repository except for access to sensitive or destructive actions?
<details><summary>Show the answer</summary><p>

- Maintainer, because the admin role would, for instance, allow them to delete the repository
> The Maintainer role in a GitHub repository or team is designed to offer comprehensive control over project development activities, such as managing issues, pull requests, and most settings, without granting permissions for sensitive or potentially destructive actions like deleting the repository. This makes it the ideal choice for contributors who need substantial control without the risk associated with admin-level permissions
</details>

---
Which feature allows users to access pre-made templates when creating a new workflow?
<details><summary>Show the answer</summary><p>

- Workflow Templates
> Workflow Templates allow repository and organization owners to provide pre-made workflow templates to their users. These templates help streamline the process of creating new workflows by offering a standardized set of workflows that can be customized as needed, enabling users to quickly set up CI/CD pipelines or automate other processes without starting from scratch
</details>

---
What is the impact of an Enterprise IP allow list on publishing a GitHub Pages site directly from a branch without a custom GitHub Actions workflow?
<details><summary>Show the answer</summary><p>

- The build process is automatically permitted access to the repository for the GitHub Pages site
> When publishing a GitHub Pages site directly from a branch, the build process is inherently allowed to access the repository without being blocked by the Enterprise IP allow list. This is because GitHub Pages and its build process are considered trusted services within the GitHub infrastructure, which means they are allowed to operate even when IP restrictions are applied to other parts of the enterprise. This setup ensures that GitHub Pages sites can be updated and published without needing to manually adjust the IP allow list for the build runners
</details>

---
Can you erase the history of a repository to keep sensitive data secret once it has been committed?
<details><summary>Show the answer</summary><p>

- No. While you can overwrite a commit, the sensitive data must be considered unsecure once committed. If it involves a secret/password, it must be renewed
> Once sensitive data has been committed to a repository, overwriting the commit does not entirely eliminate the risk that the data was exposed. The best practice in such cases is to assume the data is compromised. For secrets or passwords, the safest course of action is to renew or change them to prevent unauthorized access
</details>

---
How can you automatically assign specific persons as reviewers when a part of the code is modified?
<details><summary>Show the answer</summary><p>

- By creating and maintaining CODEOWNERS files in the repository, which specify the individuals or teams that should be automatically assigned as reviewers for specific parts of the code
> The CODEOWNERS file is a GitHub feature that allows repository administrators to define individuals or teams as "code owners" for specific parts of a repository. When changes are made to areas of the code covered by the CODEOWNERS file, GitHub automatically assigns the specified owners as reviewers for pull requests involving those areas, streamlining the review process and ensuring that the right people are notified and involved in the review
</details>

---
What is the primary method for a user to authenticate to GitHub when part of an organization with SAML SSO enabled?
<details><summary>Show the answer</summary><p>

- Through the organization's identity provider using SAML SSO
> When an organization enables SAML Single Sign-On (SSO), users authenticate to GitHub through the organization's chosen identity provider. This process ensures secure access management and aligns with enterprise security policies, allowing centralized control over user access
</details>

---
How does a user's list of permissions, such as their repository role, team membership, or organization membership, influence their actions within a GitHub organization?
<details><summary>Show the answer</summary><p>

- It dictates the specific actions a user can perform, ranging from viewing and editing files to managing access rights and settings, based on their assigned roles and memberships
> A user's permissions within a GitHub organization, determined by their repository role, team membership, and organization membership, directly influence the range of actions they are authorized to perform. These permissions can include various activities such as contributing to code, managing issues and pull requests, and adjusting repository or organization-wide settings, providing a structured and secure environment for collaboration
</details>

---
What are the consequences of a user’s membership in an instance, an organization, or multiple organizations on GitHub?
<details><summary>Show the answer</summary><p>

- Requirement to adhere to the security policies of each organization, including 2FA if enforced
> Users must comply with each organization's security policies, which may include mandatory two-factor authentication (2FA), ensuring a uniform security standard across the platform
- Eligibility to receive organization-specific notifications and participate in discussions
> Being a member of an organization allows users to receive notifications pertinent to that organization and engage in discussions, fostering community and collaboration within the organization
- Access to private repositories based on the permissions granted by organization owners or repository administrators
> Membership in an organization or instance on GitHub grants the user access to private repositories, contingent upon the specific permissions assigned by those with administrative control, enhancing collaboration within secure environments
</details>

---
Which default labels are applied to a self-hosted agent in GitHub Actions?
<details><summary>Show the answer</summary><p>

- CPU architecture: x64, ARM, or ARM64
- os: linux, windows, or macOS
- self-hosted
</details>

---
What are key components to include in a release strategy for developer workflows?
<details><summary>Show the answer</summary><p>

- Scheduled deployment windows for stable releases
> Having scheduled deployment windows for releasing changes to production helps manage risk and ensures that stakeholders are aware of when new features or fixes will be available
- Mandatory code review approvals before merging feature branches
> Requiring code review approvals enforces a review process that can catch issues early, promote knowledge sharing, and ensure that changes meet the project's standards
- Automated testing as part of the continuous integration process
> Integrating automated testing into the CI process ensures that code changes are validated before being merged, helping to maintain code quality and stability
</details>

---
Which role allows a person to manage issues of a repository without granting any write rights to the code?
<details><summary>Show the answer</summary><p>

- Triage
</details>

---
How should an enterprise adjust its policies and organization permissions on GitHub to align with its trust and control position?
<details><summary>Show the answer</summary><p>

- Implementing a granular permission model that reflects the company's specific trust levels and control needs, such as using read, write, maintain, and admin roles appropriately
> To align enterprise policies and organization permissions with a company's trust and control stance, it's essential to implement a granular permission model. This approach involves assigning roles (read, write, maintain, admin) based on the level of trust and the specific needs for control within the organization. It allows for flexible and secure access management, ensuring that members have the necessary permissions to perform their roles effectively while protecting sensitive information and maintaining overall security
</details>

---
Which of the following statements are true regarding managing encrypted secrets in GitHub Actions?
<details><summary>Show the answer</summary><p>

- Secrets can be updated but not viewed in plaintext after creation
> Once created, secrets can be updated but cannot be viewed in plaintext, ensuring their confidentiality. This protects the secret's integrity and security
- 3rd party vaults can be integrated to manage secrets outside of GitHub
> Integration with 3rd party vaults enables organizations to manage secrets outside of GitHub, providing additional flexibility and security options for managing sensitive information
- Repository-level secrets can be accessed by workflows running in that repository
> Repository-level secrets are scoped to be accessible by workflows running in the repository where they were defined, allowing for secure and specific secret management
</details>

---
How can an organization require two-factor authentication (2FA) for its members?
<details><summary>Show the answer</summary><p>

- Through the organization's security settings, by enabling the 'Require two-factor authentication' option
> An organization can require its members to use two-factor authentication by navigating to the organization's security settings and enabling the 'Require two-factor authentication' option. This ensures that all members have an additional layer of security on their accounts
</details>

---
What are the different types of Enterprise Support available from GitHub?
<details><summary>Show the answer</summary><p>

- GitHub Enterprise Premium Plus support
- GitHub Enterprise Premium support
- GitHub Enterprise Support (Included with Enterprise Cloud and Enterprise Server)
</details>

---
What is a key consideration when writing scripts to manage multiple GitHub organizations and access rights?
<details><summary>Show the answer</summary><p>

- Ensuring scripts are adaptable to handle diverse permission models and organizational structures
> When managing multiple GitHub organizations and access rights through scripts, it's essential to ensure these scripts are versatile and adaptable. They should be designed to accommodate various permission models and the unique structures of different organizations to maintain effectiveness across a broad range of administrative scenarios
</details>

---
Can you upload container images to GitHub Packages?
<details><summary>Show the answer</summary><p>

- Yes, GitHub Packages supports hosting container images
> GitHub Packages provides support for hosting container images, making it a versatile platform for developers to manage both their code and containerized applications in one place. This feature enables seamless integration of container workflows with GitHub's ecosystem
</details>

---
What is the maximum number of members allowed in a GitHub organization?
<details><summary>Show the answer</summary><p>

- 10000
> A GitHub organization can have up to 10,000 members, allowing for extensive collaboration among large teams and enterprises. This limit is designed to accommodate the needs of most organizations while maintaining performance and manageability
</details>

---
What are the benefits of using GitHub Packages within workflows?
<details><summary>Show the answer</summary><p>

- It integrates seamlessly with GitHub Actions for automating package publishing and consumption
> One of the significant benefits of GitHub Packages is its integration with GitHub Actions, enabling automated workflows for publishing new package versions and consuming packages within CI/CD pipelines. This automation streamlines the development process and ensures consistency across environments
- It provides a centralized platform for hosting and sharing software packages across teams and projects
> GitHub Packages serves as a centralized platform for hosting and sharing software packages, enhancing collaboration by allowing teams and projects to easily access and manage dependencies within the GitHub ecosystem
</details>

---
What is the appropriate repository permission level for contributors who will actively push changes to your repository?
<details><summary>Show the answer</summary><p>

- Write
</details>

---
How can an organization within a GitHub Enterprise account enforce SAML SSO?
<details><summary>Show the answer</summary><p>

- By navigating to the organization's security settings and selecting 'SAML single sign-on' under Authentication
> Administrators can enforce SAML SSO for their organization by accessing the organization's security settings on GitHub, then selecting the 'SAML single sign-on' option under the Authentication section. This allows for the configuration and enforcement of SAML SSO directly within the GitHub interface
</details>

---
How can you exclude sensitive files from being included in your GitHub repository?
<details><summary>Show the answer</summary><p>

- Building and maintaining .gitignore files to specify the files and directories that should be excluded from version control
> The .gitignore file is a crucial tool in a developer's arsenal for managing repositories. By specifying filenames, directory names, or patterns in a .gitignore file, developers can prevent sensitive or unnecessary files and directories from being added to version control. This proactive approach helps in safeguarding sensitive information and keeping repositories clean and focused on relevant code
</details>

---
What are the three roles available at the organization level within a GitHub organization?
<details><summary>Show the answer</summary><p>

- Billing Manager
- Member
- Owner
</details>

---
By default, can all users of an organization see all repositories?
<details><summary>Show the answer</summary><p>

- Yes, if the "Read" access is defined as the default role in "base permissions" in the organization's settings
> In GitHub organizations, the visibility of repositories to all users within the organization can be controlled through the "base permissions" setting. If "Read" access is set as the default role, all users in the organization can see all repositories by default, unless specific access controls are applied to restrict visibility further
</details>

---
In which folder within a self-hosted agent can you find logs for debugging the runner's behavior?
<details><summary>Show the answer</summary><p>

- /_diag
> The logs for debugging the behavior of a self-hosted runner are located in the /_diag folder. This directory contains detailed logs about the runner's operations, job execution, and any errors that may occur, making it an essential resource for troubleshooting and ensuring the smooth running of your workflows
</details>

---
What best defines Teams within a GitHub organization?
<details><summary>Show the answer</summary><p>

- Structured groups within an organization, designed to reflect company or project hierarchies, where members can be given specific access rights to repositories
> Teams within a GitHub organization are structured groups that can mirror the company's or project's hierarchy, making it easier to manage access rights and permissions. Members of a team can be granted different levels of access to repositories based on the team's purpose and needs, facilitating collaboration and maintaining security and organizational structure
</details>

---
How can tooling and workflows be effectively recommended to teams within an enterprise?
<details><summary>Show the answer</summary><p>

- By evaluating the team's specific needs, existing processes, and the potential impact of new tools on their workflow
> Effective recommendation of tooling and workflows requires a thorough understanding of each team's specific needs, the processes they currently have in place, and how the introduction of new tools will affect their workflow. This tailored approach ensures that the recommended solutions genuinely enhance productivity and efficiency
</details>

---
Which feature enables the synchronization of user identity data between your Identity Provider (IdP) and GitHub?
<details><summary>Show the answer</summary><p>

- SCIM
> The System for Cross-domain Identity Management (SCIM) is specifically designed to automate the exchange of user identity information between an identity provider (IdP) and service providers like GitHub. It supports operations such as creating, updating, and removing user accounts in a standardized format, facilitating seamless identity synchronization
</details>

---
What steps should be taken to enable and enforce SAML SSO for multiple organizations using enterprise accounts?
<details><summary>Show the answer</summary><p>

- Select a supported identity provider and obtain SAML configuration details for the enterprise
> Selecting a supported identity provider and obtaining the necessary SAML configuration details is a critical step in setting up SAML SSO. This information is essential for integrating the enterprise account with the identity provider
- Ensure all organization members are informed about the SAML SSO implementation and its requirements
> Communicating with organization members about the change to SAML SSO is crucial to ensure they are prepared for the new authentication process and understand any actions they need to take
- Configure SAML SSO at the enterprise account level to apply settings across all organizations
> Configuring SAML SSO at the enterprise account level allows for a unified authentication approach that is automatically applied to all contained organizations, streamlining the process and ensuring consistency
</details>

---
What is a key implication of enabling SAML SSO for all organizations in an enterprise account compared to an individual organization?
<details><summary>Show the answer</summary><p>

- It standardizes access control across the enterprise, enhancing security but requiring centralized identity management
> Enabling SAML SSO at the enterprise account level standardizes access control across all organizations under that account, improving security posture through centralized identity management. This approach ensures consistent authentication policies but necessitates managing user identities from a single point
</details>

---
Where should you store your security policy publicly if you plan to communicate about disclosing vulnerabilities?
<details><summary>Show the answer</summary><p>

- In the root of your repository in a file named SECURITY.md
> Storing your security policy in the root of your repository in a file named SECURITY.md is the recommended practice. This makes the policy easily discoverable for anyone looking to report security vulnerabilities. GitHub also promotes this standard by providing features that highlight the SECURITY.md file to contributors who are submitting issues or pull requests
</details>

---
What is a key difference between GitHub Packages and releases?
<details><summary>Show the answer</summary><p>

- Releases are used for distributing software versions and associated assets, while GitHub Packages is designed for hosting and managing software packages
> The key difference between GitHub Packages and releases lies in their intended use cases. GitHub Packages is tailored for hosting and managing software packages, providing features like versioning, dependency management, and integration with the GitHub ecosystem. Releases are focused on distributing software versions, often including binary files, source code, and other assets, making them ideal for final software distribution to end-users
</details>

---
What are the benefits and risks of using apps and actions from the GitHub Marketplace?
<details><summary>Show the answer</summary><p>

- Benefits include improved productivity through pre-built solutions and streamlined processes
> The use of pre-built solutions from the GitHub Marketplace can lead to improved productivity by leveraging tools and actions that automate and streamline development and deployment processes
- Risks include potential security vulnerabilities from third-party code and dependency on external developers for updates
> One of the primary risks of using third-party apps and actions is the introduction of security vulnerabilities, along with potential challenges related to maintenance and updates dependent on external developers
- Benefits include automation of workflows, enhanced security features, and integration with external tools
> Apps and actions from the GitHub Marketplace can significantly automate and enhance workflows, offer security features like automated code scanning, and facilitate seamless integration with external tools, improving efficiency
</details>

---
How can an administrator prevent users from utilizing Actions from the marketplace?
<details><summary>Show the answer</summary><p>

- By configuring Policies to restrict usage to local actions only
> Administrators can configure Policies to restrict the use of Actions to local actions only, thereby preventing users from using Actions from the marketplace. This approach allows for greater control over the actions used in workflows, ensuring compliance with security or organizational policies without disabling GitHub Actions altogether
</details>

---
How is audit access to a repository typically managed on GitHub?
<details><summary>Show the answer</summary><p>

- By utilizing GitHub's built-in audit logs feature, which tracks and records all actions taken within the repository for review and compliance purposes
> GitHub provides an audit logs feature that automatically tracks and records a wide range of activities performed within a repository, such as push operations, pull requests, changes to repository settings, and team membership updates. This feature is crucial for maintaining transparency, reviewing changes, and complying with regulatory requirements, offering administrators a comprehensive view of actions taken by users
</details>

---
How can an organization monitor the consumption of metered products like GitHub Actions minutes or storage for GitHub Packages?
<details><summary>Show the answer</summary><p>

- By accessing the "Usage reports" section within the organization's billing settings
> Organizations can monitor the consumption of metered products, such as GitHub Actions minutes or GitHub Packages storage, by accessing the "Usage reports" section within their billing settings. This feature provides detailed insights into resource utilization, helping organizations manage their usage and costs effectively
</details>

---
Which of the following are supported two-factor authentication (2FA) methods on GitHub?
<details><summary>Show the answer</summary><p>

- Security keys
> Security keys, such as those that support the FIDO U2F standard, can be used for 2FA on GitHub, providing a hardware-based method of authentication that requires the user to have the key physically present
- TOTP app
> TOTP (Time-based One-Time Password) apps generate temporary codes that users enter as part of the 2FA process. Apps like Google Authenticator or Authy are examples of TOTP apps supported by GitHub
- SMS
> SMS is a supported method for 2FA on GitHub, where a text message with a unique code is sent to the user's phone, which they must enter to complete the authentication process
</details>

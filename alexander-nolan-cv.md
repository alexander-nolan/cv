# Contact Details

Name: Alexander Nolan

Nationality: British

LinkedIn: <https://www.linkedin.com/in/alex-nolan-41929594/>

Email: [al.nolan@gmail.com](mailto:al.nolan@gmail.com)

Telephone: 07915827726

Location: Liverpool, UK

# Personal profile

GCP Professional Architect certified. MCSE (Azure) certified. AWS Professional DevOps Engineer certified.

# Career Profile

## TPXImpact (Contract)

**July 2024 – Present**

**Role**:DevOps Consultant

**Environment/Tooling:** Microsoft Azure, Azure DevOps, Azure repos, IaaS.

**Responsibilities:** Complete unfinished project and remediate vulnerabilities. Refactor terraform code. Create centralised networking IaC solution:

- Created terraform plan/apply templates/pipelines.
- Designed and implemented dynamic, scalable Enterprise VNET solution. Including
  - VNETs
  - Subnets
  - Peerings
  - VNET firewall
  - NSGs
  - NSG Flow Logs
  - Private DNS zones
  - DDOS Protection
  - Dynamically mapped VNETs to subnets. VNETs to Firewall. DNS to VNETs. Subnets to NSGs. NSGs to Flow logs.
- Refactored terraform code. Imported manually created resources into terraform state
- Infrastructure improvements:
  - Migrate from Microsoft Monitoring Agent to Azure Monitor Agent. Removed public access. Created AMPLS, DCRs, DCEs.
  - Removed public access from VM disks, Storage accounts, Log Analytics and implemented private link solution.
  - Azure Disk Encryption
  - Just in Time Access for VMs
- Advocate for agile/IaC practices across the wider business and client.
- Set up regular sessions for engineers to advocate for the usage of terraform, explain the benefits and coach team members.

## Innovationinsoftware (Contract)

**August 2024 – Present**

**Role**: DevOps Instructor

**Environment/Tooling:** Microsoft Azure, Github, Azure DevOps, Azure Kubernetes Service, Azure Key Vault, Python, REST APIs, Github Actions, Policy-as-code, Open Policy Agent, Github Actions.

**Responsibilities:** Develop Courseware for various courses. Created content and labs for the following topics:

- Azure Kubernetes Service
- Azure Key Vault
- Python
- REST APIs
- Policy As Code
- Open Policy Agent
- Github Actions

## Fluid Digital (Contract)

**August 2024 – November 2024**

**Role**: DevOps Consultant

**Environment/Tooling:** Amazon Web Services (AWS), Elastic Container Service (ECS), IAM, Route53, terraform, Github Actions, EC2, Elastic Load Balancing (ELB), Dato CMS

**Responsibilities:** Complete unfinshed project, rewrite terraform code:

- Fix outstanding CI/CD pipeline. Issues with image tags
- Sync staging and prod environments.
- Merge and deploy outstanding code updates into production.
- Create webhoook from DatoCMS to allow users to trigger CI/CD in GitHub actions and update content from Dato.
- Rewrite terraform code. Import all resources into new terraform codebase.
- Monitor and maintain infrastructure during high profile production campaign

## TerraQuest Data Solutions (Contract)

**July 2023 – July 2024**

**Role**: Senior DevOps Engineer

**Environment/Tooling:** Microsoft Azure, Azure DevOps, Azure repos, GCP IAM, Azure App Services, terraform, ASP.NET

**Responsibilities:** Evaluate current cloud estate. Identify and implement solutions to improve the environment:

- Refactored existing CI/CD pipelines
- Implemented semantic versioning process using semantic-release
- Created Architectural decision documents for:
  - App hosting solution
  - IaC solution
- Created PoCs for:
  - App hosting solution
  - IaC solutions
- Created and presented fully costed solutions to wider business team
- Created WAF policies terraform module
- Re-architected App Gateway (load balancer) to use re-usable WAF policies
- Created/re-orderd WAF rules
- Configured WAF listeners, re-ordered rules, debugged load balancer traffic flow due to failing backend health checks
- Split out products from monolithic terraform codebase
  - Designed, tested and implemented migration process including app services, function apps, database, service bus, new app gateway
  - Designed and implemented terraform state migration process for servicebus topics, subscriptions and correlation filters for organisation wide shared servicebus. This allowed us to move terraform resources from one project to another with zero downtime and no lost messages.
- Ran monthly 'lunch and learn' sessions for the engineering team. This generally involves a high level of overview, or deep dives on subjects such as:
  - Kubernetes
  - Networking
  - CI/CD pipelines
  - Terraform best practices
  - Client specific implementations of the above subjects

## Lloyds Banking Group (Contract via Publicis Sapient)

**November 2022 – July 2023**

**Role**: Senior DevOps Engineer

**Environment/Tooling:** Google Cloud Platform, Github, Github Actions, Jira, confluence, GCP IAM, Google Kubernetes Engine, terraform, Hashicorp Vault, helm, Istio/Anthos Service Mesh, GCP Private Service Connect, Terraform Cloud

**Responsibilities:** Deployed within the networking team, I am responsible for designing and creating Shared VPCs, DNS zones, connectivity options between hubs and spokes within hub & spoke network design. Designing and reviewing firewall rules. Creating archetypes to automate the creation of on-demand infrastructure etc:

- Created Shared VPC terraform module
- Created Private Service Connect terraform module
- Created Private Service Connect Architectural Decision document and presented to AD forum
- Created Multiple connectivity option Architectural Decision document and presented to AD forum
- Designed and built archetype to automate creation of Shared VPC Service projects and associated terraform cloud workspaces
- Designed and built elements of archetype to automate the creation of network composite module for other teams
- Running monthly 'lunch and learn' sessions for the engineering team. This generally involves a high level of overview, or deep dives on subjects such as:
  - Kubernetes
  - Networking
  - CI/CD pipelines
  - Terraform best practices
  - Client specific implementations of the above subjects

## Virgin Media O2

**January 2022 – November 2022**

**Role**: Senior DevOps Engineer

**Environment/Tooling:** AWS, EKS, Amazon S3, AWS IAM, AWS Codebuild, Elastic Load Balancer, CloudFormation, Route53, Google Cloud Platform, Gitlab Pipelines, Gitlab repos, Jira, confluence, GCP IAM, Google Kubernetes Engine, terraform, Hashicorp Vault, helm, Apigee, Istio/Anthos Service Mesh, env0, Angular, IaaS, PaaS, Linux containers (mostly alpine), bash

**Responsibilities:** Hired as a senior team member with existing GCP and kubernetes experience. Due to my previous experience building new environments from scratch I was immediately given high priority, high visibility work on the company CMS system that's integrated into the main, publicly facing website.

Projects:

- Migrated CMS system from a cluster running in EKS to GKE, this required substantial modification. Involved in creating the ingress, building helm charts, building pipelines and working collaboratively with several engineers to meet a tight deadline and get the system into production.
- Building and debugging AWS infrastructure – Frontend Angular application hosted in S3 buckets and deployed with CodeBuild. DNS hosted in Route53. Backend hosted in EKS prior to migration to GKE.
- Built micro-service architecture platform virtually from scratch. The system is using Apigee as an API endpoint, which was set up with an external load balancer, this then passed traffic to a GKE backend living in the same Shared VPC as the Apigee organisation. I was responsible for modifying the original proposed architecture, which was to use VPC peerings between Apigee and GKE. I proposed we instead use a Shared VPC, this proposal was then validated by Google as the correct approach. I set up the VPC, an internal load balancer, the GKE cluster, ASM and worked via Apigee to send API requests from an external location all the way to the GKE backend to ensure connectivity. I Created Build and Deployment pipelines for the platform from scratch. Also responsible for platform security – Setting up firewall rules, IAM roles etc. I did this work primarily alone for several months with limited documentation and assistance due to workload among the remainder of the team. All work was done via IaC (Terraform)
- Involved in setting up new folders, GARs, IAM etc for onboarding new departments. This was done via a complex process using env0 scripts. Was able to perform this task in a matter of days when the average time of completion prior to that was several weeks
- Proposed improvements for evergreening Infrastructure components, such as GKE, terraform modules, container images
- Worked in an extremely complex environment with repos nested inside of repos, terraform modules calling on multiple other modules and have a very good understanding of what an enterprise Infrastructure codebase should look like and how to design and navigate it.
- Mentored teammates on best practices around upgrades, security and helped various team members gain a better understanding of Kubernetes, IaC, VCS'.

## Freshfields Bruckhaus Deringer

**September 2020 – January 2022**

**Role:** Cloud Platform engineer

**Environment/Tooling:** Microsoft Azure, Azure DevOps Pipelines, Azure repos, Jira, bitbucket, confluence, Azure AD, Azure Kubernetes Service, Azure VNET design and creation, Azure NSG rule design and creation, terraform, helm, Azure SQL, Azure PostgreSQL, OracleDB, Visual Studio, Azure Data Factory, SSIS, elasticsearch, .NET applications, IIS, IaaS, PaaS, Linux/Windows containers, PowerBI, Powershell

**Responsibilities:** I was brought into the organisation to both to help put some governance and guidelines in place for managing the Azure environment due to my extensive experience managing and maintaining Enterprise Identity services like Azure Active Directory, but also due to my considerable experience as a DevOps engineer.

Projects:

- Migrated two .NET applications from SaaS into an existing AKS cluster. I also did a lot of work improving this existing environment by rearchitecting the Azure DevOps pipelines to use yaml format, and identified inefficiencies in the build process and cut out a great deal of unnecessary steps and processes. I also made numerous improvements to the Kubernetes cluster
- Created a PoC to run our primary mass claims application within. This involved migrating a complex multilayer IaaS application into AKS and Azure SQL. All configuration built out using terraform.
- Migrated existing ETL process into Azure Data Factory – Converted SSIS packages into Azure compatible versions and moved them into Azure SQL DB (SSISDB) using the Azure-SSIS integration runtime. Created ETL workflow in Azure Data Factory (ADF) with the same functionality as the existing on-prem workflow.
- Given lead on another project which is due to commence after the current one. This is also migrating a SaaS application into AKS
- Responsible for managing and maintaining Azure AD groups and delegating permissions to other users within the tenant. Identified multiple improvements that could be made in terms of user management, security and costing.
- Running monthly training sessions for other engineers to attend. Currently we're focusing on Docker and Kubernetes.

Finally, I was nominated for an internal award at the company – "The Do-er" within 3 months of being at the company. I believe this is due to my unwavering approach to delivery.

## Yozu

**April 2019 – September 2020**

**Role:** DevOps Engineer

**Environment:** Google Cloud platform, Digital Ocean, Google Kubernetes Engine, Hyper-V, Ubuntu server, Ubuntu desktop, Windows Server 2008/2012/2016, Windows 10.

**Supported application environment:** Ruby on rails, sidekiq, redis, react, ELK, graylog, Prometheus/Grafana, mysql, postgres, mongodb, nginx, apache, IIS, docker, kubernetes, ansible, terraform, AWX, bitbucket, jira, asterisk, freepbx, sage, exchange, dynamics CRM, Sharepoint, bash/powershell, bitbucket pipelines, helm, skaffold, google cloud build, vagrant

**Responsibilities:** Solely responsible for building and maintaining the infrastructure for multiple bespoke applications, as well as designing, testing and debugging CI/CD pipelines. Our environment includes over 30 virtual machines located either on site or in the cloud. I am solely responsible for creating and maintaining virtual machine instances, kubernetes clusters, docker environments, VPCs, IAM settings, firewall settings, diagnosing proxy issues, diagnosing database issues, diagnosing performance issues on core infrastructure, for instance - disk space issues. Creating and maintaining DNS records, creating and maintaining SSL certificates, creating scripts to automatically fix server and container side issues and configuring alerts. Committing all infrastructure code to source control. I'm also responsible for 4 physical servers, (over 20 Hyper-V VMs), including 2 separate active directory domains, 2 separate VOIP systems, exchange server, CRM, Sharepoint, backups etc. Racking and configuring Unifi security gateway/router and switches including opening and forwarding correct ports, port forwarding and creating security settings.  
<br/>

**Projects:**

- Documented entire infrastructure for DR purposes.
- Created 20 page infrastructure security documentation and best practices to meet client contract requirements.
- Designed and implemented backup infrastructure for all current applications (mysql dump/postgres dump & scp to a remote server.)
- Designed and built application environment for multiple applications. Mostly in docker-compose/Kubernetes. CI/CD solutions are a combination of bitbucket pipelines and Google Cloud Build.
- Created a terraform library for GCP/Digital Ocean resources. Currently in its infancy but includes the creation of a VPC that supports VPC native Kubernetes clusters, and VM instances for both GCP and Digital Ocean
- Created an ansible library for various infrastructure components. For instance server security settings, Kubernetes dev environments.
- Solely responsible for creating and maintaining 2 kubernetes clusters for 2 separate production applications. (One brownfield and one greenfield). Main deployment tool used being helm. Helm subcharts implemented including cert-manager, redis-sentinel, nginx-ingress-controller and Prometheus-operator. Mozilla sops utilised to encrypt data at rest. CI/CD solution is Google Cloud Build. DB-migrate solution using helm hooks.

## Getthelabel.com/Topgrade sportswear

**May 2015 – March 2019**

**Role:** IT support engineer

**Environment:** Windows server 2003-2012, CentOS, Windows XP/7/10, Netgear/Cisco routers & switches.

**Supported applications:** Bespoke retail ordering/warehouse management system (Elucid.), Zeacom (Call centre), sage 200, figure gemini (POS system), OfficeCalendar, photoshop, filezilla, sysaid, etc.

**Administrative applications:** Kaspersky security centre, Avaya IP Office, samsung phone system (IT tool), Windbg, Microsoft application compatibility toolkit, Windows deployment tools, Timebox (clocking machine software) MyInbound, cPanel (email server), etc.

**Supported devices:** Servers, desktops, laptops, network devices & cabling, laser printers, label printers, scanners, barcode scanners, handheld scanners, tills (POS systems), CCTV cameras, android based phones, iPhones, Intel compute sticks, monitors, IP phones, etc.

**Responsibilities:** Server maintenance, configuration & patching. Server-side application troubleshooting (services, open files, logs, permissions, etc.) Group policy administration, Active directory administration. (User setup, permissions, etc.) Client side troubleshooting (Device, application, drivers, network, etc.) Client side patching including scripting missing updates & rolling back updates with powershell. Determining necessity for device upgrades. Purchasing upgrades & supplies, liaising with 3<sup>rd</sup> parties. (Printer maintenance, phone systems, suppliers.) Device setup, maintenance & tweaking. Creating & updating documentation. Reviewing security incidents on CCTV cameras from the main site & retail stores.

**Projects:**

- Implemented, documented & scripted OS build system using Hyper-V, sysprep, DISM, imageX, WinPE, powershell etc.
- Setup Group Policy environment to be more efficient and more in line with Microsoft best practices.
- Setup IT infrastructure at various retail stores around the country, including till/device setup, camera setup, music/speaker system setup & ADSL router setup.
- Co-Installed up to 50 CCTV cameras & DVR system inside our warehouse

## Startek

**May 2014 – May 2015** (Unpaid – Part time for 6 months, full time for 6 months.)

**Role:** PC technician

**Responsibilities:**

- Troubleshooting and repairing desktops, laptops, games consoles, high end gaming and video editing PCs, tablets and mobile phones. Screens, Hard drives, keyboards, touchpads/clickers, DC jacks, optical drives, video cards, applying thermal paste, dust removal, plastic welding, soldering.
- Establishing customer requirements & details in person or via telephone.
- Ordering replacement parts from suppliers
- Organising & replenishing stock. Organising and cleaning shop floor and back room.
- Booking customers onto the system, creating invoices. Cash handling.
- Increasing revenue by offering additional services. Including subscription & contract based services.
- Handling customer grievances in a timely manner.
- Offering friendly and professional customer service. Providing after sales support, including telephone and remote support.

## B&M retail

**Jul 2011-October 2014**

**Role:** Various. (Warehouse operative, warehouse trainer, POS assistant, Accounts assistant.)

# Certifications

**AWS DevOps Engineer Professional –** August 2023

**GCP Professional Architect –** November 2022

**RHCE – (Linux Automation with Ansible) –** March 2022 (Self Funded)

**RHCSA** – March 2019 (Self Funded)

**LPIC-1** – December 2018 (Self funded)

**CompTIA Linux+** - December 2018 (Self funded)

**MCSE: Cloud Platform & Infrastructure (Implementing Azure Solutions)** – September 2018 (Self funded)

**CCNA: Routing & Switching** – July 2018 (Self funded)

**CCNA: Cyber Ops** – June 2018 (Cisco Cybersecurity Scholarship)

**CompTIA Security+** - March 2018 (Self funded)  
**MCSA: Server 2012** – December 2017 (Self funded)

**MCITP: Enterprise Desktop Support Administrator** – June 2017 (Self funded)

**MCITP: Enterprise Desktop Support Technician** – March 2017 (Mostly self funded)

**MCSA: Server 2008** – February 2017 (Self funded)  
**ITIL foundation v3** – July 2015 (Self funded)

**CompTIA Network+** - May 2015 (Self funded)

**CompTIA A+** - February 2014 (Self funded)

**Forklift Counterbalance & Forklift reach licences (Expired)** – 2012 (Self funded)

# Hobbies

Mixed Martial arts training. (BJJ Purple belt, Muay Thai and Wrestling.) Playing Guitar and singing. (Previously been in a metal band as a singer.) Playing and watching sports, mainly football. Cryptocurrency HODLing. Occasional video game player
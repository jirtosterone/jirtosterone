# Curriculum Vitae

## Basic Information

- **Name**: Jun Irie
- **Date of Birth**: March 29, 1984

## Summary

### Career History

| Period                       | Company         | Type      | Role / Position                                          |
| ---------------------------- | --------------- | --------- | -------------------------------------------------------- |
| April 2011 - February 2024   | Hitachi, Ltd.   | Full-time | Software Engineer, Public Sector SE / Supervisor         |
| October 2022 - February 2024 | SimpleForm Inc. | Contract  | Infrastructure Engineer / Tech Lead                      |
| March 2024 - Present         | SimpleForm Inc. | Full-time | Infrastructure & Security Engineer / Engineering Manager |

### Experience & Technology

- Software design and development
- Solution architect and consulting from on-premises to cloud
- Project management, pre-sales, and customer negotiations
- RFI to RFP response for government procurement
- Infrastructure architect, SRE, and platform engineering for SaaS products

### Mindset

- **Initiative**: Notice and proactively solve necessary tasks that others are reluctant to take on.
- **Immediate Practice**: Stay tuned to new technologies and practice them myself.
- **Communication and Involvement**: Output and share practiced knowledge and experience, and involve others.

### Future Goals / What I Want to Keep Doing

- Contribute to the future of the planet through engineering.
- Create and spread excitement through engineering.
- Continuously challenge new things and share the results.
- Continue proposing and building highly reliable and efficient platforms centered on AWS and infrastructure knowledge.

## Work Experience

### Hitachi, Ltd.

<details>
<summary>April 2011 - September 2015: Design, Development, and Sales of Big Data Processing Software</summary>

### Project

#### Overview

- Development of proprietary big data processing software

#### Role/Responsibility

- In charge of basic design to testing
- Led small teams of several members

#### Work Content

- Software design
- Development in Java
- Command development using bash

#### Achievements

- While the overall project was delayed, maintained delivery schedule as team lead and achieved the highest development efficiency (0.5ks/person-month) within the project.
- Presented product at conference "db tech showcase Tokyo 2015" ([presentation materials](https://www.slideshare.net/slideshow/dbts-tokyo-2015-c33-bigdata-hitachi/49595703)).

### Technologies Used

#### OS

- Linux

#### Languages

- Java
- bash
- C++

#### Frameworks

None

#### Middleware

- Proprietary RDBMS (HiRDB)
- Apache Tomcat

#### Others

- Jenkins

### Scale/Responsibility

#### Project Scale

- Total of about 15 members (led about 5 members)

#### Customers

- Domestic securities exchange
- UK telecommunications company

</details>

<details>
<summary>October 2015 - March 2021: System Proposal, Construction, and Operation in Education Sector</summary>

### Project

#### Overview

- Construction of educational research systems for universities
- Construction and operation of authentication infrastructure systems for universities
- Operation and proposal of supercomputer systems for universities
- Network system renewal proposals for universities
- Cloud migration proposals and construction

#### Role/Responsibility

- Project leader for proposals (pre-sales), construction, and operational maintenance

#### Work Content

- Overall project coordination
- System design, construction, and operational maintenance

#### Achievements

- Led authentication infrastructure system construction project for a university with tens of thousands of users as project leader. Successfully operated with minimal issues despite complex integration requirements with various campus systems and Microsoft Office 365.
- Designed and built core systems based on Azure and AWS, as well as hybrid cloud combining on-premises infrastructure. In an environment lacking cloud expertise, improved team-wide technical capabilities through certification acquisition and member training sessions while simultaneously conducting design and construction, successfully completing the project.

### Technologies Used

#### OS

- Windows
- Linux
- vSphere
- Xen

#### Languages

- Python
- PHP
- bash
- PowerShell

#### Frameworks

- Unity
- Bootstrap

#### Middleware

- PostgreSQL
- MySQL
- MariaDB
- Apache Tomcat
- Zabbix

#### Cloud

- AWS: EC2, RDS, Lambda, S3, etc.
- Azure: VM, DB, CosmosDB, Functions, ExpressRoute, etc.

### Others

- IaC: Ansible, ARM templates

### Scale/Responsibility

#### Project Scale

- Budget: Tens of millions to hundreds of millions of yen
- Team: About 50 members total (led about 10 members)

#### Customers

- National and private universities in Fukuoka
- Public universities in Hiroshima

</details>

<details>
<summary>October 2020 - February 2024: System Proposal, Construction, and Operation in Government Sector (Local Government)</summary>

### Project

#### Overview

- Construction and operational maintenance of private cloud for local governments
- Design and construction of public cloud for local governments

#### Role/Responsibility

- Overall project coordination
- System design and construction
- Cloud migration consulting

#### Work Content

- Overall project coordination
- System design, construction, and operational maintenance
- Solution architect for cloud migration

#### Achievements

- Successfully constructed and operated 12 servers and storage equipment for integrated virtualization infrastructure hosting various business systems for a prefecture within a tight 4-month deadline.
- Led proposals and design for public cloud migration, rare among local governments. As lead for cloud infrastructure design, consulted from upstream stages to create system concepts with customers and successfully won contracts for actual work.
- Promoted Digital Agency's Government Cloud pilot projects and cloud research cases for ordinance-designated cities
  - [Kobe City as Government Cloud Pilot Project](https://aws.amazon.com/jp/blogs/news/city-of-kobe-as-a-front-runner-of-government-cloud-kikankei-migration-poc/)
  - [Joint Research for Kitakyushu City Next-Generation System Common Infrastructure](https://aws.amazon.com/jp/blogs/news/city-of-kobe-as-a-front-runner-of-government-cloud-kikankei-migration-poc/)

### Technologies Used

#### OS

- Windows
- Linux
- vSphere

#### Languages

- Python
- TypeScript
- bash
- PowerShell

#### Frameworks

None

#### Middleware

- Oracle DB

#### Cloud

- AWS: EC2, RDS, Lambda, S3, Security Hub, GuardDuty, Control Tower, Direct Connect, etc.

### Others

- IaC: CloudFormation, CDK, Terraform

### Scale/Responsibility

#### Project Scale

- Budget: Billions of yen
- Team: About 80 members total (led 20-30 members)

#### Customers

- Prefectures and cities in Kyushu region
- Cities in Kansai region

</details>

### SimpleForm Inc.

<details>
<summary>March 2024 - March 2025: AWS Infrastructure Design, Construction, and Operation</summary>

### Project

#### Overview

- Development of credit assessment support service for financial institutions

#### Role/Responsibility

- Development member (contractor) primarily responsible for infrastructure design and development

#### Work Content

- Service infrastructure design
- Multi-account management and security design

#### Achievements

- Planned and executed transition from single AWS account mixing production, testing, and development environments to multi-account configuration, achieving governance management for each environment.
- Implemented SSO authentication for various services centered on IAM Identity Center, contributing to improved ID management security.
- Introduced organization-wide security configuration management and monitoring centered on Security Hub, successfully achieving continuous infrastructure security improvement.

### Technologies Used

#### Languages

- Ruby
- Python
- TypeScript
- Terraform/Terragrunt

#### Frameworks

- Ruby on Rails
- FastAPI

#### Cloud

- AWS: Control Tower, IAM Identity Center, Security Hub, GuardDuty, ECS, ELB, CloudFront, etc.

#### Others

- IaC: Terraform, Serverless, CloudFormation
- Observability: New Relic, Sentry

</details>

<details>
<summary>April 2025 - Present: Infrastructure/Security Leadership</summary>

### Project

#### Overview

- Development of credit assessment support service primarily for financial institutions

#### Role/Responsibility

- Infrastructure engineer responsible for infrastructure design and development
- Backend engineer responsible for service design and development
- Engineering manager leading infrastructure/security/IT systems

#### Work Content

- Infrastructure/security design and operation
- In-house service design, development, and operation
- Infrastructure/security/IT systems roadmap planning and various initiatives execution

#### Achievements

- Resolved performance and reliability issues with Amazon Neptune (graph database) - a technology with few global use cases - through infrastructure configuration changes (serverless introduction) and query improvements, achieving stable operation and ongoing continuous improvement.
- Proposed and introduced continuous improvement processes using GitHub Dependabot and SAST to improve overall service security, implementing DevSecOps.
- During office relocation due to company growth, led office network design and construction through vendor coordination, completing relocation without major issues. Also reviewed unnecessary telephone and network contracts during relocation, contributing to cost reduction.
- External publication: [Findy Tools - SimpleForm's Serverless Microservices Architecture](https://findy-tools.io/companies/simpleform/221/74)

### Technologies Used

#### Languages

- Ruby
- Python
- TypeScript
- Terraform/Terragrunt

#### Frameworks

- Ruby on Rails
- Django
- FastAPI

#### Cloud

- AWS: Control Tower, IAM Identity Center, Security Hub, GuardDuty, ECS, ELB, Lambda, CloudFront, Aurora MySQL, Neptune, ElastiCache, OpenSearch, etc.

#### Others

- IaC: Terraform, Serverless, CloudFormation
- CI/CD: GitHub Actions
- Observability: New Relic, Sentry, Datadog
- AI: OpenAI, Anthropic, GitHub Copilot

</details>

## Certifications

- IPA
  - Fundamental Information Technology Engineer Examination
  - Applied Information Technology Engineer Examination
  - [Registered Information Security Specialist](https://riss.ipa.go.jp/r?r=025102)
- AWS
  - AWS Certified Cloud Practitioner
  - AWS Certified Solutions Architect - Associate
  - AWS Certified CloudOps Engineer - Associate
  - AWS Certified Developer - Associate
  - AWS Certified Solutions Architect - Professional
  - AWS Certified DevOps Engineer - Professional
  - AWS Certified Advanced Network - Specialty
  - AWS Certified Security - Specialty
  - Reference: [Credly](https://www.credly.com/users/jun-irie.0e6f8b3e)
- UMTP
  - UML Proficiency Certification L1, L2, L3

## Blog & Publications

- [Zenn](https://zenn.dev/jirtosterone)
- [Qiita](https://qiita.com/jirtosterone)
- [note](https://note.com/jirtosterone)

## Skills

https://github.com/jirtosterone

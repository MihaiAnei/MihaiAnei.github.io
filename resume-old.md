<br/>

# Skills <a href="javascript:window.print()"><i class="resume-print icon-print"></i></a>

### Tools
--------
- IntelliJ IDEA, Sublime, VSCode
- Starship Prompt
- ZSH, oh-my-zsh
- GitLab, GitHub, Gogs
- GNU/Linux(Arch/Manjaro), MacOS

<br/>

### Programming Languages
------------
- Main languages: Java, Scala
- Other interests: Go, NodeJS

<br/>

### Spoken Languages
------------
- Romanian (Native)
- English (Great)

<br/>

### Other technologies and knowledge
------------------------------------
- Linux Containers (Docker, Rkt)
- Networking
- Kubernetes (Great)
- CI/CD Automation
- Virtualization (VMWare, KVM)
- ArgoCD / Flux / Helm Operator / FluxV2
- Kubernetes Operators Pattern
- Terraform
- Ansible
- Prometheus
- AWS & GCE

<br/>

### Databases / Stores / Others
------------------------------------
- PostgreSQL, Cassandra, MongoDB, Redis
- Elasticsearch, Logstash, Kibana
- Kafka/Strimzi, RabbitMQ

<br/>

# Experience

### Neverfail (Artisan Infrastructure)
*August 2013 – November 2016 | Cluj County, Romania

The company went through a lot of transitions in the last couple of years. Changing focus and building new products,
I was part of different teams focused on using new technologies that helped us implementing solutions regarding
network analysis and discovery, infrastructure automation, builing a cloud platform and big data analysis. 
I was responsible with software implementation and testing (mainly **java** with Spring but also a bit of C/C++,
bash, scala), maintenance of different systems and servers, automation and integration for a couple of external services.
<br/>

**Projects at Neverfail that I worked on:**

* #### Architect
> The project is a network analysis and discovery tool that can keep track of
> different hosts and applications on a given network. It is able to build 
> dependecies between network traffic, Operating Systems and Applications.
> I was responsible with research, implementation and building different 
> dependecies for the project (winexe, nmap, OVA appliance).
<br/>
> **Worked with: Java, Spring, PostgreSQL, Nmap, pcap, winexe, OVA Appliances, Netapp**

* #### Virtual Private Datacenter
> This project was focused on automating the deployment of new hardware and products 
> in our datacenters. I had to work with mutiple external services, integrate with their
> APIs, write automation solutions described by the sales and hardware team.
<br/>
> **Worked with: Agile-Scrum Methodologies, Java, Spring Web, Spring Boot, HATEOAS REST APIs**

* #### Cloud Service Architect
> Following the previous project, this one was focused on exposing the hardware from datacenters 
> to clients through a web platform. The whole project was based on microservice architecture, Docker
> and Rancher as a Container Orchestration tool. I worked with different teams and during the project
> I was responsible for some of the services in the platform, Rancher Orchestration server, 
> deployment architecture, continous delivery and maintenance of the production environment.
<br/>
> **Worked with: Spring Boot, Spring Cloud, Rest APIs, Salesforce Integration, MongoDB, PostgreSQL,**
> **ActiveMQ, Rancher, Docker, Jenkins, GoCD**

* #### Data Driven Services - Billing
> In order to be able to bill every hardware usage from the company, this project was designed to
> gather all the required information from the infrastructure, aggregate all the data and build an
> invoice for all the clients. Together with a team, I worked on collecting the data and save it to 
> Cassandra, writting aggregation algorithms using the data from Cassandra and Apache Spark.
> Also we had to research best practises for deploying Cassandra and Spark into a production environment
> and find the best deployment methods that suited our needs. 
<br/>
> **Worked with: Java8, Spring Boot, Immutables, Functional Programming (in Java and a bit in Scala),**
> **Cassandra, Apache Spark, ActiveMQ**

### PitechPlus
*January 2017 – March 2017 | Cluj County, Romania

Worked with AWS and CI/CD solutions for different projects.
<br/>

### iQuate Ltd.
*April 2017 – July 2018 | Cluj County, Romania

The company is focused on building a platform that scans and then analyses 
data coming from infrastructure in different datacenters.I am currently 
working on the project that takes care of the second part.
<br/>

* #### HADM
> Microservice platform written in Scala and using Akka Framework (mostly) that analyses the data regarding
> infrastructure. My main focus is the communication between the platform and the component that sends data from 
> datacenters, the deployment of the required services (Kubernetes on Bare Metal, Kafka, Cassandra) and CI/CD.
<br/>
> **Worked with: Scala, Akka, Play, Kubernetes, AWS**

### ComplyAdvantage
*July 2018 – March 2020 | Cluj County, Romania

The company is focused on building a persons database from public information
and media with the purpose of fighting financial crime and corruption.
<br/>

* #### DevOps/SRE
> Worked with an SRE team on adopting Kubernetes throughout the company and improving the general state of the infrastructure,
> which is based on AWS. At the same time worked embedded in many development teams and helped with their immediate necessities.
> Was involved in some design decisions as well for the systems we made.

> Worked on improving other aspects of development lifecycle:
> * CI and release
> * Automating integration/performance tests with GitLab and K8S
> * Technology adoption requirements
> * CD with GitOps

> Worked with the SRE team on designing and implementing the same set of toolings and infrastructure throughout all our AWS accounts.
> We reffered to this as a development and production release platform developers can use without too much of our help:
> * Same AWS EKS configuration and access
> * Prometheus Operator
> * FluentD, FluentBit and ElasticSearch stack for Logging and Application Monitoring
> * Strimzi Operator for Kafka
> * ArgoCD GitOps approach for keeping all this and application deployments up to date with just using Git
> * and many others...

> Wrote a bit of code when was required and time allowed it, in Go and Python.
<br/>
> **Worked with: AWS, Terraform, AWS EKS, ArgoCD, GitLab and many other AWS Services and other tools**

### Cloudsphere
*March 2020 – Present | Cluj County, Romania

Datacenter scanning, cloud migration planning and, more recently, cloud covernance.
<br/>

* #### DevOps/SRE
> I was responsible of improving, consolidating and updating the infrastructure for the services
> developed in the company, as well as help simplifying the CI/CD pipelines and processes.

> * Implemented monitoring stack using Prometheus Operator
> * Implemented logging stack using Elasticsearch Operator, Logstash, Filebeat and Kibana
> * PoC and then implementation of CD with Flux and Helm Operator
> * Centralized and improved GitLab CI Pipelines definitions for Scala SBT based projects
> * Upgraded most Scala services to JDK 11, mostly for better CGroups limits support
> * Cleaned up terraform and added support for workspaces in Azure, AWS and VMware
> * Moved most of service dependencies to Kubernetes: Kafka, RabbitMQ, Elasticsearch
> * Used Zalando's Postgresql Operator for on-prem environments (RKE and VMware)
> * Upgraded all K8S Clusters to at least 1.17 (RKE, AKS and EKS)
> * Migrated GitLab to a new server and used Ansible for easier management and upgrades
> * Used Ansible to deploy Cassandra in the newly created environments

<br/>

# Education

### Babeș-Bolyai University - Cluj-Napoca
--------------------------

2012 - 2015 - Bachelor of Computer Science

### Colegiul National Radu Negru - Fagaras
--------------------------

2008 - 2012 - High School Diploma Math - Computer Science

# playbook

Play |	Description |	Results |	Best Practices
--- | --- | --- | ---
Microservice Architecture | Breaks a monolithic application into self-contained microservices |	Results in easier to develop and maintain applications, autonomous and cross-functional teams, flexibility in using technologies and scalability| Loose Coupling, Stateless Application, Containerization
Cloud-Native Services | Design architecture with Cloud-Native services in mind | Results in reduced operations Cost, Elasticity, Scalability and Fault-Tolerant Applications| Infrastructure-as-Code (IaC), Immutable Infrastructure, Dev-Prod Parity
API-First Development | Treats APIs as first-class citizens when a product or service is designed and provides a contract |	Results in Parallel development teams, reusability of the developed services, good developer experience, and reduced risk of failure. |	OpenAPI Specification, Hypermedia as the Engine of Application State (HATEOAS), API Contracts
Data-Driven Solutions | Design your solution to be optimal to the problems that the data will have at scale	| Results in optimized response time, scalability, maximum value from the data | Event Storming, Domain Driven Design (DDD), Decoupled Persistence, Intelligent Search
Shift-Left Security | Security should not be an afterthought and should be built into the development process. | Results in rapid ATO, easier to resolve security issues, and reduced risk of failures | Security Scans, Encryption In-Transition and At-Rest, Penetration Testing
Automation Everywhere | Build a development pipeline that provides automation for developers and allows for rapid development	| Results in fast delivery, reduced risk of failure, measurable progress, version control	| Automated CI/CD pipeline, Automated Testing, Automated Monitoring/Alerts, Autoscaling
Built-in Quality | Quality should be part of the process and not a separate activity |	Results in lower costs, fewer bugs, increasing returns, and stakeholders confidence	| Test Driven Development (TDD), Behavior Driven Development (BDD), Unit/Integration/End-to-End/Load, Quality Gates | Human-Centered Design	Provide an approach that makes for a better user experience, including making information accessible to all constituents | Results in customer-driven solutions, maximum accessibility, good user experience	| Best practices include 508 compliance, United States web design system, code scaffolding, complete documentation

# reference architecture

![alt text](https://github.com/USPTO/playbook/blob/master/refarch.png "Reference Architecture")


# technology toolbox

Layer |	Category | Technology Tools
--- | --- | ---
Agile |	Code Repository |	GitHub, GitLab
Agile |	Collaboration |	SharePoint
Agile |	Communication |	Microsoft Teams
Agile |	Scrum/Kanban Board |	Rally
Data |	CDN | Amazon Cloud Front
Data |	Caching | Redis, Memcached, Amazon ElastiCache
Data |	Client-Side Caching |	IndexedDB, HTML WEb Storage
Data |	Cluster |	Hadoop-HDFS, Spark, Ambari, Apache Zookeeper
Data |	Content Management |	Alfresco, Patent CMS
Data |	DB-Connections |	c3p0, ODBC, JDBC, Spring JDBC
Data |	DB-Document Oriented |	MongoDB, Amazon DocumentDB (with MongoDB compatibility)
Data |	DB-Graph Oriented |	Neo4J, Amazon Neptune, Azure Cosmos DB
Data |	DB-Relational |	MySQL, Amazon Aurora (MySQL), Percona (MySQL), Oracle, Amazon RDS (Oracle), PostgreSQL
Data |	ETL/Streaming |	Apache Nifi, Alteryx, Amazon Glue, Apache Kafka, Spark Streaming, Amazon Kinesis Data Streams (Kafka), Amazon Kinesis Firehose (Kafka), Amazon Managed Streaming for Kafka (Amazon MSK)
Data |	Queue | Apache Kafka, Jboss AMQ
Data |	Schema Version Control |	Liquibase
Data |	Search |	Elasticsearch, Solr
Data |	Synchronization |	Oracle Data Guard
Data |	Visualization |	Alteryx Tableau Desktop, elastic Kibana, Amazon QuickSight, PowerBI
Data | 	 Warehouse & Data Mart | USPTO Enterprise Data Warehouse
Desktop |	Browser | Current Browser Trends
Development |	AOP |	AspectJ, Spring AOP
Development |	API |	Swagger, OpenAPI, Spring Cloud Contracts, SpringFox
Development |	Authentication/Authorization |	Okta, Oracle IAM, Amazon AWS IAM, Azure AD, MyUSPTO, Spring Security
Development |	Authoring | MS Word, CKEditor
Development |	Build Packages |	Maven, NPM, Webpack, Bower, ES6 Modules, Gulp, Angular CLI
Development |	Code Documentation |	Javadoc
Development |	Data Science Tools|	Jupyter Notebook, Zeppelin Notebook, Apache Hive
Development |	Data Science-Languages |	Julia, R Lang, Python
Development |	Data Science-ML |	Tensorflow, Google Cloud ML, Apache Spark MLlib, AWS SageMaker
Development |	Data Science-NLP |	Stanford NLP
Development |	Framework-Backend |	Spring Boot, Node.js
Development |	Framework-Frontend |	Angular, React, Vue
Development |	IDE |	Eclipse, Sublime Text, IntelliJ IDEA, Anaconda, R Studio, Visual Studio Code
Development |	Languages |	Java, JavaScript, TypeScript, Google GO
Development |	Notification |	Email, USPTO Internally Developed REST API for AWS, AWS SQS, AWS SNS
Development |	ORM | 	Hibernate, Sequelize
Development |	Optical Character Recognition (OCR) | 	Tessaract, Tika-server
Development |	PDF Content Management | Apache PDFBox, Antenna House Formatter, iText, PDFTron WebViewer
Development |	Parse, Serialize, Transform |	Jackson, Java Architecture for XML Binding (JAXB)
Development |	Services-REST | Jersey, RESTEasy JAX-RS, Spring Boot REST
Development |	Services-SOAP | Apache Axis2
Development |	Style |	USWDS, Bootstrap, HTML5, CSS3, SASS, USPTO Design Pattern Library (DPL)
Infrastructure |	API Gateway |	Kong, MuleSoft, Apogee, Broadcom Layer 7 Gateway
Infrastructure |	Cloud |	AWS, Azure, GCP, MicroPact
Infrastructure |	Cluster |	Hadoop-HDFS, Ambari, Apache Spark, Yarn, Apache Zookeeper
Infrastructure |	Container Compute | Amazon Fargate
Infrastructure |	Container |	Docker, containerd, CRI-O
Infrastructure |	IaC |	Terraform, AWS Cloud Development Kit (CDK)
Infrastructure |	Orchestration |	Kubernetes, Amazon ECS, Amazon ECR, Amazon EKS
Infrastructure |	Pipeline |	Amazon Jenkins, Jenkins, AWS CodeDeploy
Infrastructure |	Platform |	OpenShift
Infrastructure |	Repository Manager |	Nexus
Infrastructure |	Service Mesh |	Istio
Infrastructure |	Workflow |	USPTO Hierarchical Finite State Machine
Operations |	APM |	AppDynamics
Operations |	Dashboards |	Grafana, elastic Kibana
Operations |	Metrics |	Prometheus, Logstash, Splunk, Fluentd, AppDynamics Pro, Google Analytics, HP SiteScope
Operations |	Monitoring |	Splunk, Logback, Log4j2, SLF4J, AppDynamics Pro, JBoss EAP Logging, HP SiteScope, Fluentd, QRadar, Amazon X-Ray
Operations |	Scheduling |	Quartz Scheduler
Testing |	Accessibility/508 |	Pa11y, ANDI, Wave Plug-In for Chrome by Webaim
Testing |	Integration |	Selenium, Protractor, Cucumber
Testing |	Penetration |	OWASP Zed Attack Proxy (ZAP), Fortify, WebInspect
Testing |	Performance |	JMeter, Gatling, LoadRunner
Testing |	Static Code Analysis |	SonarQube
Testing |	Unit |	JUnit, Jest, Jasmine, Mockito, OpenPojo, jMock, Spring Cloud Contracts, Karma

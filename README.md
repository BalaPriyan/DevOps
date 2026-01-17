# Complete DevOps Tools Reference Guide

> A comprehensive catalog of industry-standard DevOps tools organized by category

## 🔄 Version Control Systems (VCS)

- **Git** - Distributed version control system
- **GitHub** - Web-based Git repository hosting
- **GitLab** - Complete DevOps platform with Git
- **Bitbucket** - Git repository management by Atlassian
- **Azure DevOps Repos** - Git repositories in Azure
- **Perforce (Helix Core)** - Enterprise version control
- **SVN (Subversion)** - Centralized version control
- **Mercurial** - Distributed version control

---

## 🏗️ CI/CD (Continuous Integration/Continuous Deployment)

### Cloud-Based CI/CD
- **GitHub Actions** - CI/CD integrated with GitHub
- **GitLab CI/CD** - Built into GitLab
- **CircleCI** - Cloud-native CI/CD platform
- **Travis CI** - Hosted CI service
- **Azure Pipelines** - Microsoft's CI/CD service
- **AWS CodePipeline** - Amazon's CI/CD service
- **Google Cloud Build** - GCP's CI/CD solution
- **Bitbucket Pipelines** - Atlassian's CI/CD
- **Semaphore** - Fast CI/CD platform
- **CodeShip** - Docker-based CI/CD
- **Buddy** - Fast deployment automation
- **Codefresh** - Kubernetes-native CI/CD

### Self-Hosted CI/CD
- **Jenkins** - Open-source automation server
- **Bamboo** - Atlassian's CI/CD server
- **TeamCity** - JetBrains CI/CD server
- **Drone** - Container-native CI/CD
- **Concourse CI** - Pipeline-based CI/CD
- **Buildkite** - Hybrid CI/CD platform
- **GoCD** - Open-source CD server
- **Spinnaker** - Multi-cloud CD platform
- **Argo CD** - GitOps CD for Kubernetes
- **Flux CD** - GitOps toolkit for Kubernetes
- **Tekton** - Kubernetes-native CI/CD

---

## 🐳 Containerization & Orchestration

### Container Platforms
- **Docker** - Container platform
- **Podman** - Daemonless container engine
- **containerd** - Industry-standard container runtime
- **CRI-O** - Lightweight container runtime
- **LXC/LXD** - Linux containers
- **rkt** - Container engine (archived)

### Container Orchestration
- **Kubernetes (K8s)** - Container orchestration
- **Docker Swarm** - Docker's native clustering
- **Amazon ECS** - AWS container service
- **Amazon EKS** - AWS Kubernetes service
- **Azure Kubernetes Service (AKS)** - Azure's K8s
- **Google Kubernetes Engine (GKE)** - GCP's K8s
- **Red Hat OpenShift** - Enterprise Kubernetes
- **Rancher** - Multi-cluster K8s management
- **Nomad** - HashiCorp's orchestrator
- **Apache Mesos** - Distributed systems kernel
- **K3s** - Lightweight Kubernetes
- **MicroK8s** - Minimal Kubernetes

---

## ☁️ Cloud Providers & Platforms

### Major Cloud Providers
- **AWS (Amazon Web Services)** - Leading cloud platform
- **Microsoft Azure** - Enterprise cloud platform
- **Google Cloud Platform (GCP)** - Google's cloud
- **IBM Cloud** - Enterprise cloud solutions
- **Oracle Cloud** - Enterprise cloud infrastructure
- **Alibaba Cloud** - Asian cloud leader
- **DigitalOcean** - Developer-friendly cloud
- **Linode (Akamai)** - Simple cloud hosting
- **Vultr** - Cloud compute platform
- **Hetzner Cloud** - European cloud provider

### Multi-Cloud & Hybrid
- **VMware Cloud** - Hybrid cloud platform
- **Red Hat OpenShift** - Hybrid cloud platform
- **Anthos** - Google's hybrid/multi-cloud
- **Azure Arc** - Hybrid cloud management

---

## 🏗️ Infrastructure as Code (IaC)

### Configuration Management
- **Terraform** - Infrastructure provisioning
- **Pulumi** - Modern IaC with programming languages
- **AWS CloudFormation** - AWS-native IaC
- **Azure Resource Manager (ARM)** - Azure IaC
- **Google Cloud Deployment Manager** - GCP IaC
- **OpenTofu** - Open-source Terraform fork
- **Crossplane** - Kubernetes-based IaC

### Configuration Management
- **Ansible** - Agentless automation
- **Chef** - Configuration automation
- **Puppet** - IT automation
- **SaltStack** - Event-driven automation
- **CFEngine** - Lightweight automation

### Policy as Code
- **Open Policy Agent (OPA)** - Policy engine
- **Sentinel** - Policy as code framework
- **Kyverno** - Kubernetes policy management
- **Conftest** - Test configuration files

---

## 📦 Package Managers & Registries

### Container Registries
- **Docker Hub** - Public container registry
- **Amazon ECR** - AWS container registry
- **Azure Container Registry (ACR)** - Azure registry
- **Google Container Registry (GCR)** - GCP registry
- **Harbor** - Open-source registry
- **Quay.io** - Container registry by Red Hat
- **GitHub Container Registry** - GitHub's registry
- **GitLab Container Registry** - GitLab's registry
- **JFrog Artifactory** - Universal artifact repository
- **Nexus Repository** - Artifact management

### Package Managers
- **Helm** - Kubernetes package manager
- **Kustomize** - Kubernetes config management
- **npm** - Node.js package manager
- **Maven** - Java project management
- **Gradle** - Build automation tool
- **pip** - Python package manager
- **NuGet** - .NET package manager
- **Composer** - PHP package manager
- **RubyGems** - Ruby package manager
- **Cargo** - Rust package manager

---

## 📊 Monitoring & Observability

### Metrics & Monitoring
- **Prometheus** - Time-series monitoring
- **Grafana** - Visualization & analytics
- **Datadog** - Cloud monitoring platform
- **New Relic** - Application performance monitoring
- **Dynatrace** - Software intelligence platform
- **AppDynamics** - Application performance
- **Nagios** - Infrastructure monitoring
- **Zabbix** - Enterprise monitoring
- **Sensu** - Monitoring framework
- **PRTG** - Network monitoring
- **Icinga** - Monitoring system
- **Checkmk** - IT monitoring
- **InfluxDB** - Time-series database
- **Graphite** - Metrics storage
- **VictoriaMetrics** - Fast time-series database

### Logging
- **ELK Stack (Elasticsearch, Logstash, Kibana)** - Log analytics
- **Splunk** - Data analytics platform
- **Graylog** - Log management
- **Fluentd** - Unified logging layer
- **Fluent Bit** - Lightweight log processor
- **Loki** - Log aggregation by Grafana
- **CloudWatch Logs** - AWS logging
- **Azure Monitor Logs** - Azure logging
- **Google Cloud Logging** - GCP logging
- **Papertrail** - Cloud-hosted logs
- **Logz.io** - ELK as a service

### Application Performance Monitoring (APM)
- **Jaeger** - Distributed tracing
- **Zipkin** - Distributed tracing
- **OpenTelemetry** - Observability framework
- **Elastic APM** - Application monitoring
- **AWS X-Ray** - Distributed tracing
- **Azure Application Insights** - APM service
- **Google Cloud Trace** - Distributed tracing
- **Lightstep** - Observability platform
- **Honeycomb** - Observability tool
- **Sentry** - Error tracking

### Alerting & Incident Management
- **PagerDuty** - Incident management
- **Opsgenie** - Incident management
- **VictorOps** - Incident response
- **Alertmanager** - Alert handling (Prometheus)
- **Chronosphere** - Cloud native observability
- **OnCall** - Incident management

---

## 🔐 Security & Compliance

### Secret Management
- **HashiCorp Vault** - Secrets management
- **AWS Secrets Manager** - AWS secrets
- **Azure Key Vault** - Azure secrets
- **Google Secret Manager** - GCP secrets
- **CyberArk** - Enterprise secrets
- **1Password** - Password management
- **Doppler** - SecretOps platform
- **KeyWhiz** - Secret distribution
- **Knox** - Secret management

### Security Scanning
- **Snyk** - Security scanning
- **SonarQube** - Code quality & security
- **Checkmarx** - Static analysis
- **Veracode** - Application security
- **Aqua Security** - Container security
- **Twistlock (Prisma Cloud)** - Cloud security
- **Trivy** - Vulnerability scanner
- **Clair** - Container vulnerability scanner
- **Anchore** - Container analysis
- **Grype** - Vulnerability scanner
- **Falco** - Runtime security
- **NeuVector** - Container security
- **Sysdig Secure** - Cloud security

### Compliance & Policy
- **Chef InSpec** - Compliance automation
- **OpenSCAP** - Security compliance
- **Cloud Custodian** - Cloud governance
- **Prowler** - AWS security assessment
- **ScoutSuite** - Multi-cloud security auditing

---

## 🌐 Networking & Service Mesh

### Load Balancers & Reverse Proxies
- **NGINX** - Web server & reverse proxy
- **HAProxy** - High-performance load balancer
- **Traefik** - Modern reverse proxy
- **Envoy** - Cloud-native proxy
- **Caddy** - Automatic HTTPS server
- **AWS Elastic Load Balancer (ELB)** - AWS load balancing
- **Azure Load Balancer** - Azure load balancing
- **Google Cloud Load Balancing** - GCP load balancing

### Service Mesh
- **Istio** - Service mesh platform
- **Linkerd** - Lightweight service mesh
- **Consul** - Service networking
- **Kuma** - Universal service mesh
- **AWS App Mesh** - AWS service mesh
- **Open Service Mesh** - Lightweight mesh
- **Cilium** - eBPF-based networking

### DNS & Service Discovery
- **CoreDNS** - DNS server for Kubernetes
- **Consul** - Service discovery
- **etcd** - Distributed key-value store
- **ZooKeeper** - Coordination service
- **Route 53** - AWS DNS service
- **Azure DNS** - Azure DNS service
- **Cloud DNS** - GCP DNS service

---

## 💾 Databases & Data Management

### Relational Databases (SQL)
- **PostgreSQL** - Advanced open-source DB
- **MySQL** - Popular open-source DB
- **MariaDB** - MySQL fork
- **Microsoft SQL Server** - Enterprise DB
- **Oracle Database** - Enterprise DB
- **Amazon RDS** - AWS managed databases
- **Azure SQL Database** - Azure managed DB
- **Google Cloud SQL** - GCP managed DB
- **CockroachDB** - Distributed SQL
- **TiDB** - Distributed SQL

### NoSQL Databases
- **MongoDB** - Document database
- **Redis** - In-memory data store
- **Cassandra** - Wide-column store
- **DynamoDB** - AWS NoSQL database
- **Couchbase** - Document database
- **Neo4j** - Graph database
- **Elasticsearch** - Search & analytics
- **InfluxDB** - Time-series database
- **ScyllaDB** - High-performance NoSQL

### Database Tools
- **Liquibase** - Database schema management
- **Flyway** - Database migrations
- **dbmate** - Database migration tool
- **Prisma** - Database toolkit
- **pgAdmin** - PostgreSQL management
- **MySQL Workbench** - MySQL management
- **phpMyAdmin** - Web-based MySQL admin

---

## 🧪 Testing & Quality Assurance

### Test Automation
- **Selenium** - Browser automation
- **Cypress** - End-to-end testing
- **Playwright** - Browser automation
- **Puppeteer** - Headless browser
- **JUnit** - Java testing framework
- **pytest** - Python testing framework
- **Jest** - JavaScript testing
- **Mocha** - JavaScript test framework
- **TestNG** - Testing framework
- **Cucumber** - BDD testing
- **Robot Framework** - Test automation

### Load Testing
- **JMeter** - Performance testing
- **Gatling** - Load testing tool
- **Locust** - Load testing framework
- **K6** - Modern load testing
- **Artillery** - Load testing toolkit
- **LoadRunner** - Performance testing

### Code Quality
- **SonarQube** - Code quality platform
- **ESLint** - JavaScript linting
- **Pylint** - Python linting
- **RuboCop** - Ruby linting
- **PMD** - Source code analyzer
- **Checkstyle** - Java code style

---

## 🔧 Configuration & Build Tools

### Build Tools
- **Make** - Build automation
- **Gradle** - Build automation
- **Maven** - Project management
- **Ant** - Java build tool
- **Bazel** - Fast build system
- **Buck** - Build system
- **Webpack** - Module bundler
- **Vite** - Frontend build tool
- **Rollup** - JavaScript bundler
- **Parcel** - Zero-config bundler
- **esbuild** - Fast JavaScript bundler

### Task Runners
- **Gulp** - JavaScript task runner
- **Grunt** - JavaScript task runner
- **Rake** - Ruby build tool
- **Invoke** - Python task execution

---

## 📱 Collaboration & Communication

### Chat & Communication
- **Slack** - Team communication
- **Microsoft Teams** - Enterprise collaboration
- **Discord** - Community chat
- **Mattermost** - Open-source chat
- **Rocket.Chat** - Team communication
- **Zoom** - Video conferencing
- **Google Meet** - Video meetings

### Project Management
- **Jira** - Issue tracking
- **Trello** - Kanban boards
- **Asana** - Project management
- **Monday.com** - Work management
- **Linear** - Issue tracking
- **Notion** - All-in-one workspace
- **ClickUp** - Project management
- **GitHub Projects** - Project planning
- **GitLab Issues** - Issue tracking

### Documentation
- **Confluence** - Team documentation
- **Notion** - Documentation & wiki
- **GitBook** - Documentation platform
- **ReadTheDocs** - Documentation hosting
- **Docusaurus** - Documentation websites
- **MkDocs** - Static site generator
- **Swagger/OpenAPI** - API documentation
- **Postman** - API development

---

## 🖥️ Virtual Machines & Hypervisors

- **VMware ESXi** - Bare-metal hypervisor
- **VMware Workstation** - Desktop hypervisor
- **VirtualBox** - Open-source virtualization
- **Hyper-V** - Microsoft hypervisor
- **KVM** - Linux kernel virtualization
- **QEMU** - Machine emulator
- **Vagrant** - Development environment manager
- **Proxmox** - Open-source virtualization
- **XenServer** - Enterprise hypervisor
- **Multipass** - Ubuntu VM manager

---

## 🔄 GitOps & Deployment

- **Argo CD** - GitOps CD for Kubernetes
- **Flux** - GitOps toolkit
- **Jenkins X** - CI/CD for Kubernetes
- **Keptn** - Application lifecycle orchestration
- **Weave GitOps** - GitOps platform
- **Flagger** - Progressive delivery
- **Shipper** - Multi-cluster deployment

---

## 📊 Cost Management

- **Kubecost** - Kubernetes cost monitoring
- **CloudHealth** - Cloud cost management
- **CloudCheckr** - Cloud optimization
- **Spot.io** - Cloud cost optimization
- **Infracost** - Cloud cost estimates
- **OpenCost** - Open-source cost monitoring

---

## 🛠️ Developer Tools & Utilities

### Terminal & Shell
- **zsh** - Unix shell
- **bash** - Bourne-again shell
- **fish** - Friendly shell
- **tmux** - Terminal multiplexer
- **screen** - Terminal multiplexer
- **Oh My Zsh** - Zsh framework
- **Starship** - Cross-shell prompt

### CLI Tools
- **kubectl** - Kubernetes CLI
- **helm** - Kubernetes package manager CLI
- **aws-cli** - AWS command line
- **az-cli** - Azure command line
- **gcloud** - Google Cloud CLI
- **terraform** - Infrastructure CLI
- **docker** - Container CLI
- **k9s** - Kubernetes CLI UI
- **kubectx/kubens** - Kubernetes context switcher
- **stern** - Multi-pod log tailing
- **jq** - JSON processor
- **yq** - YAML processor

### IDE & Editors
- **Visual Studio Code** - Code editor
- **IntelliJ IDEA** - Java IDE
- **PyCharm** - Python IDE
- **Sublime Text** - Text editor
- **Atom** - Text editor
- **Vim/Neovim** - Terminal editor
- **Emacs** - Extensible editor

---

## 🌐 API Gateways & Management

- **Kong** - API gateway
- **Tyk** - API gateway
- **AWS API Gateway** - AWS API service
- **Azure API Management** - Azure API gateway
- **Apigee** - API management platform
- **MuleSoft** - Integration platform
- **Ambassador** - Kubernetes API gateway
- **NGINX Plus** - Commercial NGINX
- **Gravitee** - API management

---

## 🔄 Workflow Automation

- **Apache Airflow** - Workflow orchestration
- **Prefect** - Workflow management
- **Dagster** - Data orchestration
- **Luigi** - Workflow management
- **Argo Workflows** - Container-native workflows
- **Temporal** - Durable execution
- **Cadence** - Workflow orchestration
- **n8n** - Workflow automation
- **Zapier** - Automation platform
- **IFTTT** - Automation service

---

## 📈 Analytics & Business Intelligence

- **Tableau** - Data visualization
- **Power BI** - Business analytics
- **Looker** - Business intelligence
- **Metabase** - Open-source BI
- **Redash** - Data visualization
- **Apache Superset** - Data exploration

---

## 🔧 Specialized Tools

### Chaos Engineering
- **Chaos Monkey** - Resiliency tool
- **Gremlin** - Chaos engineering platform
- **Litmus** - Kubernetes chaos engineering
- **Chaos Mesh** - Cloud-native chaos

### Feature Flags
- **LaunchDarkly** - Feature management
- **Flagsmith** - Feature flags
- **Unleash** - Open-source feature toggles
- **Split** - Feature flag platform

### Serverless
- **AWS Lambda** - Serverless compute
- **Azure Functions** - Serverless functions
- **Google Cloud Functions** - GCP serverless
- **Cloudflare Workers** - Edge computing
- **OpenFaaS** - Serverless framework
- **Knative** - Kubernetes serverless
- **Fission** - Serverless framework

---

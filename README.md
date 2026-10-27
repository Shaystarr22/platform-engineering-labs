# Platform Engineering Labs Portfolio

Welcome to my hands-on **Platform Engineering** learning repository and technical portfolio. This repository documents my practical work building, automating, containerizing, and managing modern cloud infrastructure.

## Career Goal

My goal is to become a **Platform Engineer** who designs and maintains reliable, secure, self-service infrastructure and developer platforms. Through structured, hands-on labs in this repository, I am building end-to-end proficiency across operating systems, automation scripting, container orchestration, cloud architecture, and Infrastructure as Code (IaC).

---

## Repository Structure & Learning Roadmap

Each top-level section follows a progressive learning path from core system foundations to cloud-native infrastructure and Kubernetes orchestration:

### [01 - Linux](./01-linux/README.md)
* **Focus:** Linux system administration, filesystem permissions, process management (`systemd`), networking diagnostics, and Bash scripting.
* **Labs:**
  * `lab-01-basic-commands/` — Filesystem navigation, permissions, and CLI text processing.
  * `lab-02-bash-scripting/` — Automating routine system tasks with Bash scripts.

### [02 - Python](./02-python/README.md)
* **Focus:** Infrastructure automation, working with `JSON`/`YAML`, REST API integration, CLI tools, and AWS cloud automation with `boto3`.
* **Labs:**
  * `lab-01-file-automation/` — Automating file operations and parsing structured data.
  * `lab-02-aws-boto3/` — Interacting with AWS services programmatically using `boto3`.

### [03 - Docker](./03-docker/README.md)
* **Focus:** Containerizing applications, writing secure multi-stage `Dockerfile`s, managing volumes and networks, and running multi-container stacks with Docker Compose.
* **Labs:**
  * `lab-01-first-container/` — Packaging and running a containerized application.
  * `lab-02-docker-compose/` — Running a multi-container stack with Docker Compose.

### [04 - AWS](./04-aws/README.md)
* **Focus:** Core Amazon Web Services (AWS) cloud architecture, least-privilege IAM, S3 object storage, custom VPC networking, and compute services.
* **Labs:**
  * `lab-01-iam-and-s3/` — Managing IAM policies, roles, and S3 buckets.
  * `lab-02-vpc-networking/` — Designing custom VPCs, subnets, route tables, and security groups.

### [05 - Terraform](./05-terraform/README.md)
* **Focus:** Declarative Infrastructure as Code (IaC) using HashiCorp Terraform, state management, variables/outputs, and reusable infrastructure modules.
* **Labs:**
  * `lab-01-first-ec2/` — Provisioning an EC2 instance and security group using Terraform.
  * `lab-02-s3-static-site/` — Deploying and configuring an S3 static website with IaC.

### [06 - Kubernetes](./06-kubernetes/README.md)
* **Focus:** Container orchestration, declarative YAML manifests, Pods, Deployments, Services, ConfigMaps/Secrets, health probes, and cluster operations with `kubectl`.
* **Labs:**
  * `lab-01-pods-and-services/` — Running Pods and exposing workloads with Kubernetes Services.
  * `lab-02-deployments/` — Managing scaling, self-healing, and rolling updates with Deployments.

---

## Core Technologies & Tools

| Domain | Tools & Technologies |
| :--- | :--- |
| **Operating System & Shell** | Linux, Bash, SSH, `systemd` |
| **Programming & Automation** | Python 3, `boto3`, REST APIs, JSON/YAML |
| **Containers & Orchestration** | Docker, Docker Compose, Kubernetes (`kubectl`) |
| **Cloud Provider** | Amazon Web Services (IAM, S3, VPC, EC2) |
| **Infrastructure as Code** | Terraform |
| **Version Control** | Git & GitHub |

---

## Security & Best Practices

This repository uses a strict [`.gitignore`](./.gitignore) policy to ensure sensitive data—such as AWS credentials, `.env` files, private SSH/TLS keys, and Terraform `.tfstate` or `.tfvars` files—is never committed to version control.

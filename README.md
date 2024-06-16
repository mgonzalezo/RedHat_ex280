# RedHat ex280
Red Hat Certified OpenShift Administrator exam (EX280) Overview and Preparation

Sure, here is the Markdown code you can copy and paste for your personal blog:

## Red Hat OpenShift Platform Architecture

The following diagram shows the high-level stack that comprises a Red Hat OpenShift Container Platform (RHOCP) deployment.

![RHOCP Deployment Stack](openshift_architecture.jpg)

### Red Hat OpenShift Platform Architecture Overview

The RHOCP architecture begins with the Red Hat CoreOS or Red Hat Enterprise Linux operating systems. By using machines that run one of these operating systems, RHOCP provides the necessary cluster features to deliver the container platform. Additional automated operations continue to build on Kubernetes to deliver an enterprise-class container environment.

Cluster services, such as metrics, a container image registry, and event logging deliver additional features for the environment. Container images are the collection of defined containers that are available within the cluster for deployment. Application services, such as service mesh and other middleware, are also available within the cluster. Additionally, the cluster contains developer services to aid the ongoing application development and platform administration.

The full stack of an RHOCP cluster delivers not only a container runtime environment, but also the additional required tools in enterprise-class deployments to perform the full set of tasks that a modern business application platform requires.

### Components of the RHOCP Stack

#### 1. Red Hat Enterprise Linux (RHEL) or RHEL CoreOS
- **Description**: This is the foundational layer of the stack, providing the underlying operating system on which the OpenShift Container Platform runs. It includes:
  - **RHEL**: A robust and secure Linux distribution tailored for enterprise use.
  - **RHEL CoreOS**: A lightweight, container-optimized version of RHEL specifically designed to run containerized applications efficiently.
- **Role**: Provides the necessary infrastructure and environment for deploying and managing containers and orchestrating them with Kubernetes.

#### 2. Enterprise Kubernetes
- **Description**: This layer represents the core Kubernetes functionality enhanced for enterprise use. Kubernetes is an open-source platform designed to automate deploying, scaling, and operating application containers.
- **Role**: Provides container orchestration capabilities, including scheduling, scaling, and managing containerized applications. It ensures high availability, fault tolerance, and efficient resource utilization within the cluster.

#### 3. Automated Operations
- **Description**: This layer includes tools and features for automating the deployment, management, monitoring, and scaling of applications within the OpenShift environment.
- **Role**: Facilitates the operational tasks associated with managing a containerized environment. It ensures smooth and efficient management of the infrastructure, reducing manual intervention and increasing reliability and performance.

#### 4. Cluster Services
- **Components**:
  - **Metrics**: Collects and stores metrics data from the cluster to monitor performance and resource utilization.
  - **Chargeback**: Provides mechanisms for tracking resource usage and cost allocation for billing purposes.
  - **Registry**: A container image registry to store and manage container images used for deployments within the cluster.
  - **Logging**: Captures and stores logs from applications and system components for troubleshooting and analysis.
- **Role**: Provides essential services that enhance the functionality and manageability of the cluster, ensuring it meets enterprise requirements.

#### 5. Application Services
- **Components**:
  - **Middleware**: Provides essential software components like application servers, messaging systems, and databases that support application development and deployment.
  - **Service Mesh**: Facilitates the management, security, and observability of microservices within the cluster.
  - **Serverless and Functions**: Supports serverless computing and functions as a service (FaaS) for building scalable and event-driven applications.
  - **ISV (Independent Software Vendor)**: Integration with third-party applications and services.
- **Role**: Enhances the capabilities of the platform by offering additional services that support the development, deployment, and management of applications.

#### 6. Developer Services
- **Components**:
  - **Dev Tools**: Includes integrated development environments (IDEs), command-line tools, and other utilities to support developers.
  - **Automated Builds**: Automates the process of building container images from application source code.
  - **CI/CD**: Continuous Integration and Continuous Deployment tools to automate the testing and deployment of applications.
  - **IDE**: Integrated Development Environment for easier coding and debugging.
- **Role**: Provides tools and services that streamline the development process, improving developer productivity and facilitating continuous delivery and integration practices.

Openshift, as a container Platform, includes many critical components for monitoring, automation and scaling. Take a look at the refernce image below for more details

![RedHat Openshift Container Platform](openshit_container_platform.jpg)

## Red Hat OpenShift Editions Summary

After choosing RedHat Openshift as the container orchastrator for your Business Application, the next step is chosing the edition you will implement. Here is a list of alternatives as of Openshift 4.14

#### Red Hat OpenShift Local
- Deploys a cluster on a local computer for testing and exploration.
- Suitable for initial exploration of OpenShift.
- Not intended for production environments.

#### Red Hat Developer Sandbox
- Provides 30 days of free access to a shared OpenShift cluster.
- Allows testing and exploration of OpenShift features.
- Not intended for production use.

#### Public Cloud Managed Services
- Quick access to OpenShift clusters on Amazon Web Services, Microsoft Azure, IBM Cloud, and Google Cloud.
- Managed by Red Hat and cloud providers, integrating with cloud infrastructure.
- Ideal for businesses seeking reliable and managed cluster deployments.

#### Self-Managed Editions
- Deployable on physical or virtual infrastructure, on-premise or in a public cloud.
- Offers greater control and flexibility but requires more management responsibility.
- Suitable for organizations that prefer to manage their own infrastructure and cluster services.

#### Red Hat OpenShift Kubernetes Engine
- Includes the latest Kubernetes platform with enhanced security and enterprise stability.
- Runs on Red Hat Enterprise Linux CoreOS and includes Red Hat OpenShift Virtualization.
- Provides an administrator console for operational support.

#### Red Hat OpenShift Container Platform
- Builds on the OpenShift Kubernetes Engine with additional manageability, security, and development features.
- Includes a developer console, log management, cost management, and metering information.
- Adds Red Hat OpenShift Serverless (Knative), Service Mesh (Istio), Pipelines (Tekton), and GitOps (Argo CD).

#### Red Hat OpenShift Platform Plus
- The most feature-rich edition, including all features of the Container Platform.
- Adds Red Hat Advanced Cluster Management, Advanced Cluster Security, and Red Hat Quay private registry.
- Designed for comprehensive development and administrative needs for containerized application management.

#### Red Hat Insights Advisor
- Available through the Red Hat Hybrid Cloud Console.
- Helps administrators identify and remediate cluster issues using data from the Insights Operator.
- Provides recommendations and their impacts on the cluster for proactive management.


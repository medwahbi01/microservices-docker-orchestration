# Microservices Docker Orchestration

> This project aims to develop a solution for efficiently managing two interconnected services. This solution will utilize Docker and an orchestration method to ensure the optimal deployment, execution, and termination of services.

## 1-1 Why Docker?

By using Docker, we can create isolated containers for each service, allowing them to run independently while ensuring resource isolation. Each service will be configured using a Dockerfile, defining dependencies and necessary settings for starting in a dedicated Docker container.

## 1-2 Container Orchestration

For container orchestration, we will use a suitable approach that enables us to deploy services, adjust them based on requirements, and manage updates. This configuration will be done using specific files that describe how each service should be deployed and interconnected. If necessary, external services can be configured to provide access to web services.

## 1-3 Service Interconnection

Let's take the concrete example of a configuration that includes a web service and a database. These services will be interconnected so that the web service can access the database for data storage. Dockerfiles and specific configuration files will be created for each service, taking dependencies and configuration settings into account.

Once the configuration is complete, we can deploy the entire set of services using the chosen orchestration method. This will allow us to centrally manage services, monitor their state, and implement restart strategies in case of failure. The use of Docker and this orchestration method will facilitate deployment, service management, and adaptation based on workload.

## Chapter 1: Project Overview

### 1-4 DevNet

DevNet is a community and development platform offered by Cisco Systems. It is an ecosystem dedicated to developers, network engineers, and IT professionals who want to develop, automate, and integrate network solutions based on Cisco technologies.

DevNet provides a variety of resources, tools, and support to help developers create applications, scripts, and integrations that leverage the features of Cisco products and platforms. This includes APIs, SDKs, development guides, code examples, hands-on labs, and discussion forums to exchange knowledge and ideas with other community members.

The DevNet platform covers a wide range of areas, such as programmable networking, network automation, security, Internet of Things (IoT), cloud, collaboration, and more. It enables developers to leverage advanced features of Cisco equipment, cloud services, and enterprise software to create customized and innovative solutions.

### 1-5 Sandbox

A sandbox is an isolated and secure environment in which applications or processes can run without interfering with the host operating system or other applications. It is a technique used to enhance security, test applications, run potentially dangerous programs, or explore new features without risking damage to the system.

In computing, a sandbox is often implemented using virtualization or confinement mechanisms. It creates a segregated area where applications can run safely, without accessing sensitive resources of the host system. Changes made within the sandbox are generally limited to that isolated environment and do not affect the rest of the system.

 
 

## Table of Contents
* TOC
{:toc}

## Best Practices
- Overview
    - MLRun vs Nuclio
    - General Project Organization and Directory Structure
    - Project Templates (also linked below)
    - Resource Allocation
    - Troubleshooting (also linked below)
- Link: [https://igz-us-sales.github.io/igz-best-practices/](https://igz-us-sales.github.io/igz-best-practices/)

## Troubleshooting
- Overview
    - Concepts
        - Pods
        - Jobs
        - Pipelines
    - General Troubleshooting Steps
    - Runtime Specific Troubleshooting Steps
        - KubeJob (Job)
        - MPIJob (Horovod)
        - Nuclio
    - FAQ
-  Link: [https://igz-us-sales.github.io/igz-troubleshooting/](https://igz-us-sales.github.io/igz-troubleshooting/)

## Project Templates
### Remote Deployment
- Overview
    - Python to MLRun Example
        - Execute Python code on a remote Iguazio cluster via MLRun
    - Kubeflow Pipeline Example
        - Execute pipeline made up of several Python scripts on a remote Igauzio cluster via MLRun
    - Hadoop Example
        - Execute commands on HDFS via MLRun
- Link: [https://github.com/igz-us-sales/igz-remote-deployment](https://github.com/igz-us-sales/igz-remote-deployment)

### Platform Deployment    
- Overview
    - Python to MLRun Example
        - Execute Python code on Iguazio cluster via MLRun
    - Kubeflow Pipeline Example
        - Execute pipeline made up of several Python scripts on Igauzio cluster via MLRun
- Link: [WIP](#)

## Official Documentation
### MLRun
- End-to-end open-source MLOps solution for managing and automating your entire analytics and machine-learning life cycle, from data ingestion through model development to full pipeline deployment in production.
- Link: [https://mlrun.readthedocs.io/](https://mlrun.readthedocs.io/)

### Nuclio
- Open-source Serverless Functions framework - intended to provide real-time live endpoints that can easily connect through Triggers to different sources (Kafka, Streams, HTTP, Cron, etc).
- Link: [https://nuclio.io/](https://nuclio.io/)

### Iguazio Platform
- Fully integrated and secure data science platform as a service (PaaS), which simplifies development, accelerates performance, facilitates collaboration, and addresses operational challenges. Includes documentation for managed services, API's, V3IO data layer, etc.
- Link: [https://www.iguazio.com/docs/latest-release/](https://www.iguazio.com/docs/latest-release/)
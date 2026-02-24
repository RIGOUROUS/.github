# secuRe desIGn and deplOyment of trUsthwoRthy cOntinUum computing 6G Services (RIGOUROUS)


## Open-Source Repositories

This repository aggregates links and references to the open-source components developed within the SNS RIGOUROUS European project. The listed tools, services, and Docker images support security, privacy, federated learning, orchestration, and network monitoring capabilities.

### Components

1. Injection Mechanism

A mechanism to inject sidecar containers into Kubernetes Pods. This enables dynamic extension of Pod functionality, including monitoring, policy enforcement, and security instrumentation.

* https://github.com/OneSourceConsult/injection-mechanism

2. Network Traffic Collector

Enables the collection of network traffic from a specific network interface. Designed to support monitoring, anomaly detection, and analytics workflows.

* https://github.com/OneSourceConsult/network-traffic-collector

3. Reporting Interface

Used to report network traffic anomalies and related KPI metrics. Provides visibility into system behavior and supports operational decision-making.

* https://github.com/OneSourceConsult/reporting-interface

4. PrivGuide

A tool to evaluate Service Design characteristics in the scope of internal and normative policies. Supports structured assessment of compliance, governance, and policy alignment.

* https://github.com/ATNOG/rigourous-devprivops

5. Privacy-Preserving Federated Learning (PP-FL)

Federated learning framework with privacy-preserving mechanisms.

* https://ants-gitlab.inf.um.es/rigourous/pp-fl

6. Security Orchestrator

Security orchestration framework for coordinated defense and response mechanisms.

* https://ants-gitlab.inf.um.es/bastion/bastion2

7. Privacy-Preserving Federated Learning Anomaly Detection System

An anomaly detection system built on top of privacy-preserving federated learning techniques.

* https://github.com/Samirakamali/Privacy-Preserving-FL-Anomaly-Detection-System-RIGOUROUS

8. PEAgent

A policy enforcement agent that integrates as a sidecar with Open5GS’s UPF to enforce security rules in iptables.

* Docker Hub: https://hub.docker.com/r/wardawarda/policyagent

9. AI-Powered EDoS Mitigator (Docker Images)

Docker images supporting an AI-driven Economic Denial of Sustainability (EDoS) mitigation system:

EDoS Monitoring System
* Docker Hub: https://hub.docker.com/r/wardawarda/edos-monitoring-dtb-bin

EDoS Mitigator Module
* Docker Hub: https://hub.docker.com/r/wardawarda/edosmitigator

HPA Validation Webhook
Docker Hub: https://hub.docker.com/r/wardawarda/hpa-validation-webhook-kafka

10. MTD-based Robust Federated Learning (Docker Image)

Docker image implementing a Moving Target Defense (MTD) approach for robust federated learning.

* Docker Hub: https://hub.docker.com/r/otechno/multi-model-fl

### Contributions

We also have ETSI OpenSlice (OSL) contributions available in our fork repository and the upstream in the following pull requests:

* https://labs.etsi.org/rep/osl/code/org.etsi.osl.model.tmf/-/merge_requests/32

* https://labs.etsi.org/rep/osl/code/org.etsi.osl.tmf.api/-/merge_requests/81

* https://labs.etsi.org/rep/osl/code/org.etsi.osl.tmf.api/-/merge_requests/89


# Notes

Some components are hosted on GitHub, while others are available via GitLab or Docker Hub.
Each repository or image contains detailed documentation regarding deployment, configuration, and usage.
For further information about the RIGOUROUS project, refer to the official project resources and documentation at https://rigourous.eu.
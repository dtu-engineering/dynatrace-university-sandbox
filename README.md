# Dynatrace University Sandbox

## Overview
The **Dynatrace University Sandbox** provisions a fully functional, ready‑to‑use sandbox environment. It includes a Dynatrace environment, multiple demo applications, automatic Dynatrace instrumentation, and preconfigured Dynatrace tenant settings delivering a fully observable and operational environment out of the box. 

## Included Applications

### Core Components
- **Kubernetes**  
Lightweight Kubernetes distribution | [docs](https://docs.k3s.io/)

### Demo Applications
- **Easytrade**  
  Easytrade is a Dynatrace microservices‑based trading demo application | [docs](https://github.com/Dynatrace/easytrade)

- **OpenTelemetry Demo (Astroshop)**  
  A microservice-based distributed system intended to illustrate the implementation of OpenTelemetry in a near real-world environment | [docs](https://github.com/open-telemetry/opentelemetry-demo)

- **Unguard**  
  A Dynatrace open-source and security‑focused demo application used for vulnerability and runtime analysis scenarios | [docs](https://github.com/dynatrace-oss/unguard)

- **VSCode (code-server)**  
  A fully functional Visual Studio Code application running in a web browser for local filesystem and terminal access  | [docs](https://coder.com/docs/code-server/guide)

## Dynatrace Configuration

The sandbox automatically applies several Dynatrace tenant settings to ensure a rich observability experience:

- **Custom log ingest rule**  
  Ensures all detected logs are ingested

- **Runtime and third‑party vulnerability detection enabled**  
  Supports hands‑on exploration of Dynatrace Application Security

- **Kubernetes app & Smartscape settings enabled**  
  Enables Kubernetes Platform Monitoring to provide insights into your Kubernetes clusters via the new Kubernetes app

- **Dynatrace Operator**  
Automates deployment of Dynatrace components such as OneAgent and ActiveGate | [docs](https://github.com/Dynatrace/dynatrace-operator)

## Application Versions

| Application Name                     | Version   |
|-------------------------------------|-----------|
| Kubernetes (k3s)                    | [v1.35.0](https://docs.k3s.io/release-notes/v1.35.X#release-v1350k3s1)     |
| Dynatrace Operator                  | [v1.7.3](https://github.com/Dynatrace/dynatrace-operator/releases/tag/v1.7.3)    |
| Easytrade                           | [v1.3.16](https://github.com/Dynatrace/easytrade/releases/tag/v1.3.16)    |
| OpenTelemetry Demo                  | [2.2.0](https://github.com/open-telemetry/opentelemetry-demo/releases/tag/2.2.0)     |
| Unguard                             | [v0.23.0](https://github.com/dynatrace-oss/unguard/releases/tag/v0.23.0)   |
| VSCode (code-server)                | [v4.112.0](https://github.com/coder/code-server/releases/tag/v4.112.0)   |
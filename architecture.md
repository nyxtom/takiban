# Architecture

This repository is structured to support a predictable and cloud-native architecture with the following components:

* Buildkite: For CI/CD pipelines, automating application builds and deployments.
* Terraform: Infrastructure as code, provisioning and managing GCP resources.
* GCP Kubernetes: Using GKE to orchestrate containers and scale applications.
* Istio: Service mesh providing traffic management, security, and observability.
* Vault: Secure secrets management.
* PostgreSQL: A widely-used, robust relational database.
* Typescript / React: Frontend stack for building responsive and modern web applications.
* Redis: In-memory data store for caching to improve performance.
* Prometheus: For monitoring and alerting, tracking application and infrastructure metrics.
* Grafana: Visualization layer, used in conjunction with Prometheus for performance monitoring.

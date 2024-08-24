# Personal Projects

This is just a landing page that I have created to detail out some of my personal projects that I find interesting. The list will keep changing depending on the relevance of the projects being showcased.

## Project List

Following are the prospects I am going to be working on. The links to their repositories should be updated accordingly:

1. **Operator-based Application deployment** -> Deploy an application and relevant infra from scratch using YAML file definitions via custom k8s resources and operators. First PoC will deploy a Flask application on either: 
    * a sample kind cluster hosted in a EC2 instance, or
    * an EKS/GKE/AKS cluster (whichever cloud account is cheaper, hehe)

2. **Portfolio Application** -> Mostly to brush up on my Java/Spring Boot and React/Next.js(TypeScript) skills. The web app is supposed to be a publicly available resume and showcase for all these projects. Following topics can be covered:
 * Hosted on Kubernetes (ideally with logging and monitoring enabled via Prometheus and Grafana)
 * Interacting with PostgreSQL and AWS using Spring Cloud

3. **Opentelemetry** -> PoC of implementing Opentelemetry using Go and Python for hosted applications, and explore use-cases.

4. **GitOps based gardener-operator deployment** -> Looking at GitOps options to deploy gardener-operator using ArgoCD for helm charts and Garden resource.

5. **E2E DevOps framework deployment via automation** -> Similar to what I worked with at Accenture, deploy an end-to-end DevOps that contains all the tools required for verifying and shipping the application on a cloud-native k8s environment. The tools would be following:

* Connection to GitHub repo as source code repository
* CI/CD framework (Jenkins and GitHub Actions)
* Dependency check tooling (OWASP dependency-check, sonatype tooling maybe)
* Container image scanning tooling (trivy)
* Scanning deployment environment (kube-bench)
* Hosting artifacts (Nexus/Artifactory)
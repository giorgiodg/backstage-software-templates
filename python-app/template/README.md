Test application to setup a CI/CD pipeline including

- KIND
- ArgoCD
- GitHub Actions

---

## DevOps parenthesis

- Create a GH Repo
- Install Docker
- Write a simple API app
  - Install python and pip
  - Install flask
- Dockerize app
- Deploy app as container
- Create a Docker Registry and a PAT
- Push image to Docker Registry
- Kubernetes
  - deploy a local cluster with Kind using Docker containers
  - access cluster
  - configure Ingress controller
  - deploy app on K8S
  - create Service
  - expose app using Ingress
- Helm
  - Install
  - Create a Helm chart for the app
  - Deploy helm chart on K8S
  - Delete release
- ArgoCD - Deploy via Helm - Login to ArgoCD - Integrate GitHub and ArgoCD
  [...]

## Backstage

- Install backstage via Docker
- Configure OAuth GitHub authentication
- Define a User
- Download Backstage plugin for GitHub authentication
- Add Backstage Resolver

### Backstage Software Catalog

- Import an existing App
- Define a Group
- Import an existing component in the catalog

### Backstage Software TechDocs

- Create documentation in python-app
- Integrate mkdocs in Backstage

### Backstage Software Templates

- Install GitHub builtin action
  - Add the module in the backend (if needed)
  - Add a GitHub token to integrate GitHub and Backstage
- Create a python template
  - https://backstage.io/docs/features/software-templates/writing-templates/
  - create a templates repo in our github
  - tie the template repo to our Backstage configuration in app-config.local.yaml
  - define the steps and variables

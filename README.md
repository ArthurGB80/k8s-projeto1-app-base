# k8s-projeto1-app-base

This repository contains the base application for a project aimed at deploying to a cloud cluster using Kubernetes (K8s). 

I developed a CI/CD pipeline using GitHub Actions. This automates the building of Docker images for the application's backend and database components. After the images are built, the pipeline deploys the services to a production environment managed by Red Hat OpenShift, a business-grade Kubernetes platform. The continuous integration process ensures that every push to the main branch triggers the execution of defined jobs, including secure authentication with image repositories and the application of configurations and services to the OpenShift cluster. This provides efficient continuous delivery to the cloud environment.
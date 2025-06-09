# Kubernetes Deployment - Flask App

Ce projet va déployer mon application Flask conteneurisée sur un cluster Kubernetes

Objectif : écrire des manifests Kubernetes de base (Deployment + Service).

---

## Prérequis

- Docker
- Kubernetes (ex : [Minikube](https://minikube.sigs.k8s.io/docs/start/) ou Kind)

---

## Instructions

###  Build de l'image Docker

```bash
docker build -t flask-app .
curl http://$(minikube ip):30007



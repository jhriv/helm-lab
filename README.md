# Helm Lab

## Goal

Local lab with multiple and separate Kubernetes clusters, deployable via
Helm charts.

## Setup

Two kubernetes clusters

* k3s
* minikube

Enable their respective configurations

Setup Helm to deply to both

Prove via deploying same containers via helm

## Teardown

Clean up all helm / kubernetes configurations

Stop all containers

## Desired

Setup via

* shell script
* Ansible playbooks

Architectures

* aarch64 (Apple Silicon / Raspberry Pi)
* amd64 (Intel / AMD cpu)

## Further Goals

Set up / teardown ArgoCD

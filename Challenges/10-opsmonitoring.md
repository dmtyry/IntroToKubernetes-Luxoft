# Challenge 10: Operations and Monitoring

[< Previous Challenge](./09-networking.md) - **[Home](../README.md)**

## Introduction

Running a cluster without knowing what is going on inside of it is a show-stopper for any serious production deployment. It is imperative that we are familiar with operationalizing our Kubernetes clusters and having a full view into day to day running and error state alerts.

## Description

In this challenge you will learn how to view application logs and trouble-shoot errors. View performance metrics and identity bottlenecks.

- Find the logs for your application’s containers, using:
	- `kubectl`
	- Notice how you can check the logs of any of your pods individually.
- Start a bash shell into one of the containers running on a pod and check the list of running processes
- Find out if your pods had any errors.
	- Figure out how to get details on a running pod to see reasons for failures.
- Azure Monitor:
	- Enable "Azure Monitor for Containers" on the AKS cluster
- **Optional**:
	- Install and test any open-source monitoring tools of your choice (for example Grafana + Prometheus)

## Success Criteria

1. Show logs for the containers running in your cluster.
2. Log into a running container and issue bash commands.
3. A dashboard that answers the following questions is created:
	- CPU and memory utilization of all nodes
	- What is the CPU usage of your workload? 
	- How many pods are currently pending?
	- How much memory is allocatable per node in your cluster?
	- Which pod is consuming the most memory?

## Resources
- [Azure Monitor for Containers](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/container-insights-overview)

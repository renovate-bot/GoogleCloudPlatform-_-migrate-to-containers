# Migrate to Containers integrations

There are many integrations with other GCP/GKE components which are common for many migrated workloads. This is a collection of such common patterns and allows you to quickly configure such integrations. 

## Table of Contents
* [Cloud SQL Auth Proxy](./cloudsql-proxy) - Connecting your migrated workload to [Cloud SQL](https://cloud.google.com/sql) using the [Cloud SQL Auth Proxy](https://cloud.google.com/sql/docs/mysql/sql-proxy)

* [Setting up CI/CD from migrated workload](./cloud-deploy-pipeline/) - Powered by [Cloud Deploy](https://cloud.google.com/deploy), and [Cloud Source](https://cloud.google.com/source-repositories) will allow you to continously deploy to your clusters based on commits in a git repository 

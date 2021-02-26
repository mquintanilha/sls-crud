
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=mquintanilha_sls-crud&metric=alert_status)](https://sonarcloud.io/dashboard?id=mquintanilha_sls-crud)
# Serverless REST API
Simple application example for CRUD.

## Structure

This service has a separate directory for all the todo operations. For each operation exactly one file exists e.g. `todos/delete.js`. In each of these files there is exactly one function which is directly attached to `module.exports`.

The idea behind the `todos` directory is that in case you want to create a service containing multiple resources e.g. users, notes, comments you could do so in the same service. While this is certainly possible you might consider creating a separate service for each resource. It depends on the use-case and your preference.

## Use-cases

- API for a Web Application
- API for a Mobile Application

## Setup

```bash
npm install
```

## Deploy

In order to deploy the endpoint simply run

```bash
serverless deploy
```

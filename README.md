# GCP-Cloud-Digital-Leader

This Repo is about Google cloud platform

## Region picker

[Google-Region-Picker](https://cloud.withgoogle.com/region-picker/)

![alt text](screens/image.png)

## Resource hierarchy

Org > folder > project > resources

![alt text](screens/image-1.png)

## Billing

![alt text](screens/image-2.png)

- You can set alert for you budget
  - could be per project
  - per resource

## Compute

- You need to enable the API, and specify the billing for it

  ![alt text](screens/image-3.png)

  ![alt text](screens/image-4.png)

  ![alt text](screens/image-5.png)

### Instance group
  - It's a group of instances

  ![alt text](screens/image-6.png)

  - In case of failure of onf them. `self-healing` will spin another one.

  - You spcify min number of instanes and set a role if for ex. you usage exceeds 80% scale out spin another one or scale on and increase resources

### Load Balancing

- Used to load balance traffic between VMs.
- It has multiple options to be checked in the console.

  ![alt text](screens/image-7.png)

## Database

### SQL (Relational)
- Cloud SQL

  ![alt text](screens/image-8.png)

- Spaner

  ![alt text](screens/image-9.png)

### NoSQL (Non-relational)
- Alloy Postgresql

  ![alt text](screens/image-10.png)

- Cloud Bigtable

  ![alt text](screens/image-11.png)

SQL vs NOSQL

![alt text](screens/image-12.png)

In Memory DB

![alt text](screens/image-13.png)

## Storage

- Object storage (Cloud Storage)

### Storage Classes

![alt text](screens/image-14.png)

## APIs

You can use `Apigee` to build APIs

  ![alt text](screens/image-15.png)

It helps to migrate frpm on-prem to cloud easily

## BigData

- 4V's

  ![alt text](screens/image-16.png)

### Usecase (Pub/Sub)

- DataFlow

  ![alt text](screens/image-17.png)

  - Streaming

    ![alt text](screens/image-18.png)

  - Cloud Storage

    ![alt text](screens/image-19.png)

  - Data Processing

    ![alt text](screens/image-20.png)

  - Machine Learning

    ![alt text](screens/image-21.png)

## Containers

## GKE (Kubernetes)

## CLoud Run == Lambda (AWS)

- Used to test the app without having to set GKE

  ![alt text](screens/image-22.png)

## Security

![alt text](screens/image-23.png)

- It's a shared responsibility

  ![alt text](screens/image-24.png)

## GCP Arch

![alt text](screens/image-26.png)

![alt text](screens/image-27.png)

![alt text](screens/image-28.png)

## Exam overview

![alt text](screens/image-29.png)
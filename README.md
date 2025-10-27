# Deploying a React application to a production ready state

## Step 01

### clone the repo

```
git clone https://github.com/Vennilavan12/Trend.git

```
## Step 02

### Dockerize the application

<img src="images/dockerfile.png" width="500" align="center">

## Step 03

### Define infrastructure in main.tf 

## Step 04

### Create a declarative pipeline script in jenkinsfile

## Step 05

### Use terraform command to provision infrastructure.

```
terraform init

terraform plan

terraform apply --auto-approve

```

## Step 06

### Create a DockerHub repository

<img src="images/dockerhub.png" width="500" align="center">

## Step 07

### Setup Kubernetes in AWS EKS

<img src="images/aws_eks.png" width="500" align="center">

## Step 08

### Write deployment and service YAML files.
<img src="images/deployment.yml.png" width="500" align="center">
<img src="images/service.yml.png" width="500" align="center">


## Step 09

### upload to github

```
git add .
git commmit -m "Initial commit"
git push origin main

```


## Step 10

### install jenkins and add the neccesary plugins

<img src="images/jenkins_login.png" width="500" align="center">

## Step 11

### connect github and jenkins

<img src="images/jenkins_github.png" width="500" align="center">

## Step 12

### automate the pipeline and build

<img src="images/jenkins_build.png" width="500" align="center">

## Step 13

### check application output

<img src="images/application_final.png" width="500" align="center">

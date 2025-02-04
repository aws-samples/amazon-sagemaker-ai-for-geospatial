
# Amazon SageMaker AI for geospatial data processing and analysis

This is the code repository to demonstrate how you can use Amazon SageMaker AI for geospatial data processing and analysis.

## Data

The datasets used are publicly available geospatial datasets from the AWS open data registry, for example [Sentinel-2](https://aws.amazon.com/marketplace/pp/prodview-2ostsvrguftb2) or [USGS Landsat](https://aws.amazon.com/marketplace/pp/prodview-ivr4jeq6flk7u).

The examples cover California Lakes and Counties using geographic vector data and then focus Lake Shasta in California for analyzing Sentinel-2 geospatial data and calculating spectral indices.

- The CA Counties dataset contains boundaries for CA State, counties and places from the US Census Bureau's 2016 MAF/TIGER database available [here](https://data.ca.gov/dataset/ca-geographic-boundaries).
- The California water bodies dataset is published by California. Department of Fish and Game. Marine Resources Region and is available for download [here](https://maps.princeton.edu/download/file/stanford-zx543xm6802-shapefile.zip).
- The Sentinel-2 dataset is available publicly at the [AWS open data registry](https://registry.opendata.aws/sentinel-2/).

## Prerequisites

- An AWS account
- Amazon SageMaker AI domain
- A free [Sentinel Hub](https://www.sentinel-hub.com/) account 

## Environment

If you don't already have a SageMaker AI Studio Domain created, please follow this [Quickstart guide](https://docs.aws.amazon.com/sagemaker/latest/dg/onboard-quick-start.html) to setup a domain. Alternatively you can use the CloudFormation template in the `cfn-templates` folder to provision a new domain with a user profile.

## Operational considerations
This repository provides hands-on examples of using SageMaker AI for geospatial workloads, focusing on functionality rather than on productization. 

**Do not use notebooks, scripts, the Docker file, or any other repository assets in any productive or critical workloads without change and comprehensive security, quality, and compliance review.**


## QR codes and links

### This GitHub repository
Link: https://github.com/aws-samples/amazon-sagemaker-ai-for-geospatial  

<img src="./img/gitrepo-qr-code.png" alt="GitHub repo QR code" width="300px">

### AWS workshop
Coming soon


![](./img/workshop-qr-code.svg)

---

Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.
SPDX-License-Identifier: MIT-0
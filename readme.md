
# Getting Started with Geospatial Data Analysis

This is the code repository to demonstrate how you can use Amazon SageMaker AI for geospatial data processing and analysis.

## Data

The datasets used are publicly available geographic datasets and then explore the sentinel geospatial dataset available at AWS open data registry. The examples cover California Lakes and Counties using geographic vector data and then focus Lake Shasta in California for analyzing Sentinel-2 geospatial data and calculating spectral indices.

- The CA Counties dataset contains boundaries for CA State, counties and places from the US Census Bureau's 2016 MAF/TIGER database available [here](https://data.ca.gov/dataset/ca-geographic-boundaries).
- The California water bodies dataset is published by California. Department of Fish and Game. Marine Resources Region and is available for download [here](https://maps.princeton.edu/download/file/stanford-zx543xm6802-shapefile.zip).
- The Sentinel-2 dataset is available publicly at the [AWS open data registry](https://registry.opendata.aws/sentinel-2/).

## Prerequisites

- An AWS account
- Amazon SageMaker AI domain
- A free Sentinel Hub account 

## Environment

If you don't already have a SageMaker AI Studio Domain created, please follow this [Quickstart guide](https://docs.aws.amazon.com/sagemaker/latest/dg/onboard-quick-start.html) to setup a domain. Alternatively you can use the CloudFormation template in the `cfn-templates` folder to provision a new domain with a user profile.

## QR codes and links

### This GitHub repository
Link: https://github.com/aws-samples/amazon-sagemaker-ai-for-geospatial  

<img src="./img/gitrepo-qr-code.png" alt="GitHub repo QR code" width="300px">

### AWS workshop
Link: TBD 
Short link: TBD

![](./img/workshop-qr-code.svg)

---

Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.
SPDX-License-Identifier: MIT-0
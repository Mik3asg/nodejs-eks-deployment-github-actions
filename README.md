
# eks-deployment-with-github-actions

This projet consists of deploying a simple node.js app to AWS EKS using GitHub Actions


## Pre-requisites

- Create an AWS Account
- Configure AWS CLI
- Set up an AWS Access Key and Secret Access

## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Appendix

Any additional information goes here


# Implementation steps
## 1- Creating an Amazon EKS Cluster

To create an EKS Cluster run the following command in your local machine terminal

```bash
  eksctl create cluster --name <my-cluster> --region <region-code> --nodegroup-name linux-nodes --node-type t2.micro --nodes 2
```

## 2- Creating Project Structure and artifacts on local machine
### 


## Authors

- [@octokatherine](https://www.github.com/octokatherine)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


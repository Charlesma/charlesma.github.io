---
layout: single
title:  "AWS의 대표적인 서비스 소개"
author: 마창수
categories: [ aws ]
image: assets/images/11.jpg
featured: true
hidden: false
---

# Computing

### Amazon EC2 (Elastic Compute Cloud)

* 설명
    * 가상 머신이다.
    * 재구성이 가능한 컴퓨팅 리소스
    * 쉽게 확장/축소되는 컴퓨팅 용량
    * 고객업무’영역에따른다양한인스턴스타입제공
    * 사용한 만큼만 과금 (pay-as-you-go)
* 인스턴스 Family
    * M : 범용, 컴퓨팅, 메모리, 네트워크 리소스의 균형적 사용
    * C : 컴퓨팅, EC2에서 최고 성능의 프로세서, 성능 대비 저렴한 가격
    * R : 메모리용, 메모리 용량이 많이 필요한 애플리케이션용
    * T : 성능 순간 확장, 성능 순간 확장 가능 인스턴스
    * G / P : GPU 전용, 그래픽 및 일반 목적의 GPU 컴퓨팅 애플리케이션
    * I : 높은 I/O, SSD 기반의 초고속 인스턴스 스토리지
    * D : 고밀도 스토리지, 높은 디스크 처리량, 단위당 최소의 가격
* 가격 체계
    * On-Demand : 약정 없이 사용한 대로 지불, 갑작스런 트레픽이나 예측하기 어려운 경 혹은 신규 서비스
    * Reserved : 1년 혹은 3년 약정, 항상 사용하는 안정된 서버 자원을 위한 요
    * Spot : 남은 자원에 대한 경매 방으로 더 높은 가격으로 입찰할 경우 바로 양도될 수 있으나 80~90% 저렴

### Amazon Lightsail


### Amqazon ECR (Elastic Container Registry)


### Amazon ECS (Elastic Container Service)


### Amazon EKS (Elastic Container Service for Kubernetes)



---
# Storage and Contents Distribute


### Amazon S3

* 개요
    * 무제한 객체 스토리지
    * 이미지, 비디오, 파일, 스냅샷 등
* 특징
    * 객체 기반의 무제한 파일 저장 스토리지
    * URL을통해손쉽게파일공유가능
    * 99.999999999%의 내구성
    * 사용한만큼만지불(GB당과금)
    * 정적웹사이트호스팅가능


### AWS Lamda


### AWS Batch


### AWS Elastic Beanstalk


### AWS Serverless Application Repository


### AWS Serverless Application Model


# 저장 공간 (Stroage)

### Amazon EFS (Elastic File System)


### Amazon FSx


### Amazon S3 Glacier


### Amazon Storage Gateway


### AWS Backup


### Amazon EBS (Elastic Block Storage)


### AWS Snowball


---
# Database

### Amazon RDS (Relational Database Service)


### Amazon DynamoDB


### Amazon ElasticCache


### Amazon Neptune


### Amazon Redshift


### Amazon DocumentDB


---
# Network


### Amazon CloudFront

* 개요
	* CDN 서비스


---
# DevOpe

### AWS CodeStar

### AWS CodeCommit

### AWS CodeBuild

### AWS CodeDeploy

### AWS CodePipeline

### AWS Cloud9

### AWS X-Ray

---
# Security and Authorization

### AWS IAM (Identity and Access Management)

### AWS RAM (Resource Access Manager)

### Amazon Cognito

### AWS Secrets Manager

### Amazon GuardDuty

### Amazon Inspector

### Amazon Macie

### AWS Single Sign-on

### AWS Certificate Manager (ACM)

### AWS KMS (Key Management Service)

### AWS Directory Service

### AWS WAF

### AWS Shield

---
# 기타

### Amazon ELB (Elastic Load Balancer)

### Amazon Trusted Advisor

비용 계산 도구


# Amazon Route 53

DNS 서비스


# Amazon Shield

DDos 방지를 위한 소프트웨어로 DDos 공격이 발생하면 영향도를 감소시켜주는 서비스이다.

### (1) AWS Shield Standard

Automatic protection available for all AWS customer at no additional charge

### (2) AWS Shield Advanced

Paid service for higher level of protection features, and benefits
24 X 365 contact to customer support team.

### Benefit

- cost efficient, Simless Integration and deployment, Customizable protection
Build-in protection against DDos attacks
Access to tools, services and experties to help you protect your AWS applications

# Amazon Inspector


[참조] https://waspro.tistory.com/457

---
layout: post
tag: AWS
title: AWS Solutions Architect Certificate - Associate Exam
author: 怡安
---

一開始只是想了解一下雲端服務提供什麼內容，目前最主流的雲端服務包括 Amazon Web Service（AWS)、Microsoft Azure 和 Google Cloud Platform（GCP），其中 AWS 的實用性和服務完整性目前領先 Azure 和 GCP 如下圖所示，因此我選擇學習 AWS。
![Image of MQ](/assets/img/MQ_AWS.jpg)

## 準備
從0開始到考試準備約1個月。
一開始我是先上 Cloudguru 的 [AWS Certified Solutions Architect - Associate 2018](https://www.udemy.com/aws-certified-solutions-architect-associate/)，他會講解 Architect 中會用到的服務，並且帶大家實作一遍，沒有預設要有 AWS 的使用經驗，是入門 AWS 很好的選擇。

#### 模擬試題
[AWS Certified Solutions Architect Associate Practice Exams](https://www.udemy.com/aws-certified-solutions-architect-associate-amazon-practice-exams/)  
這一共有6回的考試，有附詳細的解答，在檢討錯的題目時也順便將 Q&A 看了一下。

#### 白皮書
[建立雲端架構：AWS 最佳實務](https://d0.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf)  
這篇解釋了很多重要觀念，讓之前學的個別服務可以串起來，非常值得看。例如他有解釋 Scaling vertically vs. horizontally, Push model vs. Pull model, Stateless vs. stateful 等等的觀念，以及在 AWS 具體的實現方式。  

[AWS Well-Architected Framework](https://aws.amazon.com/tw/architecture/well-architected/)  
對於服務上不同面相的觀念也滿重要的，這些白書面也很值得讀。

## 考試技巧
* 沒有數字題，所以不用記容量、時間、價錢
* 大部分都是情境架構題
* Encryption 必考
* Autoscaling 必考
* 要會區分 Security group & Network ACL
* 也要會區分 Availability zone vs. Region
* 主要會考的服務：IAM S3 EC2 EBS Kinesis SQS SNS VPC ELB Route53 RDS DynamoDB Redshift EFS CloudWatch CloudTrail CloudFront API Gateway ElasticCache Lambda
* 當中的選項也出現了我沒看過的服務 (AWS Device Farm)，所以我建議考試前最好也要稍微了解一下 AWS 所有的服務內容
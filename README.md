# AWS SAP C01 V28.35 자격증 시험 대비 용어 정리


## 자주 사용되는 용어 정리
<details> <!-- 더보기 기능 -->
<summary>
자세히 보기
</summary>

* 고가용성 (High Availability)
  * 서버와 네트워크, 프로그램과 같은 시스템, 서비스가 오랜기간 동안 고장나지 않고 지속적으로 정상적으로 사용할 수 있고 운영 할 수 있는 성질
  * 오류가 발생하더라도 사람의 개입없이 빠른 시간내에 자동으로 복구되는 것


</details> <!-- 더보기 기능 -->


## AWS Service 용어 정리
<details> <!-- 더보기 기능 -->
<summary>
자세히 보기
</summary>

* CloudFormation
  * CloudFormation StackSets은 cf템플릿에서 aws리소스 구성을 정의할 수 있다.
 
 [go](http://stackoverflow.com){:target="_blank" rel="noopener"}
 [go](http://stackoverflow.com){:target="_blank"}
 <http://stackoverflow.com>{:target="_blank"}
  <a href="http://stackoverflow.com" target="_blank">external link</a>
  
* **Amazon EC2** (Amazon Elastic Compute Cloud) 
  * 거의 모든 워크로드에 적합한 안전하고 크기 조정 가능한 컴퓨팅 용량
  * 동일한 인스턴스는 두개의 개별 가용영역에 배치할 수 없다.
  * 한 인스턴스는 여러개의 NAT 주소를 가질수 없다.
  * Amazon Elastic Compute Cloud(Amazon EC2)는 소프트웨어 시스템을 구축하고 호스팅하는 데 사용하는 크기 조정 가능한 
    컴퓨팅 용량(말 그대로 Amazon 데이터 센터의 서버)을 제공하는 웹 서비스이다.

* **Amazon EC2 Auto Scaling** [Link](https://docs.aws.amazon.com/ko_kr/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html)
  * Amazon EC2 Auto Scaling을 사용하면 애플리케이션의 로드를 처리할 수 있는 정확한 수의 Amazon EC2 인스턴스를 유지할 수 있다. 

  

* **Amazon ECS** (Amazon Elastic Container Service) [Link](https://docs.aws.amazon.com/ko_kr/AmazonECS/latest/developerguide/Welcome.html)
  * 확장성이 뛰어나고 빠른 컨테이너 관리 서비스
  * 클러스터에서 컨테이너를 실행, 중지 및 관리할 수 있다.
  
  
* **Amazon S3** (Amazon Simple Storage Service) [Link](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/userguide/Welcome.html)
  * 업계 최고의 확장성, 데이터 가용성, 보안 및 성능을 제공하는 객체 스토리지 서비스
  * 데이터 레이크, 웹 사이트, 모바일 애플리케이션, 백업 및 복원, 아카이브, 엔터프라이즈 애플리케이션, IoT 디바이스, 
    빅 데이터 분석 등 다양한 사용 사례에서 원하는 양의 데이터를 저장하고 보호할 수 있다.

  
* **Amazon API Gateway** [Link](https://docs.aws.amazon.com/ko_kr/apigateway/latest/developerguide/welcome.html)
  * 규모와 관계없이 REST 및 WebSocket API를 생성, 게시, 유지, 모니터링 및 보호하기 위한 AWS 서비스
  
  
* **Amazon Lambda** [Link](https://docs.aws.amazon.com/ko_kr/lambda/latest/dg/welcome.html)
  * 서버를 프로비저닝하거나 관리하지 않고도 코드를 실행할 수 있게 해주는 컴퓨팅 서비스
  * 고가용성 컴퓨팅 인프라에서 코드를 실행하고 서버와 운영 체제 유지 관리, 용량 프로비저닝 및 자동 조정, 코드 및 보안 패치 배포, 로깅 등 모든 컴퓨팅 리소스 관리를 수행

* **Amazon Athena** [Link](https://docs.aws.amazon.com/ko_kr/athena/latest/ug/what-is.html)
  * 표준 SQL을 사용하여 Amazon S3(Amazon Simple Storage Service)에 있는 데이터를 직접 간편하게 분석할 수 있는 대화형 쿼리 서비스
  
  
* **Amazon Redshift** [Link](https://docs.aws.amazon.com/ko_kr/redshift/latest/mgmt/welcome.html)
  * 클라우드에서 완벽하게 관리되는 페타바이트급 데이터 웨어하우스 서비스
  
  
* **Amazon QuickSight** [Link](https://docs.aws.amazon.com/ko_kr/quicksight/latest/user/welcome.html)
  * 제공하는 데 사용할 수 있는 클라우드 규모의 비즈니스 인텔리전스 (BI, Business Intelligence)
  
  ✏️ 비즈니스 인텔리전스(BI, Business Intelligence)는 기업에서 데이터를 수집, 정리, 분석하고 활용하여 효율적인 의사결정을 할 수 있는 방법에 대해 연구하는 학문 [Link](https://ko.wikipedia.org/wiki/%EB%B9%84%EC%A6%88%EB%8B%88%EC%8A%A4_%EC%9D%B8%ED%85%94%EB%A6%AC%EC%A0%84%EC%8A%A4)

* **Amazon DynamoDB** [Link](https://docs.aws.amazon.com/ko_kr/amazondynamodb/latest/developerguide/Introduction.html)
  * 완전관리형 NoSQL 데이터베이스 서비스로서 원활한 확장성과 함께 빠르고 예측 가능한 성능을 제공
  * 유휴 시 암호화를 제공하여 중요한 데이터 보호와 관련된 운영 부담 및 복잡성을 제거

  
* **ALB** (Application Load Balancer) [Link](https://docs.aws.amazon.com/ko_kr/elasticloadbalancing/latest/application/introduction.html)
  * Elastic Load Balancing은 둘 이상의 가용 영역에서 EC2 인스턴스, 컨테이너, IP 주소 등 여러 대상에 걸쳐 수신되는 트래픽을 자동으로 분산한다.
  * 등록된 대상의 상태를 모니터링하면서 상태가 양호한 대상으로만 트래픽을 라우팅한다.
  * 수신 트래픽이 시간이 지남에 따라 변경됨에 따라 로드 밸런서를 확장한다.
  * 대다수의 워크로드에 맞게 자동으로 조정할 수 있다.
  
  
* **AWS Shield Advanced** [Link](https://docs.aws.amazon.com/ko_kr/waf/latest/developerguide/ddos-advanced-summary.html)
  * DDoS 공격, 볼류메트릭 봇, 취약성 악용 시도와 같은 외부 위협으로부터 애플리케이션을 보호하는 데 도움이 되는 관리형 서비스
  * 공격으로부터 더 높은 수준의 보호

  
* **Amazon SES** (Amazon Simple Email Service) [Link1](https://docs.aws.amazon.com/ko_kr/ses/latest/dg/Welcome.html) [Link2](https://aws.amazon.com/ko/ses/)
  * 대용량 인바운드 및 아웃바운드 클라우드 이메일 서비스
  * 사용자의 이메일 주소와 도메인을 사용해 이메일을 보내고 받기 위한 경제적이고 손쉬운 방법을 제공하는 이메일 플랫폼

  
* **AWS CloudTrail** [Link](https://docs.aws.amazon.com/ko_kr/awscloudtrail/latest/userguide/cloudtrail-user-guide.html)
  * AWS 계정의 운영 및 위험 감사, 거버넌스 및 규정 준수를 활성화하는 데 도움이 되는 AWS 서비스
  * 사용자, 역할 또는 AWS 서비스가 수행하는 작업은 CloudTrail에 이벤트로 기록된다.

  
* **Amazon CloudWatch** [Link](https://docs.aws.amazon.com/ko_kr/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)
  * Amazon Web Services(AWS) 리소스 및 AWS에서 실행되는 애플리케이션을 실시간으로 모니터링
  * CloudWatch를 사용하여 리소스 및 애플리케이션에 대해 측정할 수 있는 변수인 지표를 수집하고 추적할 수 있다.

  
* **Amazon Kinesis Data Firehose Firehose** [Link](https://docs.aws.amazon.com/ko_kr/firehose/latest/dev/what-is-this-service.html)
  * 실시간 전송을 위한 완전관리형 서비스

  
* **Amazon VPC** (Amazon Virtual Private Cloud) [Link](https://docs.aws.amazon.com/ko_kr/vpc/latest/userguide/what-is-amazon-vpc.html)
  * 사용자가 정의한 가상 네트워크로 AWS 리소스를 시작할 수 있다.
  * 이 가상 네트워크는 AWS의 확장 가능한 인프라를 사용한다는 이점과 함께 고객의 자체 데이터 센터에서 운영하는 기존 네트워크와 매우 유사하다.

  
* 
  *
  *

* 
  *
  *

  
* 
  *
  *

  
* 
  *
  *

* 
  *
  *

  
* 
  *
  *

  
* 
  *
  *

* 
  *
  *

  
* 
  *
  *

  
* 
  *
  *

* 
  *
  *

  
* 
  *
  *

  
* 
  *
  *


[LINK](){:target="_blank"}

</details> <!-- 더보기 기능 -->


## 오답 정리
<details> <!-- 더보기 기능 -->
<summary>
자세히 보기
</summary>

오답 정오표와 VCE 답이 갈리는 문제

Q. 32
* 오답 정오표 :  ACE -> 정답
* VCE     정답 :  BCE

examtopics link
https://www.examtopics.com/discussions/amazon/view/60213-exam-aws-certified-solutions-architect-professional-topic-1/

Q. 44
* 오답 정오표 : D
* VCE     정답 : B -> 정답

examtopics link
https://www.examtopics.com/discussions/amazon/view/74113-exam-aws-certified-solutions-architect-professional-topic-1/

Q. 58 문제와 보기 표기 오류
 
A retailer hosts a mission-critical online service on an Amazon Elastic Container Service (Amazon ECS) cluster that is comprised of Amazon EC2 instances. 
The web service accepts POST requests from end users and publishes data to a MySQL database running on its own EC2 server. 
The business must take precautions to avoid data loss.
Currently, the process of deploying code requires manual changes to the ECS service. 
End users reported sporadic 502 Bad Gateway failures in response to genuine web requests during a recent deployment.
The organization want to develop a dependable solution to avoid a recurrence of this situation. 
Additionally, the organization wishes to automate code deployments. The solution should be highly accessible and cost-effective.

Which combination of actions will satisfy these criteria? (Select three.)

A. Run the web service on an ECS cluster that has a Fargate launch type. Use AWS CodePipeline and AWS CodeDeploy to perform a blue/green deployment with validation testing to update the ECS service.
B. Migrate the MySQL database to run on an Amazon RDS for MySQL Multi-AZ DB instance that uses Provisioned IOPS SSD (io2) storage.
C. Configure an Amazon Simple Queue Service (Amazon SQS) queue as an event source to receive the POST requests from the web service. Configure an AWS Lambda function to poll the queue. Write the data to the database.
D. Run the web service on an ECS cluster that has a Fargate launch type. Use AWS CodePipeline and AWS CodeDeploy to perform a canary deployment to update the ECS service.
E. Configure an Amazon Simple Queue Service (Amazon SQS) queue. Install the SQS agent on the containers that run in the ECS cluster to poll the queue. Write the data to the database.
F. Migrate the MySQL database to run on an Amazon RDS for MySQL Multi-AZ DB instance that uses General Purpose SSD (gp3) storage.
Answer: ACF
 
examtopics link
 https://www.examtopics.com/discussions/amazon/view/74154-exam-aws-certified-solutions-architect-professional-topic-1/
 
 
Q. 66
* 오답 정오표 : B -> 정답
* VCE     정답 : A

examtopics link
https://www.examtopics.com/discussions/amazon/view/51221-exam-aws-certified-solutions-architect-professional-topic-1/

Q. 85
* 오답 정오표 : A -> 정답
* VCE     정답 : B

examtopics link
https://www.examtopics.com/discussions/amazon/view/70883-exam-aws-certified-solutions-architect-professional-topic-1/

Q. 99
* 오답 정오표 : B -> 정답
* VCE     정답 : A

examtopics link
https://www.examtopics.com/discussions/amazon/view/80168-exam-aws-certified-solutions-architect-professional-topic-1/

 Q. 109 문제 표기 오류 - What should the solutions architect do to meet this requirement7
 
A company is running a large containerized workload in the AWS Cloud. The workload consists of approximately 100 different services. The company uses
Amazon Elastic Container Service (Amazon ECS) to orchestrate the workload.
Recently, the company's development team started using AWS Fargate instead of Amazon EC2 instances in the ECS cluster. In the past, the workload has come close to running the maximum number of EC2 instances that are available in the account.
The company is worried that the workload could reach the maximum number of ECS tasks that are allowed. A solutions architect must implement a solution that will notify the development team when Fargate reaches 80% of the maximum number of tasks.
What should the solutions architect do to meet this requirement?

examtopics link
https://www.examtopics.com/discussions/amazon/view/68851-exam-aws-certified-solutions-architect-professional-topic-1/ 
 
Q. 186
* 오답 정오표 : B -> 정답
* VCE     정답 : C

examtopics link
https://www.examtopics.com/discussions/amazon/view/68867-exam-aws-certified-solutions-architect-professional-topic-1/

Q. 214
* 오답 정오표 : AD
* VCE     정답 : AC -> 정답

examtopics link
https://www.examtopics.com/discussions/amazon/view/78707-exam-aws-certified-solutions-architect-professional-topic-1/

Q. 230
* 오답 정오표 : A
* VCE     정답 : C -> 정답

examtopics link
https://www.examtopics.com/discussions/amazon/view/80267-exam-aws-certified-solutions-architect-professional-topic-1/

Q. 237
* 오답 정오표 : B
* VCE     정답 : D -> 정답

examtopics link
https://www.examtopics.com/discussions/amazon/view/74087-exam-aws-certified-solutions-architect-professional-topic-1/

Q. 293
* 오답 정오표 : C
* VCE     정답 : D -> 정답

examtopics link
https://www.examtopics.com/discussions/amazon/view/82118-exam-aws-certified-solutions-architect-professional-topic-1/



</details> <!-- 더보기 기능 -->


## 참고 링크
<details> <!-- 더보기 기능 -->
<summary>
자세히 보기
</summary>

* https://viassh.github.io/secret/word-book/


</details> <!-- 더보기 기능 -->

English | [日本語](README.md)

Resume
======

**Also available on [GitHub Pages](https://daichimorihara.github.io/resume/)**

Basic Information
-------
|Item|Details|
|---|-----|
|Name|Daichi Morihara|
|Date of Birth|August 1998|
|Location|Osaka, Japan|
|Education|Osaka University, Faculty of Engineering, Department of Applied Science and Engineering|
|Certifications|AWS Certified Solutions Architect - Associate, TOEIC L&R: 935|


<br>

Work Experience
-------
### Nealle Inc.
- Period: March 2024 - Present
- Business: SaaS for monthly parking lots

#### Department & Role
- September 2024 - Present: Product Development Division, Platform Group, SRE
- March 2024 - August 2024: Product Development Division, Platform Group, SRE (Intern)


#### Key Projects

|Project|Technologies Used|Overview|
|----|----|--------|
|Balancing GUI Development and IaC for Amazon Connect|Github Actions, AWS (Amazon Connect, EventBridge, Step Functions, S3), Terraform|Built a system to leverage the benefits of both the convenience of Amazon Connect's GUI for development and the stable resource management and release process provided by Infrastructure as Code (IaC).|
|Datadog Log Cost Reduction|Datadog|Achieved a 70% cost reduction by setting optimal retention periods for indexed logs for each environment and excluding some logs from indexing.|
|Migrating a Portion of the Frontend from EC2 to S3|Github Actions, AWS (Code Pipeline, S3, CloudFront)|Multiple applications were hosted on the same EC2 instance, causing release constraints. To improve this, the SPA was migrated to an S3 + CloudFront architecture. Also established the CI/CD pipeline for the migration.|
|Batch Processing Monitoring Improvement|AWS (Step Functions, ECS, EventBridge, Lambda), Datadog|Configured automatic retries for failed batches, improved infrastructure monitoring for batches, and introduced APM.|
|Backend Re-architecture|Github Actions, Django, Nginx, Docker, Gunicorn, AWS (ECS, ALB, VPC), Datadog, Terraform|Led the migration of the backend host from Elastic Beanstalk to ECS, while also setting up the AWS Network, introducing Nginx + Gunicorn, improving application logging, managing resources with IaC, setting up CI/CD, and implementing a maintenance mode.|
|Backend CD Speed Improvement|Github Actions, Docker|Improved the Docker image build process and cache storage method within the CD pipeline, reducing execution time by 10 minutes (50%).|
|Building a Windows Server for RPA|AWS (EC2, Patch Manager, CloudWatch Logs, Athena, EventBridge), Datadog|Constructed a virtual environment for running RPA. To enhance auditing, implemented Windows log aggregation and automatic periodic patching with Patch Manager.|
|Multi-Account Backup for Key Data|Github Actions, AWS (CodeCommit, RDS, S3, AWS Backup)|Created a highly secure backup AWS account to store backups of Github source code, RDS, and S3. Implemented a system for bulk transmission of existing data and synchronization of new data.|
|Automation and Improvement of Feature Environment Creation|Github Actions, AWS (RDS, Step Functions, SNS, S3, Amplify, CloudFront, ALB, Amazon Q, Route53), Nginx|Built a system to automatically create frontend and database resources for feature environments. By controlling the feature environment with labels attached to Github PRs, we improved the developer experience while keeping costs down.|

<br>

Published Articles
-------
|Date|Article|
|---|---|
|June 2025|[Improving Batch Monitoring + Reducing the Toil of Manual Retries and a Failure Story of Soaring NAT Gateway Costs](https://nealle-dev.hatenablog.com/entry/2025/06/27/104521)|
|June 2025|[How to Change KMS Keys for Amazon Aurora Without Changing the Endpoint](https://nealle-dev.hatenablog.com/entry/2025/06/24/154358)|
|April 2025|[A Solution for When WAF Blocking Doesn't Work in an S3 + CloudFront SPA Configuration](https://nealle-dev.hatenablog.com/entry/2025/04/22/114803)|
|December 2024|[A Method for Operating Feature Environments That Balances Cost and Developer Experience](https://nealle-dev.hatenablog.com/entry/2024/12/20/01)|
|November 2024|[How We Built a System to Create Aurora Snapshots with Second-Level Accuracy for KPI Aggregation](https://nealle-dev.hatenablog.com/entry/2024/11/05/100031)|

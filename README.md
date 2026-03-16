# Deployed-a-Scalable-WordPress-Site-on-AWS-From-Zero-to-Production-
https://claude.ai/public/artifacts/82866b3e-5213-4b18-bef8-763a8e42617d


🚀HIII ! 
Project ShowcaseDeployed a Scalable WordPress Site on AWS — From Zero to Production!
Built a fully production-grade, auto-scaling WordPress infrastructure on AWS using a LAMP stack, RDS, ALB & Auto Scaling Groups. Here's what I did 👇
⚙️ What I Built
🔗
SSH into EC2 via MobaXterm using a private key pair — launched an Amazon Linux 2023 instance as the web server.
🗄️
Set up Amazon RDS (MySQL 8.4.7) — provisioned a managed database, connected it from EC2, created the wordpress DB, user & privileges.
🌐
Installed Apache (httpd) + PHP 8.4 — configured the full LAMP stack, downloaded and extracted the latest WordPress package.
⚡
Configured wp-config.php — wired DB credentials, RDS hostname, and freshly generated auth salts for security.
✅
Completed WordPress 5-minute install — site live and running WordPress 6.9.4 on the Twenty Twenty-Five theme.
⚖️
Configured an Application Load Balancer (ALB) — internet-facing, spanning 2 Availability Zones (ap-south-1a & ap-south-1b) for high availability.
📈
Set up Auto Scaling Group — min 2 / max 4 instances using a Launch Template with a custom WordPress AMI. Desired capacity currently at 4.
🎯
Target Group (wptg) — 2 registered instances, health checks on HTTP:80, zero unhealthy targets. Production-ready!
🛠️ Tech Stack
🟠
AWS EC2🗄️
Amazon RDS⚖️
AWS ALB📈
Auto Scaling🐧
Amazon Linux 2023🔵
WordPress🟤
MariaDB / MySQL🔴
Apache httpd🐘
PHP 8.4🖥️
MobaXterm SSH hashtag#AWS
hashtag#CloudComputing hashtag#WordPress hashtag#LAMPStack hashtag#AmazonRDS hashtag#EC2 hashtag#AutoScaling hashtag#LoadBalancer hashtag#DevOps hashtag#PHP hashtag#Apache hashtag#Linux hashtag#CloudArchitecture hashtag#TechProject hashtag#AWSCommunity hashtag#Infrastructure hashtag#SysAdmin hashtag#MySQL

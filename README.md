# Hi, I'm Jannat Ara Nishat 👋

**DevOps Engineer** based in Dhaka, Bangladesh, with 8 years in IT infrastructure, 5 of them in DevOps.

I keep production systems running. My strongest skills are production troubleshooting, root cause analysis and monitoring. I build CI/CD pipelines, automate infrastructure with Ansible, and set up monitoring for large server fleets.

- 🔧 Currently: running and automating a large enterprise ERP platform in production
- 📈 Monitoring: 100+ servers and 20+ services with Uptime Kuma, Alertmanager, Grafana and ELK
- 🤖 Exploring: AI-assisted DevOps
- 📜 CCNA certified · CKA in progress
- 🌍 Open to remote roles and relocation

---

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| Containers & Orchestration | Docker, Docker Compose, Kubernetes, Argo CD |
| CI/CD & Automation | GitLab CI/CD, GitHub Actions, Ansible, Bash |
| Infrastructure as Code | Terraform |
| Monitoring & Logging | Grafana, Alertmanager, Uptime Kuma, ELK Stack |
| Messaging & Data | Kafka, RabbitMQ, Redis, PostgreSQL, MongoDB |
| Cloud & Infra | AWS, GCP, Linux, VMware, HAProxy |

---

## 🚀 Featured Projects

### [docker-cicd-app](https://github.com/n6jannat/docker-cicd-app)
A dynamic GitHub Actions CI/CD pipeline. A planning step decides from each event what to test, build and deploy: pull requests are only tested, `main` deploys to staging, and version tags deploy to production. The pipeline builds multi-arch Docker images, pushes them to GHCR, checks health after each deploy and rolls back automatically if the check fails.

`GitHub Actions` `Docker` `GHCR` `Bash`

### [terraform-aws-infra](https://github.com/n6jannat/terraform-aws-infra)
Modular Terraform for an AWS web stack: a multi-AZ VPC, a hardened EC2 web server, and remote state in S3 with DynamoDB locking. CI runs fmt, validate and tflint, then a full apply and destroy against LocalStack, so the stack is tested without an AWS account.

`Terraform` `AWS` `LocalStack` `GitHub Actions`

### [uptime-kuma-setup](https://github.com/n6jannat/uptime-kuma-setup)
Production-ready Uptime Kuma monitoring deployed with Docker Compose. Optional automatic HTTPS through Caddy and Let's Encrypt, a one-command installer, rotating backups, and a step-by-step guide covering alerting (email, Slack, Telegram), status pages and push monitors for cron jobs.

`Uptime Kuma` `Docker Compose` `Caddy` `Bash`

### [disk-alert](https://github.com/n6jannat/disk-alert)
A dependency-free Bash disk usage monitor for cron. It applies warning and critical thresholds per filesystem, sends alerts by email or Slack/Discord/Teams webhook, and returns Nagios-style exit codes so it plugs into existing monitoring. CI runs ShellCheck and tests on every push.

`Bash` `Linux` `Monitoring` `GitHub Actions`

---

## 📫 Connect

[LinkedIn](https://www.linkedin.com/in/jannataranishat/) · n6jannat@gmail.com

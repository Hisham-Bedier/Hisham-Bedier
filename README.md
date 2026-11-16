### Hisham Bedier

DevOps engineer with a cybersecurity background, based in Cairo. I run production Linux infrastructure and CI/CD at Irtiqa DX, and provide second-line support for retail fuel and point-of-sale systems at MADIC UK.

**What I work on**

- **CI/CD:** GitHub Actions pipelines for Odoo, Node.js and React projects. Checks run on hosted runners, deploys go through least-privilege self-hosted runners, with pre-deploy backups, health checks and automatic rollback.
- **Pipeline security:** SHA-pinned actions, read-only tokens and deploy keys, Gitleaks, Semgrep, Bandit, zizmor and Trivy gates.
- **Infrastructure:** Ubuntu servers running multi-tenant Odoo 18/19 on Nginx and PostgreSQL, Docker Compose services behind Caddy, and AWS (EC2, S3) migration and load testing with k6.
- **Monitoring:** a self-hosted fleet dashboard (FastAPI, systemd agents, debounced alerting) and Netdata rollouts.
- **Security operations:** access-control and SSH audits, incident investigation and root-cause reports, with a SOC grounding in Splunk, Microsoft Sentinel and Elastic.

Most of my day-to-day work lives in private company repositories. The repositories below are public write-ups of the same patterns.

**Featured**

- [secure-cicd-pipeline](https://github.com/Hisham-Bedier/secure-cicd-pipeline): hardened GitHub Actions pipeline with least-privilege permissions, SHA-pinned actions, a self-hosted runner guard and dependency auditing
- [zero-downtime-node-deploy](https://github.com/Hisham-Bedier/zero-downtime-node-deploy): SSH/rsync and PM2 cluster deploy with health-check rollback and a full audit log
- [linux-monitoring-playbook](https://github.com/Hisham-Bedier/linux-monitoring-playbook): Netdata and PostgreSQL monitoring and alerting, with a least-privilege database role and verified alert firing
- [n8n-caddy-hardened-deploy](https://github.com/Hisham-Bedier/n8n-caddy-hardened-deploy): case study in hardening an exposed n8n deployment with Docker, PostgreSQL and Caddy
- [odoo-multi-tenant-deploy-runbook](https://github.com/Hisham-Bedier/odoo-multi-tenant-deploy-runbook): field-tested runbook for deploying safely to multi-instance Odoo servers

**Stack**

Linux · Bash · Python · PowerShell · GitHub Actions · Docker · Nginx · Caddy · PostgreSQL · Odoo · AWS · Azure · Netdata · k6 · Trivy · Splunk · Microsoft Sentinel

[LinkedIn](https://www.linkedin.com/in/hisham-bedier)

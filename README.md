<p align="center">
  <img src="assets/banner.svg" alt="Anas Tanveer: Infrastructure, DevOps and .NET Engineer" width="100%">
</p>

<p align="center">
  <a href="mailto:anastanveer653@gmail.com"><img src="https://img.shields.io/badge/Email-anastanveer653%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/anastanveer-it/"><img src="https://img.shields.io/badge/LinkedIn-anastanveer--it-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
  <a href="https://coreitlink.com"><img src="https://img.shields.io/badge/Website-coreitlink.com-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <img src="https://img.shields.io/badge/Open_to-remote_contracts_%26_full--time-16A34A?style=for-the-badge" alt="Open to remote contracts and full-time roles">
</p>

## About

I build and run infrastructure: cloud environments defined as code, hardened Windows and Linux servers, and monitoring that tells you what broke and how to fix it. I also write the software around it, from PowerShell and Go tooling to a full HR platform on .NET and SQL Server.

My day job is enterprise IT in Karachi, where I run Windows Server, Active Directory, networking, VoIP and data-center monitoring. Every public project below is tested in CI and documented so that someone else can pick it up.

```yaml
anas:
  role: Infrastructure, DevOps & .NET Engineer
  location: Karachi, Pakistan (UTC+5)
  open_to: [remote contracts, full-time remote roles]
  day_job: Windows Server, Active Directory, networking, VoIP, data-center monitoring
  building: HR & attendance platform (.NET 10 Blazor, EF Core, SQL Server)
  ships_with: [tests, CI, runbooks, rollback]
```

## What I can do for your team

| | You get | Proof |
|---|---|---|
| ☁️ | **AWS infrastructure as code.** VPC, load balancer behind WAF, auto-scaling instances with no SSH, KMS encryption and CloudWatch alarms, delivered by a keyless GitHub Actions pipeline (OIDC) with drift detection. | [terraform-aws-starter-kit](https://github.com/anastanveer653/terraform-aws-starter-kit) |
| 🛡️ | **Hardened, auditable Windows servers.** 107 controls mapped to CIS and MITRE ATT&CK, previewed before they change anything, verified after, and rolled back with one command. | [windows-server-hardening-toolkit](https://github.com/anastanveer653/windows-server-hardening-toolkit) |
| 🐧 | **Linux servers configured the same way every time.** Idempotent Ansible roles for SSH, an nftables firewall, fail2ban, auditd and Docker, with checks that stop a bad variable from locking you out. | [ansible-linux-server-automation](https://github.com/anastanveer653/ansible-linux-server-automation) |
| 📈 | **Monitoring people trust.** Prometheus, Grafana and Alertmanager in one command. Every alert has a unit test and a runbook. | [docker-monitoring-stack](https://github.com/anastanveer653/docker-monitoring-stack) |
| 🧩 | **Internal tools and business apps.** A cross-platform Go CLI for encrypted secrets, and a Blazor + SQL Server HR system with role-based access. | [envy](https://github.com/anastanveer653/envy) · HR platform (private) |
| 🏢 | **On-prem IT that just works.** Active Directory, Group Policy, DNS/DHCP, file and print servers, VMware, pfSense and Grandstream VoIP. | Day job and home labs |

## Featured projects

| Project | What it does | Built with | CI |
|---|---|---|---|
| [**terraform-aws-starter-kit**](https://github.com/anastanveer653/terraform-aws-starter-kit) | Highly available web tier on AWS with WAF, KMS, alarms and a gated, keyless deploy pipeline. 20 `terraform test` cases run without an AWS account. | Terraform, AWS, GitHub Actions | [![terraform](https://github.com/anastanveer653/terraform-aws-starter-kit/actions/workflows/terraform.yml/badge.svg)](https://github.com/anastanveer653/terraform-aws-starter-kit/actions/workflows/terraform.yml) |
| [**windows-server-hardening-toolkit**](https://github.com/anastanveer653/windows-server-hardening-toolkit) | PowerShell module that audits, hardens and rolls back Windows Server security settings, with HTML/JSON reports. Integration-tested on Server 2022 and 2025. | PowerShell, Pester | [![CI](https://github.com/anastanveer653/windows-server-hardening-toolkit/actions/workflows/ci.yml/badge.svg)](https://github.com/anastanveer653/windows-server-hardening-toolkit/actions/workflows/ci.yml) |
| [**ansible-linux-server-automation**](https://github.com/anastanveer653/ansible-linux-server-automation) | Turns a fresh Ubuntu, Debian or RHEL-family server into a hardened, monitored host. Molecule-tested on 6 distributions. | Ansible, Molecule | [![CI](https://github.com/anastanveer653/ansible-linux-server-automation/actions/workflows/ci.yml/badge.svg)](https://github.com/anastanveer653/ansible-linux-server-automation/actions/workflows/ci.yml) |
| [**docker-monitoring-stack**](https://github.com/anastanveer653/docker-monitoring-stack) | One-command observability for Docker hosts: 4 dashboards and 21 alerts, each unit-tested and with a runbook. CI starts the full stack and smoke-tests it. | Docker Compose, Prometheus, Grafana | [![CI](https://github.com/anastanveer653/docker-monitoring-stack/actions/workflows/ci.yml/badge.svg)](https://github.com/anastanveer653/docker-monitoring-stack/actions/workflows/ci.yml) |
| [**envy**](https://github.com/anastanveer653/envy) | Encrypted, multi-environment `.env` manager (Argon2id + AES-256-GCM) with a git leak audit. Single binary for Linux, macOS and Windows. | Go, GoReleaser | [![CI](https://github.com/anastanveer653/envy/actions/workflows/ci.yml/badge.svg)](https://github.com/anastanveer653/envy/actions/workflows/ci.yml) |
| **HR Time** *(private, in development)* | HR, attendance and leave management with role-based access, built as a Clean Architecture solution with unit-tested attendance and leave engines. | C#, .NET 10 Blazor, EF Core, SQL Server | — |

## Tech stack

| Area | Tools |
|---|---|
| Cloud & IaC | <img src="https://skillicons.dev/icons?i=aws,terraform,ansible,githubactions" alt="AWS, Terraform, Ansible, GitHub Actions" height="40"> |
| Containers & monitoring | <img src="https://skillicons.dev/icons?i=docker,prometheus,grafana" alt="Docker, Prometheus, Grafana" height="40"> |
| Operating systems | <img src="https://skillicons.dev/icons?i=windows,linux,ubuntu,debian,redhat" alt="Windows, Linux, Ubuntu, Debian, Red Hat" height="40"> |
| Languages & scripting | <img src="https://skillicons.dev/icons?i=cs,go,powershell,bash,py" alt="C#, Go, PowerShell, Bash, Python" height="40"> |
| .NET & data | <img src="https://skillicons.dev/icons?i=dotnet" alt=".NET" height="40"> <img src="https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white" alt="Blazor"> <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge" alt="SQL Server"> <img src="https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge" alt="Entity Framework Core"> |
| Enterprise IT | <img src="https://img.shields.io/badge/Active_Directory-0078D4?style=for-the-badge" alt="Active Directory"> <img src="https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white" alt="VMware"> <img src="https://img.shields.io/badge/pfSense-212121?style=for-the-badge&logo=pfsense&logoColor=white" alt="pfSense"> |

## Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/anastanveer653/anastanveer653/output/github-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/anastanveer653/anastanveer653/output/github-snake.svg" alt="Contribution graph animation">
</picture>

## Work with me

Need infrastructure built, secured or automated, or an internal tool shipped? Email me a short description of the problem at **[anastanveer653@gmail.com](mailto:anastanveer653@gmail.com)** and I'll reply with how I would approach it.

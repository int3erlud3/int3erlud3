<div align="center">

```text

                       .:-----:..
                    -*%@@@@@@@@%%%##*=-=:
                 :+%@@@%%%%%%%%%%@@@@@@@@%-
              .-*@@@%%%%%%%%%%%%%%%%%%%%%@@#=.
            .+%@@@@%%%%%%%%%%%%%%##%%%%%%%%@@%=
           =%@@@@@%%%%%#********#*===++*#%%%%@@%-
         :#@@@@@@%%#*+-::::::----::::--=+**#%%%@@+
        .%@@@@@%#*=-:::........ .....:--==++*#%%@@*
        =@%@@%#+=--:::..        .....::--==++*#%%@@=
       .@@@@%#*+=--::...         ....::--===+*#%%%@%
       +@@@%%#*+=--::...            ..:--===+*#%%@@@.
      .%@@@%%##++==-:.                .:-=++**#%%@@@:
      -@@@@@%%#*+=--======-:.      .:=*####%#**%@@@@:
      .%@@@@%%#+==+#########*+-..::+####****#%*#@@@%.
       :@@@%%%*==+**++++=+***+=..:+###****#**##*%@@+
        *#*@%%+-====*#**##+*#+=. .+##+#%#*%#****%#*.
        -+-*%%=----=+#*+**=++=-:  -**+******++++#*-
        =-:+*#=-::::::--==--:::.  :=+==------=++#+=
       .-.-=+*--:...    .  .:::.  :=+=-::::::-=+#==:
       ::::.-*=--:...      .-:.   .-=+-:....:-=*#++=
       ::::-=*==-:...     .:-++:..-***=:...::-+*#+*-
        ::::-*+==-:...   ...-++***###+=--:::-++*#++.
         :--=**+=--::...... .=#####%#*=--:-==+*#+:
           ..=*+==---:....-+*%###*##%%##*+==+**#:
             -*+=--+=-::+#%%#**++****##%%%*=+***
             .**+=-=+=:-**+======+==+*+==+++**#=
             :=**+=-=+===-...:-++**++====+**##*.
            .*==#*+==++=+==-::..:::::-=+**####:
          .-:=+-=*#*++++++===-:::-----=+**#%*.
         .::::-+==*##****+++=====++++++**#%=
        :---::::==++*###*****+++******##%%#-.
  ....:--.:-::--:-=++**############%%%%%#####+:
-::::::.:-::::-:-::-=++**###%%%%%%%%%%###**####=
---:-:--::--::---------=+****###########%%######=
=--::.::::.:=-:::::-----===+******#######@@%##*++:.
----:::..::::==-------====--==+*******##*#%@%+++==+==-:.
-------:::::::-==-===========--++*****#***%%#++=--+++=++=-:
```

# Hi, I'm Ali E 👋

**Linux & Oracle Database Administrator** · Stuttgart, Germany

</div>

I work in IT operations in **critical infrastructure**, where uptime, security and clean change management aren't optional.
My day-to-day is keeping Linux servers and Oracle databases secure, observable and boring (in the good way),
automating repetitive work and writing small tools that do one thing well.

## 🛠️ Skills

| Area | Tools & topics |
|---|---|
| **Linux** | RHEL/Oracle Linux, Debian/Ubuntu, systemd, storage & LVM, networking, package management, troubleshooting |
| **Oracle Database** | Installation & patching, backup & recovery with RMAN, performance tuning, user & privilege management, monitoring |
| **Scripting** | Bash (ShellCheck-clean, tested with bats-core), Python 3 (pytest, ruff), SQL |
| **Automation** | Ansible roles & playbooks, Molecule testing, idempotent configuration management |
| **Containers** | Docker, Docker Compose, image pinning, container hardening |
| **Monitoring** | Prometheus, Alertmanager, Grafana, node-exporter, cAdvisor, alerting & dashboards |
| **Security** | System hardening, SSH, ufw/nftables, fail2ban, auditd, TLS/PKI, least privilege, secret scanning |
| **Centralized logging** | Graylog, OpenSearch, rsyslog/journald forwarding over TLS, streams & alert rules |
| **Patch management** | Uyuni / SUSE Manager, dnf/apt update auditing, security advisory tracking |
| **Directory services** | Active Directory |
| **Virtualization** | VMware, Citrix |
| **Backup & Recovery** | rsync/tar, retention strategies (GFS), integrity checks, restore testing, IBM Spectrum Protect |
| **Workflow** | Git, GitHub Actions CI, code review, documentation |

## 🎓 Certifications

- Oracle Cloud Infrastructure 2023 Certified Foundations Associate
- Oracle Data Platform 2025 Certified Foundations Associate
- Fortinet Certified Associate in Cybersecurity
- EC-Council Network Defense Essentials
- Digital Forensics Essentials
- Cybersecurity for Businesses

## 📂 Projects

#### Linux operations & automation

| Repository | Description |
|---|---|
| [server-healthcheck](https://github.com/int3erlud3/server-healthcheck) | Bash health check for CPU, RAM, disk, systemd services and ports with text/JSON output and Nagios-style exit codes |
| [backup-rotation](https://github.com/int3erlud3/backup-rotation) | Bash backups (tar/rsync) with daily/weekly/monthly retention, SHA-256 checksums, dry-run and locking |
| [user-provisioning](https://github.com/int3erlud3/user-provisioning) | Safe CSV-driven Linux user management with dry-run by default, strict validation and an audit log |
| [ansible-linux-hardening](https://github.com/int3erlud3/ansible-linux-hardening) | Ansible role for SSH, firewall, fail2ban, unattended-upgrades, sysctl and auditd, tested with Molecule |
| [systemd-hardening-kit](https://github.com/int3erlud3/systemd-hardening-kit) | Hardened systemd drop-ins and ranked `systemd-analyze security` reports with safe apply and rollback |

#### Monitoring, logging & patch management

| Repository | Description |
|---|---|
| [docker-monitoring-stack](https://github.com/int3erlud3/docker-monitoring-stack) | Prometheus, Grafana, Alertmanager, node-exporter and cAdvisor with alert rules and a provisioned dashboard |
| [graylog-central-logging](https://github.com/int3erlud3/graylog-central-logging) | Graylog/OpenSearch/MongoDB stack with rsyslog TLS forwarding, security streams and alerts for SSH, sudo and new users |
| [ops-status-page](https://github.com/int3erlud3/ops-status-page) | Static, CSP-locked status dashboard for health check and certificate expiry results |
| [patch-report](https://github.com/int3erlud3/patch-report) | Pending and security update report for dnf and apt hosts with reboot-required detection |
| [uyuni-patch-reporter](https://github.com/int3erlud3/uyuni-patch-reporter) | Read-only Uyuni / SUSE Manager report of pending patches by type, outdated systems and required reboots |

#### Oracle Database

| Repository | Description |
|---|---|
| [oracle-health-report](https://github.com/int3erlud3/oracle-health-report) | Read-only health and security audit (storage, sessions, alert log, privileges, auditing) with HTML/JSON reports |
| [oracle-rman-backup](https://github.com/int3erlud3/oracle-rman-backup) | RMAN full/incremental/archivelog backups with validation, retention, dry-run and monitoring-friendly exit codes |

#### Security & network

| Repository | Description |
|---|---|
| [log-analyzer](https://github.com/int3erlud3/log-analyzer) | Python tool that finds SSH brute-force activity in auth.log/journalctl output |
| [ssh-key-audit](https://github.com/int3erlud3/ssh-key-audit) | Audit of authorized_keys (weak, duplicate and unknown keys) plus a login timeline for incident response |
| [net-security-check](https://github.com/int3erlud3/net-security-check) | Network diagnostics and exposure audit: DNS, routes, MTU, listening ports, firewall, TLS and sysctl hardening |
| [cert-expiry-checker](https://github.com/int3erlud3/cert-expiry-checker) | TLS certificate expiry checks for many hosts with table/JSON output and webhook alerts |

#### Web / Mail

| Repository | Description |
|---|---|
| [emailSenderPhp](https://github.com/int3erlud3/emailSenderPhp) | PHPMailer CLI and contact form with verified SMTP TLS, CSRF, rate limiting, honeypot and header-injection protection |

Every project includes tests, linting and security scans in CI, and a README with usage examples and security notes.

## 🤝 Principles

- **Safe by default:** dry-runs, validation and least privilege before convenience
- **Automate and test:** if I do it twice, I script it; if I script it, I test it
- **Document for the next on-call:** clear READMEs, runbooks and comments

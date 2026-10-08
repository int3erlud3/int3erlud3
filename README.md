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
| **Backup & Recovery** | rsync/tar, retention strategies (GFS), integrity checks, restore testing |
| **Workflow** | Git, GitHub Actions CI, code review, documentation |

## 📂 Projects

| Repository | Description |
|---|---|
| [server-healthcheck](https://github.com/int3erlud3/server-healthcheck) | Bash health check for CPU, RAM, disk, systemd services and ports with text/JSON output and Nagios-style exit codes |
| [backup-rotation](https://github.com/int3erlud3/backup-rotation) | Bash backups (tar/rsync) with daily/weekly/monthly retention, SHA-256 checksums, dry-run and locking |
| [log-analyzer](https://github.com/int3erlud3/log-analyzer) | Python tool that finds SSH brute-force activity in auth.log/journalctl output |
| [ansible-linux-hardening](https://github.com/int3erlud3/ansible-linux-hardening) | Ansible role for SSH, firewall, fail2ban, unattended-upgrades, sysctl and auditd, tested with Molecule |
| [docker-monitoring-stack](https://github.com/int3erlud3/docker-monitoring-stack) | Prometheus, Grafana, Alertmanager, node-exporter and cAdvisor with alert rules and a provisioned dashboard |
| [user-provisioning](https://github.com/int3erlud3/user-provisioning) | Safe CSV-driven Linux user management with dry-run by default, strict validation and an audit log |
| [cert-expiry-checker](https://github.com/int3erlud3/cert-expiry-checker) | TLS certificate expiry checks for many hosts with table/JSON output and webhook alerts |

Every project includes tests, linting and security scans in CI, and a README with usage examples and security notes.

## 🤝 Principles

- **Safe by default:** dry-runs, validation and least privilege before convenience
- **Automate and test:** if I do it twice, I script it; if I script it, I test it
- **Document for the next on-call:** clear READMEs, runbooks and comments

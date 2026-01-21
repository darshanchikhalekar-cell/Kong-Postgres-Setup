# Kong + PostgreSQL Setup (AWX)

This repo installs:
- PostgreSQL on a dedicated VM
- Kong Gateway on a separate VM

All VM IPs and configs are provided via AWX Survey.

Execution order:
1. install_postgres.yml
2. install_kong.yml
3. bootstrap_kong.yml

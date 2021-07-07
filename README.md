# Ansible role: cloudflared-argo
### Ansible role to install, configure, and secure Cloudflare Argo Tunnels.
### Description:
Install, configure, and secure argo tunnels using this role. WILL require tweaks for your specific setup. As configured, sets up SSH and node exporter access.
When running the role, you need to provide the following as either extra variables or vault encrypted values: `argo_hostname`, `api_secret`, `api_key`.

> Author: Nolan Crooks (@crockk))


Feel free to fork and experiment.

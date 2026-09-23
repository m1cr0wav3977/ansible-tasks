# Wazuh Agent

Installs and starts the Wazuh agent. Set `wazuh_manager_host` in private
inventory or group variables; the role derives `wazuh_manager` from it.
Optional values include `wazuh_agent_group` and `wazuh_agent_name`.

The agent package version is maintained in `vars/main.yml`.
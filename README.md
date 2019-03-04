# Percona-Zabbix-Template
Update origin percona template for zabbix-server 4.0

## Percona Monitoring Plugins for Zabbix
See: https://www.percona.com/doc/percona-monitoring-plugins/LATEST/zabbix/index.html

## Configure Zabbix Server
- Import the XML template using Zabbix UI (Configuration -> Templates -> Import) by additionally choosing “Screens”.
- Create/edit hosts by assigning them “Percona Templates” group and linking the template “Percona MySQL Server Template” (Templates tab).

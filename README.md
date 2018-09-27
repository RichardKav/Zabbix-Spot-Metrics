# Zabbix Spot Metrics

These are scripts used for Zabbix that create metrics for CPU, Disk, Network and Cache. They are pushed to Zabbix through Zabbix sender.

They exist in two versions one for Zsh shells and one for Bash based shells. They are aimed at giving measurements at intervals of around 1 second.

The metrics are contained within the the template: zbx_export_templates.xml and cover the following areas:

```
CPU:
	Spot CPU Utilization
	Spot CPU Utilization - core 0
	Spot CPU Utilization - core 1
	Spot CPU Utilization - core 2
	Spot CPU Utilization - core 3
	Spot CPU Utilization - core 4
	Spot CPU Utilization - core 5
	Spot CPU Utilization - core 6
	Spot CPU Utilization - core 7

Disk:
	Spot Disk Utilization - Read
	Spot Disk Utilization - Write

Network:
	Spot Network Utilization - In
	Spot Network Utilization - Out	
	
Cache:
	Spot Cache Utilization - LLC load
	Spot Cache Utilization - LLC store
	
	Spot Cache Utilization - references
	Spot Cache Utilization - miss count
	Spot Cache Utilization - miss fraction
```
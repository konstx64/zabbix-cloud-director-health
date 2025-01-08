# cloud-director-cluster-health
Zabbix template for gathering VMware Cloud Director cluster health via API.

## Use with zabbix
   
1) Clone repository
2) Import .xml file into Zabbix as Template
3) Edit template macros, eg:

```
{$CELL.IP} - Cloud Director cell IP
{$CELL.PASSWORD} - cell username 
{$CELL.PASSWORD} - cell paswword
```
4) Apply Template module to all Cells host in Zabbix




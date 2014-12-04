zabbix_template_ceph
====================

Simple template for Zabbix that allow monitoring Ceph OSD nodes.

How to use it:

On agent node, just copy ceph_health.conf to directory with yours zabbix agent
conffiles (by default, it is /etc/zabbix/zabbix_agentd.d/), then copy
ceph_health.sh to directory with zabbix agent scripts (by default, it is
/etc/zabbix/scripts/) and restart zabbix-agent.

In frontend, import Template_App_OpenStack_Ceph.xml into templates and then
link ceph-osd node with this template. 

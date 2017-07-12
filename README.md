# SYSTEM ANALYSIS AND DESIGN
<p>This project was done to complete the semester course; System Analysis and Design. I deployed a system running a code repository with knowledge base and ticketting system (gogs) and used GlusterFs to sync file accross the vms and  Zabbix agent as a monitoring system. Vagrant is used to power 3 vms, two of which runs gogs and gluster as docker images and zabix agent. The third vm runs gluster and zabix agent. Gluster volume is created on the third vm. Vm1 and Vm2 should be brought up before vm3, as vm3 depends on vm1 and vm2.</p>
<p></p>
<li>To run all 3 vms: <b>Vagrant up</b></li>

<li>To run specific vm : <b>vagrant up vm_name</b></li>

<li>To provision scripts: <b>vagrant provision vm_name</b></li>
<li>To check vm status: <b>Vagrant status</b></li>
<li>To shutdown vm: <b>Vagrant halt vm_name</b></li>
<li>To destroy all vm: <b>Vagrant destroy</b></li>
<li>To destroy specific vm: <b>Vagrant destroy vm_name</b></li>

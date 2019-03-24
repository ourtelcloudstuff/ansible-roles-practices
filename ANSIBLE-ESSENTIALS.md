WHAT IS ANSIBLE AND THE ANSIBLE WAY
===================================
* Is and automation language than can describe an IT application Infrastructure in Ansible Playbooks.
* Ansible have a human readable automation.
* No special coding skills needed.
* Task will execute in order.
* We can spin up hundereds of nodes.
* We can use Ansible for: application deployment, configuration management, workflow orchestration, orcherstrate the application lifecycle, provisioning...
* Ansible is agentless so is more efficent and secure. Uses OpenSSH & WinRM.
* Ansible is cross platform: agentless support for all major OS, physical, virtual, cloud and network.
* Ansible come bundled with over 450 modules: cloud, monitoring, testing, containers, files, databases...
* Ansible have a big community and IRC channels.


INSTALLING ANSIBLE
==================
# The mos common and preferred way of installation
$ pip install ansible

# If you are use a CentOS or RHEL distribution
$ sudo yum install ansible

# If you need the PPA repo configured on Debian.
$ sudo apt-get install ansible


HOW ANSIBLE WORKS
=================

Ansbile playbooks
-----------------
* Ansible Playbooks are written in YAML. Tasks are executed sequentially invokes Ansible modules.

Modules
-------
* More than 450 modules.
* Modules are tools in the toolkit.
* Writing in Python, PowerShell or other langauge.
* Examples: apt/yum, ping, copy, file, user, assert, template, git, service...
* Run Commands modules:
  - script: Runs a local script on a remote node after transferring it.
  - raw: Executes a command without going through the Ansible module subsystem.

Inventory
---------
* We can define remote hosts by groups using their host names or IPs.

CMDB
----
* Ansible plays nice witha bunch of different inventory providers: OpenStack, VMware, EC2, Rackspace, GCW, Azure, Spacewalk, Hanlon, Cobbler
* You can also use custom CMDB.

PLUGINS
-------
* Python API.
* Pluggin support for callback plugins, filter, and other llokup type use cases.















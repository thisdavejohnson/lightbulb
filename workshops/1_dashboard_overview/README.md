# Workshop: Dashboard Overview

### Topics Covered

* Dashboard
* TBD
* TBD

### What You Will Learn

* TBD
* TBD
* TBD

### The Dashboard

The first item that will be seen after logging in is the dashboard. The dashboard is completely customizable and can be configured for each user, group, or tenant.  It utilizes widgets and allows for a quick overview of the environment and can provide visibility into almost any piece that CloudForms has insight into. 

Insert screenshot

#### Moving and Adding Widgets

Perform the following operations using ad-hoc commands:


1. Test that Ansible is setup correctly to communicate with all hosts in your inventory using the `ping` module.
1. Fetch and display to STDOUT Ansible facts using the `setup` module.
1. Setup and enable the EPEL package repository on the hosts in the "web" group using the yum module.
    * CentOS systems use the latest `epel-release` package
    * RHEL systems should use https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm

#### Extra Credit

1. Fetch and display only the "virtual" subset of facts for each host.
1. Fetch and display the value of fully qualified domain name (FQDN) of each host from their Ansible facts.
1. Display the uptime of all hosts using the `command` module. 
1. Ping all hosts **except** the 'control' host using the `--limit` option

### Reference

* `ansible --help`
* [ping module](http://docs.ansible.com/ansible/ping_module.html)
* [setup module](http://docs.ansible.com/ansible/setup_module.html)
* [yum module](http://docs.ansible.com/ansible/yum_module.html)
* [command module](http://docs.ansible.com/ansible/command_module.html)
* [Introduction To Ad-Hoc Commands](http://docs.ansible.com/ansible/intro_adhoc.html)




# ansiblerole-linux-common

----

Basic Role for Configuring Linux Operating System (especially Ubuntu Linux).

This Role can be used during initialization of Virtual Machines and Servers.

*Main functions of the Role:*

- Installing apt packets, that can be extremly needed during OS work;
- Configuring ntp client to synchronize;
- Setting some sysctl.conf variables (Disable IPv6, Disable IP redirect);

All this tasks, I previously made by myself on every server. Now It can
be fullfiled with this Ansible Role.

----

**Author of the Role** - Andrey Useinov aka andreyus. Description of the Role
on Russian Language can be found in blog - [IT is Easy (www.andreyus.com).](https://www.andreyus.com/bazovaya-nastroyka-servera-s-pomoshyu-ansible/) 

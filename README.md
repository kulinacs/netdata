netdata
=======


What is does this role do?
--------------------------

This role installs the netdata management information display which provides a wealth of information about a host.  More information can be found on the [netdata github page](https://github.com/firehol/netdata).


Meta
----

Files Managed:
  * /etc/iptables.d/netdata.rules
  * /var/service/netdata

Defaults Provided:
  * None

Variables Required:
  * None

Optional Variables:
  * None

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * [network](https://github.com/void-ansible-roles/network)

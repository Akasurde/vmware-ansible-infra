VMware Infra
=============

The `vmware.infra` role enables you to set up VMware infrastructure including: mac pools, data centers, clusters, networks, hosts, users, and groups.

Target machine
--------------
In case you use this role to do user management, it will use `vmware-aaa-jdbc-tool`, which is located on engine machine,
so you must execute the role on engine machine.

Note
----
Please note that when installing this role from Ansible Galaxy you are instructed to run following command:

```bash
$ ansible-galaxy install vmware.infra
```

This will download the role to the directory with the same name as you specified on the
command line, in this case `vmware.infra`. But note that it is case sensitive, so if you specify
for example `vmware.infra` it will download the same role, but it will add it to the directory named
`vmware.infra`, so you later always have to use this role with upper case prefix. So be careful how
you specify the name of the role on command line.

For the RPM installation we install three legacy names `vmware.infra`, `vmware.infra` and `vmware-infra`.
So you can use any of this name. This documentation and examples in this repository are using name `vmware.infra`.
`vmware.infra` and `vmware-infra` role names are deprecated.


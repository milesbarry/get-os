## get-os

This playbook will breakdown the information about the operating system and its
version into a textfile, which will hold the name(s) of all that match the same criteria.

A sample output could you look like:

```
OracleLinux-7.7.hosts
OracleLinux-7.8.hosts
OracleLinux-7.hosts
RedHat-6.10.hosts
RedHat-6.hosts
RedHat-7.6.hosts
RedHat-7.7.hosts
RedHat-7.8.hosts
RedHat-7.hosts
Scientific-7.5.hosts
Scientific-7.hosts
Ubuntu-18.04.hosts
Ubuntu-18.hosts
```

The `RedHat-7.hosts` would contain all the hosts contained within `RedHat-7.8.hosts`,
`RedHat-7.7.hosts` and `RedHat-7.6.hosts`

The same rule would apply for the Ubuntu, OracleLinux, Scientific, etc. 

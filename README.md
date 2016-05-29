# ansible-hadoop-dev
Deploy environment for building Apache Hadoop. This ansible playbook will install required packages for building Apache Hadoop such as Java, RPMs, Protocol Buffers 2.5.0, and Apache Maven.

# License

[Apache License v2.0](http://www.apache.org/licenses/LICENSE-2.0)

# Very rough document

## Prequisites

* This playbook is for Redhat/CentOS only.

## How to use

* Configure your hosts file

```
$ cat /your/path/to/hosts
[build]
your.remote.host
```

* Execute ansible-playbook

```
$ ansible-playbook build.yml
```

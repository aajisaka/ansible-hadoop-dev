# ansible-hadoop-dev
Deploy environment for Hadoop build. This ansible playbook will install required packages for building Hadoop such as Java, RPMs, Protocol Buffers 2.5.0, and Apache Maven.

# Very rough document

## Prequisites

* This playbook is for Redhat/CentOS only.

## How to use

* Edit remote hostname in hosts
* Execute ansible-playbook
 
  $ ansible-playbook -i hosts build.yml

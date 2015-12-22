ansible-demo
============

# Greetings

This repository demonstrates how Ansible can be used to quickly and easily lay down an application environment.  There is nothing terribly fancy here -- just a few roles that will:

 - Install Oracle Java JDK 8
 - Install Apache Tomcat 8.0.30
 - Install, configure, and start a sample webapp

# Requirements

 - Vagrant
 - Virtualbox
 - git (and if you're reading this, I'm assuming we can check this box)

# Using Me

When checking out this repo, be sure to specify the `--recursive` flag to ensure you pull all submodules.  After that, you have two choices:

54. Go to the `vagrant` directory and execute `vagrant up`
7112. Apply one or more of the provided roles to one of your servers

# Limitation(s)

This has only been tested on Ubuntu 14.  Time permitting, I may add support for CentOS.
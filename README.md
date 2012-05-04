# keystone-init

Configuring the OpenStack Identity Service (keystone), as documented in the
[OpenStack Install and Deploy manual](http://docs.openstack.org/trunk/openstack-compute/install/content/install-keystone.html), is tedious and
error-prone. *keystone-init* automates the commands as written in the
documentation.

## Usage

Edit the provided ``config.yaml`` file. Then run:

		./keystone-init.py config.yaml


## Prerequisites



 * [PyYAML](http://pyyaml.org/)
 * [python-keystoneclient](https://github.com/openstack/python-keystoneclient)

If you have keystone installed on your system then you should already have
*python-keystoneclient*.

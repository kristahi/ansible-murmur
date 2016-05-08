Murmur
======

Ansible role that installs and configures Murmur on debian, ubuntu, fedora, rhel
[Mumble voice chat software](http://mumble.sourceforge.net/). Thanks jlund for
ubuntu work!

Role Variables
--------------

There are 44 role variables available, one for every single Murmur configuration
option that can be set. All of the variables can be found in in the
`mumble-server.ini.j2` template. The original Mumble documentation of each
variable's function is located in the template file as well.

Running this role without overriding any of the variables will install the
latest version of Murmur and configure it with the default values so it is ready
for action!

License
-------

Copyright (c) 2016 Jon Robison

See included LICENSE for licensing information

# wordpress-heat-template

Heat template which installs, configures and starts Wordpress on two virtual machines, the first virtual machine will run the Wordpress web server while the second virtual machine will run the database server.

Virtual machines will connect to a private network created by this template, and this network will connect to an external public network by a router which also will be created by the template.

A public floating IP address will be assigned to the web server by the template.

The template will define the firewall rules too.

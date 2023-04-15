# Nagios_Core_4.4.9

[Nagios Core 4 Documentation](https://assets.nagios.com/downloads/nagioscore/docs/nagioscore/4/en/index.html)



Verify the Nagios config run the following command-
/usr/local/nagios/bin/nagios -v /usr/local/nagios/etc/nagios.cfg

# Pre-Installation 

1. Download the installation_elx.sh (based on your requirement)
2. chmod 766 installation_elx.sh (change the file permission)
3. ./installation_el7.sh (for RHEL 7.x, Centos 7.x, Oracle linux 7.x) or 
./installation_el8.sh (for RHEL 8.x, Centos 8.x, Oracle linux 8.x)

# Post Installation Tasks

1. Create below configuration first then continue
2. Create contacts and contact groups
3. Create Host template
4. Create service template
5. Create required commands by adding plugins
6. Create and define time periods
7. Create required directories under /usr/local/nagios and add to nagios.cfg
8. Create service groups
9. Install and configure pnp4nagios for graphs



# NSClient++

NSClient++ (nscp) is an open-source monitoring agent. It is designed to work with Nagios and compatible monitoring systems, but it can also be used as a standalone monitoring tool. NSClient++ provides various monitoring checks, including performance metrics, event log monitoring, service monitoring, process monitoring, and more.
NSClient++ is written in C++ and is available under the GNU General Public License. It is compatible with all versions of Windows and linux operating systems. NSClient++ can be installed as a service or as a standalone application, and it includes a command-line interface for managing configuration and monitoring tasks.

NSClient++ also supports various authentication methods, including Windows authentication, SSL/TLS certificates, and pre-shared keys. It also supports encryption and compression of communication between the monitoring system and the NSClient++ agent, providing secure and efficient communication.
Overall, NSClient++ is a reliable and flexible monitoring agent for Windows and linux systems, and it is widely used in the IT industry for monitoring the infrastructure.

How NSClient++ works-

It does basically three things:
1. Allow remote checks Allow a remote machine (monitoring server) to request commands to be run on this machine (the monitored machine) which returns the status of the machine.
2. Monitor system in real-time Monitor your systems and submit the findings and results to a remote (monitoring server).
3. Resolve your problems NSClient++ can take action either on its own monitoring or remotely from a central server and act on what happens and resolve issues.

[NSClient++ Download](http://nsclient.com/download/)

Your task is to write a bash script which configures a Linux firewall using IPtables.
In particular, it should be executed on the Kali VM given out for our earlier assignment
to produce a lasting permanent change to the OS's firewall configuration. You should assume
that the computer **needs to be configured as a secure web server supporting http and https
traffic, with remote ssh access for you**. Further, you want ssh access limited to a
particular static IP address (any will do). Connection tracking should be stateful, so
that you are not leaving wide ranges ports unnecessarily open, either outgoing in incoming.
Additionally, you should have secure defaults to reject all incoming and outgoing TCP and
UDP traffic not necessary for the web server's above-stated functionality. The examples
given in class contain valid firewall configuration options, but do not specify how to save
or manage the configuration in a Debian-based operating system (Kali); you will need to do
some internet research to determine the correct way to save the configuration. You should
test your firewall configuration script on the Kali VM, and validate that it behaves as you
expect, by using Wireshark to test outgoing traffic (easy) and if you can, incoming 
(slightly harder) connections, perhaps via nmap or other methods. Submit one bash script,
with full sentence comments above each configuration command, describing what you are doing
with EVERY line of of the configuration script. The file should be named: lastname_SID.sh

Note: You can choose IPv4 or IPv6, or both, and are only required to do one or the other. 

- Produce a lasting permanent change to the OS's firewall configuration
- Secure web server supporting http and https traffic
- Remote ssh access for you
- ssh access limited to a particular static IP address (any will do)
- Connection tracking should be stateful, so that you are not leaving wide ranges of ports
unnecessarily open, either outgoing or incoming
- Have secure defaults to reject all incoming and outgoing TCP and UDP traffic not necessary
for the web server's above-stated functionality

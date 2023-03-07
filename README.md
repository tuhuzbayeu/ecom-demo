# E-commerce demo

The demo e-commerce environment consists of several components that work together to create a functional website: Ubuntu + Apache + Wordpress + MySQL. Together, these components create an e-commerce website that can be used to  practice performance testing.

### How to deploy

1. Run [the Ecom-demo.ova file](https://drive.google.com/file/d/100PKESRCfzKOjt9L_AIaOMJUYPC3Cchc/view?usp=sharing) and import it into VirtualBox.
2. In the Network settings, select either Bridge or Host-Only.
3. Start the virtual machine. The login and password for the Linux system are *ubuntu:ubuntu*.
4. Enter the *ip r* command to obtain the machine's IP address, for example, *192.168.56.101*.
Next, in the hosts file of your host, add the following line:
```
e.com *IP of the Linux machine*
```
**Login credentials**

Website admin panel:
* Link: *http://e.com/admin*
* Username: *admin*
* Password: *admin*

MySQL:
* Username: *wordpress*
* Password: *wordpress*

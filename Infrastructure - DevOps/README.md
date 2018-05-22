# Linux 
## Linux file system explained
http://www.linuxandubuntu.com/home/the-linux-file-system-structure-explained
logical structure contrary to windows with physical structure
- / - logical beginning of the file system structure
- /bin - binary files
- /boot - files needed at boot time
- /dev - physical hard drive mount
- /etc - conf files affected to all users
- /home - user specific files
- /lib - libraries
- /media - another place external devices
- /mnt - placeholder for mounting (used for network locations etc)
- /opt - optional software for system
- /proc - system infos, kernel communication
- /root - equivalent to home with root access
- /sbin - dedicates to certain command for root user
- /tmp - temporary files
- /usr - files and utilities shared between user
- /var - data, system logs

# http://www.penguintutor.com/linux/basic-shell-reference


### Network and DNS
https://www.appliedtrust.com/resources/infrastructure/understanding-dns-essential-knowledge-for-all-it-professionals

https://www.techrepublic.com/article/understanding-how-dns-works-part-1/

https://community.spiceworks.com/networking/articles/2849-dns-at-the-local-area-network-level

An Introduction to DNS 
- Hierarchical distributed database with delegated authority, maps names to IP addresses
- Delegated authority ensure that those who know best about mapping names to IP addresses are the one responsible
- A name server in most cases maintains the records for a portion of the DNS name space called a zone. In many cases, the terms zone and domain seem synonymous, but they’re actually not the same thing. A zone comprises all the data for a given domain except those parts of the domain that are delegated to other name servers. 
- The main purpose for DNS is to map host names to IP addresses, and the data that makes that possible are stored as records in a zone file

##### Configure private network dns server
https://www.digitalocean.com/community/tutorials/how-to-configure-bind-as-a-private-network-dns-server-on-ubuntu-16-04

https://www.ostechnix.com/install-and-configure-dns-server-ubuntu-16-04-lts/

https://community.spiceworks.com/networking/articles/2849-dns-at-the-local-area-network-level

##### Apache and nginx
https://www.digitalocean.com/community/tutorials/apache-vs-nginx-practical-considerations

- 
-- Apache
-- **


### Project TODO

- Install and build Jenkins, Buildbot server on VM => 3 days

- On VM install apache webserver => 1 day

- On RPI install NGinx with load balancers and multiple instances => try to dockerize it - 5 days

- Practice configuration management tools like Puppet, Ansible - 
6 days

- Etcd, flannel
- Kubernetes - 7 days 

- Train for AWWS solution architecte => pass the certification 2 mounth

- Testing and modulatity on NodeJS

- Hight scalabity backend design https://github.com/binhnguyennus/awesome-scalability


### Docker
https://www.digitalocean.com/community/tutorials/the-docker-ecosystem-an-introduction-to-common-components
Service discovery, network tools, and orchestration



## Flannel

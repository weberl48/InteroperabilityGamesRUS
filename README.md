CISY 8303

Final Project 

-

GamesRUS

Screenshots

Servers: VLAN 20, VLAN 10

Windows Server 2012

Active Directory :

DHCP :

DNS :

CentOS

Email :

File/FTP :

Windows Server 2008

SpiceWorks :

Ubuntu - VLAN 10 DMZ

Web :

Configurations

Routers :  VLAN 5 External, VLAN 20 Internal

Cisco 1841 - External Router

Cisco 1841 - Internal Router

Switch: VLAN 99

# Screenshots

## Servers: VLAN 20, VLAN 10

### 	Windows Server 2012 

	IP:172.20.242.30

This server is acting as Active Directory,DNS, and DHCP for GamesRUS.com internal network. Its responsibilities are client/server authentication , ip address distribution with the ipv4 scope 172.20.242.1 - 172.20.242.100 and address resolution internally and externally. 

#### Active Directory :

#### DHCP :

#### DNS :

### 	

### CentOS 

This server is acting as the GamesRus.com internal email its address is webmail.GamesRUS.com it utilizes Postfix and DoveCot as its software solution….

#### Email :

#### 	

#### File/FTP :

	

### 	Windows Server 2008 

This server is running spiceworks as GamesRus.com network management soloutin

	

#### SpiceWorks :

### 	

### Ubuntu - VLAN 10 DMZ

This server is acting as the web server for [www.GamesRus.com](http://www.gamesrus.com/) it runs on apache [2.4.10](http://httpd.apache.org/download.cgi#apache24). 

#### Web :

# Clients

	

# Configurations 

## Routers :  VLAN 5 External, VLAN 20 Internal

	  

#### 	**Cisco 1841 - External Router** 

**Fa0/0:**172.224.133.50/30

**Fa0/1:**172.20.240.1/30

**	**

#### 	**Cisco 1841 - Internal Router **

	**Fa0/0**: 172.20.240.6/30

	**Fa0/1: **172.20.243.1/24

	

## 	Switch: VLAN 99 

	

	


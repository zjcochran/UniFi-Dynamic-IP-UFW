# UniFI-Dynamic-IP-UFW
Python script for updating a Ubuntu UniFi Controller UFW for dynamic WAN IP clients

# Requirements
Python 3 (v3.6 minimum)

The pyufw module.  Install with "pip3 install pyufw".

# How to use
Simply add the dynamic DNS hostnames to the hosts variable.  Its a simple array so you just need ["host1.fq.dn","host2.fq.dn",etc,etc]
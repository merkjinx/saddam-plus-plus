# Saddam Plus Plus
DDoS Tool that supports:
  * DNS Amplification with "any" querys and txt dns query
  * NTP Amplification (Network Time Protocol)
  * SNMP Amplification (Simple Network Management Protocol)
  * SSDP Amplification (Simple Service Discovery Protocol)
 
 
![](http://2.bp.blogspot.com/-TkNwFJsznto/VOs3l0uSgDI/AAAAAAAAALQ/S5BNt8ULwpg/s1600/9.png)

Read more about DDoS Amplification Attacks [here](http://www.pythonforpentesting.com/2015/02/ddos-amplification-attacks.html)

Donation would be much appreciated: 1Gi5Rpz5RBEUpGknSwyRgqzk7b5bQ7Abp2 ~ the original developer
# Requirements
 * OS Supports raw sockets (For scanners and saddam++)
 * Python 2.7
 * [Pinject](https://github.com/OffensivePython/Pinject)

# Usage
```
	   _____           __    __                   ____  __              ____  __              
	  / ___/____ _____/ /___/ /___ _____ ___     / __ \/ /_  _______   / __ \/ /_  _______    
	  \__ \/ __ `/ __  / __  / __ `/ __ `__ \   / /_/ / / / / / ___/  / /_/ / / / / / ___/    
	 ___/ / /_/ / /_/ / /_/ / /_/ / / / / / /  / ____/ / /_/ (__  )  / ____/ / /_/ (__  )     
	/____/\__,_/\__,_/\__,_/\__,_/_/ /_/ /_/  /_/   /_/\__,_/____/  /_/   /_/\__,_/____/      
	https://github.com/OffensivePython/Saddam ~ https://github.com/merkjinx/saddam-plus-plus
	https://twitter.com/OffensivePython

Usage: 
Saddam.py target.com [options]        # DDoS
Saddam.py benchmark [options]         # Calculate AMPLIFICATION factor


Options:
  -h, --help            show this help message and exit
  -d FILE:FILE|DOMAIN, --dns=FILE:FILE|DOMAIN
                        DNS Amplification File and Domains to Resolve (e.g:
                        dns.txt:[evildomain.com|domains_file.txt]
  -n FILE, --ntp=FILE   NTP Amplification file
  -s FILE, --snmp=FILE  SNMP Amplification file
  -p FILE, --ssdp=FILE  SSDP Amplification file
  -t N, --threads=N     Number of threads (default=1)
  -P port, --port=port  Attack port of target
```

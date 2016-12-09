# Scanners for saddam
 includes 
 * dns scanner
 * ntp scanner

# Requierments
 * gcc
 * automake (Optional)

# quick compile:

Run 

```
make
```

* Note: I havent tested the makefile yet if there is an issue please report it. I will fix it ASAP

# dns scanner: 

# compile: 
  * gcc dns.c -pthread -o dns-scanner
  
# usage 
```
./dns-scanner <ip class start> <ip class end> <outfile> <threads> <scan delay in ms>
```
# ntp scanner:

# compile: 
  * gcc ntp.c -pthread -o ntp-scanner
  
# usage 
```
./ntp-scanner <ip range start (192.0.0.0)> <ip range end (198.255.255.255)> <outfile> <threads> <scan delay in ms>
```

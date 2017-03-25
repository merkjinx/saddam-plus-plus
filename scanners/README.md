# Scanners for saddam-plus-plus
 includes 
 * dns scanner
 * ntp scanner

# Requirements
 * gcc
 * automake (Optional) Makefile not working as of now

# compile: 
```
./build.sh
```


# usage 
dns:
```
./dns-scanner <ip class start> <ip class end> <outfile> <threads> <scan delay in ms>
```  
ntp:
```
./ntp-scanner <ip range start (192.0.0.0)> <ip range end (198.255.255.255)> <outfile> <threads> <scan delay in ms>
```

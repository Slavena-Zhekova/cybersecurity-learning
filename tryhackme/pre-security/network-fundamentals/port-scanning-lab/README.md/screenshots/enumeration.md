# Enumeration Steps

## Host Check

* Ping failed (no ICMP response)
* Host confirmed via ARP

## Port Scanning

* Nmap scan revealed port 80 open

## Service Detection

* nginx 1.24.0 (Ubuntu)

## Service Testing

* curl → HTTP 200 OK
* SSH → connection refused

## Service Validation

* nginx stopped on target
* No response after stop

## Conclusion

Target was reachable and HTTP service was successfully identified and verified.

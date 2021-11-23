---
title: 'System Preferences'
media_order: 'Screenshot 2021-11-23 at 09.50.25.png,Screenshot 2021-11-23 at 10.29.26.jpg,Screenshot 2021-11-23 at 10.32.45.png,Screenshot 2021-11-23 at 10.40.28.png'
visible: true
---

As an alternative solution, you can configure your system to use CarrotProxy as system DNS resolver. We suggest this solution only in case CarrotProxy Daemon for macOS does not work on your machine.

Please note that this would resolve all domain names using CarrotProxy DNS (non-related traffic will NOT be forwarded through CarrotProxy, however, CarrotProxy does not guarantee the same uptime as Google, CloudFlare or other DNS providers).

If your ISP provider does not provide you a with static public IP address, you will have to re-save your IP address in CarrotProxy Accounts via website in case it changes. CarrotProxy Daemon for macOS automatically updates your account IP address in case it changes.

**Configuration Guide**
1. Open macOS System Preferences![Screenshot%202021-11-23%20at%2010.29.26](Screenshot%202021-11-23%20at%2010.29.26.jpg?resize=400)
2. Go to Network
![Screenshot%202021-11-23%20at%2009.50.25](Screenshot%202021-11-23%20at%2009.50.25.png?resize=400)
3. Click on Advanced... in bottom right corner.
4. Switch to DNS tab 
5. Remove any existing DNS servers with '-' button
6. Add a new DNS server with '+' button
![Screenshot%202021-11-23%20at%2010.32.45](Screenshot%202021-11-23%20at%2010.32.45.png?resize=400)
7. Enter IP address of CarrotProxy DNS server. You can check available servers, their IP address (make sure you are logged in) and test latency at [https://www.carrotproxy.com/servers](https://www.carrotproxy.com/servers)
8. Click OK
9. Click Apply
![Screenshot%202021-11-23%20at%2010.40.28](Screenshot%202021-11-23%20at%2010.40.28.png?resize=400)
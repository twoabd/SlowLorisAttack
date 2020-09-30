# SlowLorisAttack
What is a Slowloris Attack?
Slowloris is an application layer DDoS attack which uses partial HTTP requests to open connections between a single computer and a targeted Web server, then keeping those connections open for as long as possible, thus overwhelming and slowing down the target. This type of DDoS attack requires minimal bandwidth to launch and only impacts the target web server, leaving other services and ports unaffected. Slowloris attacks can target many type of Web server software, but has proven highly-effective against Apache 1.x and 2.x.

# note*
python slowloris.py example.com

# Details
Doesn't work on Websites with Reverse Proxy (Cloudflare).   
Works mostly on thread based servers e.g. Apache and IIS.   
Tested on Small Websites.   
Some server may block source IP, use VPN.   
Verbose, Random User Agent is on.  
Sleep time is 0, Sockets Count is 500.

# Awesome-HTTPRequestSmuggling [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)]()
> A curated list of awesome research about HTTP request smuggling attacks.  Feel free to contribute!  🍻

## Blogs
- [HTTP Request Smuggling](https://www.cgisecurity.com/lib/HTTP-Request-Smuggling.pdf) - The original research by Watchfire
- [HTTP Desync Attacks: Request Smuggling Reborn](https://portswigger.net/research/http-desync-attacks-request-smuggling-reborn) -  By James Kettle
- [HTTP Desync Attacks: what happened next](https://portswigger.net/research/http-desync-attacks-what-happened-next) - By James Kettle
- [Breaking the chains on HTTP Request Smuggler](https://portswigger.net/research/breaking-the-chains-on-http-request-smuggler) - By James Kettle
- [h2c Smuggling: Request Smuggling Via HTTP/2 Cleartext (h2c)](https://labs.bishopfox.com/tech-blog/h2c-smuggling-request-smuggling-via-http/2-cleartext-h2c) - By Jake Miller
- [HTTP Desync Attacks with Python and AWS](https://medium.com/@emilefugulin/http-desync-attacks-with-python-and-aws-1ba07d2c860f) - By Emile Fugulin
- [Security: HTTP Smuggling, Apache Traffic Server](https://regilero.github.io/english/security/2019/10/17/security_apache_traffic_server_http_smuggling/) - By Regileros
- [HAProxy HTTP request smuggling (CVE-2019-18277)](https://nathandavison.com/blog/haproxy-http-request-smuggling) - By Nathan Davison
- [Understanding the root cause of F5 Networks K52145254: TMUI RCE vulnerability CVE-2020-5902](https://research.nccgroup.com/2020/07/12/understanding-the-root-cause-of-f5-networks-k52145254-tmui-rce-vulnerability-cve-2020-5902/)
- [Desync Mitigation Mode for Amazon AWS Application and Classic Load Balancers ](https://aws.amazon.com/about-aws/whats-new/2020/08/application-and-classic-load-balancers-adding-defense-in-depth-with-introduction-of-desync-mitigation-mode/)
- [Protocol Layer Attack - HTTP Request Smuggling](https://paper.seebug.org/1049/) - [中文版本](https://paper.seebug.org/1048/)
- [Integer Overflow Enables HTTP Smuggling in HAProxy](https://jfrog.com/blog/critical-vulnerability-in-haproxy-cve-2021-40346-integer-overflow-enables-http-smuggling/)
- [HTTP-Request-Smuggling slides](https://docs.google.com/presentation/d/1DV-VYkoEsjFsePPCmzjeYjMxSbJ9PUH5EIN2ealhr5I/edit#slide=id.gc72dc9a11a_1_252) - A collection of HTTP-Request-Smuggling mutations
- [Cache Poisoning at Scale](https://youst.in/posts/cache-poisoning-at-scale/)
- [Empirical Study of HTTP Request Smuggling in Open-Source Servers and Proxies](http://kth.diva-portal.org/smash/get/diva2:1596031/FULLTEXT01.pdf)
- [Harvesting Active Directory credentials via HTTP Request Smuggling](https://northwave-security.com/harvesting-active-directory-credentials-via-http-request-smuggling/)

## Talks
- [DEF CON 24 - Hiding Wookiees in HTTP: HTTP smuggling](https://infocon.org/cons/DEF%20CON/DEF%20CON%2024/DEF%20CON%2024%20presentations/DEF%20CON%2024%20-%20Regilero-Hiding-Wookiees-In-Http.pdf) - By regilero
- [BH USA 2019 - HTTP Desync Attacks: Smashing into the Cell Next Door](https://i.blackhat.com/USA-19/Wednesday/us-19-Kettle-HTTP-Desync-Attacks-Smashing-Into-The-Cell-Next-Door.pdf) - By James Kettle
- [BH USA 2020 - HTTP Request Smuggling in 2020 – New Variants, New Defenses and New Challenges](https://www.blackhat.com/us-20/briefings/schedule/#http-request-smuggling-in---new-variants-new-defenses-and-new-challenges-20019) - By Amit Klein
- [BH USA 2017 - Web Cache Deception Attack](https://www.blackhat.com/docs/us-17/wednesday/us-17-Gil-Web-Cache-Deception-Attack.pdf) - By Omer Gil
- [BH EU 2021 - Practical HTTP Header Smuggling: Sneaking Past Reverse Proxies to Attack AWS and Beyond](https://www.blackhat.com/eu-21/briefings/schedule/#practical-http-header-smuggling-sneaking-past-reverse-proxies-to-attack-aws-and-beyond-24363) - By Daniel Thatcher
- [Practical Attacks Using HTTP Request Smuggling](https://drive.google.com/file/d/1iC0972G4meFPGTmqfs8g61qat7ZYLQgf/view) - By Evan Custodio at NahamCon
- [HTTP Request Smuggling via higher HTTP versions](https://www.slideshare.net/neexemil/http-request-smuggling-via-higher-http-versions) - By Emil Lerner at PHDays2021
- [HTTP/2: The Sequel is Always Worse](https://www.blackhat.com/us-21/briefings/schedule/#http-the-sequel-is-always-worse-22668) - By James Kettle at BHUSA2021
- [Response Smuggling: Pwning HTTP 1 1 Connections](https://drive.google.com/file/d/1sbcq-f670wbnARIlJcSA_wGAWqUNcI5I/view) - By Martin Doyhenard at DEF CON 29
- [BH USA 2022 - Browser-Powered Desync Attacks: A New Frontier in HTTP Request Smuggling](https://www.blackhat.com/us-22/briefings/schedule/index.html#browser-powered-desync-attacks-a-new-frontier-in-http-request-smuggling-26414) - By James Kettle

## Tools
- [PortSwigger/http-request-smuggler](https://github.com/PortSwigger/http-request-smuggler)
- [defparam/smuggler](https://github.com/defparam/smuggler) - An HTTP Request Smuggling / Desync testing tool written in Python 3
- [SafeBreach-Labs/HRS](https://github.com/SafeBreach-Labs/HRS) 
- [regilero/HTTPWookiee](https://github.com/regilero/HTTPWookiee) - An HTTP server and proxy stress tool (respect of RFC, HTTP Smuggling issues, etc)
- [BishopFox/h2csmuggler](https://github.com/BishopFox/h2csmuggler) - HTTP Request Smuggling over HTTP/2 Cleartext (h2c)
- [aws/http-desync-guardian](https://github.com/aws/http-desync-guardian) - Analyze HTTP requests to minimize risks of HTTP Desync attacks
- [neex/http2smugl](https://github.com/neex/http2smugl) - detects HTTP Request Smuggling that arise during HTTP/2 -> HTTP/1.1 conversion

## Bug reports and bounties
- [Paypal.com](https://hackerone.com/reports/488147) - Stored XSS on paypal.com/signin via cache poisoning. $18,900
- [Paypal.com](https://hackerone.com/reports/510152) - Bypass for #488147 enables stored XSS on paypal.com/signin again. $20,000
- [Slack account takeovers](https://hackerone.com/reports/737140) - Mass account takeovers using HTTP Request Smuggling to steal session cookies. $6,500
- [Newrelic.com](https://hackerone.com/reports/498052) - Password theft login.newrelic.com via Request Smuggling. $3,000
- [U.S. Dept Of Defense](https://hackerone.com/reports/526880) - Request smuggling on U.S. Dept Of Defense website
- [Labs.data.gov](https://hackerone.com/reports/726773) - HTTP Request Smuggling on labs.data.gov. $750
- [Ruby webrick](https://hackerone.com/reports/965267) - Potential HTTP Request Smuggling in ruby webrick. $500
- [Cloudflare fixed an HTTP/2 smuggling vulnerability](https://lab.wallarm.com/cloudflare-fixed-an-http-2-smuggling-vulnerability/) - Cloudflare applies weak validation on HTTP/2 headers. $1000
- [Multiple HTTP Smuggling reports](https://hackerone.com/reports/648434) - By regilero

## Other related attacks
- [Host-of-Troubles attacks](https://hostoftroubles.com) - Multiple Host header ambiguity to enable cache poisoning and firewall bypass
- [BH USA 2020 - You have No Idea Who Sent that Email: 18 Attacks on Email Sender Authentication](http://i.blackhat.com/USA-20/Thursday/us-20-Chen-You-Have-No-Idea-Who-Sent-That-Email-18-Attacks-On-Email-Sender-Authentication.pdf) - Exploiting email ambiguities to bypass SPF, DKIM, and DMARC authentication

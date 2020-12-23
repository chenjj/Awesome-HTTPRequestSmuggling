# Awesome-HTTPRequestSmuggling [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)]()
> A curated list of awesome blogs and tools about HTTP request smuggling attacks.   Feel free to contribute!  🍻

## Blogs
- [HTTP Request Smuggling](https://www.cgisecurity.com/lib/HTTP-Request-Smuggling.pdf) - The original research by Watchfire
- [HTTP Desync Attacks: Request Smuggling Reborn](https://portswigger.net/research/http-desync-attacks-request-smuggling-reborn) -  By James Kettle
- [HTTP Desync Attacks: what happened next](https://portswigger.net/research/http-desync-attacks-what-happened-next) - By James Kettle
- [Breaking the chains on HTTP Request Smuggler](https://portswigger.net/research/breaking-the-chains-on-http-request-smuggler) - By James Kettle

## Talks
- [DEF CON 24 - Hiding Wookiees in HTTP: HTTP smuggling](https://infocon.org/cons/DEF%20CON/DEF%20CON%2024/DEF%20CON%2024%20presentations/DEF%20CON%2024%20-%20Regilero-Hiding-Wookiees-In-Http.pdf) - By regilero
- [BH USA 2019 - HTTP Desync Attacks: Smashing into the Cell Next Door](https://i.blackhat.com/USA-19/Wednesday/us-19-Kettle-HTTP-Desync-Attacks-Smashing-Into-The-Cell-Next-Door.pdf) - By James Kettle
- [BH USA 2020 - HTTP Request Smuggling in 2020 – New Variants, New Defenses and New Challenges](https://www.blackhat.com/us-20/briefings/schedule/#http-request-smuggling-in---new-variants-new-defenses-and-new-challenges-20019) - By Amit Klein

## Tools
- [PortSwigger/http-request-smuggler](https://github.com/PortSwigger/http-request-smuggler)
- [defparam/smuggler](https://github.com/defparam/smuggler) - An HTTP Request Smuggling / Desync testing tool written in Python 3
- [SafeBreach-Labs/HRS](https://github.com/SafeBreach-Labs/HRS) 
- [regilero/HTTPWookiee](https://github.com/regilero/HTTPWookiee) - An HTTP server and proxy stress tool (respect of RFC, HTTP Smuggling issues, etc)

## Bug reports and bounties
- [Paypal.com](https://hackerone.com/reports/488147) - Stored XSS on paypal.com/signin via cache poisoning. $18,900
- [Paypal.com](https://hackerone.com/reports/510152) - Bypass for #488147 enables stored XSS on paypal.com/signin again. $20,000
- [Slack account takeovers](https://hackerone.com/reports/737140) - Mass account takeovers using HTTP Request Smuggling to steal session cookies. $6,500
- [Newrelic.com](https://hackerone.com/reports/498052) - Password theft login.newrelic.com via Request Smuggling. $3,000
- [U.S. Dept Of Defense](https://hackerone.com/reports/526880) - Request smuggling on U.S. Dept Of Defense website
- [Labs.data.gov](https://hackerone.com/reports/726773) - HTTP Request Smuggling on labs.data.gov. $750

## Other related attacks
- [Host-of-Troubles attacks](https://hostoftroubles.com) - Multiple Host header ambiguity to enable cache poisoning and firewall bypass
- [BH USA 2020 - You have No Idea Who Sent that Email: 18 Attacks on Email Sender Authentication](http://i.blackhat.com/USA-20/Thursday/us-20-Chen-You-Have-No-Idea-Who-Sent-That-Email-18-Attacks-On-Email-Sender-Authentication.pdf) - Exploiting email ambiguities to bypass SPF, DKIM, and DMARC authentication

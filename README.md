# Awesome-Web-Application-Firewall

## Top Web Application Firewall (WAF)



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Web Application Security, API Protection, Bot Mitigation, DDoS Protection & Application-Layer Threat Detection*  

**Last updated: August 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Web Application Firewalls (WAF)**. These tools protect web applications and APIs against common application-layer attacks, malicious traffic, bots, exploits, abuse, and other web security threats using rule-based detection, behavioral analysis, signatures, machine learning, and virtual patching.



**Examples** include Cloudflare WAF, Imperva, F5 Distributed Cloud WAAP, Akamai App & API Protector, AWS WAF, Azure Web Application Firewall, Fastly Next-Gen WAF, Barracuda WAF, Fortinet FortiWeb, and Radware Cloud WAF.



**Open-source emphasis**: This section is heavily expanded with open-source WAF engines, reverse proxies, web-security modules, ModSecurity rule sets, API gateways, ingress controllers, bot-detection components, and security-focused proxy projects that can be self-hosted and combined into custom WAF architectures.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [Additional Strong Open-Source Options](#additional-strong-open-source-options)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Cloudflare WAF](https://www.cloudflare.com/application-services/products/waf/)** | Cloud-based WAF protecting web applications and APIs with managed rules, custom rules, bot management, DDoS protection, and edge-based traffic inspection. | Free tier available ($0); Pro tier starts at $20/month (billed annually) or $25/month (monthly); Business tier at $200/month | Free forever plan includes unmetered DDoS mitigation and up to 5 custom firewall rules per domain |
| **[AWS WAF](https://aws.amazon.com/waf/)** | Managed AWS WAF service for filtering web requests using managed rule groups, custom rules, rate-based rules, and AWS infrastructure integrations. | $5.00/month per Web ACL + $1.00/month per rule + $0.60 per 1M requests (prorated hourly) | 30-day free trial with 10,000,000 requests processed per month for AWS WAF Bot Control |
| **[Google Cloud Armor](https://cloud.google.com/armor)** | Google Cloud edge security service providing WAF capabilities, DDoS protection, adaptive protection, rate limiting, and traffic filtering. | Standard tier: $5.00/month per security policy + $1.00/month per rule + $0.75 per 1M requests; Enterprise: $3,000/month | 90-day free trial with $300 in Google Cloud Platform credits |
| **[Azure Web Application Firewall](https://azure.microsoft.com/products/web-application-firewall)** | Microsoft-managed WAF for Azure application delivery services, providing OWASP-based protection, custom rules, and bot protection. | $5.00/month per WAF policy + ~$0.448/hour (~$327/month) Application Gateway v2 base fee + $0.0144/hour/CU | 30-day free trial with $200 in Microsoft Azure credits |
| **[Oracle Cloud WAF](https://www.oracle.com/security/cloud-security/web-application-firewall/)** | Managed WAF service providing application-layer protection, access control, rate limiting, and security rule management. | $5.00/month per rule set + $0.60 per 1M requests + $0.0015/GB outbound data transfer | 30-day free trial with $300 in Oracle Cloud Infrastructure credits |
| **[Alibaba Cloud WAF](https://www.alibabacloud.com/product/web-application-firewall)** | Managed cloud WAF providing web attack protection, bot management, API security, and traffic control. | Basic subscription starts at ~$140/month; Pay-As-You-Go starts at $0.01 per SeCU (~$50/month base) | 30-day free trial via Alibaba Cloud free trial credits |
| **[Sucuri Website Firewall](https://sucuri.net/website-firewall/)** | Cloud-based website firewall providing WAF, DDoS mitigation, malware protection, and application traffic filtering. | Basic plan starts at $9.99/month ($119.88/year); Pro plan at $19.98/month ($239.88/year) | 30-day free trial with full WAF protection for 1 website |
| **[Imperva](https://www.imperva.com/)** | Application and API security platform providing WAF, DDoS protection, bot management, API protection, and threat intelligence. | Cloud WAF entry plans start at ~$59/month (Pro) and ~$299/month (Business) | 30-day free trial with full access to Cloud WAF and Login Protect features |
| **[Fastly Next-Gen WAF](https://www.fastly.com/products/next-gen-waf)** | Cloud WAF platform providing application protection, behavioral detection, API security, and edge-based security controls. | Starts at ~$2,000/month (annual contract based on deployment model and request volume) | 30-day proof-of-concept (POC) trial environment via enterprise sales engagement |
| **[Barracuda WAF](https://www.barracuda.com/products/application-protection/web-application-firewall)** | Application-security platform providing WAF, API protection, bot management, DDoS defense, and application delivery. | PAYG starts at ~$1.19/hour on AWS Marketplace; Cloud-delivered WAF starts at ~$199/month | 30-day free trial on AWS/Azure Marketplace with full feature access |
| **[Fortinet FortiWeb](https://www.fortinet.com/products/web-application-firewall)** | Web application firewall providing protection against OWASP application attacks, bots, APIs, and automated threats. | FortiWeb Cloud starts at $0.04/hour or ~$20/month per web app via consumption points | 14-day to 30-day free trial on AWS, Azure, and GCP marketplaces |
| **[Radware Cloud WAF](https://www.radware.com/cybersecurity/application-security/web-application-firewall/)** | Cloud-based WAF and application-security platform providing WAF, API protection, bot management, and DDoS mitigation. | Starting at ~$1,000/month for entry-level managed cloud WAF | 30-day free trial for enterprise evaluation with full managed WAF capabilities |
| **[F5 Distributed Cloud WAAP](https://www.f5.com/cloud)** | Web Application and API Protection platform combining WAF, API security, bot defense, and DDoS mitigation. | AWS Marketplace PAYG starts at ~$3.704/hour (~$2,700/month); Subscription packages start at ~$500/month | 45-day free trial for enterprise evaluation via F5 Distributed Cloud console |
| **[F5 BIG-IP Advanced WAF](https://www.f5.com/products/security/web-application-firewall)** | Enterprise WAF providing application-layer protection, behavioral analysis, bot defense, and advanced threat mitigation. | Starts at ~$1.96/hour on AWS/Azure Marketplace (~$1,430/month) or perpetual license from ~$4,000/instance | 30-day free trial on AWS and Azure marketplaces with all WAF modules enabled |
| **[Check Point CloudGuard WAF](https://www.checkpoint.com/cloudguard/cloudguard-waf/)** | Cloud application-security service providing WAF, API protection, bot mitigation, and automated threat prevention. | Starts at ~$0.024/hour (~$17.50/month) or ~$299/month on AWS/Azure Marketplace | 30-day free trial on AWS Marketplace and Check Point Infinity Portal |
| **[Citrix Web App and API Protection](https://www.netscaler.com/)** | Application and API protection capabilities integrated with Citrix NetScaler application delivery infrastructure. | Starts at ~$0.40/hour on AWS/Azure Marketplace (~$290/month) or pooling licenses from ~$3,000/year | 90-day free trial for NetScaler VPX Express / 30-day trial on cloud marketplaces |
| **[A10 Networks WAF](https://www.a10networks.com/products/application-delivery-controller/)** | Application-delivery and security platform providing WAF and traffic-management capabilities for enterprise applications. | Starts at ~$0.80/hour on AWS Marketplace (~$584/month) or perpetual appliance/virtual licensing | 30-day free trial on AWS Marketplace |
| **[Akamai App & API Protector](https://www.akamai.com/products/app-and-api-protector)** | Edge-based application and API security service providing WAF, automated attack detection, bot protection, and DDoS mitigation. | Enterprise contract starting at ~$2,000/month based on traffic tier and protected hostnames | 30-day proof-of-concept / evaluation trial via Akamai sales |
| **[Akamai Kona Site Defender](https://www.akamai.com/)** | Akamai application-security technology providing edge WAF and DDoS protection for internet-facing applications. | Enterprise contract starting at ~$3,000/month based on bandwidth and scale | 30-day guided evaluation trial via Akamai enterprise sales |
| **[StackPath WAF](https://www.stackpath.com/)** | Edge security and application delivery platform with WAF and traffic-filtering capabilities. | Discontinued (Operations ceased June 2024; historically started at $10.00/month) | Discontinued (Historically offered 30-day free trial with 1M requests/mo) |



## Open-Source GitHub Projects



- **[ModSecurity](https://github.com/owasp-modsecurity/ModSecurity)**  

  One of the most widely used open-source WAF engines. ModSecurity provides a rules-based inspection engine that can be integrated with web servers and reverse proxies to detect and block malicious HTTP traffic.



- **[OWASP Core Rule Set (CRS)](https://github.com/coreruleset/coreruleset)**  

  Open-source generic WAF rule set maintained by OWASP. It provides rules for detecting common web attacks such as SQL injection, cross-site scripting, local file inclusion, and other OWASP Top 10 threats.



- **[Coraza WAF](https://github.com/corazawaf/coraza)**  

  Modern open-source WAF engine compatible with the ModSecurity SecLang rule language and designed for cloud-native and proxy environments.



- **[Coraza Proxy-WASM](https://github.com/corazawaf/proxy-wasm)**  

  WebAssembly-based integration of Coraza designed for deployment within modern proxy and service-mesh environments.



- **[NAXSI](https://github.com/nbs-system/naxsi)**  

  Open-source, high-performance WAF module for NGINX using a positive-security approach and rule-based HTTP request filtering.



- **[OpenResty](https://github.com/openresty/openresty)**  

  NGINX-based web platform extended with Lua scripting, useful for building programmable reverse proxies, request filters, API gateways, and custom WAF functionality.



- **[NGINX](https://github.com/nginx/nginx)**  

  High-performance open-source web server and reverse proxy that can serve as the foundation for custom WAF architectures using modules, Lua, NAXSI, ModSecurity, or external security engines.



- **[Apache HTTP Server](https://github.com/apache/httpd)**  

  Open-source web server supporting security modules such as ModSecurity for building self-hosted WAF deployments.



- **[HAProxy](https://github.com/haproxy/haproxy)**  

  Open-source high-performance load balancer and reverse proxy that can be combined with ACLs, Lua, external inspection systems, and security tooling to create application-security gateways.



- **[Envoy Proxy](https://github.com/envoyproxy/envoy)**  

  Open-source cloud-native proxy frequently used as a foundation for API gateways, ingress, service meshes, and programmable security policies.



- **[Istio](https://github.com/istio/istio)**  

  Open-source service mesh built around Envoy that provides traffic-management and security-policy capabilities useful for protecting microservices and APIs.



- **[Kong](https://github.com/Kong/kong)**  

  Open-source API gateway and reverse proxy with authentication, rate limiting, request transformation, and plugin-based security capabilities.



- **[Apache APISIX](https://github.com/apache/apisix)**  

  Open-source cloud-native API gateway providing plugins for authentication, rate limiting, traffic control, request filtering, and API security.



- **[Traefik](https://github.com/traefik/traefik)**  

  Open-source cloud-native reverse proxy and ingress controller that can be extended with middleware for authentication, rate limiting, headers, and traffic filtering.



- **[Caddy](https://github.com/caddyserver/caddy)**  

  Open-source web server and reverse proxy with automatic HTTPS and extensible middleware architecture suitable for custom application-security gateways.



- **[OpenResty ModSecurity](https://github.com/owasp-modsecurity/ModSecurity)**  

  ModSecurity can be deployed with NGINX/OpenResty-based architectures to provide rule-driven WAF inspection.



- **[Lua-Nginx-WAF](https://github.com/loveshell/ngx_lua_waf)**  

  Open-source Lua-based WAF designed for NGINX/OpenResty environments, providing configurable request inspection and attack detection.



- **[Nginx Ultimate Bad Bot Blocker](https://github.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker)**  

  Open-source NGINX configuration and rule collection for identifying and blocking unwanted bots, crawlers, scanners, and abusive clients.



- **[CrowdSec](https://github.com/crowdsecurity/crowdsec)**  

  Open-source collaborative security engine that analyzes logs and network behavior to detect malicious activity and enforce decisions through security bouncers.



- **[Fail2Ban](https://github.com/fail2ban/fail2ban)**  

  Open-source intrusion-prevention framework that monitors logs and dynamically blocks abusive IP addresses. It can complement a WAF with brute-force and automated-abuse protection.



- **[OpenAppSec](https://github.com/openappsec/openappsec)**  

  Open-source machine-learning-based application-security engine designed to protect web applications and APIs from malicious traffic.



- **[OpenAppSec NGINX](https://github.com/openappsec/openappsec)**  

  OpenAppSec can be integrated into NGINX-based application delivery architectures to provide ML-driven application-layer protection.



- **[SafeLine](https://github.com/chaitin/SafeLine)**  

  Open-source Web Application Firewall providing web-attack detection and protection with a self-hosted deployment model.



- **[BunkerWeb](https://github.com/bunkerity/bunkerweb)**  

  Open-source, containerized Web Application Firewall based on NGINX, designed to protect web applications and APIs with security policies and automated configuration.



- **[BunkerWeb Cloud Native](https://github.com/bunkerity/bunkerweb)**  

  BunkerWeb can be deployed with Docker, Kubernetes, and other environments to provide self-hosted WAF protection.



- **[Shadow Daemon](https://github.com/LoRexxar/Shadow Daemon)**  

  Open-source application firewall designed to detect and prevent malicious requests before they reach vulnerable web applications.



- **[WebKnight](https://github.com/WebKnightRCE/WebKnight)**  

  Open-source IIS-based web application firewall providing request filtering and application-layer protection for Microsoft web environments.



- **[IronBee](https://github.com/ironbee/ironbee)**  

  Open-source web application firewall engine and security framework designed for HTTP traffic inspection and application protection.



- **[Naxsi](https://github.com/nbs-system/naxsi)**  

  Lightweight open-source NGINX WAF module based on a positive-security model and request scoring.



- **[WAF-FLE](https://github.com/EnableSecurity/waf-fle)**  

  Open-source tooling and research around WAF rule evaluation and testing.



- **[OWASP CRS](https://github.com/coreruleset/coreruleset)**  

  The most important open-source complement to ModSecurity and other compatible WAF engines, providing a maintained set of generic attack-detection rules.



### Additional Strong Open-Source Options



- **[ModSecurity](https://github.com/owasp-modsecurity/ModSecurity)** for a mature open-source WAF inspection engine.

- **[OWASP Core Rule Set](https://github.com/coreruleset/coreruleset)** for maintained generic WAF rules.

- **[Coraza](https://github.com/corazawaf/coraza)** for a modern ModSecurity-compatible WAF engine.

- **[NAXSI](https://github.com/nbs-system/naxsi)** for lightweight NGINX-native WAF protection.

- **[BunkerWeb](https://github.com/bunkerity/bunkerweb)** for an integrated self-hosted WAF built around NGINX.

- **[SafeLine](https://github.com/chaitin/SafeLine)** for an integrated open-source WAF deployment.

- **[OpenAppSec](https://github.com/openappsec/openappsec)** for ML-based application and API protection.

- **[Nginx Ultimate Bad Bot Blocker](https://github.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker)** for bot and crawler filtering.

- **[CrowdSec](https://github.com/crowdsecurity/crowdsec)** for collaborative behavioral threat detection and automated blocking.

- **[Fail2Ban](https://github.com/fail2ban/fail2ban)** for automated IP blocking based on observed abusive behavior.

- **[Kong](https://github.com/Kong/kong)** for API gateway security and traffic controls.

- **[Apache APISIX](https://github.com/apache/apisix)** for cloud-native API gateway security.

- **[Envoy](https://github.com/envoyproxy/envoy)** for programmable proxy-based application security.

- **[HAProxy](https://github.com/haproxy/haproxy)** for high-performance reverse-proxy and traffic-filtering architectures.

- **[OpenResty](https://github.com/openresty/openresty)** for programmable NGINX-based security gateways.



**Frameworks for building custom open-source WAF systems**: Combine **NGINX/OpenResty + ModSecurity/Coraza + OWASP CRS** for traditional rule-based WAF protection. For cloud-native environments, combine **Envoy/Kong/Apache APISIX + Coraza/OpenAppSec + Kubernetes**. Add **CrowdSec + Fail2Ban** for behavioral and IP-reputation-based enforcement and **Nginx Ultimate Bad Bot Blocker** for automated crawler/bot filtering.



A practical self-hosted WAF architecture can look like:



`Internet → CDN/Load Balancer → NGINX/Envoy → ModSecurity/Coraza + OWASP CRS → Application/API`



For a Kubernetes-oriented architecture:



`Internet → Ingress/Envoy → Coraza/OpenAppSec → API Gateway → Kubernetes Services`



For a broader open-source security stack:



`CDN → WAF → Bot Detection → Rate Limiting → API Gateway → Application → SIEM/Security Analytics`



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Open-source projects differ significantly in scope: some are complete WAF products, while others are WAF engines, rule sets, reverse proxies, API gateways, bot-detection systems, or security components.

- A reverse proxy or API gateway is not automatically a WAF; several projects listed here are included because they provide important building blocks for constructing application-security gateways.

- WAF rules require continuous maintenance, tuning, testing, and monitoring to minimize both false positives and false negatives.

- Production WAF deployments should be tested against the specific applications, APIs, frameworks, and traffic patterns they are intended to protect.



---



**Made for security engineers, DevSecOps teams, application-security teams, API developers, and infrastructure technologists.**  

Let's make web application security more open, programmable, transparent, and accessible.

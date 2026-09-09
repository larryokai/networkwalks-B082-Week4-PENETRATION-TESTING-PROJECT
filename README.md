# networkwalks-B082-Week4-PENETRATION-TESTING-PROJECT
A limited external reconnaissance engagement was performed against the publicly accessible website and supporting infrastructure of medirozahospital.com. The goal was to map the attack surface, identify technologies in use, and note any immediately visible security posture issues.

Key Observations: 
•	The site is a modern-looking hospital website advertising emergency services, departments, and patient/staff portals.
•	Infrastructure is hosted on Namecheap shared/web hosting with privacy-protected WHOIS.
•	Multiple mail-related and FTP ports are exposed.
•	A LiteSpeed WAF and OpenResty (with Cloudflare edge caching headers) are present.
•	No critical remote code execution or authentication bypass was attempted or identified during this recon-only phase.
Overall risk from the recon data alone is Medium due to the number of open services and the presence of login portals (Staff Login and Patient Portal).

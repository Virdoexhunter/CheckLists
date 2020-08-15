# BugBounty CheckLists

Recon -> Recon Checklists

1-Subdomain Enumeration -> done using subfinder and get all alive domains and their status code:)
2-Subdomain Takeovers
3-Misconfigured Third Party Services
4-Misconfigured Storage Options (S3 Buckets)
5-Broken Link Hijacking
6-Directory Enumeration
7-Service Enumeration
8-JS Files for Domains, Sensitive Information such as Hardcoded APIs & Secrets
9-GitHub Recon
10-Parameter Discovery
11-Wayback History & Waybackurls
12-Google Dork for Increasing Attack Surface
13-Internet Search Engine Discovery (Shodan, Censys, Fofa, BinaryEdge, Spyse, Etc.)
14-Potential URL Extraction for Vulnerability Automation (GF Patterns + Automation Scripts

Vulnerability Checklists

1-Old Session Does Not expire ->  grab all login and signup functionality
2-Password Reset Token Leakage -> Check for password reset token leakage
3-Password reset token leakage      
4-Session Hijacking
5-CSRF all types
6-OAuth Token Leakage
7-HTML Injection
8-XSS
9-Email Change
10-IDOR
11-Parameter Tampring
12-SSRF
13-CVES
14-Other Service exploits
15-Host Header Injection
16-Open Redirects
17-Web Cache Poisoning
18-CSRF token not expired
19-Rate Limits(bypass)
20-2FA bypass
21-Concurrent Issues

Github Dorks To Look For:
1- filename:.bash_history DOMAIN-NAME
2- SECRET_KEY_BASE=
3- "stie.com" vim_settings.xml
4-  Wordpress_DB_PASSWORD
5- filename: wp-config.php

List of github dorks
api_key
“api keys”
authorization_bearer:
oauth
auth
authentication
client_secret
api_token:
“api token”
client_id
password
user_password
user_pass
passcode
client_secret
secret
password hash
OTP
user auth

XSS_JSON :
1- "}]}';alert('oBonito')</script>

CSRF BYPASS:

1-Change POST to GET
2-Remove Total Token Parameter
3-Blank
4-Replace random value with same length
5-change Content-Type:form/multipart


Google Dorks:
1-inurl:site.com intitle:"index of"
2-inurl:site.com intitle:"index of /" "*key.pem"
3-inurl:site.com ext:sql|ext:bak|ext:old|ext:env|ext:xls|ext:xml|ext:json|ext:csv|ext:yml
4-inurl:site.com "MYSQL_ROOT_PASSWORD"

---------------------------------------------------------------------BEST TWEETS---------------------------------------------------------------------------------------

JS FILES LOOKUP:
https://twitter.com/Haoneses/status/1291387580299321358/photo/1

Broken Link Hijacking:
https://twitter.com/micha3lb3n/status/1289939398797037568/photo/1

ADMIN PORTAL BYPASS CHECK:
https://twitter.com/SalahHasoneh1/status/1287825026134269958/photo/1

ACCOUNT TAKEOVER:
https://twitter.com/Muhe76355002/status/1287250650028482562/photo/1


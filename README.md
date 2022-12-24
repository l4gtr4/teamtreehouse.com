# Host Header Injection Lead To Account Takeover.

hi team,

Weakness: Privilege Escalation
Severity: Critical (8 ~ 10)

Affected URL: https://teamtreehouse.com

This allows an attacker to insert a malicious host header, leading to data leakage.

Impact
- Account takeover

Steps to Reproduce:
1. Visit The Home Page
2. Intercept the HTTP request in Burp Suite & Add X-Forwarded-Host: attacker.com
3.) Forward the request and login

PoC: https://mega.nz/file/a2AmkSYJ#qm2H2ESRtz4uDurR6RAEXzJBzmwKQTPrL9Omm4y0Yj0

Suggested Mitigation/Remediation Actions:
Use $_SERVER['SERVER_NAME'] rather than $_SERVER['HTTP_HOST']

    I hope this report will be useful

    Paypal: "monaimr46@gmail.com"

    Coinbase: "monaimr46@gmail.com"

> HAVE A NICE DAY SIR :-)

# nginx security advisories
All nginx security issues should be reported to security-alert@nginx.org.

Patches are signed using one of the PGP public keys.

Integer overflow in the range filter
Severity: medium
Advisory
CVE-2017-7529
Not vulnerable: 1.13.3+, 1.12.1+
Vulnerable: 0.5.6-1.13.2
The patch  pgp

NULL pointer dereference while writing client request body
Severity: medium
Advisory
CVE-2016-4450
Not vulnerable: 1.11.1+, 1.10.1+
Vulnerable: 1.3.9-1.11.0
The patch  pgp  (for 1.9.13-1.11.0)
The patch  pgp  (for 1.3.9-1.9.12)

Invalid pointer dereference in resolver
Severity: medium
Advisory
CVE-2016-0742
Not vulnerable: 1.9.10+, 1.8.1+
Vulnerable: 0.6.18-1.9.9

Use-after-free during CNAME response processing in resolver
Severity: medium
Advisory
CVE-2016-0746
Not vulnerable: 1.9.10+, 1.8.1+
Vulnerable: 0.6.18-1.9.9

Insufficient limits of CNAME resolution in resolver
Severity: medium
Advisory
CVE-2016-0747
Not vulnerable: 1.9.10+, 1.8.1+
Vulnerable: 0.6.18-1.9.9

SSL session reuse vulnerability
Severity: medium
Advisory
CVE-2014-3616
Not vulnerable: 1.7.5+, 1.6.2+
Vulnerable: 0.5.6-1.7.4

STARTTLS command injection
Severity: medium
Advisory
CVE-2014-3556
Not vulnerable: 1.7.4+, 1.6.1+
Vulnerable: 1.5.6-1.7.3
The patch  pgp

SPDY heap buffer overflow
Severity: major
Advisory
CVE-2014-0133
Not vulnerable: 1.5.12+, 1.4.7+
Vulnerable: 1.3.15-1.5.11
The patch  pgp

SPDY memory corruption
Severity: major
Advisory
CVE-2014-0088
Not vulnerable: 1.5.11+
Vulnerable: 1.5.10
The patch  pgp

Request line parsing vulnerability
Severity: medium
Advisory
CVE-2013-4547
Not vulnerable: 1.5.7+, 1.4.4+
Vulnerable: 0.8.41-1.5.6
The patch  pgp

Memory disclosure with specially crafted HTTP backend responses
Severity: medium
Advisory
CVE-2013-2070
Not vulnerable: 1.5.0+, 1.4.1+, 1.2.9+
Vulnerable: 1.1.4-1.2.8, 1.3.9-1.4.0
The patch  pgp  (for 1.3.9-1.4.0)
The patch  pgp  (for 1.1.4-1.2.8)

Stack-based buffer overflow with specially crafted request
Severity: major
Advisory
CVE-2013-2028
Not vulnerable: 1.5.0+, 1.4.1+
Vulnerable: 1.3.9-1.4.0
The patch  pgp

Vulnerabilities with Windows directory aliases
Severity: medium
Advisory
CVE-2011-4963
Not vulnerable: 1.3.1+, 1.2.1+
Vulnerable: nginx/Windows 0.7.52-1.3.0

Buffer overflow in the ngx_http_mp4_module
Severity: major
Advisory
CVE-2012-2089
Not vulnerable: 1.1.19+, 1.0.15+
Vulnerable: 1.1.3-1.1.18, 1.0.7-1.0.14
The patch  pgp

Memory disclosure with specially crafted backend responses
Severity: major
Advisory
CVE-2012-1180
Not vulnerable: 1.1.17+, 1.0.14+
Vulnerable: 0.1.0-1.1.16
The patch  pgp

Buffer overflow in resolver
Severity: medium
CVE-2011-4315
Not vulnerable: 1.1.8+, 1.0.10+
Vulnerable: 0.6.18-1.1.7

Vulnerabilities with invalid UTF-8 sequence on Windows
Severity: major
CVE-2010-2266
Not vulnerable: 0.8.41+, 0.7.67+
Vulnerable: nginx/Windows 0.7.52-0.8.40

Vulnerabilities with Windows file default stream
Severity: major
CVE-2010-2263
Not vulnerable: 0.8.40+, 0.7.66+
Vulnerable: nginx/Windows 0.7.52-0.8.39

Vulnerabilities with Windows 8.3 filename pseudonyms
Severity: major
CORE-2010-0121
Not vulnerable: 0.8.33+, 0.7.65+
Vulnerable: nginx/Windows 0.7.52-0.8.32

An error log data are not sanitized
Severity: none
CVE-2009-4487
Not vulnerable: none
Vulnerable: all

The renegotiation vulnerability in SSL protocol
Severity: major
VU#120541  CVE-2009-3555
Not vulnerable: 0.8.23+, 0.7.64+
Vulnerable: 0.1.0-0.8.22
The patch  pgp

Directory traversal vulnerability
Severity: minor
CVE-2009-3898
Not vulnerable: 0.8.17+, 0.7.63+
Vulnerable: 0.1.0-0.8.16

Buffer underflow vulnerability
Severity: major
VU#180065  CVE-2009-2629
Not vulnerable: 0.8.15+, 0.7.62+, 0.6.39+, 0.5.38+
Vulnerable: 0.1.0-0.8.14
The patch  pgp

Null pointer dereference vulnerability
Severity: major
CVE-2009-3896
Not vulnerable: 0.8.14+, 0.7.62+, 0.6.39+, 0.5.38+
Vulnerable: 0.1.0-0.8.13
The patch  pgp


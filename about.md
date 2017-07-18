# nginx

Basic HTTP server features
Other HTTP server features
Mail proxy server features
TCP/UDP proxy server features
Architecture and scalability
Tested OS and platforms
nginx [engine x] is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server, originally written by Igor Sysoev. For a long time, it has been running on many heavily loaded Russian sites including Yandex, Mail.Ru, VK, and Rambler. According to Netcraft, nginx served or proxied 29.10% busiest sites in June 2017. Here are some of the success stories: Netflix, Wordpress.com, FastMail.FM.

The sources and documentation are distributed under the 2-clause BSD-like license.

Commercial support is available from Nginx, Inc.

# Basic HTTP server features
Serving static and index files, autoindexing; open file descriptor cache;
Accelerated reverse proxying with caching; load balancing and fault tolerance;
Accelerated support with caching of FastCGI, uwsgi, SCGI, and memcached servers; load balancing and fault tolerance;
Modular architecture. Filters include gzipping, byte ranges, chunked responses, XSLT, SSI, and image transformation filter. Multiple SSI inclusions within a single page can be processed in parallel if they are handled by proxied or FastCGI/uwsgi/SCGI servers;
SSL and TLS SNI support;
Support for HTTP/2 with weighted and dependency-based prioritization.

#Other HTTP server features
Name-based and IP-based virtual servers;
Keep-alive and pipelined connections support;
Access log formats, buffered log writing, fast log rotation, and syslog logging;
3xx-5xx error codes redirection;
The rewrite module: URI changing using regular expressions;
Executing different functions depending on the client address;
Access control based on client IP address, by password (HTTP Basic authentication) and by the result of subrequest;
Validation of HTTP referer;
The PUT, DELETE, MKCOL, COPY, and MOVE methods;
FLV and MP4 streaming;
Response rate limiting;
Limiting the number of simultaneous connections or requests coming from one address;
IP-based geolocation;
A/B testing;
Embedded Perl;
nginScript.

# Mail proxy server features
User redirection to IMAP or POP3 server using an external HTTP authentication server;
User authentication using an external HTTP authentication server and connection redirection to an internal SMTP server;
Authentication methods:
POP3: USER/PASS, APOP, AUTH LOGIN/PLAIN/CRAM-MD5;
IMAP: LOGIN, AUTH LOGIN/PLAIN/CRAM-MD5;
SMTP: AUTH LOGIN/PLAIN/CRAM-MD5;
SSL support;
STARTTLS and STLS support.
TCP/UDP proxy server features

# Generic proxying of TCP and UDP;
SSL and TLS SNI support for TCP;
Load balancing and fault tolerance;
Access control based on client address;
Executing different functions depending on the client address;
Limiting the number of simultaneous connections coming from one address;
Access log formats, buffered log writing, fast log rotation, and syslog logging;
IP-based geolocation;
A/B testing;
nginScript.

#Architecture and scalability
One master and several worker processes; worker processes run under an unprivileged user;
Flexible configuration;
Reconfiguration and upgrade of an executable without interruption of the client servicing;
Support for kqueue (FreeBSD 4.1+), epoll (Linux 2.6+), /dev/poll (Solaris 7 11/99+), event ports (Solaris 10), select, and poll;
The support of the various kqueue features including EV_CLEAR, EV_DISABLE (to temporarily disable events), NOTE_LOWAT, EV_EOF, number of available data, error codes;
The support of various epoll features including EPOLLRDHUP (Linux 2.6.17+, glibc 2.8+) and EPOLLEXCLUSIVE (Linux 4.5+, glibc 2.24+);
sendfile (FreeBSD 3.1+, Linux 2.2+, macOS 10.5+), sendfile64 (Linux 2.4.21+), and sendfilev (Solaris 8 7/01+) support;
File AIO (FreeBSD 4.3+, Linux 2.6.22+);
DIRECTIO (FreeBSD 4.4+, Linux 2.4+, Solaris 2.6+, macOS);
Accept-filters (FreeBSD 4.1+, NetBSD 5.0+) and TCP_DEFER_ACCEPT (Linux 2.4+) support;
10,000 inactive HTTP keep-alive connections take about 2.5M memory;
Data copy operations are kept to a minimum.

#Tested OS and platforms
FreeBSD 3 — 11 / i386; FreeBSD 5 — 11 / amd64;
Linux 2.2 — 4 / i386; Linux 2.6 — 4 / amd64; Linux 3 — 4 / armv6l, armv7l, aarch64, ppc64le;
Solaris 9 / i386, sun4u; Solaris 10 / i386, amd64, sun4v;
AIX 7.1 / powerpc;
HP-UX 11.31 / ia64;
macOS / ppc, i386;
Windows XP, Windows Server 2003.

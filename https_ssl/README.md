# HTTPS SSL

- 0-world_wide_web: shows the DNS record type and destination of subdomains (www, lb-01, web-01, web-02)
- 1-haproxy_ssl_termination: HAProxy config that terminates SSL on port 443
- 2-redirect_http_to_https: HAProxy config that redirects HTTP to HTTPS with a 301

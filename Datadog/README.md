- datadog-agent configcheck
- datadog-agent health
- datadog-agent hostname 
- datadog-agent status


logs:
  - type: file
    path: /var/log/nginx/access.log
    service: nginx
    source: nginx

  - type: file
    path: /var/log/nginx/error.log
    service: nginx
    source: nginx
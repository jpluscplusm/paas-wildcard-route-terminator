# paas-wildcard-route-terminator

An app which returns per-FQDN HTTP response codes for all requests

# Deploying

```
cf push --var SYSTEM_DNS_ZONE_NAME=<your-system-domain>
```

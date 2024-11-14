# DNS

DNS proxy to geoblock.

## Example
```bash
docker run -d --cap-add=NET_ADMIN -p 53:53/udp -p 443:443 -p 80:80 -e IP=public_ip dimalop/smartdns
```

## Variables
| ENV  |  Default  |  Description  |
| ALLOWED_IP | 0.0.0.0/0  | for all ips |

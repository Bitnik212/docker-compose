# Firezone VPN APP

## Network

External network for access from internet

```yaml
networks:
  nginx:
    external: true
```

## Environments

### Generate secret variables

1. Run script
```bash
docker run --rm firezone/firezone bin/gen-env
```
2. Copy variables:
 - GUARDIAN_SECRET_KEY, 
 - SECRET_KEY_BASE, 
 - LIVE_VIEW_SIGNING_SALT, 
 - COOKIE_SIGNING_SALT, 
 - COOKIE_ENCRYPTION_SALT, 
 - DATABASE_ENCRYPTION_KEY


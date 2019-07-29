# Hasura GraphQL Engine on Docker form HTTPS redirect

- `caddy` microservice is exposed at PORT 8080
- Any requests coming in with `X-Forwarded-Proto: http` will be responded with a 301 redirect to HTTPS
- `DOMAIN` environment variable needs to be set



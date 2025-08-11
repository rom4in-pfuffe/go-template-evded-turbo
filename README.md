
#  Shipfast Deploy

**zero-config deployment for static and SSR sites**

![Node](https://img.shields.io/badge/node-%3E%3D18-green)
![CI/CD](https://img.shields.io/badge/ci%2Fcd-ready-blue)

## usage

```bash
npx shipfast-deploy
```

auto-detects framework (Next.js, Astro, Nuxt, Vite) and deploys to edge CDN.

## init project

```bash
shipfast init mysite
```

creates `.shipfast/config.json`:

```json
{
  "name": "mysite",
  "region": "us-east",
  "env": {
    "NODE_ENV": "production"
  }
}
```

## deploy

```bash
shipfast deploy
```

output:

```
✓ detected nextjs
✓ building... (24s)
✓ deploying... (8s)
Deployed → https://mysite.shipfast.app
```

## integrations

* GitHub Actions ([actions.shipfast.app](https://actions.shipfast.app))
* GitLab CI ([gitlab.shipfast.app](https://gitlab.shipfast.app))
* Cloudflare DNS ([dns.shipfast.app](https://dns.shipfast.app))

## plans

| tier | bandwidth | domains | price |
| ---- | --------- | ------- | ----- |
| hobby | 100GB | 1 | free |
| pro | 1TB | 10 | $10/mo |
| team | ∞ | ∞ | $25/mo |


# PR Merge: 2025-10-28 10:57:32

# PR Merge: 2025-10-28 10:58:08

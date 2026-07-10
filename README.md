# redirects

Host-based URL redirect service deployed on [Vercel](https://vercel.com), used to point short/alternate domains to their final destinations.

## Configuration

Defined in `vercel.json` using Vercel's `redirects` with host-based matching:

| Host | Redirects to |
|---|---|
| `links.nataya.dev` | https://linktr.ee/natayadev |
| `links.nataya.com.ar` | https://linktr.ee/natayadev |
| `nataya.com.ar` | https://nataya.dev |

## Deployment

Deploy the project to Vercel and attach the domains above; Vercel reads `vercel.json` at build time and applies the redirects automatically — no application code is required.

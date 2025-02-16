# landingPage
Shadcn Landing Page
### Deploy to Cloudflare Workers

1. Create a `wrangler.toml` file in the root directory with the following configuration:

    ```toml
    name = "my-v0-project"
    type = "webpack"
    account_id = "your_cloudflare_account_id" ### On The Dashboard Workers & Pages
    workers_dev = true
    compatibility_date = "2025-02-16"

    [env.production]
    route = "your_domain.com/*"
    zone_id = "your_zone_id"
    ```
## Deploy To Cloudflare (Easy Way)

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/Anujtemp/owebdevs.github.io)


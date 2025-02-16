# landingPage
Shadcn Landing Page
### Deploy to Cloudflare Workers

1. Create a `wrangler.toml` file in the root directory with the following configuration:

    ``` type = "javascript"
account_id = "id" ### On The Dashboard Workers & Pages
workers_dev = true

[site]
bucket = "./out"
    ```
## Deploy To Cloudflare (Easy Way)

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/Anujtemp/owebdevs.github.io)


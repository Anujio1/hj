# LandingPage

## Shadcn Landing Page

### Deploy to Cloudflare Workers

1. **Create a `wrangler.toml` file** in the root directory with the following configuration:

    ```toml
    type = "javascript"
    account_id = "YOUR_ACCOUNT_ID" ### On The Dashboard Workers & Pages
    workers_dev = true

    [site]
    bucket = "./out"
    ```

    Replace `"YOUR_ACCOUNT_ID"` with your actual Cloudflare account ID found on the Dashboard under Workers & Pages.

### Deploy to Cloudflare (Easy Way)

You can use the following button to deploy to Cloudflare Workers:

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/Anujtemp/owebdevs.github.io)

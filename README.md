# Cloudflare Workers Template

Press `Use this template` button to create a new repository from this template.

---

## Getting Started

1. Add your [Cloudflare API Token](https://dash.cloudflare.com/profile/api-tokens) (`CF_API_TOKEN`) in secrets page of your GitHub repository
2. Clone the repo
3. Edit `wrangler.toml` and replace `your-worker-name` with your worker name.
4. Update `compatibility_date` in `wrangler.toml` to the [latest date](https://developers.cloudflare.com/workers/platform/compatibility-dates/#change-history).
5. Update `account_id` in `wrangler.toml` to your Cloudflare account ID.

## Development

1. `npm ci` to install dependencies.
2. Run `npm run start` to start the development server.
3. (Optional) Run `npm run publish` to publish the worker to your Cloudflare account.

## Deployment

1. Add a tag to the commit you want to deploy. (E.g. `git tag v1.0.0`)
2. Push the tag to the remote. (E.g. `git push origin v1.0.0`)

The worker will be deployed automatically.

## Acknowledgments & References

- [Cloudflare Workers](https://developers.cloudflare.com/workers/)

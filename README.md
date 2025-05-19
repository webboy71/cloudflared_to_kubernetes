# cloudflared_to_kubernetes

Don't use this repo, rather pick a branch that you're interested in and work with that.

All the examples require tunnels created via the Cloudflare GUI or API, create a values.yaml file for helm to feed in the tunnel tokens:

data:
  webService: <tunnel-token here>
  mongoExpressService: <tunnel-token here> 
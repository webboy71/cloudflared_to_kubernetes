# cloudflared_to_kubernetes

simple deployment example, easiest to deploy with helm (helm install cloudflare-simple-deploy .)

tunnel secrets are base64 encoded and stored and helm values (i.e. you should add a values.yaml file) - replace helm template stuff in tunnel-secrets if desired (remember to add to .gitignore if pushing to a repo)

![deployment diagram](https://github.com/webboy71/cloudflared_to_kubernetes/blob/aea4218b4ff088046fb75a69b18df7783da601fa/images/cloudflare_tunnel_opt-Deployment%20option.png)
# cloudflared_to_kubernetes

simple deployment example, easiest to deploy with helm (helm install cloudflare-simple-deploy .)

tunnel secrets are base64 encoded and stored and helm values (i.e. you should add a values.yaml file) - replace helm template stuff in tunnel-secrets if desired (remember to add to .gitignore if pushing to a repo)
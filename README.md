# ingress example

All the examples require tunnels created via the Cloudflare GUI or API. 


Ingress example, easiest to deploy with helm (e.g. ```helm install cloudflare-ingress .```)

Tunnel secrets are base64 encoded and stored and helm values (i.e. you should add a values.yaml file) (remember to add to .gitignore if pushing to a repo)

e.g. ```echo -n <token from cloudflare> | base64```

Create a values.yaml file for helm: 

```
data:
  webService: <tunnel-token here>
  mongoExpressService: <tunnel-token here> 
```

![ingress diagram](https://github.com/webboy71/cloudflared_to_kubernetes/blob/aea4218b4ff088046fb75a69b18df7783da601fa/images/%20Ingress.png)

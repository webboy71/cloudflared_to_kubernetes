# ingress example



All the examples require tunnels created via the Cloudflare GUI or API. 

Create a values.yaml file for helm to feed in the tunnel tokens (values.yaml is in .gitignore so as not to be pushed to any repo):

```
data:
  webService: <tunnel-token here>
  mongoExpressService: <tunnel-token here> 
```

![ingress diagram](https://github.com/webboy71/cloudflared_to_kubernetes/blob/aea4218b4ff088046fb75a69b18df7783da601fa/images/%20Ingress.png)
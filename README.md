# cloudflared_to_kubernetes

NOTE: Don't use this branch (main,) rather pick the branch that you're interested in and work with that.



All the examples require tunnels created via the Cloudflare GUI or API. 

Create a values.yaml file for helm to feed in the tunnel tokens (values.yaml is in .gitignore so as not to be pushed to any repo):

```
data:
  webService: <tunnel-token here>
  mongoExpressService: <tunnel-token here> 
```
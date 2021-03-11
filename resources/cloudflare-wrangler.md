# Cloudflare Wrangler

Prerequisites

1. Node JS and NPM
2. Visual Studio Code



Source: 

{% embed url="https://developers.cloudflare.com/workers/starters" %}



[Worker SitesOpen external link](https://github.com/cloudflare/worker-sites-template)Easily deploy a static site or static assets to Cloudflare’s edge network.Copy

```text
wrangler generate my-app https://github.com/cloudflare/worker-sites-template
```

You can rename my-app to anything you want. It will create folder public,  in this foler put all of your file and assets i.e. index.html, css, js and etc. 



Commands Wrangler:

{% embed url="https://developers.cloudflare.com/workers/cli-wrangler/commands" %}



Use .toml file under folder that was created by CF





Issue: 

Restricted Policy:

{% embed url="https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about\_execution\_policies?view=powershell-7.1" %}

Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope CurrentUser 



Run Using Admin RIght




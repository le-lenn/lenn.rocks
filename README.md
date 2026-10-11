# lenn.rocks

[www.lenn.rocks](https://lenn.rocks) landing page.

## Deployment Instructions

On Pennard-1, enable the shared auto-deployer with `systemctl enable --now compose-deploy@lenn.rocks.timer`.

#### Portainer

![Portainer deployment stack settings](assets/deployment.png)

#### Set Github Secrets

See [gh action deploy.yml](.github/workflows/deploy.yml).

#### DNS

Set DNS entries for website.

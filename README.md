# Diino Does

## Deployment

We use [DigitalOcean's (DO) App Platform](https://www.digitalocean.com/pricing/app-platform) to manage deployment. DO automatically builds our images using its [NodeJS buildpack process](https://docs.digitalocean.com/products/app-platform/reference/buildpacks/nodejs/) which leverages the [Cloud Native Buildpacks technology](https://buildpacks.io/). 

Here's a [sample app](https://docs.digitalocean.com/products/app-platform/getting-started/sample-apps/node/) to demonstrate how our app is built and hosted.

Later, we can configure [deployment with DO and GitHub Actions](https://www.youtube.com/watch?v=uijgmwOdcXQ) to **automate** the deployment process on [release](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases). For now, we use the DO App Platform UI to initiate deployment.

# Nagbot Ops

This is a deployment project for Nagbot on Kubernetes

See [Nagbot](../NagbotOnGraph/README.md)

Currently the app is hosted on Azure and is available at http://nagbot.vivitap.com. 


# Deploying and running the application on Kubernetes 

For deployment to Kubernetes you can use the `deploy/kubeDeploy` directory.  

Also in the `deploy/` directory you will find a `fluxDeploy/` to enable git ops and various optional scripts to config the Kubernetes environment.

To use the gitops approach you will need to add a flux deployment key to your github repository.  See teh `deploy-gitops.sh` script for the details.

# Contributions

We welcome contributions but response time will be very slow.

See the [Contributor Guide](./.github/contibuting.md)

# Code of Conduct

See the [Code of Conduct Guide](./.github/CODE_OF_CONDUCT.md)


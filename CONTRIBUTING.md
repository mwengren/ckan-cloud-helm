# Contributing to CKAN Cloud Helm

* Welcome to CKAN Cloud!
* Contributions of any kind are welcome.
* Please [Search for issues across the different CKAN Cloud repositories](https://github.com/search?q=repo%3AViderumGlobal%2Fckan-cloud-docker+repo%3AViderumGlobal%2Fckan-cloud-helm+repo%3AViderumGlobal%2Fckan-cloud-cluster&type=Issues)

## Suggested development flow

You want to make some changes to the helm charts? Great!

Please follow this suggested flow:

* Changes to Docker images should be done in ViderumGlobal/ckan-cloud-docker repo
  * Test changes to the Docker images using the `ckan-cloud-docker` docker compose environment
* Use the [Minikube environment](QUICKSTART_MINIKUBE.md) to test and modify the Helm templates
* Finally, test on a [Production environment](QUICKSTART_PRODUCTION.md)

## CI/CD

* Helm chart repository is hosted on the same GitHub branch as the helm charts
* The repository is updated when a new release is published on GitHub
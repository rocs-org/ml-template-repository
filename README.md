# ML bases covid cases nowcasting

[![ML-Pipeline](https://github.com/jakobkolb/ml-covid-nowcasting/actions/workflows/update.yaml/badge.svg?branch=main)](https://github.com/jakobkolb/ml-covid-nowcasting/actions/workflows/update.yaml)

## Description
Template repo for simple model pipelines with Github actions set up to run periodicallly.

If you want to use github actions to commit updated files to the repo on a self hosted runner with this repo, you have to set up the following repository secrets:
* A [deploy key](https://docs.github.com/en/developers/overview/managing-deploy-keys) as `GITHUB_TOKEN`
* The sudo password of the self hosted runner as `PASSWORD`
* A pgp key to decrypt the db credentials as `GPG_PRIVATE_KEY`
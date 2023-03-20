# helm-infra

Chart for deploying web application.

## Steps to update the chart using GitHub Actions

1. Update the chart version in `Chart.yaml` file.
2. Use the same chart version in `cr.yaml` file.
3. Commit the changes and push to the master branch.

## Add the chart repository

run `helm repo add squadcast-helm https://squadcasthub.github.io/helm-infra/`

## Install the chart

run `helm install squadcast-helm squadcast-helm/squadcast-helm`

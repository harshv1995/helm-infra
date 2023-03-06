# helm-infra

Chart for deploying web application.

## Steps:

1. Update version in Chart.yaml
2. Run `cr package squadcast-helm --config cr.yaml` to package the chart
3. Run `cr upload --config cr.yaml` to upload the chart to the chart repository
4. Run `cr index --config cr.yaml` to generate the index.yaml file

## Add the chart repository

run `helm repo add squadcast-helm https://squadcasthub.github.io/helm-infra/`

## Install the chart

run `helm install squadcast-helm squadcast-helm/squadcast-helm`

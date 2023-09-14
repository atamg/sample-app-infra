This is a helm chart for deploying sample-app to the different environments (prod, dev).

There are two values (valus-dev.yaml, values-prod.yaml) files that should be fine-tuned based on the need for deploying in different environment.

Two environment values also must be provided when deploying the chart (name, license). 

Sample manual deploy command:
helm install dev-release . --values=values-dev.yaml --set name="XXXX XXX" --set license=XXXX
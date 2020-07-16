FROM quay.io/operator-framework/helm-operator:v0.6.0
LABEL name="Postgresql Operator" \
      vendor="OpenLabs" \
      version="v0.0.1" \
      release="1" \
      summary="This is an example of a postgresql helm operator." \
      description="This operator will deploy postgresql to the cluster."
COPY helm-charts/ ${HOME}/helm-charts/
COPY watches.yaml ${HOME}/watches.yaml

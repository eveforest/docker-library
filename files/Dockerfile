ARG DIR=/files
ARG K8S_DIR=/files/k8s
WORKDIR $DIR
RUN apt-get update && apt-get install -y curl
ARG DASHBOARD_DIR=/files/k8s/dashboard/v2.7.0
RUN mkdir -p $DASHBOARD_DIR && cd $DASHBOARD_DIR && curl -LO "https://raw.githubusercontent.com/kubernetes/dashboard/v2.7.0/aio/deploy/recommended.yaml"

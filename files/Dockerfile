ARG DIR=/files
ARG K8S_DIR=$DIR/k8s
WORKDIR $DIR
RUN apt-get update && apt-get install -y curl
RUN mkdir -p $K8S_DIR/dashboard/v2.7.0 &&  curl -LO "https://raw.githubusercontent.com/kubernetes/dashboard/v2.7.0/aio/deploy/recommended.yaml"

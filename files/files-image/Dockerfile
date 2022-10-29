FROM fission/alpinecurl
ARG DIR=/files
ARG K8S_DIR=$DIR/k8s
WORKDIR $DIR
ARG DASHBOARD_DIR=$K8S_DIR/dashboard/v2.7.0
RUN mkdir -p $DASHBOARD_DIR
RUN curl -Lo $DASHBOARD_DIR/dashboard.yaml "https://raw.githubusercontent.com/kubernetes/dashboard/v2.7.0/aio/deploy/recommended.yaml"


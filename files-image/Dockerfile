FROM fission/alpinecurl
ARG DIR=/files
ARG K8S_DIR=$DIR/k8s
WORKDIR $DIR
ARG DASHBOARD_DIR=$K8S_DIR/dashboard/v2.7.0
#RUN curl "www.baidu.com"
RUN mkdir -p $DASHBOARD_DIR && cd $DASHBOARD_DIR && curl -LO "https://raw.githubusercontent.com/kubernetes/dashboard/v2.7.0/aio/deploy/recommended.yaml"
CMD sh

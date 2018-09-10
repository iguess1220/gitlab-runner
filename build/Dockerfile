FROM dtzar/helm-kubectl
WORKDIR /root/.kube
COPY config /root/.kube/config
COPY helm  /usr/local/bin/helm
RUN helm init --client-only --service-account=tiller --stable-repo-url=https://kubernetes.oss-cn-hangzhou.aliyuncs.com/charts

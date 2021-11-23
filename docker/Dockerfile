FROM argoproj/argocd:v2.1.6

USER root

RUN apt-get update \
 && apt-get install -y git-crypt \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

# RUN mv /usr/bin/git /usr/bin/git.bindoc
# COPY git /usr/bin/git

USER 999
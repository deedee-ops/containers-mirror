FROM docker.io/hivemq/hivemq4:4.28.2

RUN bash -c 'cd /opt/hivemq/extensions && wget https://github.com/hivemq/hivemq-file-rbac-extension/releases/download/4.5.3/hivemq-file-rbac-extension-4.5.3.zip && unzip hivemq-file-rbac-extension-4.5.3.zip && rm -rf hivemq-file-rbac-extension-4.5.3.zip && chmod -R 770 hivemq-file-rbac-extension/'

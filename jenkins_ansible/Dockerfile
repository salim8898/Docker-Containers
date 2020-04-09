FROM jenkins/jenkins

USER root

RUN usermod -u 1001 jenkins

RUN curl -O https://bootstrap.pypa.io/get-pip.py && \
    python get-pip.py && \
    pip install ansible --upgrade

USER jenkins

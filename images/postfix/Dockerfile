FROM openshift/base-centos7
EXPOSE 25
RUN yum install -y postfix && \
    yum clean all
CMD ["/usr/libexec/postfix/master", "-w"]




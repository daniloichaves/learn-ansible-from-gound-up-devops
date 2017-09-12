FROM centos:centos6

ENV http_proxy=http_proxy=http://172.18.218.60:8080
ENV https_proxy=https_proxy=http://172.18.218.60:8080

RUN env
RUN yum -y update
RUN yum -y upgrade
RUN useradd -ms /bin/bash  vagrant
WORKDIR /home/vagrant
#RUN yum install ssh

CMD ["/bin/bash"]
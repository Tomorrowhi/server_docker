FROM centos:7
# 更新yum源,更新Centos7系统
RUN yum repolist  \
    && yum install -y epel-release  \
    && rpm -Uvh http://rpms.famillecollet.com/enterprise/remi-release-7.rpm \
    && yum -y update  \
    && yum repolist \
    && yum install -y yum-utils \
    && yum clean all

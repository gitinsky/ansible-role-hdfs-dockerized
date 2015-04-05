FROM gitinsky/oracle-java-8:0.1.1
MAINTAINER Git In Sky <support@gitinsky.com>

RUN \
#  apt-get install unzip && \
  cd / && \
#  mkdir /config && \
  wget http://mirrors.koehn.com/apache/hadoop/common/hadoop-2.6.0/hadoop-2.6.0.tar.gz && \
  tar xvzf hadoop-2.6.0.tar.gz && \
  rm -f hadoop-2.6.0.tar.gz && \
  mv /hadoop-2.6.0 /hadoop && \
  mkdir /var/hadoop && \
  mkdir /hadoop/conf && \
  useradd -m hadoop

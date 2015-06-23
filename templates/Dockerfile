FROM gitinsky/oracle-java-8:0.1.4
MAINTAINER Git In Sky <support@gitinsky.com>

RUN \
  cd / && \
  wget http://mirrors.koehn.com/apache/hadoop/common/hadoop-2.6.0/hadoop-2.6.0.tar.gz && \
  tar xvzf hadoop-2.6.0.tar.gz && \
  rm -f hadoop-2.6.0.tar.gz && \
  ln -s /hadoop-2.6.0 /hadoop && \
  mkdir /var/hadoop && \
  mkdir /hadoop/conf && \
  useradd -m hadoop

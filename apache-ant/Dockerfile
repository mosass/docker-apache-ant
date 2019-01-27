FROM java:6-jdk

WORKDIR /project

ENV ANT_VERSION 1.9.13
ENV ANT_HOME /opt/apache-ant-${ANT_VERSION}

COPY apache-ant-${ANT_VERSION}-bin.tar.gz /tmp/
RUN tar zxf /tmp/apache-ant-${ANT_VERSION}-bin.tar.gz -C /opt/
RUN rm -f /tmp/*.gz

ENV PATH ${PATH}:${ANT_HOME}/bin
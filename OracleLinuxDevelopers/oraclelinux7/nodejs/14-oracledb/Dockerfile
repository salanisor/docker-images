# Copyright (c) 2020 Oracle and/or its affiliates.
# Licensed under the Universal Permissive License v 1.0 as shown at https://oss.oracle.com/licenses/upl.
FROM quay.io/canit0/oraclelinux:7-slim

RUN yum -y install oracle-nodejs-release-el7 oracle-instantclient-release-el7 && \
    yum -y install nodejs node-oracledb-node14 && \
    rm -rf /var/cache/yum/*

ENV NODE_PATH=/usr/lib/node_modules/

CMD ["/bin/node", "-v"]

# Copyright Greg Haskins All Rights Reserved
#
# SPDX-License-Identifier: Apache-2.0
#
FROM hyperledger/fabric-baseimage:x86_64-0.3.2
COPY payload/protoc-gen-go /usr/local/bin/
ADD payload/gotools.tar.bz2 /usr/local/bin/
LABEL org.hyperledger.fabric.version=1.1.0-snapshot-590dce1 \
      org.hyperledger.fabric.base.version=0.3.2

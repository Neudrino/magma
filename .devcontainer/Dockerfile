# Note: You can use any Debian/Ubuntu based image you want.
FROM ubuntu:focal as magma-mme-builder

##### Set Python Path
ENV PYTHONPATH=$MAGMA_ROOT/lte/gatway/python:$MAGMA_ROOT/orc8r/gatway/python

RUN ln -s $MAGMA_ROOT/bazel/bazelrcs/devcontainer.bazelrc /etc/bazelrc

WORKDIR $MAGMA_ROOT

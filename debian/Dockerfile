#
#
#--------------------------------------------------------------------------
# apidoc
#--------------------------------------------------------------------------
#

FROM chinayin/node:20-slim

ENV NPM_CONFIG_PREFIX=/home/node/.npm-global
ENV PATH=$PATH:$NPM_CONFIG_PREFIX/bin

ENV APIDOC_VERSION 1.2.0

RUN mkdir -p /home/node/apidoc

WORKDIR /home/node/apidoc

RUN npm install --only=prod -g apidoc --tag $APIDOC_VERSION \
    && npm install --only=prod -g apidoc-plugin-schema apidoc-plugin-example json-schema-ref-parser

ENTRYPOINT ["apidoc"]

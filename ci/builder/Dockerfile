FROM mhart/alpine-node:8.17

RUN apk --no-cache add git curl xz bash python make g++

VOLUME /dcos-website
WORKDIR /dcos-website

CMD ["ci/test.sh"]

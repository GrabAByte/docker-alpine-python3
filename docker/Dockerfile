FROM grababyte/alpine-base:0.7.3

LABEL devops.grababyte.image.authors="GrabAByte"

RUN \
  apk add --no-cache python3==3.9.5-r2 && \
  rm -rf /var/cache/apk/* && \
  python3 -m ensurepip && \
  pip3 install --no-cache-dir --upgrade \
    pip==22.0.4 \
    setuptools==62.2.0

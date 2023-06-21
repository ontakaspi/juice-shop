FROM alpine:3.17.4

RUN apk add curl

COPY smoke-test.sh smoke-test.sh
COPY smoke-1test.sh smoke-t1est.sh

CMD ["sh", "smoke-test.sh", "http://app:3000"]

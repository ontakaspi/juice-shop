FROM alpine:3.17.4

RUN apk add curl

ADD smoke-test.sh smoke-test.sh
COPY smoke-1test.sh smoke-t1est.sh

COPY smoke-2test.sh smoke-21est.sh

COPY smoke-5test.sh smoke-5est.sh
ADD smoke-6test.sh smoke-61est.sh

CMD ["sh", "smoke-test.sh", "http://app:3000"]

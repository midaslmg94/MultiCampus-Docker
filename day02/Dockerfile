FROM alpine:3.7

RUN echo "Hello, Docker!"

ADD test.sh /mydata/

RUN chmod +x /mydata/test.sh
CMD [ "ping", "www.google.com" ] 
ENTRYPOINT ping www.google.com

FROM alpine
WORKDIR /app
RUN apk add --no-cache curl
ARG VERSION=dev
RUN echo "версия $VERSION" > version.txt
ENV NAME=мир
COPY hello.sh .
RUN chmod +x hello.sh
CMD ["./hello.sh"]

FROM alpine

RUN apk add --no-cache \
                ca-certificates
                
COPY dist/gcp-pubsub-gateway /bin/
ENTRYPOINT [ "/bin/gcp-pubsub-gateway" ]

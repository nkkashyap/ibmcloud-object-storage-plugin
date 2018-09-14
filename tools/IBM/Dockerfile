FROM alpine:3.7
RUN apk add --update bash
RUN apk add --update python
COPY entrypoint .
COPY check_cos_mount_status .
RUN chmod u+x check_cos_mount_status entrypoint

CMD ["./entrypoint"]

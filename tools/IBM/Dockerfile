FROM alpine:3.7
RUN apk add --update bash  
COPY check_s3fs_status .
RUN chmod u+x check_s3fs_status

CMD ["./check_s3fs_status"]

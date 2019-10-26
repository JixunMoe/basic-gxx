FROM alpine:3.10.3

COPY ./runner-info /bin/runner-info
RUN chmod a+x /bin/runner-info

ENTRYPOINT [ "/bin/runner-info" ]

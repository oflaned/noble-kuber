FROM alpine:latest

#Instal nobled
RUN wget https://github.com/noble-assets/noble/releases/download/v4.1.2/nobled_linux-amd64 -O /usr/local/bin/nobled && \
    chmod +x /usr/local/bin/nobled && \
    mkdir /root/.nobled

CMD ["/usr/local/bin/nobled", "start", "--x-crisis-skip-assert-invariants"]
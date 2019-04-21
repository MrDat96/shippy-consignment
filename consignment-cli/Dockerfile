FROM debian:latest

RUN mkdir -p /app
WORKDIR /app
COPY consignment.json /app/consignment.json
COPY consignment-cli /app/consignment-cli

CMD ["./consignment-cli"]
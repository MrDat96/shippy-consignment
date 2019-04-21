FROM debian:latest

RUN mkdir /app
WORKDIR /app
ADD ./ /app/shippy-service-vessel

CMD ["./shippy-service-vessel/vessel-service"]
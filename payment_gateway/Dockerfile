from alpine:3.17.3

RUN adduser -D payment
USER payment
COPY process.sh /home/payment/process.sh
CMD /home/payment/process.sh

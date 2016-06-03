FROM debian

RUN apt-get update && apt-get install -y squid3

ADD etc/squid.conf /etc/squid/squid.conf

EXPOSE 3128

CMD /usr/sbin/squid3 -N -X

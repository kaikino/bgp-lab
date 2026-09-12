FROM frrouting/frr:latest
COPY daemons /etc/frr/daemons
COPY frr.conf /etc/frr/frr.conf
USER root
RUN chown -R frr:frr /etc/frr

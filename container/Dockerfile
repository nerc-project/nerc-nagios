FROM almalinux:9

RUN dnf -y update
RUN dnf -y install procps
RUN dnf -y install epel-release
RUN dnf -y install nagios
RUN dnf -y install mod_ssl mod_auth_openidc
RUN dnf -y install nagios-plugins-tcp
RUN dnf -y install nagios-plugins-ssl_validity
RUN dnf -y install nrpe
RUN dnf -y install perl-Math-BigInt
RUN chmod u+s /usr/bin/ping

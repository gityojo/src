FROM mysql:5.7

ADD ./my.cnf /etc/mysql/conf.d/my.cnf
ADD ./default_authentication.cnf /etc/mysql/conf.d/default_authentication.cnf

RUN chmod 644 /etc/mysql/conf.d/default_authentication.cnf
RUN chmod 644 /etc/mysql/conf.d/my.cnf

FROM iredmail:1.4.2

ADD main.cf /etc/postfix/main.cf
ADD master.cf /etc/postfix/master.cf

ADD mta.ini /etc/supervisord.d/mta.ini
ADD extra.ini /etc/supervisord.d/extra.ini
ADD frontend.ini /etc/supervisord.d/frontend.ini

FROM nginx:latest
LABEL maintainer='Zulqarnain <muhammad.zulqarnain1001@gmail.com>'
LABEL project='VProfileProject'

RUN rm -rf /etc/nginx/conf.d/default.conf

COPY ./nginxvprofileapp.conf /etc/nginx/conf.d/default.conf


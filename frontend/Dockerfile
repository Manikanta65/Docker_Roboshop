FROM nginx:1.24.0
RUN  rm -rf /usr/share/nginx/html/* 
RUN  rm -f /etc/nginx/conf.d/default.conf
RUN  rm -f /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY frontendcode /usr/share/nginx/html/

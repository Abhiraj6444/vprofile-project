FROM nginx
LABEL "Project"="Vprofile"
LABEL "Author"="Abhiraj"

RUN rm -rf /etc/nginx/conf.d/default.conf

COPY nginvproapp.conf /etc/nginx/conf.d/default.conf
EXPOSE 8080
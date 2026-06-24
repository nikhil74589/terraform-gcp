FROM nginx:alpine
COPY index.html /usr/share/nginx/html/index.html
RUN sed -i 's/listen 80;/listen 8080;/g' /etc/nginx/conf.d/default.conf
CMD ["nginx","-g","daemon off;"]
ENV PORT=8080
EXPOSE 8080 
#FIG

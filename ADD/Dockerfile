FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/jaganmohan5525/dockerfiles-shiva8/refs/heads/main/RUN/Dockerfile /usr/share/nginx/html/index.html
CMD ["nginx", "-g","daemon off;"]

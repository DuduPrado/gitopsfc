FROM --platform=linux/amd64 nginx:latest

COPY html /usr/share/nginx/html

ENTRYPOINT ["/docker-entrypoint.sh"]
CMD ["nginx", "g", "daemon off;"]

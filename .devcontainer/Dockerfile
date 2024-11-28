
FROM nginx:alpine


RUN apk add \
  musl \
  libgcc \
  libstdc++ \
  git \
  gnupg \
  nginx

RUN rm -rf /usr/share/nginx/html
RUN ln -s /workspaces/ads /usr/share/nginx/html
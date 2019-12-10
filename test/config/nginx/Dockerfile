FROM nginx:latest

COPY --from=billxiong/aloes-client /home/node/aloes-client/dist /etc/nginx/html

RUN rm /etc/nginx/conf.d/default.conf

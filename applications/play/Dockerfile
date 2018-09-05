FROM node:8@sha256:47a2131abc86d41faa910465b35987bc06b014c335309b551c876e517b5a4402
ADD . /playground
WORKDIR /playground
RUN npm install && npm run build

EXPOSE 3000

CMD ["/playground/node_modules/.bin/next", "start", "--host", "0.0.0.0"]

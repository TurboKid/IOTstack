FROM nodered/node-red:latest
RUN for addonnodes in \
node-red-node-pi-gpiod \
node-red-dashboard \
node-red-node-openweathermap \
node-red-node-google \
node-red-node-emoncms \
node-red-node-geofence \
node-red-node-ping \
node-red-node-random \
node-red-node-smooth \
node-red-node-darksky \
node-red-contrib-influxdb \
node-red-contrib-config \
node-red-contrib-grove \
node-red-contrib-diode \
node-red-contrib-bigtimer \
node-red-contrib-esplogin \
node-red-contrib-timeout \
node-red-contrib-moment \
node-red-contrib-particle \
node-red-contrib-web-worldmap \
node-red-contrib-ramp-thermostat \
node-red-contrib-isonline \
node-red-contrib-npm \
node-red-contrib-file-function \
node-red-contrib-boolean-logic \
node-red-contrib-home-assistant-websocket \
node-red-contrib-blynk-ws \
node-red-contrib-owntracks \
node-red-contrib-alexa-local \
node-red-contrib-heater-controller \
; do \
npm install ${addonnodes} ;\
done;
RUN npm install --unsafe-perm node-red-node-sqlite

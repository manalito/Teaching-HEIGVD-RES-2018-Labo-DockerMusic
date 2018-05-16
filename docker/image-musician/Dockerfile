FROM node:4.3.1
MAINTAINER Aurélien Siu <aurelien.siu@heig-vd.ch>


COPY src /opt/app/

WORKDIR /opt/app/
RUN ["npm","install","uuid","--save"]

ENTRYPOINT ["node", "/opt/app/musician.js"]

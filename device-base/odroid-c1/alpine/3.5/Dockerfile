FROM resin/armhf-alpine:3.5

LABEL io.resin.device-type="odroid-c1"

RUN apk add --update \
		less \
		nano \
		net-tools \
		ifupdown \		
		usbutils \
		gnupg \
	&& rm -rf /var/cache/apk/*

FROM alpine
RUN apk update && apk add tzdata
RUN cp /usr/share/zoneinfo/Europe/Brussels /etc/localtime
ENV TZ=America/New_York
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
CMD date
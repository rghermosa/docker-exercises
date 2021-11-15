FROM nginx:alpine

RUN apk --update --no-cache add curl

HEALTHCHECK --interval=45s --start-period=15s --timeout=5s --retries=2 CMD curl --fail http://localhost || exit 1  

EXPOSE 8082
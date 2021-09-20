#Use an existing docker image as a base / You can see this as a base O.S
FROM alpine



#Download and install a dependency
RUN apk add --update redis



#Tell the image what to do when it starts as a container
CMD ["redis-server"]
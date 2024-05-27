#Step1 specify the base image
FROM alpine

#Step2 Download and install dependencies
RUN apk add --update redis

#Step3 Setup the startup command
CMD ["redis-server"]

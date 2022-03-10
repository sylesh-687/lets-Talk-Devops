FROM ubuntu:21.04
RUN apt update && apt install nodejs -y
COPY . /tmp/
CMD ["node","/tmp/hello_world.js"]
EXPOSE 3000

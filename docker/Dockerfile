FROM ubuntu:focal
RUN apt update && apt install apache2 -y && apt install net-tools -y
EXPOSE 80
CMD ["service", "apache2", "start"]

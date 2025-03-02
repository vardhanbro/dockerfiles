FROM almalinux:9
RUN dnf install nginx -y 

ENV course="Devops with AWS" \
    trainer="siva kumar" \
    duration="120HRS"
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
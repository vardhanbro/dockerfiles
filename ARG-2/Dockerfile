
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="sivakumar reddy" \
    duration="120HRS"
ARG ${username:-some_user}	
RUN echo "Hello ${trainer}" > /tmp/devops.txt
CMD ["sleep", "100"]
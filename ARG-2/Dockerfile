FROM almalinux:9
ENV course="DevOps with AWS" \
    trainer="sivakumar reddy" \
    duration="120HRS"
 #here ARG "USERNAME" is key, "kumar" is default value
ARG USERNAME=kumar
RUN echo "Hello User: ${USERNAME}" > /tmp/devops.txt
CMD ["sleep", "100"]
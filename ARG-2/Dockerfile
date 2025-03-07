FROM almalinux:9
ENV course="DevOps with AWS" \
    trainer="sivakumar reddy" \
    duration="120HRS"
 #here user1 is key, someuser is default value
ARG ${username:-some_user}	
RUN echo "Hello ${username}" > /tmp/devops.txt
CMD ["sleep", "100"]
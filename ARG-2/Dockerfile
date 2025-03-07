
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="sivakumar reddy" \
    duration="120HRS"
 #here user1 is key, someuser is default value
ARG ${username:-some_user}	
RUN echo "Hello ${trainer}" > /tmp/devops.txt
CMD ["sleep", "100"]
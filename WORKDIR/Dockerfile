FROM almalinux:9
RUN mkdir /tmp/work-dir-demo
#RUN cd /tmp/work-dir-demo

#cd will not work here 
WORKDIR /tmp/work-dir-demo
RUN pwd
RUN echo "Hello from WORK DIR" > hello.txt
CMD ["sleep", "100"]
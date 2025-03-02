FROM almalinux:8
# RUN cd /tmp
WORKDIR /tmp
RUN echo "hello people" > help.txt
#here we gave tmp to store there, but in container it saves in the root directory 
#so to save where we want use WORKDIR instead of RUN.
CMD ["sleep", "100"]
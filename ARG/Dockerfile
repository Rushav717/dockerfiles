ARG version
FROM almalinux:${version:-9}
ENV project="expense"\
      environment="dev"\
      component="frontend"\
      author="rushhav"
ARG USERNAME=rushhav
RUN echo "Hello I am ${USERNAME}, image version ${version}" > /tmp/devops.txt
CMD [ "sleep","100" ]
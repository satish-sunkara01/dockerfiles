ARG version
FROM almalinux:${version:-8}
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN  echo "course : ${COURSE}, Trainer : ${TRAINER}, version : ${version}"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
ENV version=${version}
CMD [ "sleep","100" ]
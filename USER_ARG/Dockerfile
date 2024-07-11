FROM almalinux:8
ARG username
RUN useradd $username
USER $username
ARG TRAINER
ARG COURSE
ENV TRAINER=${TRAINER}
ENV COURSE=${COURSE}
CMD [ "sleep", "100" ]


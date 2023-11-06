ARG version
From almalinux:${version:-8}
# ARG variable before FROM will not work after FROM
ARG COURSE
ARG TRAINER
ARG DURATION

ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
ENV DURATION=${DURATION}
RUN echo "Course is: ${COURSE}, And the trainer is  ${TRAINER}, the total duration is ${DURATION}" 
ARG version
FROM almalinux:${version:-9}
ARG COURSE="DOCKER" \
    TRAINER="SIVAKUMAR"
ENV COURSE=${COURSE}   
ENV version=${version}
RUN echo "Trainer: ${TRAINER},Course:${COURSE},version:${version}"
CMD ["sleep", "1000"]
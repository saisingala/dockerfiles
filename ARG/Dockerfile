#FROM almalinux:10
ARG version
FROM almalinux:${version:-9}
ARG course="Devops witj aws" \
    duration="120hrs" \
    trainer="sivakumar"
ENV duration=$duration 
# set arg value to env variable
RUN echo "course: $course, duration: $duration, trainer:$trainer"
CMD ["sleep", "100"]

#docker build -t arg:v1  --build-arg version=8 .

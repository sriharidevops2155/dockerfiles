ARG version
FROM almalinux:${version:-9}
ENV course="DevOps"\
    duration="FlexileTime" 
ARG Trainer="myself"
ENV Trainer=$Trainer
RUN echo "Hi, Course is: ${course}, duration is: ${duration}, Trainer is: ${version}"
CMD [ "sleep","1000" ]

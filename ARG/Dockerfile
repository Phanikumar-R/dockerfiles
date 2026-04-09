ARG version=8

# if version is not set, default to 8 as the base image
FROM almalinux:${version:-8} 

ARG COURSE="Linux for Beginners" \
    TRAINER="John Doe" \
    DURATION="4 hours" \
    DESCRIPTION="This course covers the basics of Linux, including command line usage, file management.

RUN echo "Trainer is $TRAINER, course is $COURSE, duration is $DURATION, description is $DESCRIPTION"

CMD ["Sleep", "200"]

    




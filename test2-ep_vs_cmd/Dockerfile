# Sample Image build using Ubuntu

FROM ubuntu
MAINTAINER hgadgil@icloud.com

RUN apt-get update
RUN apt-get install -y iputils-ping

# Note- entry point makes it the default command to run
# to override - use --entrypoint
ENTRYPOINT ["ping", "-c", "3"]

# Sort of serves as a default arg. Can be overridden on command line
CMD ["localhost"]

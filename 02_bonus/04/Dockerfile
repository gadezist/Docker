FROM debian

MAINTAINER abytko <abytko@student.unit.ua>

RUN apt-get update -y && apt-get upgrade -y && \
	apt-get install -y git gcc clang binutils vim make

ENTRYPOINT ["/bin/bash"]

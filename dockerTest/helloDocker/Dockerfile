FROM ubuntu:21.04
RUN apt-get update && \
	DEBIAN_FRONTEND=noninteractive apt-get install --no-install-recommends -y python3
ADD hello.py /
CMD ["python3", "/hello.py"]

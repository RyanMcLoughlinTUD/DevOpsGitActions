FROM python:latest
WORKDIR /Lotto
COPY . /Lotto
RUN apt update && apt-get upgrade -y && apt-get install -y
RUN make
CMD ["./Lotto"]

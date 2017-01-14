FROM mono:4.6.2.7
LABEL Description="Akka.NET Mono Continuous Integration Base Image" Vendor="Akka.NET" Version="4.6.2.7"

RUN echo "Hello team Akka.NET!"

RUN echo "deb http://download.mono-project.com/repo/debian wheezy/snapshots/4.6.2.7 main" \
    && apt-get update \
    && apt-get install -y git wget \
    && rm -rf /var/lib/apt/lists/*
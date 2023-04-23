ARG version
FROM almalinux:${version:-8}
ARG Greeting="hi good morning"
ENV Gree=${Greeting}
RUN echo "$Greeting"
RUN echo "$version"
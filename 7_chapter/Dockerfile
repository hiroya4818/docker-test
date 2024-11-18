FROM ubuntu:20.04 AS base
RUN apt update # Common
CMD ["sh", "-c", "echo My name is $my_name"]

FROM base AS dev
ENV my_name=TEST

FROM base AS prod
ENV my_name=TEST

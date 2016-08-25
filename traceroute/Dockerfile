FROM debian:jessie

MAINTAINER Chris Kanich <kaytwo@gmail.com>

RUN apt-get update && apt-get install -y traceroute

ENTRYPOINT ["/usr/sbin/traceroute"]

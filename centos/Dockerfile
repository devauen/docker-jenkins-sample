FROM centos:latest
MAINTAINER James Turnbull "james@example.com"
ENV REFRESHED_AT 2016-06-01
RUN yum -y install ruby rubygems rubygem-rake
RUN gem install --no-document rspec ci_reporter_rspec

FROM node:7.2-slim

MAINTAINER Oleg Shalygin <oshalygin@gmail.com>

# Global install yarn package manager
RUN npm set progress=false && \
    npm install -g --progress=false yarn

WORKDIR /workspace

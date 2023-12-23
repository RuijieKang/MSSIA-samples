FROM openjdk:11
RUN apt-get update && apt-get install -y maven
RUN curl -sL https://deb.nodesource.com/setup_12.x | bash -
RUN apt-get install -y nodejs
RUN npm install -g npm@6.14.3
RUN npm install -g @angular/cli@9.0.4

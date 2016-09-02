FROM ruby:latest

RUN apt-get update \
    && apt-get install -y --no-install-recommends postgresql-client \
    && curl -sL https://deb.nodesource.com/setup_6.x | bash - \
    && apt-get install -y nodejs \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /usr/src/app
RUN gem install rails 

EXPOSE 3000
CMD ["rails", "server", "-b", "0.0.0.0"]

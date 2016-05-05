FROM ruby:2.2

ADD app.rb app.rb
RUN gem install sinatra

EXPOSE 4567
CMD ["ruby", "app.rb"]

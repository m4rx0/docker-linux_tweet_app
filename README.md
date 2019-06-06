[![Build Status](https://travis-ci.org/m4rx0/docker-linux_tweet_app.svg?branch=dev)](https://travis-ci.org/m4rx0/docker-linux_tweet_app)

# Linux Tweet App

This is very simple NGINX website that allows a user to send a tweet. 

It's mostly used as a sample application for Docker 101 workshops. 

To use it:

Build it:
`docker build -t linux_tweet_app .`

Run it:
`docker container run --detach -p 80:80 linux_tweet_app`


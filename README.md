[![Build Status](https://travis-ci.org/urbanriskmap/cognicity-notification-lambda.svg?branch=master)](https://travis-ci.org/urbanriskmap/cognicity-notification-lambda) [![Coverage Status](https://coveralls.io/repos/github/urbanriskmap/cognicity-notification-lambda/badge.svg?branch=master)](https://coveralls.io/github/urbanriskmap/cognicity-notification-lambda?branch=master)

# cognicity-notification-lambda
Notification service for CogniCity (send messages to SNS topic)

Exposes a RESTFul API for sending messages to existing CogniCity users via their chosen social media channel.

This Lambda publishes to AWS SNS topic, which is then captured by the appropriate social lambda (Twitter, Facebook, Telegram) to send message to user.

# Minecraft update notifier

Uses Twilio to send an SMS when the minecraft server is updated by Mojang.

# Heroku setup

    $ heroku create
    $ heroku config:add BUILDPACK_URL=http://github.com/kr/heroku-buildpack-inline.git
    $ heroku config:set TWILIO_USER=abcdefg TWILIO_PASS=abcdefg SMS_FROM=+15551234567 SMS_TO=+15551234567
    
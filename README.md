This stock bot uses the [Linklater](https://github.com/hlian/linklater) API to make a Slack bot that returns stock info based on a given public company. The information is accessed from this [HackerNews](https://github.com/dmjio/hackernews) and this [Haskell Twilio wrapper](https://github.com/markandrus/twilio-haskell). To run, clone the repo, *stack build*, *stack exec stockbot*, and then open up a Ngrok tunnel. You'll need a [Slack incoming webhook](https://api.slack.com/incoming-webhooks), too, which you will copy the URL of and paste into your Slack app.
To run, clone the repo, *stack build*, *stack exec redditbot*, and then open up a Ngrok tunnel. You'll need a [Slack incoming webhook](https://api.slack.com/incoming-webhooks), too.

Slack steps:
1. After going to *your apps* in the top righthand corner of https://api.slack.com, and selecting the bot you want (or creating a new one),select *incoming webhooks* to generate your web hook. Put this in a file called hook. ![webhook](https://cloud.githubusercontent.com/assets/8932430/25603467/0a42ce9e-2eca-11e7-9ad2-fdc7cb1b00d1.png) 
2. Right below that, you should this on the left-hand side.
![slashcommands](https://cloud.githubusercontent.com/assets/8932430/25603307/9a7197f4-2ec8-11e7-9e19-826e47ff3936.png)

Select *slash commands* underneath features.

3. Put your ngrok URL under *Request URL*, fill in some of the optional spots, and you're good to go!
![ngrokurl](https://cloud.githubusercontent.com/assets/8932430/25603651/86bc31f8-2ecb-11e7-8599-359594712020.png)

Try it out for yourself! 

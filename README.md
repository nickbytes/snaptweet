# SnapTweet

A tiny Node app which automatically deletes your tweets after ~~24 hours~~ 1 week, a bit like Snapchat.

I forked this from [https://github.com/JohnONolan/snaptweet](https://github.com/JohnONolan/snaptweet). There are very slight differences, but I've set this up to be deployed quickly using [now](https://zeit.co/now).

## Setup

1. [Register](https://apps.twitter.com/app/new) a new Twitter App, give it all permissions.
2. ~~Fill your consumer key/secret and access token key/secret in `app.js`~~ Rename `key.sample.js` to `key.js` and fill your consumer key/secret and access token key/secret.
3. ~~Change the date on line 38, if you want a hard cutoff. Eg. Don’t delete any tweets before:  Jan 16th, 2017.~~ There's no cutoff now, this will delete all tweets unless they are favorited or created within last 7 days.
4. ~~Deploy [somewhere](https://www.digitalocean.com/), keep it running using [Forever.js](https://github.com/foreverjs/forever)~~ Deploy using [now](https://zeit.co/now)! (Though DO + forever is a good idea too!)
5. Have fun! 😎

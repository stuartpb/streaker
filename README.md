# streaker

Translates GitHub activity feeds into contribution streak status feeds.

(NOTE: README-driven development, doc state does not reflect code state)

## How does this work?

GET a route in the app, the server will read your current GH activity feed and return an RSS item representing your current streak status. (Yes, _an_ item. It's ephemeral data- this only cares about whether you're streaking or you're not, the past is inconsequential.)

## What can I use it for?

Plug your feed URL into the app as the input to an externally managed feed reader so you can get ghetto notifications about when your GitHub streak is in danger.

## Why?

Because I have a pigheaded sense of pride about my GitHub streak, and I want notifications when I'm in danger of breaking it, so I don't just absentmindedly forget to contribute one day and kill my streak (which has happened a few times in the past).
